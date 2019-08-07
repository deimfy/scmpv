# scmpv
### Soundcloud wrapper for mpv player

#### Dependencies
- `curl`
- `mpv`
- `youtube-dl`

#### Installing/Uninstalling
```shell
#!/bin/bash
~ $ cd /path/to/working/dir/
/path/to/working/dir/ $ sudo (un)install.sh
```

#### Usage
```shell
#!/bin/bash
~ $ scmpv [argument] [query]
# List of arguments:
#   track, tracks, sound, sounds, tr, so    Search for specified  track
#   people, artist, artists, pe, ar         Search for specified artist
#   album, albums, al                       Search for specified album
#   set, sets, playlist, playlists, st, pl  Search for specified playlist
```