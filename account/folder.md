# folder

- **Default**: "~/Mail"
- **Flags**: DT_STRING|DT_PATH|DT_MAILBOX
- **Variable**: C_Folder

Specifies the default location of your mailboxes.  A "+" or "=" at the
beginning of a pathname will be expanded to the value of this
variable.  Note that if you change this variable (from the default)
value you need to make sure that the assignment occurs before
you use "+" or "=" for any other variables since expansion takes place
when handling the "mailboxes" command.
