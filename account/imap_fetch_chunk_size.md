# imap_fetch_chunk_size

- **Default**: 0
- **Flags**: DT_LONG|DT_NOT_NEGATIVE
- **Variable**: C_ImapFetchChunkSize

When set to a value greater than 0, new headers will be downloaded
in sets of this size.  If you have a very large mailbox, this might
prevent a timeout and disconnect when opening the mailbox, by sending
a FETCH per set of this size instead of a single FETCH for all new
headers.
