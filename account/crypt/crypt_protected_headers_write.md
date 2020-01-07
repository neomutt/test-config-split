# crypt_protected_headers_write

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_CryptProtectedHeadersWrite

When set, NeoMutt will generate protected headers ("Memory Hole") for
signed and encrypted emails.
Protected headers are stored inside the encrypted or signed part of an
an email, to prevent disclosure or tampering.
For more information see https://github.com/autocrypt/memoryhole.
Currently NeoMutt only supports the Subject header.
(Crypto only)
