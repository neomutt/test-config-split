# crypt_use_gpgme

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_CryptUseGpgme

This variable controls the use of the GPGME-enabled crypto backends.
If it is set and NeoMutt was built with gpgme support, the gpgme code for
S/MIME and PGP will be used instead of the classic code.  Note that
you need to set this option in .neomuttrc; it won't have any effect when
used interactively.

Note that the GPGME backend does not support creating old-style inline
(traditional) PGP encrypted or signed messages (see $pgp_autoinline).
