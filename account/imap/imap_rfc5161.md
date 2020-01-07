# imap_rfc5161

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_ImapRfc5161

When set, NeoMutt will use the IMAP ENABLE extension (RFC 5161) to
select CAPABILITIES. Some servers (notably Coremail System IMap Server) do
not properly respond to ENABLE commands, which might cause NeoMutt to hang.
If your connection seems to freeze at login, try unsetting this. See also
https://github.com/neomutt/neomutt/issues/1689
