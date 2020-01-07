# spam_separator

- **Default**: ","
- **Flags**: DT_STRING
- **Variable**: C_SpamSeparator

This variable controls what happens when multiple spam headers
are matched: if unset, each successive header will overwrite any
previous matches value for the spam label. If set, each successive
match will append to the previous, using this variable's value as a
separator.
