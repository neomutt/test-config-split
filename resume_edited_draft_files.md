# resume_edited_draft_files

- **Default**: yes
- **Flags**: DT_BOOL
- **Variable**: C_ResumeEditedDraftFiles

If set, draft files previously edited (via -E -H on
the command line) will have $resume_draft_files automatically
set when they are used as a draft file again.

The first time a draft file is saved, NeoMutt will add a header,
X-Mutt-Resume-Draft to the saved file.  The next time the draft
file is read in, if NeoMutt sees the header, it will set
$resume_draft_files.

This option is designed to prevent multiple signatures,
user-defined headers, and other processing effects from being
made multiple times to the draft file.
