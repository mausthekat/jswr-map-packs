# JSW Redux - Custom Map Packs

The official catalog of downloadable custom map packs for
[Jet Set Willy: Redux](https://github.com/mausthekat/jswr).

Layout:

```
index.yaml        # the catalog (fetched by the in-game Custom Maps browser)
packs/<id>.jswp   # one bundled JSWP map pack per catalog entry
covers/<id>.png   # optional cover art
```

The game fetches these via raw.githubusercontent.com; entries are verified
by size + BLAKE2s hash before install. Catalog format spec lives in the
main repo at `docs/formats/MAP_REPO_CATALOG.md`.
