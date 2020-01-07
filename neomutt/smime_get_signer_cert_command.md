# smime_get_signer_cert_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_SmimeGetSignerCertCommand

This command is used to extract only the signers X509 certificate from a S/MIME
signature, so that the certificate's owner may get compared to the
email's "From:" field.

This is a format string, see the $smime_decrypt_command command for
possible printf(3)-like sequences.
(S/MIME only)
