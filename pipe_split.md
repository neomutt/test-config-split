# pipe_split

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_PipeSplit

Used in connection with the <pipe-message> function following
<tag-prefix>.  If this variable is unset, when piping a list of
tagged messages NeoMutt will concatenate the messages and will pipe them
all concatenated.  When set, NeoMutt will pipe the messages one by one.
In both cases the messages are piped in the current sorted order,
and the $pipe_sep separator is added after each message.
