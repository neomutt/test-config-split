# print_split

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_PrintSplit

Used in connection with the <print-message> command.  If this option
is set, the command specified by $print_command is executed once for
each message which is to be printed.  If this option is unset,
the command specified by $print_command is executed only once, and
all the messages are concatenated, with a form feed as the message
separator.

Those who use the enscript(1) program's mail-printing mode will
most likely want to set this option.
