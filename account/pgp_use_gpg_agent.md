# pgp_use_gpg_agent

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_PgpUseGpgAgent

If set, NeoMutt expects a gpg-agent(1) process will handle
private key passphrase prompts.  If unset, NeoMutt will prompt
for the passphrase and pass it via stdin to the pgp command.

Note that as of version 2.1, GnuPG automatically spawns an agent
and requires the agent be used for passphrase management.  Since
that version is increasingly prevalent, this variable now
defaults set.

NeoMutt works with a GUI or curses pinentry program.  A TTY pinentry
should not be used.

If you are using an older version of GnuPG without an agent running,
or another encryption program without an agent, you will need to
unset this variable.
(PGP only)
