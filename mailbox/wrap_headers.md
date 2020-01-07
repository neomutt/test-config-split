# wrap_headers

- **Default**: 78
- **Flags**: DT_NUMBER|DT_NOT_NEGATIVE
- **Variable**: C_WrapHeaders

This option specifies the number of characters to use for wrapping
an outgoing message's headers. Allowed values are between 78 and 998
inclusive.

Note: This option usually shouldn't be changed. RFC5233
recommends a line length of 78 (the default), so please only change
this setting when you know what you're doing.
