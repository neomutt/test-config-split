# maildir_header_cache_verify

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_MaildirHeaderCacheVerify

Check for Maildir unaware programs other than NeoMutt having modified maildir
files when the header cache is in use.  This incurs one stat(2) per
message every time the folder is opened (which can be very slow for NFS
folders).
