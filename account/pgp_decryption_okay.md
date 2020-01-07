# pgp_decryption_okay

- **Default**: ""
- **Flags**: DT_REGEX
- **Variable**: C_PgpDecryptionOkay

If you assign text to this variable, then an encrypted PGP
message is only considered successfully decrypted if the output
from $pgp_decrypt_command contains the text.  This is used to
protect against a spoofed encrypted message, with multipart/encrypted
headers but containing a block that is not actually encrypted.
(e.g. simply signed and ascii armored text).

Note that if $pgp_check_gpg_decrypt_status_fd is set, this variable
is ignored.
(PGP only)
