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

4. Put your own Silent Hill 1 disc image in the ROM folder, as explained below.

## ROM Placement

Silent Hill: United does not include the original game. You must provide your own legally obtained Silent Hill 1 disc image.

After extracting the release package, open this folder:

```text
C:\Games\Silent Hill United\Data\ROM\
```

Put the game disc image directly inside `Data\ROM`. The recommended file name is:

```text
Silent Hill (v1.1).bin
```

Your install should look like this:

```text
C:\Games\Silent Hill United\
  Launcher.exe
  Silent Hill United.exe
  Data\
    ROM\
      Silent Hill (v1.1).bin
      Silent Hill (v1.1).cue
```

The `.cue` file is optional for the current runtime, but if your dump includes one, keep it next to the `.bin` and make sure it points to the same `.bin` file. The `.bin` is the important file.

Accepted exact `.bin` names:

```text
Silent Hill (USA).bin
Silent Hill (USA) (v1.1).bin
Silent Hill (USA) (Rev 1).bin
Silent Hill (v1.1).bin
Silent Hill (Rev 1).bin
Silent Hill (PAL).bin
Silent Hill (Europe) (En,Fr,De,Es,It).bin
```

If your file has a different name, the game may still try to autodetect it if it is a valid `.bin`, but renaming it to one of the names above is the safest option.

Common mistakes to avoid:

```text
Wrong: C:\Games\Silent Hill United\Silent Hill (v1.1).bin
Right: C:\Games\Silent Hill United\Data\ROM\Silent Hill (v1.1).bin

Wrong: C:\Games\Silent Hill United\Data\ROM\Silent Hill (v1.1).cue only
Right: C:\Games\Silent Hill United\Data\ROM\Silent Hill (v1.1).bin

Wrong: C:\Games\Silent Hill United\Data\ROM\Silent Hill.iso
Wrong: C:\Games\Silent Hill United\Data\ROM\Silent Hill.chd
Wrong: C:\Games\Silent Hill United\Data\ROM\Silent Hill.zip
Right: C:\Games\Silent Hill United\Data\ROM\Silent Hill (v1.1).bin
```

Do not put the ROM in `Data\Saves`, `Data\Maps`, `Data\DLLs`, the root install folder, or a nested folder inside `Data\ROM`.

If the launcher says it cannot find the disc image, check three things:

- The file is inside `Data\ROM`.
- The file ends in `.bin`.
- The name matches one of the accepted names above.

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
