# print_decode

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_PrintDecode

Used in connection with the <print-message> command.  If this
option is set, the message is decoded before it is passed to the
external command specified by $print_command.  If this option
is unset, no processing will be applied to the message when
printing it.  The latter setting may be useful if you are using
some advanced printer filter which is able to properly format
e-mail messages for printing.
