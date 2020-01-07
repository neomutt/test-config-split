# certificate_file

- **Default**: "~/.mutt_certificates"
- **Flags**: DT_STRING|DT_PATH
- **Variable**: C_CertificateFile

This variable specifies the file where the certificates you trust
are saved. When an unknown certificate is encountered, you are asked
if you accept it or not. If you accept it, the certificate can also
be saved in this file and further connections are automatically
accepted.

You can also manually add CA certificates in this file. Any server
certificate that is signed with one of these CA certificates is
also automatically accepted.

Example:
set certificate_file=~/.neomutt/certificates
