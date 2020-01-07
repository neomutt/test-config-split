# crypt_opportunistic_encrypt

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_CryptOpportunisticEncrypt

Setting this variable will cause NeoMutt to automatically enable and
disable encryption, based on whether all message recipient keys
can be located by NeoMutt.

When this option is enabled, NeoMutt will enable/disable encryption
each time the TO, CC, and BCC lists are edited.  If
$edit_headers is set, NeoMutt will also do so each time the message
is edited.

While this is set, encryption can't be manually enabled/disabled.
The pgp or smime menus provide a selection to temporarily disable
this option for the current message.

If $crypt_autoencrypt or $crypt_replyencrypt enable encryption for
a message, this option will be disabled for that message.  It can
be manually re-enabled in the pgp or smime menus.
(Crypto only)
