# smime_certificates

- **Default**: ""
- **Flags**: DT_STRING|DT_PATH
- **Variable**: C_SmimeCertificates

Since for S/MIME there is no pubring/secring as with PGP, NeoMutt has to handle
storage and retrieval of keys by itself. This is very basic right
now, and keys and certificates are stored in two different
directories, both named as the hash-value retrieved from
OpenSSL. There is an index file which contains mailbox-address
keyid pairs, and which can be manually edited. This option points to
the location of the certificates.
(S/MIME only)
