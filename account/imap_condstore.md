# imap_condstore

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_ImapCondstore

When set, NeoMutt will use the CONDSTORE extension (RFC 7162)
if advertised by the server.  NeoMutt's current implementation is basic,
used only for initial message fetching and flag updates.

For some IMAP servers, enabling this will slightly speed up
downloading initial messages.  Unfortunately, Gmail is not one
those, and displays worse performance when enabled.  Your
mileage may vary.
