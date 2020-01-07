# nm_unread_tag

- **Default**: "unread"
- **Flags**: DT_STRING
- **Variable**: C_NmUnreadTag

This variable specifies notmuch tag which is used for unread messages. The
variable is used to count unread messages in DB and set the unread flag when
modifiying tags. All other NeoMutt commands use standard (e.g. maildir) flags.
