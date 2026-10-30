# crstian19's Scoop bucket

[Scoop](https://scoop.sh) bucket for apps by [crstian19](https://github.com/crstian19).

```powershell
scoop bucket add crstian19 https://github.com/crstian19/scoop-bucket
scoop install crstian19/herakleo
```

| App | Description |
|---|---|
| [Herakleo](https://github.com/crstian19/herakleo) | Desktop IPTV player for M3U playlists and Xtream Codes accounts |

## Herakleo

Herakleo plays channels in an external player, so install one too:

```powershell
scoop bucket add extras
scoop install mpv   # or: scoop install vlc
```

Update with `scoop update herakleo`, remove with `scoop uninstall herakleo`. Your lists and settings
stay in `%AppData%\herakleo`.

Manifests update themselves every day when a new release is out
([`excavator.yml`](.github/workflows/excavator.yml)).
