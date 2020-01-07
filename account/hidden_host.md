# hidden_host

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_HiddenHost

When set, NeoMutt will skip the host name part of $hostname variable
when adding the domain part to addresses.  This variable does not
affect the generation of Message-IDs, and it will not lead to the
cut-off of first-level domains.
