<h1 align="center">⊹ Hayase OSC ⊹</h1>

<p align="center">
  <samp>「 An osc inspired by hayase's UI for the local mpv experience. 」</samp>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/669f6024-d3c9-419b-8fbc-045634da4a3e" width="85%">
</p>

## Overview

This is a personal fork of [osc.lua](https://github.com/mpv-player/mpv/blob/master/player/lua/osc.lua), and a sibling to **ModernZ**, sharing much of its core logic and features. I wanted the [hayase.watch](https://hayase.watch) player experience in my local mpv setup, so I rewrote the interface using Lucide icons and a more refined, minimal layout.

&nbsp; ✦ &nbsp; **Visuals** - hayase inspired layout with web style hover states and consistent visual feedback.  
&nbsp; ✦ &nbsp; **Interactive menus** - mpv’s built-in menus for tracks, chapters, playlists, etc.  
&nbsp; ✦ &nbsp; **Lucide icons** - Lucide icon set used throughout.  
&nbsp; ✦ &nbsp; **Thumbnail previews** - optional progress bar previews via [_thumbfast_](https://github.com/po5/thumbfast).

## Installation

**Requirements:**

- **[mpv](https://mpv.io/installation/)** (v0.39.0 or above)
- **[thumbfast](https://github.com/po5/thumbfast)** (_Optional_: for hover thumbnails)

Place your files in the mpv configuration folder. On **Windows**, use `%APPDATA%/mpv/`. On **Linux** or **macOS**, use `~/.config/mpv/`. If these folders don't exist yet, create the _mpv_ folder manually and add _scripts_ and _fonts_ subfolders inside it. You also need an **mpv.conf** file with the following:

```
osc=no
title-bar=no # Optional: for the frameless look
```

Copy [hayase-osc.lua](scripts/hayase-osc.lua) into the scripts folder and [Lucide.ttf](fonts/Lucide.ttf) into the fonts folder. Your file structure should look like this:

```
mpv/
├── fonts/
│   └── Lucide.ttf
├── scripts/
│   └── hayase-osc.lua
└── mpv.conf
```

## Acknowledgments

- **[mpv contributors](https://github.com/mpv-player/mpv/graphs/contributors)** - The base [osc.lua](https://github.com/mpv-player/mpv/blob/master/player/lua/osc.lua) script, which serves as the primary upstream.
- **[ModernZ](https://github.com/Samillion/ModernZ)** - Sibling project with shared features and logic.
- **[uosc](https://github.com/tomasklaen/uosc)** - Architectural and logic inspiration.
- **[ThaUnknown](https://github.com/ThaUnknown)** - UI/UX inspiration.
- **[Lucide](https://github.com/lucide-icons/lucide)** - Icon set.

## License

This project is licensed under the **GNU Lesser General Public License v2.1 (LGPL-2.1)**.  
This project is a derivative of mpv's **osc.lua** and is distributed under the same terms. See the [LICENSE](LICENSE) file for details.

<br>

<p align="center">
<i>"Look, an emoji!"</i><br>
🌸
</p>
