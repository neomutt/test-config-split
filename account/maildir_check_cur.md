# maildir_check_cur

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_MaildirCheckCur

If set, NeoMutt will poll both the new and cur directories of
a maildir folder for new messages.  This might be useful if other
programs interacting with the folder (e.g. dovecot) are moving new
messages to the cur directory.  Note that setting this option may
slow down polling for new messages in large folders, since NeoMutt has
to scan all cur messages.
