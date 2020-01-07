# smime_encrypt_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_SmimeEncryptCommand

This command is used to create encrypted S/MIME messages.

This is a format string, see the $smime_decrypt_command command for
possible printf(3)-like sequences.
(S/MIME only)

Encrypt the message to $smime_default_key too.
(S/MIME only)
