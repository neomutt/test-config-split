# sort_browser

- **Default**: alpha
- **Flags**: DT_SORT|DT_SORT_BROWSER
- **Variable**: C_SortBrowser

Specifies how to sort entries in the file browser.  By default, the
entries are sorted alphabetically.  Valid values:
- alpha (alphabetically)
- count (all message count)
- date
- desc (description)
- new (new message count)
- size
- unsorted

You may optionally use the "reverse-" prefix to specify reverse sorting
order (example: "set sort_browser=reverse-date").
