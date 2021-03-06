# header_cache

- **Default**: ""
- **Flags**: DT_STRING|DT_PATH
- **Variable**: C_HeaderCache

This variable points to the header cache database. If the path points to
an existing directory, NeoMutt will create a dedicated header cache
database per folder. Otherwise, the path points to a regular file, which
will be created as needed and used as a shared global header cache for
all folders.
By default it is unset so no header caching will be used.

Header caching can greatly improve speed when opening POP, IMAP
MH or Maildir folders, see "caching" for details.
