# pgp_check_gpg_decrypt_status_fd

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_PgpCheckGpgDecryptStatusFd

If set, NeoMutt will check the status file descriptor output
of $pgp_decrypt_command and $pgp_decode_command for GnuPG status codes
indicating successful decryption.  This will check for the presence of
DECRYPTION_OKAY, absence of DECRYPTION_FAILED, and that all
PLAINTEXT occurs between the BEGIN_DECRYPTION and END_DECRYPTION
status codes.

If unset, NeoMutt will instead match the status fd output
against $pgp_decryption_okay.
(PGP only)
