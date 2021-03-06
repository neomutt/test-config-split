# crypt_protected_headers_save

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_CryptProtectedHeadersSave

When $crypt_protected_headers_read is set, and a message with a
protected Subject is opened, NeoMutt will save the updated Subject
into the header cache by default.  This allows searching/limiting
based on the protected Subject header if the mailbox is
re-opened, without having to re-open the message each time.
However, for mbox/mh mailbox types, or if header caching is not
set up, you would need to re-open the message each time the
mailbox was reopened before you could see or search/limit on the
protected subject again.

When this variable is set, NeoMutt additionally saves the protected
Subject back in the clear-text message headers.  This
provides better usability, but with the tradeoff of reduced
security.  The protected Subject header, which may have
previously been encrypted, is now stored in clear-text in the
message headers.  Copying the message elsewhere, via NeoMutt or
external tools, could expose this previously encrypted data.
Please make sure you understand the consequences of this before
you enable this variable.
(Crypto only)
