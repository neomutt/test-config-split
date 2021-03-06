# timeout

- **Default**: 600
- **Flags**: DT_NUMBER|DT_NOT_NEGATIVE
- **Variable**: C_Timeout

When NeoMutt is waiting for user input either idling in menus or
in an interactive prompt, NeoMutt would block until input is
present. Depending on the context, this would prevent certain
operations from working, like checking for new mail or keeping
an IMAP connection alive.

This variable controls how many seconds NeoMutt will at most wait
until it aborts waiting for input, performs these operations and
continues to wait for input.

A value of zero or less will cause NeoMutt to never time out.
