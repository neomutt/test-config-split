# meta_key

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_MetaKey

If set, forces NeoMutt to interpret keystrokes with the high bit (bit 8)
set as if the user had pressed the Esc key and whatever key remains
after having the high bit removed.  For example, if the key pressed
has an ASCII value of 0xf8, then this is treated as if the user had
pressed Esc then "x".  This is because the result of removing the
high bit from 0xf8 is 0x78, which is the ASCII character
"x".
