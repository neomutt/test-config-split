# tunnel

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_Tunnel

Setting this variable will cause NeoMutt to open a pipe to a command
instead of a raw socket. You may be able to use this to set up
preauthenticated connections to your IMAP/POP3/SMTP server. Example:
set tunnel="ssh -q mailhost.net /usr/local/libexec/imapd"

Note: For this example to work you must be able to log in to the remote
machine without having to enter a password.

When set, NeoMutt uses the tunnel for all remote connections.
Please see "account-hook" in the manual for how to use different
tunnel commands per connection.
