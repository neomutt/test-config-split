# crypt_protected_headers_subject

- **Default**: "Encrypted subject"
- **Flags**: DT_STRING
- **Variable**: C_CryptProtectedHeadersSubject

When $crypt_protected_headers_write is set, and the message is marked
for encryption, this will be substituted into the Subject field in the
message headers.
To prevent a subject from being substituted, unset this variable, or set it
to the empty string.
(Crypto only)
