# read_inc

- **Default**: 10
- **Flags**: DT_NUMBER|DT_NOT_NEGATIVE
- **Variable**: C_ReadInc

If set to a value greater than 0, NeoMutt will display which message it
is currently on when reading a mailbox or when performing search actions
such as search and limit. The message is printed after
this many messages have been read or searched (e.g., if set to 25, NeoMutt will
print a message when it is at message 25, and then again when it gets
to message 50).  This variable is meant to indicate progress when
reading or searching large mailboxes which may take some time.
When set to 0, only a single message will appear before the reading
the mailbox.

Also see the $write_inc, $net_inc and $time_inc variables and the
"tuning" section of the manual for performance considerations.
