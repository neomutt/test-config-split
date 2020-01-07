# include_encrypted

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_IncludeEncrypted

Controls whether or not NeoMutt includes separately encrypted attachment
contents when replying.

This variable was added to prevent accidental exposure of encrypted
contents when replying to an attacker.  If a previously encrypted message
were attached by the attacker, they could trick an unwary recipient into
decrypting and including the message in their reply.
