# spoolfile

- **Default**: ""
- **Flags**: DT_STRING|DT_PATH|DT_MAILBOX
- **Variable**: C_Spoolfile

If your spool mailbox is in a non-default place where NeoMutt can't find
it, you can specify its location with this variable. The description from
"named-mailboxes" or "virtual-mailboxes" may be used for the spoolfile.

If not specified, then the environment variables $MAIL and
$MAILDIR will be checked.
