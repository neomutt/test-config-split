# forward_decode

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_ForwardDecode

Controls the decoding of complex MIME messages into text/plain when
forwarding a message.  The message header is also RFC2047 decoded.
This variable is only used, if $mime_forward is unset,
otherwise $mime_forward_decode is used instead.
