# ssl_verify_host

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_SslVerifyHost

If set (the default), NeoMutt will not automatically accept a server
certificate whose host name does not match the host used in your folder
URL. You should only unset this for particular known hosts, using
the <account-hook> function.
