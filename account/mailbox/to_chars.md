# to_chars

- **Default**: " +TCFLR"
- **Flags**: DT_MBTABLE
- **Variable**: C_ToChars

Controls the character used to indicate mail addressed to you.
Character Default Description
1       <space> The mail is not addressed to your address.
2       + You are the only recipient of the message.
3       T Your address appears in the "To:" header field, but you are not the only recipient of the message.
4       C Your address is specified in the "Cc:" header field, but you are not the only recipient.
5       F Indicates the mail that was sent by you.
6       L Indicates the mail was sent to a mailing-list you subscribe to.
7       R Your address appears in the "Reply-To:" header field but none of the above applies.
