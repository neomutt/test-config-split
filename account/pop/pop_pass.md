# pop_pass

- **Default**: ""
- **Flags**: DT_STRING|DT_SENSITIVE
- **Variable**: C_PopPass

Specifies the password for your POP account.  If unset, NeoMutt will
prompt you for your password when you open a POP mailbox.

Warning: you should only use this option when you are on a
fairly secure machine, because the superuser can read your neomuttrc
even if you are the only one who can read the file.
