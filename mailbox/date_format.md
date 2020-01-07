# date_format

- **Default**: "!%a, %b %d, %Y at %I:%M:%S%p %Z"
- **Flags**: DT_STRING|DT_NOT_EMPTY
- **Variable**: C_DateFormat

This variable controls the format of the date printed by the "%d"
sequence in $index_format.  This is passed to the strftime(3)
function to process the date, see the man page for the proper syntax.

Unless the first character in the string is a bang ("!"), the month
and week day names are expanded according to the locale.
If the first character in the string is a
bang, the bang is discarded, and the month and week day names in the
rest of the string are expanded in the C locale (that is in US
English).
