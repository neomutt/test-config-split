# mh_purge

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_MhPurge

When unset, NeoMutt will mimic mh's behavior and rename deleted messages
to ,<old file name> in mh folders instead of really deleting
them. This leaves the message on disk but makes programs reading the folder
ignore it. If the variable is set, the message files will simply be
deleted.

This option is similar to $maildir_trash for Maildir folders.
