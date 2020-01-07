# net_inc

- **Default**: 10
- **Flags**: DT_NUMBER|DT_NOT_NEGATIVE
- **Variable**: C_NetInc

Operations that expect to transfer a large amount of data over the
network will update their progress every $net_inc kilobytes.
If set to 0, no progress messages will be displayed.

See also $read_inc, $write_inc and $net_inc.
