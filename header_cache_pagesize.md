# header_cache_pagesize

- **Default**: 16384
- **Flags**: DT_LONG|DT_NOT_NEGATIVE
- **Variable**: C_HeaderCachePagesize

When NeoMutt is compiled with either gdbm or bdb4 as the header cache backend,
this option changes the database page size.  Too large or too small
values can waste space, memory, or CPU time. The default should be more
or less optimal for most use cases.
