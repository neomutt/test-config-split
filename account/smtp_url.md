# smtp_url

- **Default**: ""
- **Flags**: DT_STRING|DT_SENSITIVE
- **Variable**: C_SmtpUrl

Defines the SMTP smarthost where sent messages should relayed for
delivery. This should take the form of an SMTP URL, e.g.:
smtp[s]://[user[:pass]@]host[:port]

where "[...]" denotes an optional part.
Setting this variable overrides the value of the $sendmail
variable.

Also see $write_bcc.
