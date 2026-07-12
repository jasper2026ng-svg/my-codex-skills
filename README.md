# My Codex Skills

Personal Codex skills and portable sync packages.

## Included skills

- `structured-problem-framing`
- `first-principles-reframing`
- `critical-questioning`

## Recommended install path on Windows

Codex loads personal skills from:

```powershell
$env:USERPROFILE\.codex\skills
```

## Install from the sync package

1. Download `packages/personal-skill-sync-pack-20260712.zip`.
2. Extract the zip on the target computer.
3. Open PowerShell inside the extracted `personal-skill-sync-pack` folder.
4. Verify the package:

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -File .\verify-package.ps1
```

5. Install the skills:

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -File .\install-windows.ps1
```

If the target computer already has older versions and you want to replace them:

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -File .\install-windows.ps1 -Force
```

Restart Codex Desktop after installation if the skills do not appear immediately.

## Manual install from this repository

Copy each folder under `skills/` into:

```powershell
$env:USERPROFILE\.codex\skills
```

Each skill folder must keep its internal structure, including `SKILL.md`, `agents/`, and `references/`.
