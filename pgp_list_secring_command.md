# pgp_list_secring_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_PgpListSecringCommand

This command is used to list the secret key ring's contents.  The
output format must be analogous to the one used by:
gpg --list-keys --with-colons --with-fingerprint

Note: gpg's fixed-list-mode option should not be used.  It
produces a different date format which may result in NeoMutt showing
incorrect key generation dates.

This is a format string, see the $pgp_decode_command command for
possible printf(3)-like sequences.
(PGP only)
