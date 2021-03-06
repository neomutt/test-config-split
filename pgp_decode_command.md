# pgp_decode_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_PgpDecodeCommand

This format strings specifies a command which is used to decode
application/pgp attachments.

The PGP command formats have their own set of printf(3)-like sequences:
%p      Expands to PGPPASSFD=0 when a pass phrase is needed, to an empty
        string otherwise. Note: This may be used with a %? construct.
%f      Expands to the name of a file containing a message.
%s      Expands to the name of a file containing the signature part
                   of a multipart/signed attachment when verifying it.
%a      The value of $pgp_sign_as if set, otherwise the value
        of $pgp_default_key.
%r      One or more key IDs (or fingerprints if available).

For examples on how to configure these formats for the various versions
of PGP which are floating around, see the pgp and gpg sample configuration files in
the samples/ subdirectory which has been installed on your system
alongside the documentation.
(PGP only)
