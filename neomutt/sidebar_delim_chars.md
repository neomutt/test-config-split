# sidebar_delim_chars

- **Default**: "/."
- **Flags**: DT_STRING
- **Variable**: C_SidebarDelimChars

This contains the list of characters which you would like to treat
as folder separators for displaying paths in the sidebar.

Local mail is often arranged in directories: 'dir1/dir2/mailbox'.
set sidebar_delim_chars='/'

IMAP mailboxes are often named: 'folder1.folder2.mailbox'.
set sidebar_delim_chars='.'

See also: $sidebar_short_path, $sidebar_folder_indent, $sidebar_indent_string.
