# honor_disposition

- **Default**: no
- **Flags**: DT_BOOL
- **Variable**: C_HonorDisposition

When set, NeoMutt will not display attachments with a
disposition of "attachment" inline even if it could
render the part to plain text. These MIME parts can only
be viewed from the attachment menu.

If unset, NeoMutt will render all MIME parts it can
properly transform to plain text.
