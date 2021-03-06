# wait_key

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_WaitKey

Controls whether NeoMutt will ask you to press a key after an external command
has been invoked by these functions: <shell-escape>,
<pipe-message>, <pipe-entry>, <print-message>,
and <print-entry> commands.

It is also used when viewing attachments with "auto_view", provided
that the corresponding mailcap entry has a needsterminal flag,
and the external program is interactive.

When set, NeoMutt will always ask for a key. When unset, NeoMutt will wait
for a key only if the external command returned a non-zero status.
