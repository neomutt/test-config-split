# imap_headers

- **Default**: ""
- **Flags**: DT_STRING
- **Variable**: C_ImapHeaders

NeoMutt requests these header fields in addition to the default headers
("Date:", "From:", "Sender:", "Subject:", "To:", "Cc:", "Message-Id:",
"References:", "Content-Type:", "Content-Description:", "In-Reply-To:",
"Reply-To:", "Lines:", "List-Post:", "X-Label:") from IMAP
servers before displaying the index menu. You may want to add more
headers for spam detection.

Note: This is a space separated list, items should be uppercase
and not contain the colon, e.g. "X-BOGOSITY X-SPAM-STATUS" for the
"X-Bogosity:" and "X-Spam-Status:" header fields.
