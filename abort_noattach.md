# abort_noattach

- **Default**: no
- **Flags**: DT_QUAD
- **Variable**: C_AbortNoattach

If set to yes, when composing messages containing the regular
expression specified by $abort_noattach_regex and no attachments are
given, composition will be aborted. If set to no, composing messages
as such will never be aborted.

Example:
set abort_noattach_regex = "\\<attach(|ed|ments?)\\>"
