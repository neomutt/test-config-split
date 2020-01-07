# hdrs

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_Hdrs

When unset, the header fields normally added by the "my_hdr"
command are not created.  This variable must be unset before
composing a new message or replying in order to take effect.  If set,
the user defined header fields are added to every new message.
