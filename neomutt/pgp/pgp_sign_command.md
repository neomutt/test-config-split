# pgp_sign_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_PgpSignCommand

This command is used to create the detached PGP signature for a
multipart/signed PGP/MIME body part.

This is a format string, see the $pgp_decode_command command for
possible printf(3)-like sequences.
(PGP only)
