# Scoop bucket for Herakleo

[Scoop](https://scoop.sh) bucket for [Herakleo](https://github.com/crstian19/herakleo), a desktop
IPTV player for M3U playlists and Xtream Codes accounts.

```powershell
scoop bucket add herakleo https://github.com/crstian19/scoop-herakleo
scoop install herakleo
```

Herakleo plays channels in an external player, so install one too:

```powershell
scoop bucket add extras
scoop install mpv   # or: scoop install vlc
```

Update with `scoop update herakleo`, remove with `scoop uninstall herakleo`. Your lists and settings
stay in `%AppData%\herakleo`.

The manifest updates itself every day when a new Herakleo release is out
([`excavator.yml`](.github/workflows/excavator.yml)).
