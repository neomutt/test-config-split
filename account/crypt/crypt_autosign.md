# crypt_autosign

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_CryptAutosign

Setting this variable will cause NeoMutt to always attempt to
cryptographically sign outgoing messages.  This can be overridden
by use of the pgp menu, when signing is not required or
encryption is requested as well. If $smime_is_default is set,
then OpenSSL is used instead to create S/MIME messages and settings can
be overridden by use of the smime menu instead of the pgp menu.
(Crypto only)
