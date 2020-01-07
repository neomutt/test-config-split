# sidebar_sort_method

- **Default**: order
- **Flags**: DT_SORT|DT_SORT_SIDEBAR
- **Variable**: C_SidebarSortMethod

Specifies how to sort entries in the file browser.  By default, the
entries are sorted alphabetically.  Valid values:
- alpha (alphabetically)
- count (all message count)
- flagged (flagged message count)
- name (alphabetically)
- new (unread message count)
- path (alphabetically)
- unread (unread message count)
- unsorted

You may optionally use the "reverse-" prefix to specify reverse sorting
order (example: "set sort_browser=reverse-date").
