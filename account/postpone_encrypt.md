# postpone_encrypt

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_PostponeEncrypt

When set, postponed messages that are marked for encryption will be
self-encrypted.  NeoMutt will first try to encrypt using the value specified
in $pgp_default_key or $smime_default_key.  If those are not
set, it will try the deprecated $postpone_encrypt_as.
(Crypto only)
