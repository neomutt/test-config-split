# autocrypt_acct_format

- **Default**: "%4n %-30a %20p %10s"
- **Flags**: DT_STRING
- **Variable**: C_AutocryptAcctFormat

This variable describes the format of the ``autocrypt account'' menu.
The following printf(3)-style sequences are understood
%a      email address
%k      gpg keyid
%n      current entry number
%p      prefer-encrypt flag
%s      status flag (active/inactive)

(Autocrypt only)
