# MSI Software Repository

This repository provides minimal, essential MSI notebook software, avoiding the bloat of the full MSI suite.

## Programs

### 1. Feature Manager

A lightweight control panel distributed by MSI to OEMs (e.g., GameGaraj, MonsterNotebook). It allows:

- Enabling/disabling hardware features.
- Adjusting performance settings.
- Managing user profiles.
- Bundles a minimal **MSI NBFoundation Service**.

### 2. MSI NBFoundation Service

Support service mainly for hotkey functionality.

- By itself, it spawns unnecessary background processes.
- Only useful when paired with Feature Manager.
- Recommended: **Install Feature Manager instead.**

### 3. YAMDCC – Yet Another MSI (Dragon) Center Clone

An open-source alternative to using both Feature Manager and MSI NBFoundation Service.

- GitHub: [YAMDCC](https://github.com/Sparronator9999/YAMDCC)
- Lightweight and actively maintained.

## Versioning Info

Program executables follow this format:

`MSI NBFoundation Service_2.0.2506.1201`

Where:
- `2506` = Year/Month (2025/06)
- `1201` = Day/Build revision (12th day, rev 01)

> This format is inferred from version patterns during repo maintenance.

### Source of Executables

- **Feature Manager** builds come from OEM packages (GameGaraj, MonsterNotebook).
- **MSI NBFoundation Service** builds are extracted from official MSI installers.

## How to Download

### Option 1: Full Repo
- Click **Code** > **Download ZIP**

### Option 2: Individual Files
- Browse to the file
- Click it > **Download**

---

Contributions via issues or pull requests are welcome.
