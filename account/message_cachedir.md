# message_cachedir

- **Default**: ""
- **Flags**: DT_STRING|DT_PATH
- **Variable**: C_MessageCachedir

Set this to a directory and NeoMutt will cache copies of messages from
your IMAP and POP servers here. You are free to remove entries at any
time.

When setting this variable to a directory, NeoMutt needs to fetch every
remote message only once and can perform regular expression searches
as fast as for local folders.

Also see the $message_cache_clean variable.
