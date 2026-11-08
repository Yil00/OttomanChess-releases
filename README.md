# OttomanChess — Downloads & updates

**OttomanChess** is a chess analysis assistant for macOS: an overlay appears
right on your **lichess.org** and **chess.com** games and shows the best moves
computed **locally** by a chess engine — nothing ever leaves your Mac.

➡️ **[Download the latest release](https://github.com/Yil00/OttomanChess-releases/releases/latest)** · [Project page](https://yil00.github.io/OttomanChess-releases/)

## Features

- Live position analysis during your games (lichess & chess.com), with White or Black
- Up to **5 best moves** displayed, with customizable colors and opacity
- **Full engine lines (PV)** when hovering an arrow
- **Analysis history + annotated PGN export** (`[%eval …]`, importable into lichess / chess.com)
- **Engine choice**: Stockfish 19, Reckless, PlentyChess — switch mid-game
- Adjustable depth, evaluation bar, ad blocker (chess.com)
- Persistent per-site sessions, **one-click sign-in profiles** (macOS Keychain)
- Keyboard shortcuts, **automatic updates** (Sparkle, EdDSA-signed)
- App **signed with Developer ID and notarized by Apple**

## Installation

1. Download the `.dmg` from the [latest release](../../releases/latest)
2. Open it and drag **OttomanChess** into **Applications**
3. Launch the app — no Gatekeeper warning (notarized app)

**Requirements**: Apple silicon Mac, macOS 26.5 or later.

## Privacy

- Analysis engines run **100% locally** — no position is ever sent online
- No accounts, no analytics, no trackers
- Credentials (optional) stay in the **macOS Keychain**
- This repository only contains published DMGs and the update feed: the source code is private

## This repository

- **Releases**: notarized DMGs for every version ([Releases tab](../../releases))
- **`appcast.xml`**: Sparkle automatic-update feed
- **`index.html`**: project page ([GitHub Pages](https://yil00.github.io/OttomanChess-releases/))
- A bug or an idea? Open an [issue](../../issues)

## Licenses

OttomanChess source code: private, all rights reserved.
Bundled third-party engines under their respective licenses: Stockfish (GPLv3), Reckless (AGPLv3), PlentyChess (GPL).
