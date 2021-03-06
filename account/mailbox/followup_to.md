# followup_to

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_FollowupTo

Controls whether or not the "Mail-Followup-To:" header field is
generated when sending mail.  When set, NeoMutt will generate this
field when you are replying to a known mailing list, specified with
the "subscribe" or "lists" commands.

This field has two purposes.  First, preventing you from
receiving duplicate copies of replies to messages which you send
to mailing lists, and second, ensuring that you do get a reply
separately for any messages sent to known lists to which you are
not subscribed.

The header will contain only the list's address
for subscribed lists, and both the list address and your own
email address for unsubscribed lists.  Without this header, a
group reply to your message sent to a subscribed list will be
sent to both the list and your address, resulting in two copies
of the same email for you.
