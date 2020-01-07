# pager_context

- **Default**: 0
- **Flags**: DT_NUMBER|DT_NOT_NEGATIVE
- **Variable**: C_PagerContext

This variable controls the number of lines of context that are given
when displaying the next or previous page in the internal pager.  By
default, NeoMutt will display the line after the last one on the screen
at the top of the next page (0 lines of context).

This variable also specifies the amount of context given for search
results. If positive, this many lines will be given before a match,
if 0, the match will be top-aligned.
