# smtp_authenticators

- **Default**: ""
- **Flags**: DT_SLIST|SLIST_SEP_COLON
- **Variable**: C_SmtpAuthenticators

This is a colon-delimited list of authentication methods NeoMutt may
attempt to use to log in to an SMTP server, in the order NeoMutt should
try them.  Authentication methods are any SASL mechanism, e.g. "plain",
"digest-md5", "gssapi" or "cram-md5".
This option is case-insensitive. If it is "unset"
(the default) NeoMutt will try all available methods, in order from
most-secure to least-secure. Support for the "plain" mechanism is
bundled; other mechanisms are provided by an external SASL library (look
for +USE_SASL in the output of neomutt -v).

Example:
set smtp_authenticators="digest-md5:cram-md5"
