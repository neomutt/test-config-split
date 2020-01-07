# time_inc

- **Default**: 0
- **Flags**: DT_NUMBER|DT_NOT_NEGATIVE
- **Variable**: C_TimeInc

Along with $read_inc, $write_inc, and $net_inc, this
variable controls the frequency with which progress updates are
displayed. It suppresses updates less than $time_inc milliseconds
apart. This can improve throughput on systems with slow terminals,
or when running NeoMutt on a remote system.

Also see the "tuning" section of the manual for performance considerations.
