# smileys

- **Default**: "(>From )|(:[-^]?[][)(><}{|/DP])"
- **Flags**: DT_REGEX
- **Variable**: C_Smileys

The pager uses this variable to catch some common false
positives of $quote_regex, most notably smileys and not consider
a line quoted text if it also matches $smileys. This mostly
happens at the beginning of a line.
