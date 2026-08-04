# WallX

**Live wallpapers for your Mac.** WallX turns your own video files into dynamic, moving wallpapers.

## Features

- **Use your own videos** — Load any `.mp4` or `.mov` file and set it as your live wallpaper in one click.
- **Smooth playback** — Videos loop seamlessly for a clean, continuous backdrop.
- **Multi-display support** — Run your live wallpaper across all connected screens.
- **Retina-ready** — Optimized for high-resolution Mac displays, from MacBooks to Studio Displays.
- **Lightweight & native** — A clean, unobtrusive menu bar app built for macOS that stays out of your way.

## Installing WallX

WallX is a free, open-source app that isn't notarized by Apple (notarization requires a paid Apple Developer account). It's completely safe — macOS is just cautious about apps it can't automatically verify. Here's how to open it the first time:

### First launch

1. Download `WallX.zip` from the [latest release](https://github.com/UnxnownYT/WallX/releases/latest) and unzip it.
2. Move **WallX.app** to your **Applications** folder.
3. **Double-click** WallX.app, that will open it.
4. In the dialog that appears, click **Open** again.

You only need to do this once. After that, WallX opens normally, and updates install automatically.

### If you don't see an "Open" option

On newer macOS versions, instead:

1. Double-click WallX.app (it'll be blocked — that's expected).
2. Open **System Settings → Privacy & Security**.
3. Scroll down to the message about WallX and click **Open Anyway**.

### Still stuck?

You can clear the quarantine flag manually in Terminal:

```
xattr -dr com.apple.quarantine /Applications/WallX.app
```

---

**Why this step exists:** Apple charges $99/year for the certificate that removes this prompt. WallX is free, so it skips that — the tradeoff is this one-time manual open. I will make this app open-source after v0.0.6 since it still is developing.

## Usage

1. Click the WallX icon in your menu bar (the waterdrop).
2. Select **Choose Video…** and pick a `.mp4` or `.mov` file.
3. Your live wallpaper is applied instantly across all displays.
4. If you want to add it to the Lock Screen, Press 'Lock Screen > Replace Lock Screen with Current Video (note that it only works for Aerial wallpapers not 

## Requirements

- macOS 13.0 or higher (Apple Silicon and Intel supported)
- A `.mp4` or `.mov` video file

## Roadmap

- [x] Release
- [x] Adding the icons
- [x] Settings
- [x] Audio playback support
- [x] Per-display wallpaper customization
- [x] Opacity
- [x] Low Power Mode
- [x] Pause options
- [x] Wallpaper Library
- [x] Playlist Rotation
- [x] Volume Slider
- [x] Now Playing Tab
- [x] Drag a Video to the Icon support
- [x] Dual monitor support
- [ ] UI Revamp
- [ ] "Open With..." option
- [ ] 
