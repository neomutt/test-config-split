# crypt_autoencrypt

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_CryptAutoencrypt

Setting this variable will cause NeoMutt to always attempt to PGP
encrypt outgoing messages.  This is probably only useful in
connection to the "send-hook" command.  It can be overridden
by use of the pgp menu, when encryption is not required or
signing is requested as well.  If $smime_is_default is set,
then OpenSSL is used instead to create S/MIME messages and
settings can be overridden by use of the smime menu instead.
(Crypto only)
