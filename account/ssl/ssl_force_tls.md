# ssl_force_tls

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_SslForceTls

If this variable is set, NeoMutt will require that all connections
to remote servers be encrypted. Furthermore it will attempt to
negotiate TLS even if the server does not advertise the capability,
since it would otherwise have to abort the connection anyway. This
option supersedes $ssl_starttls.
