# fcc_before_send

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_FccBeforeSend

When this variable is set, FCCs will occur before sending
the message.  Before sending, the message cannot be manipulated,
so it will be stored the exact same as sent:
$fcc_attach and $fcc_clear will be ignored (using their default
values).

When unset, the default, FCCs will occur after sending.
Variables $fcc_attach and $fcc_clear will be respected, allowing
it to be stored without attachments or encryption/signing if
desired.
