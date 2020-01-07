# write_inc

- **Default**: 10
- **Flags**: DT_NUMBER|DT_NOT_NEGATIVE
- **Variable**: C_WriteInc

When writing a mailbox, a message will be printed every
$write_inc messages to indicate progress.  If set to 0, only a
single message will be displayed before writing a mailbox.

Also see the $read_inc, $net_inc and $time_inc variables and the
"tuning" section of the manual for performance considerations.
