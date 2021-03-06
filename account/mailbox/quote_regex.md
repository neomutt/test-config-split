# quote_regex

- **Default**: "^([ \t]*[|>:}#])+"
- **Flags**: DT_REGEX
- **Variable**: C_QuoteRegex

A regular expression used in the internal pager to determine quoted
sections of text in the body of a message. Quoted text may be filtered
out using the <toggle-quoted> command, or colored according to the
"color quoted" family of directives.

Higher levels of quoting may be colored differently ("color quoted1",
"color quoted2", etc.). The quoting level is determined by removing
the last character from the matched text and recursively reapplying
the regular expression until it fails to produce a match.

Match detection may be overridden by the $smileys regular expression.
