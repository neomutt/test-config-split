# pgp_retainable_sigs

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_PgpRetainableSigs

If set, signed and encrypted messages will consist of nested
multipart/signed and multipart/encrypted body parts.

This is useful for applications like encrypted and signed mailing
lists, where the outer layer (multipart/encrypted) can be easily
removed, while the inner multipart/signed part is retained.
(PGP only)
