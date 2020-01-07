# encode_from

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_EncodeFrom

When set, NeoMutt will quoted-printable encode messages when
they contain the string "From " (note the trailing space) in the beginning of a line.
This is useful to avoid the tampering certain mail delivery and transport
agents tend to do with messages (in order to prevent tools from
misinterpreting the line as a mbox message separator).
