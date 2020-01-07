# pager_index_lines

- **Default**: 0
- **Flags**: DT_NUMBER|DT_NOT_NEGATIVE
- **Variable**: C_PagerIndexLines

Determines the number of lines of a mini-index which is shown when in
the pager.  The current message, unless near the top or bottom of the
folder, will be roughly one third of the way down this mini-index,
giving the reader the context of a few messages before and after the
message.  This is useful, for example, to determine how many messages
remain to be read in the current thread.  One of the lines is reserved
for the status bar from the index, so a setting of 6
will only show 5 lines of the actual index.  A value of 0 results in
no index being shown.  If the number of messages in the current folder
is less than $pager_index_lines, then the index will only use as
many lines as it needs.
