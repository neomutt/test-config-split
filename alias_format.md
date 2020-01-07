# alias_format

- **Default**: "%4n %2f %t %-10a   %r"
- **Flags**: DT_STRING|DT_NOT_EMPTY
- **Variable**: C_AliasFormat

Specifies the format of the data displayed for the "alias" menu.  The
following printf(3)-style sequences are available:
%a      Alias name
%f      Flags - currently, a "d" for an alias marked for deletion
%n      Index number
%r      Address which alias expands to
%t      Character which indicates if the alias is tagged for inclusion
