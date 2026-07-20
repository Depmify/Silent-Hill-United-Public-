# Silent Hill: United

Silent Hill: United is an unofficial PC multiplayer mod project for Silent Hill 1.

Step back into Silent Hill with another player at your side: fight through the town together, keep track of each other on the map, and experience a custom multiplayer presentation built around Harry and Lisa.

This repository is used only for public releases, update metadata, and distribution files.
The source code is not hosted here.

## Community

Join the Discord server to follow Silent Hill: United development, release news, and multiplayer testing:

https://discord.gg/dXqEzN54s

The same community also follows Resident Evil: United, a modern-engine multiplayer recreation inspired by Resident Evil 1, with elements combined from Resident Evil 3.

## Highlights

### In-Game Online Lobby

Multiplayer starts inside Silent Hill: United. Open the in-game online lobby, choose who you want to play with, and the official server handles the connection for you: no VPN setup, no external matchmaking tools, no extra ritual before entering town. If both players are on the same home network, LAN play is still available as an alternative.

![In-game online lobby showing available players and connection status](assets/highlights/online-lobby.png)

How to play online with another person:

1. Download the latest public release package from the Releases page.
2. Follow [INSTALL.md](INSTALL.md) and place your own legal Silent Hill 1 disc image in the required ROM folder.
3. Start `Launcher.exe`.
4. Use the launcher updater first if you need to move to the latest `Release` build.
5. Launch the game from the launcher.
6. Open the in-game online lobby.
7. Wait until the lobby shows your connection as ready.
8. Select the player you want to join from the player list.
9. Confirm the connection and let the official server handle the session.
10. Start playing once both players are connected.

Lobby status tips:

- `JOINABLE` means the player can be selected for online play.
- `IN LOBBY` means the player is available in the online lobby.
- `IN GAME` means the player is already playing and may not be available.
- High ping can cause delay, desync, or unstable sessions.

If you cannot see or join another player, make sure both players are using the same release channel and version, both games are allowed through the Windows firewall, and both players have restarted the lobby after updating. For two PCs on the same home network, LAN play is also available.

### Cooperative Combat

Silent Hill feels different when you are not alone. Harry and Lisa can stand together in the same scene, cover each other in tight corridors, and turn enemy encounters into tense co-op moments instead of solitary survival.

![Cooperative combat with Lisa and Harry](assets/highlights/cooperative-combat.png)

### Real-Time Companion Map

Find your partner without breaking the atmosphere. The map shows both players in real time, making it easier to regroup, split up, and navigate Old Silent Hill while still preserving the original map-driven feel.

![Real-time companion markers on the Silent Hill map](assets/highlights/realtime-map-companion.png)

### Explore Silent Hill Together

The mod is built around shared presence: both players can move through story spaces, investigate locations, and experience the town as a pair while keeping the visual tone of the original PC experience.

![Harry and Lisa exploring a dark room together](assets/highlights/shared-exploration.png)

### Lisa's Exclusive Inventory Look

Lisa is not just a second player marker. Her inventory presentation gets its own identity, including a Lisa portrait and a UI style that makes her feel like a real playable partner instead of a duplicated Harry.

![Lisa inventory screen with exclusive portrait and item presentation](assets/highlights/lisa-inventory.png)

## Download

Get the latest version from the Releases page:

https://github.com/Depmify/Silent-Hill-United-Public-/releases

Do not clone this repository to install the mod. Use the latest release package instead.

For setup steps, see [INSTALL.md](INSTALL.md).

## Release Channels

- Release: stable public builds intended for normal play.
- Nightly: experimental prerelease builds for testing the latest work.

Update manifests may be provided per channel:

```text
manifest-release.json
manifest-nightly.json
manifest.json
```

## What This Repository Contains

- Public release builds
- Update manifest files
- Changelogs
- Installation notes
- Public screenshots and highlight media

## What This Repository Does Not Contain

- Source code
- Original Silent Hill game files
- Disc images, ROMs, ISOs, or original game content files
- Internal debug symbols or development tools

## Requirements

- Windows PC
- A valid copy of Silent Hill 1 / compatible PC setup
- Network access for multiplayer features

See [INSTALL.md](INSTALL.md) for download, setup, update, and package notes.

## Updating

The launcher may check this repository for the latest public version using the update manifest.

Example update metadata:

```json
{
  "version": "0.1.0",
  "channel": "Release",
  "url": "https://github.com/Depmify/Silent-Hill-United-Public-/releases/download/v0.1.0/Silent-Hill-United-v0.1.0.zip",
  "sha256": "SHA256_HASH_HERE",
  "mandatory": false
}
```

## Status

This project is experimental and under active development. Multiplayer stability is the current priority.

## Credits

Special thanks to [Vatuu/silent-hill-decomp](https://github.com/Vatuu/silent-hill-decomp) and its contributors for the Silent Hill 1 decompilation work that helped make this project possible.

## Disclaimer

Silent Hill is owned by its respective rights holders.
This is an unofficial fan project and is not affiliated with or endorsed by Konami.

No original game files, disc images, ROMs, or ISOs are distributed in this repository.

## Support

For bugs, crashes, multiplayer issues, or feature requests, open an issue using the matching GitHub issue template.

Useful details include:

- Mod version
- Release channel
- Windows version
- What you were doing when the issue happened
- Crash log or error message, if available
