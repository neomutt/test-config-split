# check_new

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_CheckNew

Note: this option only affects maildir and MH style
mailboxes.

When set, NeoMutt will check for new mail delivered while the
mailbox is open.  Especially with MH mailboxes, this operation can
take quite some time since it involves scanning the directory and
checking each file to see if it has already been looked at.  If
this variable is unset, no check for new mail is performed
while the mailbox is open.
