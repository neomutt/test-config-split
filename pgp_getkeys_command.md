# pgp_getkeys_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_PgpGetkeysCommand

This command is invoked whenever NeoMutt needs to fetch the public key associated with
an email address.  Of the sequences supported by $pgp_decode_command, %r is
the only printf(3)-like sequence used with this format.  Note that
in this case, %r expands to the email address, not the public key ID (the key ID is
unknown, which is why NeoMutt is invoking this command).
(PGP only)
