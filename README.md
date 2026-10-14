# Zoids Wild Infinity Blast — English Translation

By **StepPhone of the StepHackerZ**. **Patch v0.5.5 — test release.**

English localization overlay for the Japanese Switch game **0100BF9011CBE000**. The supplied mod targets the Japanese base game (v0 / 1.0.0). Compatibility with update 1.0.1 (v65536) has not been established in this packaging review. Patch and game version numbers are separate.

## Download

Get the ZIP for your platform from the [v0.5.5 release](https://github.com/StepPhone/zoids-wild-infinity-blast-translation/releases/tag/v0.5.5):

| Platform | Download |
| --- | --- |
| Eden | [ZWI-English-v0.5.5-Eden.zip](https://github.com/StepPhone/zoids-wild-infinity-blast-translation/releases/download/v0.5.5/ZWI-English-v0.5.5-Eden.zip) |
| Switch / Atmosphere | [ZWI-English-v0.5.5-Switch.zip](https://github.com/StepPhone/zoids-wild-infinity-blast-translation/releases/download/v0.5.5/ZWI-English-v0.5.5-Switch.zip) |

**Ready to install: no Python, terminal commands, extracted RomFS, or builder needed.** You need your own installed Japanese game. Download only one ZIP. The automatic Source code archives are not the recommended mod download.

## Install in Eden

1. Save and stop the game. Disable the previous translation mod, if present.
2. Extract the **Eden** ZIP.
3. Right-click Zoids Wild Infinity Blast and choose **Open Mod Data Location**.
4. Copy the extracted **ZWI_English_Translation** folder into that directory.
5. Enable **ZWI_English_Translation** in the game's Add-Ons settings and launch.

The path must be `<game mod directory>/ZWI_English_Translation/romfs/Data/...`. Do not put the Switch `atmosphere` folder inside Eden's mod directory.

## Install on Switch

Requires Atmosphere already configured for game mods. Physical hardware testing has not been verified.

1. Save and close the game; keep a save backup.
2. Extract the **Switch** ZIP.
3. Copy its **atmosphere** folder to the SD card root, merging folders and preserving unrelated mods.
4. Launch the Japanese game.

The path must be `SD:/atmosphere/contents/0100BF9011CBE000/romfs/Data/...`.

## Update or uninstall

Close the game before replacing files. Do not enable two translation versions together. In Eden, disable or remove only **ZWI_English_Translation**. On Switch, use the included `FILES.txt` to remove only this mod's files; do not delete the whole title folder if it contains other mods. Installing or removing the mod does not edit saves.

## Included scope

The supplied overlay includes boot, main-menu, character-select, common, customization, friend, mission, battle, gallery and options text bundles, an adventure-information bundle, title/menu assets and a StepHackerZ start screen. Version 0.5.5 also includes UI-label changes in the local, mission, mission-shop, mission-tutorial, results and login-bonus bundles. This describes the files included, not a claim that every line in those areas is translated.

## Test status and known issues

- Battle, gallery and options text bundles are included; complete translation coverage is not established.
- Full playthrough, update 1.0.1 compatibility and physical Switch behavior are not verified here.
- Some Japanese text or texture labels may remain, and English text may overflow or be cut off.
- Packaging validation checks ZIP contents and hashes against the supplied mod. It does not establish in-game stability or translation completeness.

Report issues with a screenshot, patch/game version, emulator version or hardware, and reproduction steps. Do not post game files, keys or private logs.

## Credits

Translation project and start-screen artwork: **StepPhone of the StepHackerZ**. [Support StepPhone](https://ko-fi.com/stepphone).

The original game and assets belong to their respective rights holders. The development workspace and builder are not included in this public repository.
