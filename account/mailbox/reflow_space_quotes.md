# reflow_space_quotes

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_ReflowSpaceQuotes

This option controls how quotes from format=flowed messages are displayed
in the pager and when replying (with $text_flowed unset).
When set, this option adds spaces after each level of quote marks, turning
">>>foo" into "> > > foo".

Note: If $reflow_text is unset, this option has no effect.
Also, this option does not affect replies when $text_flowed is set.
