# reverse_name

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_ReverseName

It may sometimes arrive that you receive mail to a certain machine,
move the messages to another machine, and reply to some the messages
from there.  If this variable is set, the default From: line of
the reply messages is built using the address where you received the
messages you are replying to if that address matches your
"alternates".  If the variable is unset, or the address that would be
used doesn't match your "alternates", the From: line will use
your address on the current machine.

Also see the "alternates" command and $reverse_realname.
