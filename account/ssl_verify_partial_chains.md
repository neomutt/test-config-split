# ssl_verify_partial_chains

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_SslVerifyPartialChains

This option should not be changed from the default unless you understand
what you are doing.

Setting this variable to yes will permit verifying partial
certification chains, i. e. a certificate chain where not the root,
but an intermediate certificate CA, or the host certificate, are
marked trusted (in $certificate_file), without marking the root
signing CA as trusted.

(OpenSSL 1.0.2b and newer only).
