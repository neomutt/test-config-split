# smime_import_cert_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_SmimeImportCertCommand

This command is used to import a certificate via smime_keys.

This is a format string, see the $smime_decrypt_command command for
possible printf(3)-like sequences.  NOTE: %c and %k will default
to $smime_sign_as if set, otherwise $smime_default_key.
(S/MIME only)
