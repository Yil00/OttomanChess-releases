# OttomanChess — Downloads & updates

**OttomanChess** is a chess analysis assistant for **macOS** and **Windows**:
an overlay appears right on your **lichess.org** and **chess.com** games and
shows the best moves computed **locally** by a chess engine — nothing ever
leaves your machine.

➡️ **[Download the latest release](https://github.com/Yil00/OttomanChess-releases/releases/latest)** ·
[🍎 macOS page](https://yil00.github.io/OttomanChess-releases/) ·
[🪟 Windows page](https://yil00.github.io/OttomanChess-releases/windows.html)

## Features

- Live position analysis during your games (lichess & chess.com), with White or Black
- Up to **5 best moves** displayed, with customizable colors and opacity
- **Full engine lines (PV)** when hovering an arrow
- **Analysis history + annotated PGN export** (`[%eval …]`, importable into lichess / chess.com)
- **Engine choice**: Stockfish 19, Reckless, PlentyChess — switch mid-game
- Adjustable depth, evaluation bar, ad blocker (chess.com)
- Persistent per-site sessions, **one-click sign-in profiles**
  (macOS Keychain / Windows Credential Manager)
- Keyboard shortcuts, **automatic updates** (Sparkle on macOS, NetSparkle on
  Windows — both Ed25519-signed)
- macOS app **signed with Developer ID and notarized by Apple**

## Installation

### macOS

1. Download the `.dmg` from the [latest release](../../releases/latest)
2. Open it and drag **OttomanChess** into **Applications**
3. Launch the app — no Gatekeeper warning (notarized app)

**Requirements**: Apple silicon Mac, macOS 26.5 or later.

### Windows

1. Download the installer from the [Windows page](https://yil00.github.io/OttomanChess-releases/windows.html)
   (**x64** for almost all PCs, **ARM64** for Snapdragon devices)
2. If SmartScreen warns, click **More info → Run anyway** — the installer is
   not code-signed yet (a paid certificate is planned)
3. Launch OttomanChess from the Start menu

**Requirements**: Windows 10 or 11, x64 or ARM64. No admin rights needed.

## Privacy

- Analysis engines run **100% locally** — no position is ever sent online
- No accounts, no analytics, no trackers
- Credentials (optional) stay in the **macOS Keychain** / **Windows Credential Manager**
- This repository only contains published installers and update feeds: the source code is private

## This repository

- **Releases**: notarized DMGs (macOS) and Inno Setup installers (Windows) for
  every version ([Releases tab](../../releases))
- **`appcast.xml`**: Sparkle update feed (macOS)
- **`appcast-windows-arm64.xml` / `appcast-windows-x64.xml`**: NetSparkle update feeds (Windows)
- **`index.html` / `windows.html`**: project pages ([GitHub Pages](https://yil00.github.io/OttomanChess-releases/))
- A bug or an idea? Open an [issue](../../issues)

## Licenses

OttomanChess source code: private, all rights reserved.
Bundled third-party engines under their respective licenses: Stockfish (GPLv3), Reckless (AGPLv3), PlentyChess (GPL).
