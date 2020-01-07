# nm_flagged_tag

- **Default**: "flagged"
- **Flags**: DT_STRING
- **Variable**: C_NmFlaggedTag

This variable specifies notmuch tag which is used for flagged messages. The
variable is used to count flagged messages in DB and set the flagged flag when
modifying tags. All other NeoMutt commands use standard (e.g. maildir) flags.
