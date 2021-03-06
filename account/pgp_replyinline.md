# pgp_replyinline

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_PgpReplyinline

Setting this variable will cause NeoMutt to always attempt to
create an inline (traditional) message when replying to a
message which is PGP encrypted/signed inline.  This can be
overridden by use of the pgp menu, when inline is not
required.  This option does not automatically detect if the
(replied-to) message is inline; instead it relies on NeoMutt
internals for previously checked/flagged messages.

Note that NeoMutt might automatically use PGP/MIME for messages
which consist of more than a single MIME part.  NeoMutt can be
configured to ask before sending PGP/MIME messages when inline
(traditional) would not work.

Also see the $pgp_mime_auto variable.

Also note that using the old-style PGP message format is strongly
deprecated.
(PGP only)
