# mask

- **Default**: "!^\\.[^.]"
- **Flags**: DT_REGEX|DT_REGEX_MATCH_CASE|DT_REGEX_ALLOW_NOT|DT_REGEX_NOSUB
- **Variable**: C_Mask

A regular expression used in the file browser, optionally preceded by
the not operator "!".  Only files whose names match this mask
will be shown. The match is always case-sensitive.
