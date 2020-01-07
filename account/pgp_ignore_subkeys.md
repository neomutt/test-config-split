# pgp_ignore_subkeys

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_PgpIgnoreSubkeys

Setting this variable will cause NeoMutt to ignore OpenPGP subkeys. Instead,
the principal key will inherit the subkeys' capabilities.  Unset this
if you want to play interesting key selection games.
(PGP only)
