# status_chars

- **Default**: "-*%A"
- **Flags**: DT_MBTABLE
- **Variable**: C_StatusChars

Controls the characters used by the "%r" indicator in $status_format.
Character Default Description
1       - Mailbox is unchanged
2       * Mailbox has been changed and needs to be resynchronized
3       % Mailbox is read-only, or will not be written when exiting.
        (You can toggle whether to write changes to a mailbox
        with the <toggle-write> operation, bound by default
        to "%")
4       A Folder opened in attach-message mode.
        (Certain operations like composing a new mail, replying,
        forwarding, etc. are not permitted in this mode)
