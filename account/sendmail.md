# sendmail

- **Default**: "/usr/sbin/sendmail -oem -oi"
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_Sendmail

Specifies the program and arguments used to deliver mail sent by NeoMutt.
NeoMutt expects that the specified program interprets additional
arguments as recipient addresses.  NeoMutt appends all recipients after
adding a -- delimiter (if not already present).  Additional
flags, such as for $use_8bitmime, $use_envelope_from,
$dsn_notify, or $dsn_return will be added before the delimiter.

See also: $write_bcc.
