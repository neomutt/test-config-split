# ssl_ca_certificates_file

- **Default**: ""
- **Flags**: DT_STRING|DT_PATH
- **Variable**: C_SslCaCertificatesFile

This variable specifies a file containing trusted CA certificates.
Any server certificate that is signed with one of these CA
certificates is also automatically accepted. (GnuTLS only)

Example:
set ssl_ca_certificates_file=/etc/ssl/certs/ca-certificates.crt
