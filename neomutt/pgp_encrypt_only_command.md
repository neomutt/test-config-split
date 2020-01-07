# pgp_encrypt_only_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_PgpEncryptOnlyCommand

This command is used to encrypt a body part without signing it.

This is a format string, see the $pgp_decode_command command for
possible printf(3)-like sequences.
Note that in this case, %r expands to the search string, which is a list of
one or more quoted values such as email address, name, or keyid.
(PGP only)
