# default_hook

- **Default**: "~f %s !~P | (~P ~C %s)"
- **Flags**: DT_STRING
- **Variable**: C_DefaultHook

This variable controls how "message-hook", "reply-hook", "send-hook",
"send2-hook", "save-hook", and "fcc-hook" will
be interpreted if they are specified with only a simple regex,
instead of a matching pattern.  The hooks are expanded when they are
declared, so a hook will be interpreted according to the value of this
variable at the time the hook is declared.

The default value matches
if the message is either from a user matching the regular expression
given, or if it is from you (if the from address matches
"alternates") and is to or cc'ed to a user matching the given
regular expression.
