# braille_friendly

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_BrailleFriendly

When this variable is set, NeoMutt will place the cursor at the beginning
of the current line in menus, even when the $arrow_cursor variable
is unset, making it easier for blind persons using Braille displays to
follow these menus.  The option is unset by default because many
visual terminals don't permit making the cursor invisible.
