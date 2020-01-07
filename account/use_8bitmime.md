# use_8bitmime

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_Use8bitmime

Warning: do not set this variable unless you are using a version
of sendmail which supports the -B8BITMIME flag (such as sendmail
8.8.x) or you may not be able to send mail.

When set, NeoMutt will invoke $sendmail with the -B8BITMIME
flag when sending 8-bit messages to enable ESMTP negotiation.
