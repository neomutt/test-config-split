# mailcap_sanitize

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_MailcapSanitize

If set, NeoMutt will restrict possible characters in mailcap % expandos
to a well-defined set of safe characters.  This is the safe setting,
but we are not sure it doesn't break some more advanced MIME stuff.

DON'T CHANGE THIS SETTING UNLESS YOU ARE REALLY SURE WHAT YOU ARE
DOING!
