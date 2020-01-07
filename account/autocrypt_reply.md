# autocrypt_reply

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_AutocryptReply

When set, replying to an autocrypt email automatically
enables autocrypt in the reply.  You may want to unset this if you're using
the same key for autocrypt as normal web-of-trust, so that autocrypt
isn't forced on for all encrypted replies.
(Autocrypt only)
