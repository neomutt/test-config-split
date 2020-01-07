# imap_check_subscribed

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_ImapCheckSubscribed

When set, NeoMutt will fetch the set of subscribed folders from
your server whenever a mailbox is selected, and add them to the set
of mailboxes it polls for new mail just as if you had issued individual
"mailboxes" commands.
