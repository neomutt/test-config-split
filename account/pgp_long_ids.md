# pgp_long_ids

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_PgpLongIds

If set, use 64 bit PGP key IDs, if unset use the normal 32 bit key IDs.
NOTE: Internally, NeoMutt has transitioned to using fingerprints (or long key IDs
as a fallback).  This option now only controls the display of key IDs
in the key selection menu and a few other places.
(PGP only)
