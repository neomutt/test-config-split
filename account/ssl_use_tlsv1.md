# ssl_use_tlsv1

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_SslUseTlsv1

If set , NeoMutt will use TLSv1.0 when communicating with servers that
request it. N.B. As of 2015, TLSv1.0 is considered insecure, and using
it is inadvisable. See https://tools.ietf.org/html/rfc7525 .
