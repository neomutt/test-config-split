# imap_pipeline_depth

- **Default**: 15
- **Flags**: DT_NUMBER|DT_NOT_NEGATIVE
- **Variable**: C_ImapPipelineDepth

Controls the number of IMAP commands that may be queued up before they
are sent to the server. A deeper pipeline reduces the amount of time
NeoMutt must wait for the server, and can make IMAP servers feel much
more responsive. But not all servers correctly handle pipelined commands,
so if you have problems you might want to try setting this variable to 0.

Note: Changes to this variable have no effect on open connections.
