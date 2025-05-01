Build qbittorrent-nox with conda packages.

## Install

The easy way is to install with [pixi](https://pixi.sh/dev/)

```bash
pixi global install -c conda-forge -c https://repo.prefix.dev/bit-torrent qbittorrent-nox
```

If you want to build qbittorrent with your own patches, we have a conda package `libtorrent-static`,
you can take [recipe.yaml](https://github.com/trim21/qbittorrent-feedstock/blob/master/recipe/recipe.yaml) as example.

## channels

<https://prefix.dev/channels/bit-torrent>
