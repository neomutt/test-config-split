# smime_decrypt_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_SmimeDecryptCommand

This format string specifies a command which is used to decrypt
application/x-pkcs7-mime attachments.

The OpenSSL command formats have their own set of printf(3)-like sequences
similar to PGP's:
%f      Expands to the name of a file containing a message.
%s      Expands to the name of a file containing the signature part
                   of a multipart/signed attachment when verifying it.
%k      The key-pair specified with $smime_default_key
%i      Intermediate certificates
%c      One or more certificate IDs.
%a      The algorithm used for encryption.
%d      The message digest algorithm specified with $smime_sign_digest_alg.
%C      CA location:  Depending on whether $smime_ca_location
                   points to a directory or file, this expands to
                   "-CApath $smime_ca_location" or "-CAfile $smime_ca_location".

For examples on how to configure these formats, see the smime.rc in
the samples/ subdirectory which has been installed on your system
alongside the documentation.
(S/MIME only)
