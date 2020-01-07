# pop_auth_try_all

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_PopAuthTryAll

If set, NeoMutt will try all available authentication methods.
When unset, NeoMutt will only fall back to other authentication
methods if the previous methods are unavailable. If a method is
available but authentication fails, NeoMutt will not connect to the POP server.
