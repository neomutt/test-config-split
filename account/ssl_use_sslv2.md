# ssl_use_sslv2

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_SslUseSslv2

If set , NeoMutt will use SSLv2 when communicating with servers that
request it. N.B. As of 2011, SSLv2 is considered insecure, and using
is inadvisable. See https://tools.ietf.org/html/rfc6176 .
(OpenSSL only)
