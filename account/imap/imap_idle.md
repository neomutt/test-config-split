# imap_idle

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_ImapIdle

When set, NeoMutt will attempt to use the IMAP IDLE extension
to check for new mail in the current mailbox. Some servers
(dovecot was the inspiration for this option) react badly
to NeoMutt's implementation. If your connection seems to freeze
up periodically, try unsetting this.
