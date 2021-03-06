# imap_keepalive

- **Default**: 300
- **Flags**: DT_NUMBER|DT_NOT_NEGATIVE
- **Variable**: C_ImapKeepalive

This variable specifies the maximum amount of time in seconds that NeoMutt
will wait before polling open IMAP connections, to prevent the server
from closing them before NeoMutt has finished with them. The default is
well within the RFC-specified minimum amount of time (30 minutes) before
a server is allowed to do this, but in practice the RFC does get
violated every now and then. Reduce this number if you find yourself
getting disconnected from your IMAP server due to inactivity.
