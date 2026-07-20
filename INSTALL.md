# Installation Guide

This repository is for public releases and update metadata only. Do not clone the repository to install Silent Hill: United.

## Requirements

- Windows PC
- A valid personal copy of Silent Hill 1 / compatible PC setup
- Network access for online multiplayer features
- The latest Silent Hill: United release package from GitHub Releases

No original game files, disc images, ROMs, ISOs, saves, or personal configuration files are distributed here.

## Download

1. Open the Releases page:

   https://github.com/Depmify/Silent-Hill-United-Public-/releases

2. Download the latest package for the channel you want:

   - `Release`: stable public builds intended for normal play.
   - `Nightly`: experimental prerelease builds for testing the latest work.

3. Extract the package into a folder you control, for example:

   ```text
   C:\Games\Silent Hill United\
   ```

4. Follow the release notes for the exact game-data placement required by that build.

## Package Notes

Public packages are expected to exclude:

- `Server.exe`
- User configuration files
- Save files
- ROMs, ISOs, disc images, or original game content

Some folders may be included empty so the launcher or game can create runtime files in the expected location.

## Launching

1. Run `Launcher.exe`.
2. Check that the launcher shows the expected mod version.
3. Choose the release channel or multiplayer option you want to test.
4. Start or join a session.

Both players should use the same mod version when testing multiplayer.

## Updating

The launcher may check GitHub release manifests to find public updates.

If you update manually:

1. Close the game and launcher.
2. Download the new release package.
3. Extract it over the previous Silent Hill: United install folder.
4. Keep your own game files, saves, and personal configuration files separate unless the release notes say otherwise.
5. Start `Launcher.exe` and confirm the version changed.

## Troubleshooting

If something goes wrong, open a GitHub issue using the matching issue template and include:

- Release channel
- Mod version
- Windows version
- Whether you were host or client
- What happened and how to reproduce it
- Logs, crash details, screenshots, or clips when available

Do not attach original game files, disc images, ROMs, ISOs, or copyrighted assets.

For development news and multiplayer testing, join the Discord:

https://discord.gg/dXqEzN54s
