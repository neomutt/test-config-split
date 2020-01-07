# external_search_command

- **Default**: ""
- **Flags**: DT_STRING|DT_COMMAND
- **Variable**: C_ExternalSearchCommand

If set, contains the name of the external program used by "~I" patterns.
This will usually be a wrapper script around mairix, mu, or similar
indexers other than notmuch (for which there is optional special support).

Here is an example how it works.  Let's assume $external_search_command
is set to "mairix_filter", and mairix_filter is a script which
runs the old but well loved mairix indexer with the arguments
given to mairix_filter, in the "raw" mode of mairix, producing
on the standard output a list of Message-IDs, one per line.

If possible, it also filters down the results coming from mairix
such that only messages in the current folder remain.  It can do
this because it gets a hidden first argument which is the path
to the folder.
(This can be the type of clean and simple script called a one-liner.)

Now if NeoMutt gets a limit or tag command followed by the pattern
"~I '-t s:bleeping='", mairix_filter runs mairix with the
arguments from inside the quotes (the quotes are needed because
of the space after "-t"), mairix finds all messages with
"bleeping" in the Subject plus all messages sharing threads
with these and outputs their file names, and mairix_filter
translates the file names into Message-IDs.  Finally, NeoMutt
reads the Message-IDs and targets the matching messages with the
command given to it.

You, the user, still have to rewrite the mairix_filter script to
match the behavior of your indexer, but this should help users
of indexers other than notmuch to integrate them cleanly with NeoMutt.
