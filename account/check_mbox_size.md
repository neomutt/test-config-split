# check_mbox_size

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_CheckMboxSize

When this variable is set, NeoMutt will use file size attribute instead of
access time when checking for new mail in mbox and mmdf folders.

This variable is unset by default and should only be enabled when
new mail detection for these folder types is unreliable or doesn't work.

Note that enabling this variable should happen before any "mailboxes"
directives occur in configuration files regarding mbox or mmdf folders
because NeoMutt needs to determine the initial new mail status of such a
mailbox by performing a fast mailbox scan when it is defined.
Afterwards the new mail status is tracked by file size changes.
