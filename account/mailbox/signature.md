# signature

- **Default**: "~/.signature"
- **Flags**: DT_STRING|DT_PATH
- **Variable**: C_Signature

Specifies the filename of your signature, which is appended to all
outgoing messages.   If the filename ends with a pipe ("|"), it is
assumed that filename is a shell command and input should be read from
its standard output.
