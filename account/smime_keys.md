# smime_keys

- **Default**: ""
- **Flags**: DT_STRING|DT_PATH
- **Variable**: C_SmimeKeys

Since for S/MIME there is no pubring/secring as with PGP, NeoMutt has to handle
storage and retrieval of keys/certs by itself. This is very basic right now,
and stores keys and certificates in two different directories, both
named as the hash-value retrieved from OpenSSL. There is an index file
which contains mailbox-address keyid pair, and which can be manually
edited. This option points to the location of the private keys.
(S/MIME only)
