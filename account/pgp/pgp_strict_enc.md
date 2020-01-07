# pgp_strict_enc

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_PgpStrictEnc

If set, NeoMutt will automatically encode PGP/MIME signed messages as
quoted-printable.  Please note that unsetting this variable may
lead to problems with non-verifyable PGP signatures, so only change
this if you know what you are doing.
(PGP only)
