# sort

- **Default**: date
- **Flags**: DT_SORT
- **Variable**: C_Sort

Specifies how to sort messages in the "index" menu.  Valid values
are:
- date or date-sent
- date-received
- from
- mailbox-order (unsorted)
- score
- size
- spam
- subject
- threads
- to

You may optionally use the "reverse-" prefix to specify reverse sorting
order.

Example:
set sort=reverse-date-sent
