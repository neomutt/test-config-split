# config_charset

- **Default**: ""
- **Flags**: DT_STRING
- **Variable**: C_ConfigCharset

When defined, NeoMutt will recode commands in rc files from this
encoding to the current character set as specified by $charset
and aliases written to $alias_file from the current character set.

Please note that if setting $charset it must be done before
setting $config_charset.

Recoding should be avoided as it may render unconvertable
characters as question marks which can lead to undesired
side effects (for example in regular expressions).
