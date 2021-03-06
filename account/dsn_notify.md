# dsn_notify

- **Default**: ""
- **Flags**: DT_STRING
- **Variable**: C_DsnNotify

This variable sets the request for when notification is returned.  The
string consists of a comma separated list (no spaces!) of one or more
of the following: never, to never request notification,
failure, to request notification on transmission failure,
delay, to be notified of message delays, success, to be
notified of successful transmission.

Example:
set dsn_notify="failure,delay"

Note: when using $sendmail for delivery, you should not enable
this unless you are either using Sendmail 8.8.x or greater or a MTA
providing a sendmail(1)-compatible interface supporting the -N option
for DSN. For SMTP delivery, DSN support is auto-detected so that it
depends on the server whether DSN will be used or not.
