# crypt_replysignencrypted

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_CryptReplysignencrypted

If set, automatically PGP or OpenSSL sign replies to messages
which are encrypted. This makes sense in combination with
$crypt_replyencrypt, because it allows you to sign all
messages which are automatically encrypted.  This works around
the problem noted in $crypt_replysign, that NeoMutt is not able
to find out whether an encrypted message is also signed.
(Crypto only)
