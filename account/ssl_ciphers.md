# ssl_ciphers

- **Default**: ""
- **Flags**: DT_STRING
- **Variable**: C_SslCiphers

Contains a colon-separated list of ciphers to use when using SSL.
For OpenSSL, see ciphers(1) for the syntax of the string.

For GnuTLS, this option will be used in place of "NORMAL" at the
start of the priority string.  See gnutls_priority_init(3) for the
syntax and more details. (Note: GnuTLS version 2.1.7 or higher is
required.)
