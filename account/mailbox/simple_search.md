# simple_search

- **Default**: "~f %s | ~s %s"
- **Flags**: DT_STRING
- **Variable**: C_SimpleSearch

Specifies how NeoMutt should expand a simple search into a real search
pattern.  A simple search is one that does not contain any of the "~" pattern
operators.  See "patterns" for more information on search patterns.

For example, if you simply type "joe" at a search or limit prompt, NeoMutt
will automatically expand it to the value specified by this variable by
replacing "%s" with the supplied string.
For the default value, "joe" would be expanded to: "~f joe | ~s joe".
