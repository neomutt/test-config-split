# crypt_protected_headers_read

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_CryptProtectedHeadersRead

When set, NeoMutt will display protected headers ("Memory Hole") in the pager,
and will update the index and header cache with revised headers.
Protected headers are stored inside the encrypted or signed part of an
an email, to prevent disclosure or tampering.
For more information see https://github.com/autocrypt/memoryhole.
Currently NeoMutt only supports the Subject header.

Encrypted messages using protected headers often substitute the exposed
Subject header with a dummy value (see $crypt_protected_headers_subject).
NeoMutt will update its concept of the correct subject after the
message is opened, i.e. via the <display-message> function.
If you reply to a message before opening it, NeoMutt will end up using
the dummy Subject header, so be sure to open such a message first.
(Crypto only)
