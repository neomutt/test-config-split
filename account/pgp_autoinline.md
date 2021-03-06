# pgp_autoinline

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_PgpAutoinline

This option controls whether NeoMutt generates old-style inline
(traditional) PGP encrypted or signed messages under certain
circumstances.  This can be overridden by use of the pgp menu,
when inline is not required.  The GPGME backend does not support
this option.

Note that NeoMutt might automatically use PGP/MIME for messages
which consist of more than a single MIME part.  NeoMutt can be
configured to ask before sending PGP/MIME messages when inline
(traditional) would not work.

Also see the $pgp_mime_auto variable.

Also note that using the old-style PGP message format is strongly
deprecated.
(PGP only)
