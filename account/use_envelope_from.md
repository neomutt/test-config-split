# use_envelope_from

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_UseEnvelopeFrom

When set, NeoMutt will set the envelope sender of the message.
If $envelope_from_address is set, it will be used as the sender
address. If unset, NeoMutt will attempt to derive the sender from the
"From:" header.

Note that this information is passed to sendmail command using the
-f command line switch. Therefore setting this option is not useful
if the $sendmail variable already contains -f or if the
executable pointed to by $sendmail doesn't support the -f switch.
