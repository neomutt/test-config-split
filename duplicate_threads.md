# duplicate_threads

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_DuplicateThreads

This variable controls whether NeoMutt, when $sort is set to threads, threads
messages with the same Message-Id together.  If it is set, it will indicate
that it thinks they are duplicates of each other with an equals sign
in the thread tree.
