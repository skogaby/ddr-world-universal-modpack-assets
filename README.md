# DDR World Universal Modpack — assets

Dancers and stages ported from other DDR releases, for the Background Dancers mod of the
[DDR World Universal Modpack](https://github.com/skogaby/ddr-world-universal-modpack).

This repository holds the models in their authoring form:

```
dancers/<Source>/<Friendly name>/pl_<key>/…
stages/<Source>/<Friendly name>/mapset_<key>/…
```

Each `<Source>` folder is one optional **pack**. The packs are published as zip files on
this repository's [`packs` release](https://github.com/skogaby/ddr-world-universal-modpack-assets/releases/tag/packs).
The modpack's updater downloads the ones a user selects; a pack zip can also be unzipped
by hand into the game folder.

The tools that build and publish the packs live in the modpack repository
(`scripts/build_packs.py`, `scripts/publish_packs.sh`). They expect this repository to be
checked out beside it, or its location in the `DDR_WORLD_ASSETS` environment variable.
