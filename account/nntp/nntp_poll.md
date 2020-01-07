# nntp_poll

- **Default**: 60
- **Flags**: DT_NUMBER|DT_NOT_NEGATIVE
- **Variable**: C_NntpPoll

The time in seconds until any operations on newsgroup except post new
article will cause recheck for new news.  If set to 0, NeoMutt will
recheck newsgroup on each operation in index (stepping, read article,
etc.).
