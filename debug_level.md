# debug_level

- **Default**: 0
- **Flags**: DT_NUMBER
- **Variable**: C_DebugLevel

Debug logging is controlled by the variables $debug_file and $debug_level.

The debug level controls how much information is saved to the log file.
If you have a problem with NeoMutt, then enabling logging may help find the cause.
Levels 1-3 will usually provide enough information for writing a bug report.
Levels 4,5 will be extremely verbose.

Warning: Logging at high levels may save private information to the file.

This option can be enabled on the command line, "neomutt -d 2"

See also: $debug_file
