# smime_is_default

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_SmimeIsDefault

The default behavior of NeoMutt is to use PGP on all auto-sign/encryption
operations. To override and to use OpenSSL instead this must be set.
However, this has no effect while replying, since NeoMutt will automatically
select the same application that was used to sign/encrypt the original
message.  (Note that this variable can be overridden by unsetting $crypt_autosmime.)
(S/MIME only)
