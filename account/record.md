# record

- **Default**: "~/sent"
- **Flags**: DT_STRING|DT_PATH|DT_MAILBOX
- **Variable**: C_Record

This specifies the file into which your outgoing messages should be
appended.  (This is meant as the primary method for saving a copy of
your messages, but another way to do this is using the "my_hdr"
command to create a "Bcc:" field with your email address in it.)

The value of $record is overridden by the $force_name and
$save_name variables, and the "fcc-hook" command.  Also see $copy
and $write_bcc.
