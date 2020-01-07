# message_cache_clean

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_MessageCacheClean

If set, NeoMutt will clean out obsolete entries from the message cache when
the mailbox is synchronized. You probably only want to set it
every once in a while, since it can be a little slow
(especially for large folders).
