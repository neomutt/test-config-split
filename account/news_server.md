# news_server

- **Default**: ""
- **Flags**: DT_STRING
- **Variable**: C_NewsServer

This variable specifies domain name or address of NNTP server.

You can also specify username and an alternative port for each news server,
e.g. [[s]news://][username[:password]@]server[:port]

This option can also be set using the command line option "-g", the
environment variable $NNTPSERVER, or putting the server name in the
file "/etc/nntpserver".
