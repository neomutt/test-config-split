# imap_authenticators

- **Default**: ""
- **Flags**: DT_SLIST|SLIST_SEP_COLON
- **Variable**: C_ImapAuthenticators

This is a colon-delimited list of authentication methods NeoMutt may
attempt to use to log in to an IMAP server, in the order NeoMutt should
try them.  Authentication methods are either "login" or the right
side of an IMAP "AUTH=xxx" capability string, e.g. "digest-md5", "gssapi"
or "cram-md5". This option is case-insensitive. If it's
unset (the default) NeoMutt will try all available methods,
in order from most-secure to least-secure.

Example:
set imap_authenticators="gssapi:cram-md5:login"

Note: NeoMutt will only fall back to other authentication methods if
the previous methods are unavailable. If a method is available but
authentication fails, NeoMutt will not connect to the IMAP server.
