<h1 align="center">⊹ Hayase OSC ⊹</h1>

<p align="center">
  <samp>「 An osc inspired by hayase's UI for the local mpv experience. 」</samp>
</p>

<p align="center">
  <a href="https://github.com/Samillion/ModernZ">
    <img src="https://img.shields.io/badge/based_on-ModernZ-cba6f7?style=flat-square&labelColor=313244" alt="ModernZ">
  </a>
  <a href="https://github.com/hayase-app">
    <img src="https://img.shields.io/badge/inspired_by-hayase.watch-b4befe?style=flat-square&labelColor=313244" alt="Hayase">
  </a>
</p>

<p align="center">
  <img src="https://i.imgur.com/7COFhYY.png" width="85%">
</p>

## Overview

This is a personal fork of **ModernZ** (which, like this script, stems from mpv's original [`osc.lua`](https://github.com/mpv-player/mpv/blob/master/player/lua/osc.lua)). I wanted the [hayase.watch](https://hayase.watch) player experience in my local mpv setup, so I rewrote the interface using **Lucide** icons and a more refined, minimal layout.

&nbsp; ✦ &nbsp; **Visuals** - a minimal, hayase-inspired layout with web-style hover states and consistent visual feedback.  
&nbsp; ✦ &nbsp; **Interactive menus** - mpv’s built-in menus for tracks, chapters, playlists, etc.  
&nbsp; ✦ &nbsp; **Lucide icons** - Lucide icon set used throughout.  
&nbsp; ✦ &nbsp; **Thumbnail previews** - optional preview support via [_thumbfast_](https://github.com/po5/thumbfast).

## Installation

### Requirements

- **[mpv](https://mpv.io/installation/)** (v0.39.0 or above)
- **[thumbfast](https://github.com/po5/thumbfast)** (_Optional_: for hover thumbnails)

### Files Setup

Place the files into your mpv config folder and update your config:

1. Copy [`hayase-osc.lua`](/scripts/hayase-osc.lua) to `scripts/`
2. Copy [`Lucide.ttf`](/fonts/Lucide.ttf) to `fonts/`
3. Create `mpv.conf` and add:

```ini
osc=no
title-bar=no # Optional: for the frameless look
```

> [!IMPORTANT]
> First time using mpv? Create the **mpv** folder, then add **scripts/** and **fonts/** inside it.

### Config location

```
Windows -  %APPDATA%/mpv/
Linux   -  ~/.config/mpv/
macOS   -  ~/Library/Application Support/mpv/
```

### Folder layout

```
mpv/
├── fonts/
│   └── Lucide.ttf
├── scripts/
│   └── hayase-osc.lua
└── mpv.conf
```

## Acknowledgments

- **[ModernZ](https://github.com/Samillion/ModernZ)** - For the foundation this script was built upon.
- **[mpv contributors](https://github.com/mpv-player/mpv/graphs/contributors)** - For the original [`osc.lua`](https://github.com/mpv-player/mpv/blob/master/player/lua/osc.lua) script.
- **[ThaUnknown](https://github.com/ThaUnknown)** - For the UI/UX inspiration.
- **[Lucide](https://github.com/lucide-icons/lucide)** - For the icon set.

## License

This project is licensed under the **GNU Lesser General Public License v2.1 (LGPL-2.1)**.  
This project is a derivative of **ModernZ** and mpv's **osc.lua** and is distributed under the same terms. See the [LICENSE](LICENSE) file for details.

<br>

<p align="center">
<i>"Yet another modern osc fork"</i><br>
🌸
</p>
