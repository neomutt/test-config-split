# mime_type_query_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_MimeTypeQueryCommand

This specifies a command to run, to determine the mime type of a
new attachment when composing a message.  Unless
$mime_type_query_first is set, this will only be run if the
attachment's extension is not found in the mime.types file.

The string may contain a "%s", which will be substituted with the
attachment filename.  NeoMutt will add quotes around the string substituted
for "%s" automatically according to shell quoting rules, so you should
avoid adding your own.  If no "%s" is found in the string, NeoMutt will
append the attachment filename to the end of the string.

The command should output a single line containing the
attachment's mime type.

Suggested values are "xdg-mime query filetype" or
"file -bi".
