# autoedit

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_Autoedit

When set along with $edit_headers, NeoMutt will skip the initial
send-menu (prompting for subject and recipients) and allow you to
immediately begin editing the body of your
message.  The send-menu may still be accessed once you have finished
editing the body of your message.

Note: when this option is set, you can't use send-hooks that depend
on the recipients when composing a new (non-reply) message, as the initial
list of recipients is empty.

Also see $fast_reply.
