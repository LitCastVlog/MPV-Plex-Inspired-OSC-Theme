# Plex HTPC-Inspired theme for MPV

![image](https://raw.githubusercontent.com/LitCastVlog/MPV-Plex-Inspired-OSC-Theme/main/screnshot.png)

# Important Info:

use `ESC` key to hide OSC/Buttons (if it doesn't autohide)


keyboard navigation can be enabled (mimics the keyboard functions of Plex HTPC) to enable, open PlexOSC.lua in a text editor, scroll to line 57 and 

change `keyboardnavigation = false` to `keyboardnavigation = true`

# Installation:

Locate your MPV folder. It is typically located at `\%APPDATA%\mpv\` on Windows and `~/.config/mpv/` on Linux/MacOS. 

Put PlexOSC.lua into your mpv "\~\~/scripts/" folder. Create the "\~\~/scripts/" folder if you don't already have one and remove any other OSC scripts,
then put `Material-Design-Iconic-Font.ttf` in the "\~\~/fonts" folder.

in mpv.conf:

```
osc = no
border = no # Optional, but recommended
```
`Material-Design-Iconic-Font.ttf` can also be downloaded from [here](https://zavoloklom.github.io/material-design-iconic-font/).

# Thumbnails

To enable thumbnails in timeline, install [thumbfast](https://github.com/po5/thumbfast). No other step necessary.

# Buttons

like the built-in script, some buttons may accept multiple mouse actions, here is a list:

## Seekbar
* Left mouse button: seek to chosen position.
* Right mouse button: seek to the head of chosen chapter
## Playlist back/forward buttons
* Left mouse button: play previous/next file.
* Right mouse button: show playlist.
## Cycle audio/subtitle buttons
* Left mouse button/Right mouse button: cycle to next/previous track.
* Middle mouse button: show track list.
## Playback time
* Left mouse button: display time in milliseconds
## Duration
* Left mouse button: display total time instead of remaining time
