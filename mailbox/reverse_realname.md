# reverse_realname

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_ReverseRealname

This variable fine-tunes the behavior of the $reverse_name feature.

When it is unset, NeoMutt will remove the real name part of a
matching address.  This allows the use of the email address
without having to also use what the sender put in the real name
field.

When it is set, NeoMutt will use the matching address as-is.

In either case, a missing real name will be filled in afterwards
using the value of $realname.
