# pgp_check_exit

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_PgpCheckExit

If set, NeoMutt will check the exit code of the PGP subprocess when
signing or encrypting.  A non-zero exit code means that the
subprocess failed.
(PGP only)
