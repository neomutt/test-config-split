# mime_subject

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_MimeSubject

If unset, 8-bit "subject:" line in article header will not be
encoded according to RFC2047 to base64.  This is useful when message
is Usenet article, because MIME for news is nonstandard feature.
