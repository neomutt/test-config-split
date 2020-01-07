# sidebar_short_path

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_SidebarShortPath

By default the sidebar will show the mailbox's path, relative to the
$folder variable. Setting sidebar_shortpath=yes will shorten the
names relative to the previous name. Here's an example:
shortpath=no shortpath=yes shortpath=yes, folderindent=yes, indentstr=".."
fruit           fruit         fruit
fruit.apple  apple         ..apple
fruit.banana banana        ..banana
fruit.cherry cherry        ..cherry

See also: $sidebar_delim_chars, $sidebar_folder_indent,
$sidebar_indent_string, $sidebar_component_depth.
