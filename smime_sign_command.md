# smime_sign_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_SmimeSignCommand

This command is used to created S/MIME signatures of type
multipart/signed, which can be read by all mail clients.

This is a format string, see the $smime_decrypt_command command for
possible printf(3)-like sequences.
(S/MIME only)
