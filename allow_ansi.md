# allow_ansi

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_AllowAnsi

Controls whether ANSI color codes in messages (and color tags in
rich text messages) are to be interpreted.
Messages containing these codes are rare, but if this option is set,
their text will be colored accordingly. Note that this may override
your color choices, and even present a security problem, since a
message could include a line like
[-- PGP output follows ...

and give it the same color as your attachment color (see also
$crypt_timestamp).
