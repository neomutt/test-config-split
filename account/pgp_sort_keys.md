# pgp_sort_keys

- **Default**: address
- **Flags**: DT_SORT|DT_SORT_KEYS
- **Variable**: C_PgpSortKeys

Specifies how the entries in the pgp menu are sorted. The
following are legal values:
address sort alphabetically by user id
keyid   sort alphabetically by key id
date    sort by key creation date
trust   sort by the trust of the key

If you prefer reverse order of the above values, prefix it with
"reverse-".
(PGP only)
