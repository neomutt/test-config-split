# newsrc

- **Default**: "~/.newsrc"
- **Flags**: DT_STRING|DT_PATH
- **Variable**: C_Newsrc

The file, containing info about subscribed newsgroups - names and
indexes of read articles.  The following printf-style sequence
is understood:
Expando  Description Example
%a      Account url       news:news.gmane.org
%p      Port              119
%P      Port if specified 10119
%s      News server name  news.gmane.org
%S      Url schema        news
%u      Username          username
