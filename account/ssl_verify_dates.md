# ssl_verify_dates

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_SslVerifyDates

If set (the default), NeoMutt will not automatically accept a server
certificate that is either not yet valid or already expired. You should
only unset this for particular known hosts, using the
<account-hook> function.
