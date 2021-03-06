# attach_format

- **Default**: "%u%D%I %t%4n %T%.40d%> [%.7m/%.10M, %.6e%?C?, %C?, %s] "
- **Flags**: DT_STRING|DT_NOT_EMPTY
- **Variable**: C_AttachFormat

This variable describes the format of the "attachment" menu.  The
following printf(3)-style sequences are understood:
%C      Charset
%c      Requires charset conversion ("n" or "c")
%D      Deleted flag
%d      Description (if none, falls back to %F)
%e      MIME content-transfer-encoding
%f      Filename
%F      Filename in content-disposition header (if none, falls back to %f)
%I      Disposition ("I" for inline, "A" for attachment)
%m      Major MIME type
%M      MIME subtype
%n      Attachment number
%Q      "Q", if MIME part qualifies for attachment counting
%s      Size (see formatstrings-size)
%T      Graphic tree characters
%t      Tagged flag
%u      Unlink (=to delete) flag
%X      Number of qualifying MIME parts in this part and its children
        (please see the "attachments" section for possible speed effects)
%>X     Right justify the rest of the string and pad with character "X"
%|X     Pad to the end of the line with character "X"
%*X     Soft-fill with character "X" as pad

For an explanation of "soft-fill", see the $index_format documentation.
