# mail_check_stats

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_MailCheckStats

When set, NeoMutt will periodically calculate message
statistics of a mailbox while polling for new mail.  It will
check for unread, flagged, and total message counts.  Because
this operation is more performance intensive, it defaults to
unset, and has a separate option, $mail_check_stats_interval, to
control how often to update these counts.

Message statistics can also be explicitly calculated by invoking the
<check-stats> function.
