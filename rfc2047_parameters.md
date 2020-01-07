# rfc2047_parameters

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_Rfc2047Parameters

When this variable is set, NeoMutt will decode RFC2047-encoded MIME
parameters. You want to set this variable when NeoMutt suggests you
to save attachments to files named like:
=?iso-8859-1?Q?file=5F=E4=5F991116=2Ezip?=

When this variable is set interactively, the change won't be
active until you change folders.

Note that this use of RFC2047's encoding is explicitly
prohibited by the standard, but nevertheless encountered in the
wild.

Also note that setting this parameter will not have the effect
that NeoMutt generates this kind of encoding.  Instead, NeoMutt will
unconditionally use the encoding specified in RFC2231.
