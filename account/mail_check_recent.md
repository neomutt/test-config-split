# mail_check_recent

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_MailCheckRecent

When set, NeoMutt will only notify you about new mail that has been received
since the last time you opened the mailbox.  When unset, NeoMutt will notify you
if any new mail exists in the mailbox, regardless of whether you have visited it
recently.

When $mark_old is set, NeoMutt does not consider the mailbox to contain new
mail if only old messages exist.
