# text_flowed

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_TextFlowed

When set, NeoMutt will generate "format=flowed" bodies with a content type
of "text/plain; format=flowed".
This format is easier to handle for some mailing software, and generally
just looks like ordinary text.  To actually make use of this format's
features, you'll need support in your editor.

The option only controls newly composed messages.  Postponed messages,
resent messages, and draft messages (via -H on the command line) will
use the content-type of the source message.

Note that $indent_string is ignored when this option is set.
