# reflow_text

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_ReflowText

When set, NeoMutt will reformat paragraphs in text/plain
parts marked format=flowed.  If unset, NeoMutt will display paragraphs
unaltered from how they appear in the message body.  See RFC3676 for
details on the format=flowed format.

Also see $reflow_wrap, and $wrap.
