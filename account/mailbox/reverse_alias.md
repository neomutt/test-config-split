# reverse_alias

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_ReverseAlias

This variable controls whether or not NeoMutt will display the "personal"
name from your aliases in the index menu if it finds an alias that
matches the message's sender.  For example, if you have the following
alias:
alias juser abd30425@somewhere.net (Joe User)

and then you receive mail which contains the following header:
From: abd30425@somewhere.net

It would be displayed in the index menu as "Joe User" instead of
"abd30425@somewhere.net."  This is useful when the person's e-mail
address is not human friendly.
