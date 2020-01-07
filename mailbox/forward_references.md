# forward_references

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_ForwardReferences

When set, forwarded messages set the "In-Reply-To:" and
"References:" headers in the same way as normal replies would. Hence the
forwarded message becomes part of the original thread instead of starting
a new one.
