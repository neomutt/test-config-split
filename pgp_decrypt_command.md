# pgp_decrypt_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_PgpDecryptCommand

This command is used to decrypt a PGP encrypted message.

This is a format string, see the $pgp_decode_command command for
possible printf(3)-like sequences.
(PGP only)

Note: When decrypting messages using gpg, a pinentry program needs to
be invoked unless the password is cached within gpg-agent.
Currently, the pinentry-tty program (usually distributed with
gpg) isn't suitable for being invoked by NeoMutt.  You are encouraged
to use a different pinentry-program when running NeoMutt in order to avoid
problems.

See also: https://github.com/neomutt/neomutt/issues/1014
