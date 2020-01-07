# sidebar_format

- **Default**: "%B%*  %n"
- **Flags**: DT_STRING|DT_NOT_EMPTY
- **Variable**: C_SidebarFormat

This variable allows you to customize the sidebar display. This string is
similar to $index_format, but has its own set of printf(3)-like
sequences:
%B      Name of the mailbox
%D      Description of the mailbox
%S      * Size of mailbox (total number of messages)
%N      * Number of unread messages in the mailbox
%n      N if mailbox has new mail, blank otherwise
%F      * Number of Flagged messages in the mailbox
%!      "!" : one flagged message;
        "!!" : two flagged messages;
        "n!" : n flagged messages (for n > 2).
        Otherwise prints nothing.
%d      * @ Number of deleted messages
%L      * @ Number of messages after limiting
%t      * @ Number of tagged messages
%>X     right justify the rest of the string and pad with "X"
%|X     pad to the end of the line with "X"
%*X     soft-fill with character "X" as pad

* = Can be optionally printed if nonzero
@ = Only applicable to the current folder

In order to use %S, %N, %F, and %!, $mail_check_stats must
be set.  When thus set, a suggested value for this option is
"%B%?F? [%F]?%* %?N?%N/?%S".
