# indent_string

- **Default**: "> "
- **Flags**: DT_STRING
- **Variable**: C_IndentString

Specifies the string to prepend to each line of text quoted in a
message to which you are replying.  You are strongly encouraged not to
change this value, as it tends to agitate the more fanatical netizens.

The value of this option is ignored if $text_flowed is set, because
the quoting mechanism is strictly defined for format=flowed.

This option is a format string, please see the description of
$index_format for supported printf(3)-style sequences.
