# header_cache_compress

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_HeaderCacheCompress

When NeoMutt is compiled with qdbm, tokyocabinet or kyotocabinet
as header cache backend, this option determines whether the
database will be compressed. Compression results in database
files roughly being one fifth of the usual diskspace, but the
decompression can result in a slower opening of cached folder(s)
which in general is still much faster than opening non header
cached folders.
