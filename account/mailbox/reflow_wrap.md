# reflow_wrap

- **Default**: 78
- **Flags**: DT_NUMBER
- **Variable**: C_ReflowWrap

This variable controls the maximum paragraph width when reformatting text/plain
parts when $reflow_text is set.  When the value is 0, paragraphs will
be wrapped at the terminal's right margin.  A positive value sets the
paragraph width relative to the left margin.  A negative value set the
paragraph width relative to the right margin.

Also see $wrap.
