# GithubCSGO FastDL

FastDL root for CS:GO custom files.

Use this repo with GitHub Pages or raw.githubusercontent.com.

Required map path:

```text
maps/de_dust3.bsp.bz2
```

Server config example:

```cfg
sv_allowdownload "1"
sv_allowupload "0"
sv_downloadurl "https://memphis-cat.github.io/GithubCSGO"
```

The game server must still have the uncompressed file locally:

```text
csgo/maps/de_dust3.bsp
```

Do not upload `.zip`, `.rar`, or `.7z` for FastDL. Source/CS:GO FastDL uses `.bsp` or `.bsp.bz2`.
