# debug_file

- **Default**: "~/.neomuttdebug"
- **Flags**: DT_STRING|DT_PATH
- **Variable**: C_DebugFile

Debug logging is controlled by the variables $debug_file and $debug_level.
$debug_file specifies the root of the filename.  NeoMutt will add "0" to the end.
Each time NeoMutt is run with logging enabled, the log files are rotated.
A maximum of five log files are kept, numbered 0 (most recent) to 4 (oldest).

This option can be enabled on the command line, "neomutt -l mylog"

See also: $debug_level
