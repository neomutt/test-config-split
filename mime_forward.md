# mime_forward

- **Default**: no
- **Flags**: DT_QUAD
- **Variable**: C_MimeForward

When set, the message you are forwarding will be attached as a
separate message/rfc822 MIME part instead of included in the main body of the
message.  This is useful for forwarding MIME messages so the receiver
can properly view the message as it was delivered to you. If you like
to switch between MIME and not MIME from mail to mail, set this
variable to "ask-no" or "ask-yes".

Also see $forward_decode and $mime_forward_decode.
