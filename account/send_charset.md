# send_charset

- **Default**: "us-ascii:iso-8859-1:utf-8"
- **Flags**: DT_STRING
- **Variable**: C_SendCharset

A colon-delimited list of character sets for outgoing messages. NeoMutt will use the
first character set into which the text can be converted exactly.
If your $charset is not "iso-8859-1" and recipients may not
understand "UTF-8", it is advisable to include in the list an
appropriate widely used standard character set (such as
"iso-8859-2", "koi8-r" or "iso-2022-jp") either instead of or after
"iso-8859-1".

In case the text can't be converted into one of these exactly,
NeoMutt uses $charset as a fallback.
