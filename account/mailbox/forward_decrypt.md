# forward_decrypt

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_ForwardDecrypt

Controls the handling of encrypted messages when forwarding a message.
When set, the outer layer of encryption is stripped off.  This
variable is only used if $mime_forward is set and
$mime_forward_decode is unset.
(PGP only)
