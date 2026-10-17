# TotalArchery catalog

Manufacturer data used by the TotalArchery app: compound bows (2022–2026,
all tiers), arrow shafts, arrow components (points, broadheads, inserts,
collars, nocks, vanes), 3D targets and bow sights. The app ships with a copy
of these lists and downloads this repo's JSON weekly so new products show up
without an app update.

`range_targets.json` holds the targets that are not 3D animals: block and bag
range targets, throwing targets and a few accessories (`kind` is `range`,
`throwing`, `accessory` or `other`). It is curated through the admin console and
is not overwritten by the nightly export. `candidates.json` lists new finds in
`sights`, `targets` (3D animals), `rangeTargets` and `arrows`.

`index.json` carries the `updatedAt` stamp; the other files are plain arrays.
Rows marked `"verified": false` are figures that couldn't be confirmed
against the maker's own spec page.
