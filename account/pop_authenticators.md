# pop_authenticators

- **Default**: ""
- **Flags**: DT_SLIST|SLIST_SEP_COLON
- **Variable**: C_PopAuthenticators

This is a colon-delimited list of authentication methods NeoMutt may
attempt to use to log in to an POP server, in the order NeoMutt should
try them.  Authentication methods are either "user", "apop" or any
SASL mechanism, e.g. "digest-md5", "gssapi" or "cram-md5".
This option is case-insensitive. If this option is unset
(the default) NeoMutt will try all available methods, in order from
most-secure to least-secure.

Example:
set pop_authenticators="digest-md5:apop:user"
