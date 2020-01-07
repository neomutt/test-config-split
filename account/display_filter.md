# display_filter

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_DisplayFilter

When set, specifies a command used to filter messages.  When a message
is viewed it is passed as standard input to $display_filter, and the
filtered message is read from the standard output.

When preparing the message, NeoMutt inserts some escape sequences into the
text.  They are of the form: <esc>]9;XXX<bel> where "XXX" is a random
64-bit number.

If these escape sequences interfere with your filter, they can be removed
using a tool like ansifilter or sed 's/^\x1b]9;[0-9]\+\x7//'

If they are removed, then PGP and MIME headers will no longer be coloured.
This can be fixed by adding this to your config:
color body magenta default '^\[-- .* --\]$'.
