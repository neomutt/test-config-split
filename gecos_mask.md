# gecos_mask

- **Default**: "^[^,]*"
- **Flags**: DT_REGEX
- **Variable**: C_GecosMask

A regular expression used by NeoMutt to parse the GECOS field of a password
entry when expanding the alias.  The default value
will return the string up to the first "," encountered.
If the GECOS field contains a string like "lastname, firstname" then you
should set it to ".*".

This can be useful if you see the following behavior: you address an e-mail
to user ID "stevef" whose full name is "Steve Franklin".  If NeoMutt expands
"stevef" to '"Franklin" stevef@foo.bar' then you should set the $gecos_mask to
a regular expression that will match the whole name so NeoMutt will expand
"Franklin" to "Franklin, Steve".
