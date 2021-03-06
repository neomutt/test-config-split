# alias_file

- **Default**: "~/.neomuttrc"
- **Flags**: DT_STRING|DT_PATH
- **Variable**: C_AliasFile

The default file in which to save aliases created by the
<create-alias> function. Entries added to this file are
encoded in the character set specified by $config_charset if it
is set or the current character set otherwise.

Note: NeoMutt will not automatically source this file; you must
explicitly use the "source" command for it to be executed in case
this option points to a dedicated alias file.

The default for this option is the currently used neomuttrc file, or
"~/.neomuttrc" if no user neomuttrc was found.
