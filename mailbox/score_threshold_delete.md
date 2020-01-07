# score_threshold_delete

- **Default**: -1
- **Flags**: DT_NUMBER
- **Variable**: C_ScoreThresholdDelete

Messages which have been assigned a score equal to or lower than the value
of this variable are automatically marked for deletion by NeoMutt.  Since
NeoMutt scores are always greater than or equal to zero, the default setting
of this variable will never mark a message for deletion.
