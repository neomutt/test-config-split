# folder_format

- **Default**: "%2C %t %N %F %2l %-8.8u %-8.8g %8s %d %i"
- **Flags**: DT_STRING|DT_NOT_EMPTY
- **Variable**: C_FolderFormat

This variable allows you to customize the file browser display to your
personal taste.  This string is similar to $index_format, but has
its own set of printf(3)-like sequences:
%C      Current file number
%d      Date/time folder was last modified
%D      Date/time folder was last modified using $date_format.
%f      Filename ("/" is appended to directory names,
        "@" to symbolic links and "*" to executable files)
%F      File permissions
%g      Group name (or numeric gid, if missing)
%i      Description of the folder
%l      Number of hard links
%m      Number of messages in the mailbox *
%n      Number of unread messages in the mailbox *
%N      "N" if mailbox has new mail, blank otherwise
%s      Size in bytes (see formatstrings-size)
%t      "*" if the file is tagged, blank otherwise
%u      Owner name (or numeric uid, if missing)
%>X     Right justify the rest of the string and pad with character "X"
%|X     Pad to the end of the line with character "X"
%*X     Soft-fill with character "X" as pad

For an explanation of "soft-fill", see the $index_format documentation.

* = can be optionally printed if nonzero

%m, %n, and %N only work for monitored mailboxes.
%m requires $mail_check_stats to be set.
%n requires $mail_check_stats to be set (except for IMAP mailboxes).
