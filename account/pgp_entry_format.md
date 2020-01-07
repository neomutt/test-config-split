# pgp_entry_format

- **Default**: "%4n %t%f %4l/0x%k %-4a %2c %u"
- **Flags**: DT_STRING|DT_NOT_EMPTY
- **Variable**: C_PgpEntryFormat

This variable allows you to customize the PGP key selection menu to
your personal taste. This string is similar to $index_format, but
has its own set of printf(3)-like sequences:
%a      Algorithm
%c      Capabilities
%f      Flags
%k      Key id
%l      Key length
%n      Number
%p      Protocol
%t      Trust/validity of the key-uid association
%u      User id
%[<s>]  Date of the key where <s> is an strftime(3) expression

(PGP only)
