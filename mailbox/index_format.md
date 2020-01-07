# index_format

- **Default**: "%4C %Z %{%b %d} %-15.15L (%?l?%4l&%4c?) %s"
- **Flags**: DT_STRING|DT_NOT_EMPTY
- **Variable**: C_IndexFormat

This variable allows you to customize the message index display to
your personal taste.

"Format strings" are similar to the strings used in the C
function printf(3) to format output (see the man page for more details).
For an explanation of the %? construct, see the status_format description.
The following sequences are defined in NeoMutt:
%a      Address of the author
%A      Reply-to address (if present; otherwise: address of author)
%b      Filename of the original message folder (think mailbox)
%B      The list to which the letter was sent, or else the folder name (%b).
%C      Current message number
%c      Number of characters (bytes) in the body of the message (see formatstrings-size)
%cr     Number of characters (bytes) in the raw message, including the header (see formatstrings-size)
%D      Date and time of message using date_format and local timezone
%d      Date and time of message using date_format and sender's timezone
%e      Current message number in thread
%E      Number of messages in current thread
%F      Author name, or recipient name if the message is from you
%Fp     Like %F, but plain. No contextual formatting is applied to recipient name
%f      Sender (address + real name), either From: or Return-Path:
%g      Newsgroup name (if compiled with NNTP support)
%g      Message tags (e.g. notmuch tags/imap flags)
%Gx     Individual message tag (e.g. notmuch tags/imap flags)
%H      Spam attribute(s) of this message
%I      Initials of author
%i      Message-id of the current message
%J      Message tags (if present, tree unfolded, and != parent's tags)
%K      The list to which the letter was sent (if any; otherwise: empty)
%L      If an address in the "To:" or "Cc:" header field matches an address
        Defined by the users "subscribe" command, this displays
        "To <list-name>", otherwise the same as %F
%l      number of lines in the unprocessed message (may not work with
        maildir, mh, and IMAP folders)
%M      Number of hidden messages if the thread is collapsed
%m      Total number of message in the mailbox
%N      Message score
%n      Author's real name (or address if missing)
%O      Original save folder where NeoMutt would formerly have
        Stashed the message: list name or recipient name
        If not sent to a list
%P      Progress indicator for the built-in pager (how much of the file has been displayed)
%q      Newsgroup name (if compiled with NNTP support)
%R      Comma separated list of "Cc:" recipients
%r      Comma separated list of "To:" recipients
%S      Single character status of the message ("N"/"O"/"D"/"d"/"!"/"r"/"*")
%s      Subject of the message
%T      The appropriate character from the $to_chars string
%t      "To:" field (recipients)
%u      User (login) name of the author
%v      First name of the author, or the recipient if the message is from you
%W      Name of organization of author ("Organization:" field)
%x      "X-Comment-To:" field (if present and compiled with NNTP support)
%X      Number of MIME attachments
        (please see the "attachments" section for possible speed effects)
%Y      "X-Label:" field, if present, and (1) not at part of a thread tree,
        (2) at the top of a thread, or (3) "X-Label:" is different from
        Preceding message's "X-Label:"
%y      "X-Label:" field, if present
%Z      A three character set of message status flags.
        The first character is new/read/replied flags ("n"/"o"/"r"/"O"/"N").
        The second is deleted or encryption flags ("D"/"d"/"S"/"P"/"s"/"K").
        The third is either tagged/flagged ("*"/"!"), or one of the characters
        Listed in $to_chars.
%zc     Message crypto flags
%zs     Message status flags
%zt     Message tag flags
%@name@ insert and evaluate format-string from the matching
        ``index-format-hook'' command
%{fmt}  the date and time of the message is converted to sender's
        time zone, and "fmt" is expanded by the library function
        strftime(3); a leading bang disables locales
%[fmt]  the date and time of the message is converted to the local
        time zone, and "fmt" is expanded by the library function
        strftime(3); a leading bang disables locales
%(fmt)  the local date and time when the message was received.
        "fmt" is expanded by the library function strftime(3);
        a leading bang disables locales
%>X     right justify the rest of the string and pad with character "X"
%|X     pad to the end of the line with character "X"
%*X     soft-fill with character "X" as pad

Date format expressions can be constructed based on relative dates. Using
the date formatting operators along with nested conditionals, the date
format can be modified based on how old a message is.  See the section on
"Conditional Dates" for an explanation and examples

Note that for mbox/mmdf, ``%l'' applies to the unprocessed message, and
for maildir/mh, the value comes from the ``Lines:'' header field when
present (the meaning is normally the same). Thus the value depends on
the encodings used in the different parts of the message and has little
meaning in practice.

"Soft-fill" deserves some explanation: Normal right-justification
will print everything to the left of the "%>", displaying padding and
whatever lies to the right only if there's room. By contrast,
soft-fill gives priority to the right-hand side, guaranteeing space
to display it and showing padding only if there's still room. If
necessary, soft-fill will eat text leftwards to make room for
rightward text.

Note that these expandos are supported in
``save-hook'', ``fcc-hook'' and ``fcc-save-hook'', too.
