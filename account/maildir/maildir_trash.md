# maildir_trash

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_MaildirTrash

If set, messages marked as deleted will be saved with the maildir
trashed flag instead of unlinked.  Note: this only applies
to maildir-style mailboxes.  Setting it will have no effect on other
mailbox types.
