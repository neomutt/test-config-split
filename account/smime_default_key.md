# smime_default_key

- **Default**: ""
- **Flags**: DT_STRING
- **Variable**: C_SmimeDefaultKey

This is the default key-pair to use for S/MIME operations, and must be
set to the keyid (the hash-value that OpenSSL generates) to work properly.

It will be used for encryption (see $postpone_encrypt and
$smime_self_encrypt).

It will be used for decryption unless $smime_decrypt_use_default_key
is unset.

It will also be used for signing unless $smime_sign_as is set.

The (now deprecated) smime_self_encrypt_as is an alias for this
variable, and should no longer be used.
(S/MIME only)
