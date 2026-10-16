
# GTA: Chinatown Wars — RG52 Mini 16:9 Port

A native Linux port of the Android version of Grand Theft Auto: Chinatown Wars, adapted for the RG52 Mini and its 16:9 display.

This project is based on [GTACTW-Port-R36-for-arkos4clones](https://github.com/dzikk/GTACTW-Port-R36-for-arkos4clones), which in turn is based on [GTACTW-Port-R36s](https://github.com/mafradon/GTACTW-Port-R36s).

## Status

- Adapted for 16:9 displays
- Centered viewport
- Fixed and stretched HUD
- Corrected oval minimap
- Fixed save/autosave screen cropping
- Corrected pause menu positioning

## Tested On

- RG52 Mini
- Debian 11 / glibc 2.31

## Requirements

You must supply the following files from a legitimate copy of the Android version of GTA: Chinatown Wars. These files are not included in this repository for copyright reasons.

- `main.4.com.rockstargames.gtactw.obb` — approximately 865 MB of game data
- `gtacw.apk` — Android version 1.04, required for game assets, text strings, legal screens, and font support files

## Installation

1. Extract the port archive into `/roms/ports/`.
2. Copy your legally obtained game files into the directory expected by the port.
3. Refresh the game list if necessary.
4. Launch GTA: Chinatown Wars from the Ports menu.

## Credits

- [dzikk](https://github.com/dzikk/GTACTW-Port-R36-for-arkos4clones) — ArkOS4clones port and direct upstream.
- [mafradon](https://github.com/mafradon/GTACTW-Port-R36s) — original R36S port.
- [TheOfficialFloW](https://github.com/TheOfficialFloW/gtactw_vita) — prior GTA: Chinatown Wars Vita port and related reverse-engineering work.

## Disclaimer

This is an unofficial community project. It is not affiliated with, endorsed by, or sponsored by Rockstar Games.

Grand Theft Auto: Chinatown Wars and its associated intellectual property belong to their respective owners. No copyrighted game assets are included in this repository.
