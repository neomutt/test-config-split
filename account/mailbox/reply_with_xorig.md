# reply_with_xorig

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_ReplyWithXorig

This variable provides a toggle. When active, the From: header will be
extracted from the current mail's 'X-Original-To:' header. This setting
does not have precedence over "reverse_realname".

Assuming 'fast_reply' is disabled, this option will prompt the user with a
prefilled From: header.
