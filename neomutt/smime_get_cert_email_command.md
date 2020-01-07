# smime_get_cert_email_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_SmimeGetCertEmailCommand

This command is used to extract the mail address(es) used for storing
X509 certificates, and for verification purposes (to check whether the
certificate was issued for the sender's mailbox).

This is a format string, see the $smime_decrypt_command command for
possible printf(3)-like sequences.
(S/MIME only)
