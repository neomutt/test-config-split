# smime_decrypt_use_default_key

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_SmimeDecryptUseDefaultKey

If set (default) this tells NeoMutt to use the default key for decryption. Otherwise,
if managing multiple certificate-key-pairs, NeoMutt will try to use the mailbox-address
to determine the key to use. It will ask you to supply a key, if it can't find one.
(S/MIME only)
