# query_format

- **Default**: "%4c %t %-25.25a %-25.25n %?e?(%e)?"
- **Flags**: DT_STRING|DT_NOT_EMPTY
- **Variable**: C_QueryFormat

This variable describes the format of the "query" menu. The
following printf(3)-style sequences are understood:
%a      Destination address
%c      Current entry number
%e      Extra information *
%n      Destination name
%t      "*" if current entry is tagged, a space otherwise
%>X     Right justify the rest of the string and pad with "X"
%|X     Pad to the end of the line with "X"
%*X     Soft-fill with character "X" as pad

For an explanation of "soft-fill", see the $index_format documentation.

* = can be optionally printed if nonzero, see the $status_format documentation.
