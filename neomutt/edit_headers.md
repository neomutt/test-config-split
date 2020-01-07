# edit_headers

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_EditHeaders

This option allows you to edit the header of your outgoing messages
along with the body of your message.

Although the compose menu may have localized header labels, the
labels passed to your editor will be standard RFC2822 headers,
(e.g. To:, Cc:, Subject:).  Headers added in your editor must
also be RFC2822 headers, or one of the pseudo headers listed in
"edit-header".  NeoMutt will not understand localized header
labels, just as it would not when parsing an actual email.

Note that changes made to the References: and Date: headers are
ignored for interoperability reasons.
