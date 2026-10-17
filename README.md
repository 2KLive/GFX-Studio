# GFX Studio

**The WWE 2K19 graphics and font workspace — by [2KLIVE](https://patreon.com/2KLive).**

Create, edit and convert the on-screen graphics and fonts of WWE 2K19 in one native Windows app. Open a game PAC, edit it visually, export a validated copy, and drop it into your install.

---

## Download

Grab the latest build from the **[Releases](https://github.com/2KLive/GFX-Studio/releases/latest)** page. Unzip the **whole** folder somewhere writable and run `GFX Studio.exe`. Keep the EXE next to its `_internal` and `styles` folders and `texconv.exe`. No Python install is needed.

**Requirements:** Windows 10/11 (x64) and a WWE 2K19 installation (GFX Studio reads the game's `oo2core_6_win64.dll`). Bink video conversion additionally needs the free RAD Video Tools, which are not bundled (set up from *GFX Converter → Set Up RAD Tools*).

---

## What GFX Studio does

### 🏠 Home dashboard
Open any supported PAC and Home detects whether it is a font or a graphic and routes it to the right workspace. Recent files, quick access and update checks live here.

### 🪪 Nameplates
Edit names, social handles and championship layouts with a layer tree, live preview and per-variant control.

### 🎞️ Transitions & motion
Inspect frames, scrub the timeline and preserve the entrance/exit animations you need. Includes a native animation library.

### 📍 Locators
Build readable location cards with safe-area and grid guides.

### 🏆 Match results
Static font-and-foreground workflow for winner/draw screens.

### 🆚 Matchups
Compose the loading match screen: competitor text, font atlas viewing/export/import, full-screen layout fixes for compatible slots, wrestler render references, and background video replacement (Bink, or MP4 via conversion).

### 🔤 Font Studio
Template-based font workspace: generate lettering from **TTF/OTF**, port donor game fonts and SYM artwork, and make precise glyph and atlas repairs.

### 🖼️ Images & foregrounds
Replace artwork with PNG or DDS; PNGs are encoded to the target's original DDS format with texconv.

### 🎬 GFX Converter
Verified Bink conversion for nameplate, locator and matchup movies, with progress, cancel and speed controls.

### 📦 Safe export
**Export PAC** always writes a validated *copy* — it never overwrites the file you opened — with optional backup of previous exports.

---

## User Guide

See **[GFX Studio - Complete User Guide.pdf](./GFX%20Studio%20-%20Complete%20User%20Guide.pdf)** — 37 chapters covering setup, every workspace, export, in-game install, troubleshooting and a project checklist. Start with *Quick Start*.

**Basic workflow:** set your game folder in *Settings* → open a PAC → edit → *Export PAC* → close the game, back up the live PAC, install the exported copy under the correct slot filename → test in-game.

---

## Support

- **Bugs / feature requests:** open an [Issue](https://github.com/2KLive/GFX-Studio/issues)
- **Community & help:** [Patreon](https://patreon.com/2KLive)

---

*GFX Studio is a fan-made modding tool. Not affiliated with 2K, Visual Concepts, WWE, RAD Game Tools, or anyone else.*
