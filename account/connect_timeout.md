# connect_timeout

- **Default**: 30
- **Flags**: DT_NUMBER
- **Variable**: C_ConnectTimeout

Causes NeoMutt to timeout a network connection (for IMAP, POP or SMTP) after this
many seconds if the connection is not able to be established.  A negative
value causes NeoMutt to wait indefinitely for the connection attempt to succeed.
