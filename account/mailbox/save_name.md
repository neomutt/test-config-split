# save_name

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_SaveName

This variable controls how copies of outgoing messages are saved.
When set, a check is made to see if a mailbox specified by the
recipient address exists (this is done by searching for a mailbox in
the $folder directory with the username part of the
recipient address).  If the mailbox exists, the outgoing message will
be saved to that mailbox, otherwise the message is saved to the
$record mailbox.

Also see the $force_name variable.
