# charset

- **Default**: ""
- **Flags**: DT_STRING|DT_NOT_EMPTY
- **Variable**: C_Charset

Character set your terminal uses to display and enter textual data.
It is also the fallback for $send_charset.

Upon startup NeoMutt tries to derive this value from environment variables
such as $LC_CTYPE or $LANG.

Note: It should only be set in case NeoMutt isn't able to determine the
character set used correctly.
