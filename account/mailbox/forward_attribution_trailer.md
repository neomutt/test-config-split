# forward_attribution_trailer

- **Default**: "----- End forwarded message -----"
- **Flags**: DT_STRING
- **Variable**: C_ForwardAttributionTrailer

This is the string that will follow a message which has been forwarded
in the main body of a message (when $mime_forward is unset).
For a full listing of defined printf(3)-like sequences see
the section on $index_format.  See also $attribution_locale.
