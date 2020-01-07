# news_cache_dir

- **Default**: "~/.neomutt"
- **Flags**: DT_STRING|DT_PATH
- **Variable**: C_NewsCacheDir

This variable pointing to directory where NeoMutt will save cached news
articles and headers in. If unset, articles and headers will not be
saved at all and will be reloaded from the server each time.
