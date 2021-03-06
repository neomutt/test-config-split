# ignore_list_reply_to

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_IgnoreListReplyTo

Affects the behavior of the <reply> function when replying to
messages from mailing lists (as defined by the "subscribe" or
"lists" commands).  When set, if the "Reply-To:" field is
set to the same value as the "To:" field, NeoMutt assumes that the
"Reply-To:" field was set by the mailing list to automate responses
to the list, and will ignore this field.  To direct a response to the
mailing list when this option is set, use the <list-reply>
function; <group-reply> will reply to both the sender and the
list.
