# write_bcc

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_WriteBcc

Controls whether mutt writes out the ``Bcc:'' header when
preparing messages to be sent.  Some MTAs, such as Exim and
Courier, do not strip the ``Bcc:'' header; so it is advisable to
leave this unset unless you have a particular need for the header
to be in the sent message.

If mutt is set to deliver directly via SMTP(see $smtp_url),
this option does nothing: mutt will never write out the ``Bcc:''
header in this case.

Note this option only affects the sending of messages.  Fcc'ed
copies of a message will always contain the ``Bcc:'' header if
one exists.
