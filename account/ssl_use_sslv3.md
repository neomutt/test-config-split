# ssl_use_sslv3

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_SslUseSslv3

If set , NeoMutt will use SSLv3 when communicating with servers that
request it. N.B. As of 2015, SSLv3 is considered insecure, and using
it is inadvisable. See https://tools.ietf.org/html/rfc7525 .
