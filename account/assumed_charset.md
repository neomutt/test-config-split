# assumed_charset

- **Default**: ""
- **Flags**: DT_STRING
- **Variable**: C_AssumedCharset

This variable is a colon-separated list of character encoding
schemes for messages without character encoding indication.
Header field values and message body content without character encoding
indication would be assumed that they are written in one of this list.
By default, all the header fields and message body without any charset
indication are assumed to be in "us-ascii".

For example, Japanese users might prefer this:
set assumed_charset="iso-2022-jp:euc-jp:shift_jis:utf-8"

However, only the first content is valid for the message body.
