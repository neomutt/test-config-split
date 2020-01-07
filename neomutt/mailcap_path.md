# mailcap_path

- **Default**: "~/.mailcap:/usr/share/neomutt/mailcap:/etc/mailcap:/etc/mailcap:/usr/etc/mailcap:/usr/local/etc/mailcap"
- **Flags**: DT_SLIST|SLIST_SEP_COLON
- **Variable**: C_MailcapPath

This variable specifies which files to consult when attempting to
display MIME bodies not directly supported by NeoMutt.  The default value
is generated during startup: see the ``mailcap'' section of the manual.

$mailcap_path is overridden by the environment variable $MAILCAPS.

The default search path is from RFC1524.
