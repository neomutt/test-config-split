# attribution_locale

- **Default**: ""
- **Flags**: DT_STRING
- **Variable**: C_AttributionLocale

The locale used by strftime(3) to format dates in the
attribution string.  Legal values are the strings your system
accepts for the locale environment variable $LC_TIME.

This variable is to allow the attribution date format to be
customized by recipient or folder using hooks.  By default, NeoMutt
will use your locale environment, so there is no need to set
this except to override that default.
