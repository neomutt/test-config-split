# preconnect

- **Default**: ""
- **Flags**: DT_STRING
- **Variable**: C_Preconnect

If set, a shell command to be executed if NeoMutt fails to establish
a connection to the server. This is useful for setting up secure
connections, e.g. with ssh(1). If the command returns a  nonzero
status, NeoMutt gives up opening the server. Example:
set preconnect="ssh -f -q -L 1234:mailhost.net:143 mailhost.net \
sleep 20 < /dev/null > /dev/null"

Mailbox "foo" on "mailhost.net" can now be reached
as "{localhost:1234}foo".

Note: For this example to work, you must be able to log in to the
remote machine without having to enter a password.
