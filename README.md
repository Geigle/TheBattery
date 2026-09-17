# The Battery

A **format-coverage test album** for audio players and library apps.

One ~120-second clip per common **music** codec/container that RockBox-class players may encounter. Files are tagged with album **The Battery** so a library scan groups them together.

## Music license

All tracks are compositions/recordings by **Kevin MacLeod** ([incompetech.com](https://incompetech.com)), licensed under **[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)**.

They are **not** public domain. You may copy, redistribute (including via this repository), and adapt them **if you give attribution**. See [ATTRIBUTION.md](ATTRIBUTION.md) and [LICENSE-MUSIC.md](LICENSE-MUSIC.md).

Packaging, scripts, and documentation in this repository (everything that is *not* Kevin MacLeod’s music) are dedicated to the public domain under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) — see [LICENSE](LICENSE).

## Track list

| # | Title | Format | File |
|---|-------|--------|------|
| 01 | Clash Defiant | MP3 | `audio/01 - Clash Defiant [MP3].mp3` |
| 02 | Darkest Child | AAC (M4A) | `audio/02 - Darkest Child [AAC].m4a` |
| 03 | Enter the Maze | ALAC (M4A) | `audio/03 - Enter the Maze [ALAC].m4a` |
| 04 | Five Armies | FLAC | `audio/04 - Five Armies [FLAC].flac` |
| 05 | Hard Boiled | WAV | `audio/05 - Hard Boiled [WAV].wav` |
| 06 | Killers | AIFF | `audio/06 - Killers [AIFF].aiff` |
| 07 | Night of Chaos | Ogg Vorbis | `audio/07 - Night of Chaos [OGG].ogg` |
| 08 | Oppressive Gloom | Opus | `audio/08 - Oppressive Gloom [Opus].opus` |
| 09 | Riptide | WMA v2 | `audio/09 - Riptide [WMA].wma` |
| 10 | Volatile Reaction | WavPack | `audio/10 - Volatile Reaction [WavPack].wv` |
| 11 | Whiskey on the Mississippi | Speex | `audio/11 - Whiskey on the Mississippi [Speex].spx` |
| 12 | Digya | TTA | `audio/12 - Digya [TTA].tta` |
| 13 | Rocket Power | MP2 | `audio/13 - Rocket Power [MP2].mp2` |
| 14 | Hitman | Wave64 | `audio/14 - Hitman [Wave64].w64` |
| 15 | Heroic Age | Sun AU | `audio/15 - Heroic Age [AU].au` |
| 16 | Stormfront | AAC ADTS | `audio/16 - Stormfront [AAC-ADTS].aac` |
| 17 | Crusade | WMA v1 | `audio/17 - Crusade [WMA1].wma` |
| 18 | Americana | Ogg Vorbis (OGA) | `audio/18 - Americana [OGA].oga` |

Genre mix: rock/metal-heavy, with soundtrack/epic and blues tracks for variety.

## Modifications

Compared to the Incompetech MP3 downloads:

- Re-encoded with FFmpeg into the formats above (source fidelity is **not** a goal)
- Truncated to about **120 seconds** for a portable test set
- Album metadata set to **The Battery**; artist/album artist set to Kevin MacLeod

## Not included (yet)

| Format | Why |
|--------|-----|
| AC3 / A52 | Video/surround-centric; omitted on purpose |
| Monkey’s Audio (APE) | No encoder on the build host used for v1 |
| Musepack (MPC) | No encoder on the build host used for v1 |
| Shorten (SHN) | Obsolete; impractical to produce |
| SID, MOD, NSF, SPC, SAP, ADX | Chip/tracker/game formats — planned as *actual* chip-style material under **their own** licenses, not MacLeod re-encodes |

## Suggested credit (for apps embedding this pack)

```
Clash Defiant — Kevin MacLeod (incompetech.com)
Licensed under Creative Commons: By Attribution 4.0
https://creativecommons.org/licenses/by/4.0/
```

(Replace the title for each track you ship or demo.) Full per-track credits: [ATTRIBUTION.md](ATTRIBUTION.md).

## Using with music apps / a simulator

Point a library root at `audio/`, or copy the folder into the app’s Documents / Music tree, then rescan.
