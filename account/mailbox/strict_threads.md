# strict_threads

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_StrictThreads

If set, threading will only make use of the "In-Reply-To" and
"References:" fields when you $sort by message threads.  By
default, messages with the same subject are grouped together in
"pseudo threads.". This may not always be desirable, such as in a
personal mailbox where you might have several unrelated messages with
the subjects like "hi" which will get grouped together. See also
$sort_re for a less drastic way of controlling this
behavior.
