# from

- **Default**: ""
- **Flags**: DT_ADDRESS
- **Variable**: C_From

When set, this variable contains a default "from" address.  It
can be overridden using "my_hdr" (including from a "send-hook") and
$reverse_name.  This variable is ignored if $use_from is unset.

If not specified, then it may be read from the environment variable $EMAIL.
