# implicit_autoview

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_ImplicitAutoview

If set to "yes", NeoMutt will look for a mailcap entry with the
"copiousoutput" flag set for every MIME attachment it doesn't have
an internal viewer defined for.  If such an entry is found, NeoMutt will
use the viewer defined in that entry to convert the body part to text
form.
