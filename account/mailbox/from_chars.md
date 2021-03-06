# from_chars

- **Default**: ""
- **Flags**: DT_MBTABLE
- **Variable**: C_FromChars

Controls the character used to prefix the %F and %L fields in the
index.
Character Description
1       Mail is written by you and has a To address, or has a known mailing list in the To address.
2       Mail is written by you and has a Cc address, or has a known mailing list in the Cc address.
3       Mail is written by you and has a Bcc address.
4       All remaining cases.

If this is empty or unset (default), the traditional long "To ",
"Cc " and "Bcc " prefixes are used.  If set but too short to
include a character for a particular case, a single space will be
prepended to the field.  To prevent any prefix at all from being
added in a particular case, use the special value CR (aka ^M)
for the corresponding character.

This slightly odd interface is necessitated by NeoMutt's handling of
string variables; one can't tell a variable that is unset from one
that is set to the empty string.
