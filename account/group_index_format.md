# group_index_format

- **Default**: "%4C %M%N %5s  %-45.45f %d"
- **Flags**: DT_STRING|DT_NOT_EMPTY
- **Variable**: C_GroupIndexFormat

This variable allows you to customize the newsgroup browser display to
your personal taste.  This string is similar to "index_format", but
has its own set of printf()-like sequences:
%C      Current newsgroup number
%d      Description of newsgroup (becomes from server)
%f      Newsgroup name
%M      - if newsgroup not allowed for direct post (moderated for example)
%N      N if newsgroup is new, u if unsubscribed, blank otherwise
%n      Number of new articles in newsgroup
%s      Number of unread articles in newsgroup
%>X     Right justify the rest of the string and pad with character "X"
%|X     Pad to the end of the line with character "X"
