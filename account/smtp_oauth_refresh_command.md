# smtp_oauth_refresh_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND|DT_SENSITIVE
- **Variable**: C_SmtpOauthRefreshCommand

The command to run to generate an OAUTH refresh token for
authorizing your connection to your SMTP server.  This command will be
run on every connection attempt that uses the OAUTHBEARER authentication
mechanism.  See "oauth" for details.
