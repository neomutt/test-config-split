# imap_passive

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_ImapPassive

When set, NeoMutt will not open new IMAP connections to check for new
mail.  NeoMutt will only check for new mail over existing IMAP
connections.  This is useful if you don't want to be prompted for
user/password pairs on NeoMutt invocation, or if opening the connection
is slow.
