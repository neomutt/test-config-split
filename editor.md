# editor

- **Default**: "vi"
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_Editor

This variable specifies which editor is used by NeoMutt.
It defaults to the value of the $VISUAL, or $EDITOR, environment
variable, or to the string "vi" if neither of those are set.

The $editor string may contain a %s escape, which will be replaced by the name
of the file to be edited.  If the %s escape does not appear in $editor, a
space and the name to be edited are appended.

The resulting string is then executed by running
sh -c 'string'

where string is the expansion of $editor described above.
