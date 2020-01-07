# pgp_auto_decode

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_PgpAutoDecode

If set, NeoMutt will automatically attempt to decrypt traditional PGP
messages whenever the user performs an operation which ordinarily would
result in the contents of the message being operated on.  For example,
if the user displays a pgp-traditional message which has not been manually
checked with the <check-traditional-pgp> function, NeoMutt will automatically
check the message for traditional pgp.
