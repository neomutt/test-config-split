# save_empty

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_SaveEmpty

When unset, mailboxes which contain no saved messages will be removed
when closed (the exception is $spoolfile which is never removed).
If set, mailboxes are never removed.

Note: This only applies to mbox and MMDF folders, NeoMutt does not
delete MH and Maildir directories.
