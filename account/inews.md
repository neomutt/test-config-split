# inews

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_Inews

If set, specifies the program and arguments used to deliver news posted
by NeoMutt.  Otherwise, NeoMutt posts article using current connection to
news server.  The following printf-style sequence is understood:
%a      account url
%p      port
%P      port if specified
%s      news server name
%S      url schema
%u      username

Example:
set inews="/usr/local/bin/inews -hS"
