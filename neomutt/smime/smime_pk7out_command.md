# smime_pk7out_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_SmimePk7outCommand

This command is used to extract PKCS7 structures of S/MIME signatures,
in order to extract the public X509 certificate(s).

This is a format string, see the $smime_decrypt_command command for
possible printf(3)-like sequences.
(S/MIME only)
