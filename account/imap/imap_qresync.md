# imap_qresync

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_ImapQresync

When set, NeoMutt will use the QRESYNC extension (RFC 7162)
if advertised by the server.  NeoMutt's current implementation is basic,
used only for initial message fetching and flag updates.

Note: this feature is currently experimental.  If you experience
strange behavior, such as duplicate or missing messages please
file a bug report to let us know.
