# sig_dashes

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_SigDashes

If set, a line containing "-- " (note the trailing space) will be inserted before your
$signature.  It is strongly recommended that you not unset
this variable unless your signature contains just your name.  The
reason for this is because many software packages use "-- \n" to
detect your signature.  For example, NeoMutt has the ability to highlight
the signature in a different color in the built-in pager.
