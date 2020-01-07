# imap_poll_timeout

- **Default**: 15
- **Flags**: DT_NUMBER|DT_NOT_NEGATIVE
- **Variable**: C_ImapPollTimeout

This variable specifies the maximum amount of time in seconds
that NeoMutt will wait for a response when polling IMAP connections
for new mail, before timing out and closing the connection.  Set
to 0 to disable timing out.
