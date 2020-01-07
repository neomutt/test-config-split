# use_domain

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_UseDomain

When set, NeoMutt will qualify all local addresses (ones without the
"@host" portion) with the value of $hostname.  If unset, no
addresses will be qualified.
