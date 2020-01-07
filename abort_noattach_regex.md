# abort_noattach_regex

- **Default**: "\\<(attach|attached|attachments?)\\>"
- **Flags**: DT_REGEX
- **Variable**: C_AbortNoattachRegex

Specifies a regular expression to match against the body of the message, to
determine if an attachment was mentioned but mistakenly forgotten.  If it
matches, $abort_noattach will be consulted to determine if message sending
will be aborted.

Like other regular expressions in NeoMutt, the search is case sensitive
if the pattern contains at least one upper case letter, and case
insensitive otherwise.
