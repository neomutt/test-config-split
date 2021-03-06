# attach_charset

- **Default**: ""
- **Flags**: DT_STRING
- **Variable**: C_AttachCharset

This variable is a colon-separated list of character encoding
schemes for text file attachments. NeoMutt uses this setting to guess
which encoding files being attached are encoded in to convert them to
a proper character set given in $send_charset.

If unset, the value of $charset will be used instead.
For example, the following configuration would work for Japanese
text handling:
set attach_charset="iso-2022-jp:euc-jp:shift_jis:utf-8"

Note: for Japanese users, "iso-2022-*" must be put at the head
of the value as shown above if included.
