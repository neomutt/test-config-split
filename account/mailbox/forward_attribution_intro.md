# forward_attribution_intro

- **Default**: "----- Forwarded message from %f -----"
- **Flags**: DT_STRING
- **Variable**: C_ForwardAttributionIntro

This is the string that will precede a message which has been forwarded
in the main body of a message (when $mime_forward is unset).
For a full listing of defined printf(3)-like sequences see
the section on $index_format.  See also $attribution_locale.
