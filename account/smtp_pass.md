# smtp_pass

- **Default**: ""
- **Flags**: DT_STRING|DT_SENSITIVE
- **Variable**: C_SmtpPass

Specifies the password for your SMTP account.  If unset, NeoMutt will
prompt you for your password when you first send mail via SMTP.
See $smtp_url to configure NeoMutt to send mail via SMTP.

Warning: you should only use this option when you are on a
fairly secure machine, because the superuser can read your neomuttrc even
if you are the only one who can read the file.
