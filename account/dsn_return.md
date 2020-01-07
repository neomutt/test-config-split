# dsn_return

- **Default**: ""
- **Flags**: DT_STRING
- **Variable**: C_DsnReturn

This variable controls how much of your message is returned in DSN
messages.  It may be set to either hdrs to return just the
message header, or full to return the full message.

Example:
set dsn_return=hdrs

Note: when using $sendmail for delivery, you should not enable
this unless you are either using Sendmail 8.8.x or greater or a MTA
providing a sendmail(1)-compatible interface supporting the -R option
for DSN. For SMTP delivery, DSN support is auto-detected so that it
depends on the server whether DSN will be used or not.
