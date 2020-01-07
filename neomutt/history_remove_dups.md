# history_remove_dups

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_HistoryRemoveDups

When set, all of the string history will be scanned for duplicates
when a new entry is added.  Duplicate entries in the $history_file will
also be removed when it is periodically compacted.
