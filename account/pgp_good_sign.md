# pgp_good_sign

- **Default**: ""
- **Flags**: DT_REGEX
- **Variable**: C_PgpGoodSign

If you assign a text to this variable, then a PGP signature is only
considered verified if the output from $pgp_verify_command contains
the text. Use this variable if the exit code from the command is 0
even for bad signatures.
(PGP only)
