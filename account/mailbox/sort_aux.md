# sort_aux

- **Default**: date
- **Flags**: DT_SORT|DT_SORT_AUX
- **Variable**: C_SortAux

This provides a secondary sort for messages in the "index" menu, used
when the $sort value is equal for two messages.

When sorting by threads, this variable controls how threads are sorted
in relation to other threads, and how the branches of the thread trees
are sorted.  This can be set to any value that $sort can, except
"threads" (in that case, NeoMutt will just use "date-sent").  You can also
specify the "last-" prefix in addition to the "reverse-" prefix, but "last-"
must come after "reverse-".  The "last-" prefix causes messages to be
sorted against its siblings by which has the last descendant, using
the rest of $sort_aux as an ordering.  For instance,
set sort_aux=last-date-received

would mean that if a new message is received in a
thread, that thread becomes the last one displayed (or the first, if
you have "set sort=reverse-threads".)

Note: For reversed-threads $sort
order, $sort_aux is reversed again (which is not the right thing to do,
but kept to not break any existing configuration setting).
