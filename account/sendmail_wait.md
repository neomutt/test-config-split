# sendmail_wait

- **Default**: 0
- **Flags**: DT_NUMBER
- **Variable**: C_SendmailWait

Specifies the number of seconds to wait for the $sendmail process
to finish before giving up and putting delivery in the background.

NeoMutt interprets the value of this variable as follows:
>0      number of seconds to wait for sendmail to finish before continuing
0       wait forever for sendmail to finish
<0      always put sendmail in the background without waiting

Note that if you specify a value other than 0, the output of the child
process will be put in a temporary file.  If there is some error, you
will be informed as to where to find the output.
