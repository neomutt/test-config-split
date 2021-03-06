# hostname

- **Default**: ""
- **Flags**: DT_STRING
- **Variable**: C_Hostname

Specifies the fully-qualified hostname of the system NeoMutt is running on
containing the host's name and the DNS domain it belongs to. It is used
as the domain part (after "@") for local email addresses as well as
Message-Id headers.

If not specified in a config file, then NeoMutt will try to determine the hostname itself.

Optionally, NeoMutt can be compiled with a fixed domain name.

Also see $use_domain and $hidden_host.
