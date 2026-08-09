# Velano Living catalogue images, by product

Every finished catalogue image SilverShore produced or now holds custody of,
one directory per product and one per variant beneath it.

    products/<product>/<finish>-<size>/1-studio.jpg
                                       2-macro.jpg
                                       3-couch.jpg
                                       4-bedroom.jpg
                                       5-corner.jpg

Shot names match the SOP: image 1 is the studio, 2 the macro, 3 beside the couch
with a window behind, 4 the bedroom, 5 the corner beside a window.

## Why this exists

220 of these were hosted on a third-party generation CDN we no longer use. They
are client deliverables and were sitting on infrastructure we do not control, so
if that account lapsed the live catalogue would have gone dead in 220 places.
They are now here.

Not mirrored: the Haussmann reference photography on cdn.shopify.com. That is
the client's own imagery on the client's own store, and copying it would add
custody we do not need plus a copy that can drift from theirs.

The method that produced these is documented at
https://silvershore-partners.github.io/velano-living-catalogue-images/sop/
