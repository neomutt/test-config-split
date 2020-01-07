# tmpdir

- **Default**: "/tmp"
- **Flags**: DT_STRING|DT_PATH
- **Variable**: C_Tmpdir

This variable allows you to specify where NeoMutt will place its
temporary files needed for displaying and composing messages.

If this variable is not set, the environment variable $TMPDIR is
used.  Failing that, then "/tmp" is used.
