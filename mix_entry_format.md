# mix_entry_format

- **Default**: "%4n %c %-16s %a"
- **Flags**: DT_STRING|DT_NOT_EMPTY
- **Variable**: C_MixEntryFormat

This variable describes the format of a remailer line on the mixmaster
chain selection screen.  The following printf(3)-like sequences are
supported:
%a      The remailer's e-mail address
%c      Remailer capabilities
%n      The running number on the menu
%s      The remailer's short name
