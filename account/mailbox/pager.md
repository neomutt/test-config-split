# pager

- **Default**: "builtin"
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_Pager

This variable specifies which pager you would like to use to view
messages. The value "builtin" means to use the built-in pager, otherwise this
variable should specify the pathname of the external pager you would
like to use.

Using an external pager may have some disadvantages: Additional
keystrokes are necessary because you can't call NeoMutt functions
directly from the pager, and screen resizes cause lines longer than
the screen width to be badly formatted in the help menu.
