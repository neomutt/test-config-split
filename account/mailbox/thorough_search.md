# thorough_search

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_ThoroughSearch

Affects the ~b and ~h search operations described in
section "patterns".  If set, the headers and body/attachments of
messages to be searched are decoded before searching. If unset,
messages are searched as they appear in the folder.

Users searching attachments or for non-ASCII characters should set
this value because decoding also includes MIME parsing/decoding and possible
character set conversions. Otherwise NeoMutt will attempt to match against the
raw message received (for example quoted-printable encoded or with encoded
headers) which may lead to incorrect search results.
