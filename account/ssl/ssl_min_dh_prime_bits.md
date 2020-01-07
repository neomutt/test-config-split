# ssl_min_dh_prime_bits

- **Default**: 0
- **Flags**: DT_NUMBER|DT_NOT_NEGATIVE
- **Variable**: C_SslMinDhPrimeBits

This variable specifies the minimum acceptable prime size (in bits)
for use in any Diffie-Hellman key exchange. A value of 0 will use
the default from the GNUTLS library. (GnuTLS only)
