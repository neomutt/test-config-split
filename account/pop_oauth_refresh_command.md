# pop_oauth_refresh_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND|DT_SENSITIVE
- **Variable**: C_PopOauthRefreshCommand

The command to run to generate an OAUTH refresh token for
authorizing your connection to your POP server.  This command will be
run on every connection attempt that uses the OAUTHBEARER authentication
mechanism.  See "oauth" for details.
