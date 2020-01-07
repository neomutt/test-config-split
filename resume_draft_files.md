# resume_draft_files

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_ResumeDraftFiles

If set, draft files (specified by -H on the command
line) are processed similarly to when resuming a postponed
message.  Recipients are not prompted for; send-hooks are not
evaluated; no alias expansion takes place; user-defined headers
and signatures are not added to the message.
