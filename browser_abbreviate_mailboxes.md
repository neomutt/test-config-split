# browser_abbreviate_mailboxes

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_BrowserAbbreviateMailboxes

When this variable is set, NeoMutt will abbreviate mailbox
names in the browser mailbox list, using '~' and '='
shortcuts.

The default "alpha" setting of $sort_browser uses
locale-based sorting (using strcoll(3)), which ignores some
punctuation.  This can lead to some situations where the order
doesn't make intuitive sense.  In those cases, it may be
desirable to unset this variable.
