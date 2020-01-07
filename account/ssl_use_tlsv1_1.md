# ssl_use_tlsv1_1

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_SslUseTlsv11

If set , NeoMutt will use TLSv1.1 when communicating with servers that
request it. N.B. As of 2015, TLSv1.1 is considered insecure, and using
it is inadvisable. See https://tools.ietf.org/html/rfc7525 .
