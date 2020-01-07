# nntp_authenticators

- **Default**: ""
- **Flags**: DT_STRING
- **Variable**: C_NntpAuthenticators

This is a colon-delimited list of authentication methods NeoMutt may
attempt to use to log in to a news server, in the order NeoMutt should
try them.  Authentication methods are either "user" or any
SASL mechanism, e.g. "digest-md5", "gssapi" or "cram-md5".
This option is case-insensitive.  If it's unset (the default)
NeoMutt will try all available methods, in order from most-secure to
least-secure.

Example:
set nntp_authenticators="digest-md5:user"

Note: NeoMutt will only fall back to other authentication methods if
the previous methods are unavailable. If a method is available but
authentication fails, NeoMutt will not connect to the IMAP server.
