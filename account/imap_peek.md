# imap_peek

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_ImapPeek

When set, NeoMutt will avoid implicitly marking your mail as read whenever
you fetch a message from the server. This is generally a good thing,
but can make closing an IMAP folder somewhat slower. This option
exists to appease speed freaks.
