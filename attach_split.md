# attach_split

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_AttachSplit

If this variable is unset, when operating (saving, printing, piping,
etc) on a list of tagged attachments, NeoMutt will concatenate the
attachments and will operate on them as a single attachment. The
$attach_sep separator is added after each attachment. When set,
NeoMutt will operate on the attachments one by one.
