# auto_subscribe

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_AutoSubscribe

When set, NeoMutt assumes the presence of a List-Post header
means the recipient is subscribed to the list.  Unless the mailing list
is in the "unsubscribe" or "unlist" lists, it will be added
to the "subscribe" list.  Parsing and checking these things slows
header reading down, so this option is disabled by default.
