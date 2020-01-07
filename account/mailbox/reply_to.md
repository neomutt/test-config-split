# reply_to

- **Default**: ask-yes
- **Flags**: DT_QUAD
- **Variable**: C_ReplyTo

If set, when replying to a message, NeoMutt will use the address listed
in the Reply-to: header as the recipient of the reply.  If unset,
it will use the address in the From: header field instead.  This
option is useful for reading a mailing list that sets the Reply-To:
header field to the list address and you want to send a private
message to the author of a message.
