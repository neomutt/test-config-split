# query_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_QueryCommand

This specifies the command NeoMutt will use to make external address
queries.  The string may contain a "%s", which will be substituted
with the query string the user types.  NeoMutt will add quotes around the
string substituted for "%s" automatically according to shell quoting
rules, so you should avoid adding your own.  If no "%s" is found in
the string, NeoMutt will append the user's query to the end of the string.
See "query" for more information.
