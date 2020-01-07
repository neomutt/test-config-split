# compose_format

- **Default**: "-- NeoMutt: Compose  [Approx. msg size: %l   Atts: %a]%>-"
- **Flags**: DT_STRING
- **Variable**: C_ComposeFormat

Controls the format of the status line displayed in the "compose"
menu.  This string is similar to $status_format, but has its own
set of printf(3)-like sequences:
%a      Total number of attachments
%h      Local hostname
%l      Approximate size (in bytes) of the current message (see formatstrings-size)
%v      NeoMutt version string

See the text describing the $status_format option for more
information on how to set $compose_format.
