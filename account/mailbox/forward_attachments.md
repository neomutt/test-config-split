# forward_attachments

- **Default**: ask-yes
- **Flags**: DT_QUAD
- **Variable**: C_ForwardAttachments

When forwarding inline (i.e. $mime_forward unset or
answered with ``no'' and $forward_decode set), attachments
which cannot be decoded in a reasonable manner will be attached
to the newly composed message if this quadoption is set or
answered with ``yes''.
