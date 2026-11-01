# Diablo III Ultimate Evil Edition – CheatRunner Cheats (PS4 CUSA00433 v01.46)

A collection of **12 independently selectable cheat toggles** for **Diablo III: Reaper of Souls – Ultimate Evil Edition** (`CUSA00433`, game version `01.46`), used with **CheatRunner v0.18** on a jailbroken PS5.

**This project is separate from BGH – BawertL's Game Hub.** It contains a CheatRunner JSON configuration, not the game or a game executable.

## Compatibility

| Item | Tested setup |
|---|---|
| Game | Diablo III: Reaper of Souls – Ultimate Evil Edition |
| PS4 Title ID | `CUSA00433` |
| Game version | `01.46` |
| Cheat loader | CheatRunner v0.18 |
| Console | Jailbroken PS5, firmware 13.60 |
| Target process | `eboot.bin` |

**Other title IDs and game updates, including v01.47, have not been verified.** Cheats use game-version-specific offsets; do not apply them to another version without independent validation.

## Included toggles

| # | Cheat | Test notes |
|---|---|---|
| 1 | God Mode / Infinite Health | Confirmed in game |
| 2 | Infinite combat resources (mana etc.) | Confirmed with Wizard |
| 3 | No Cooldown V2 | Confirmed with Barbarian Ground Stomp; not verified for every class/skill |
| 4 | Loot Sanft | Natural drops; configured 10% Primal / 10% Ancient for eligible loot |
| 5 | Loot Abenteuer | Natural drops; configured 30% Primal / 10% Ancient |
| 6 | Loot Uralt Plus | Natural drops; configured 10% Primal / 20% Ancient |
| 7 | Max Loot Mix | Modified Legendary/Set loot; configured approximately 1/3 Primal |
| 8 | Max Loot Primal | Modified Legendary/Set loot; intended all eligible Primal |
| 9 | Attack Speed 5.0 APS | Character stats displayed 5.00 APS; attack animation speed not separately measured |
| 10 | Critical Hit 100% Chance + 100% Damage | Both character-stat values confirmed |
| 11 | Magic Find 300% | Character-stat value confirmed; drop-rate impact not separately measured |
| 12 | Movement Speed +50% | Subjective movement changes; normal running may be limited by game caps |

**Loot percentages describe the programmed cheat settings, not statistically verified long-run drop rates.** The five loot modes are **mutually exclusive**: enable only one at a time. Some effects may be class-, skill-, or situation-dependent.

## Installation

1. Install and configure **CheatRunner** for your PS5 homebrew environment.
2. Copy `CUSA00433_01.46.json` to:

   ```text
   /data/cheatrunner/cheats/json/CUSA00433_01.46.json
   ```

3. Start the matching **CUSA00433 v01.46** game build.
4. Open CheatRunner and enable only the cheats you want.
5. **Use at most one loot mode at a time.**

Keep a backup of the original JSON if you already have one at this path. Disable cheats if they cause instability or unexpected behavior.

## Project scope and credits

- **Cheat configuration and testing:** bawertL
- **Game:** Diablo III by Blizzard Entertainment; all game rights belong to their respective owners.
- **CheatRunner:** Separate third-party homebrew software; not included.
- **BGH – BawertL's Game Hub:** https://github.com/bawertl/BGH-Universal-PS5-Game-Hub

No commercial game files, decrypted executable, or proprietary game content are distributed in this repository.

## Disclaimer

Community-made, version-specific game modifications. Provided as-is; compatibility and stability cannot be guaranteed. This is not an official Blizzard or CheatRunner project.
