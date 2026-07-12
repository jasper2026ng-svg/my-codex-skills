# My Codex Skills

Personal Codex skills and portable single-skill packages.

## Included Skills

- `structured-problem-framing`
- `first-principles-reframing`
- `critical-questioning`
- `pyramid-communication`

## Recommended Install Path On Windows

Codex loads personal skills from:

```powershell
$env:USERPROFILE\.codex\skills
```

## Install One Skill From A Zip Package

Download the skill package you need from `packages/`, extract it, and copy the extracted skill folder into:

```powershell
$env:USERPROFILE\.codex\skills
```

For example, `packages/pyramid-communication-20260712.zip` extracts to:

```text
pyramid-communication/
```

Copy that whole folder into:

```text
C:\Users\<your-user>\.codex\skills
```

Restart Codex Desktop after installation if the skill does not appear immediately.

## Current Individual Packages

- `packages/structured-problem-framing-20260712.zip`
- `packages/first-principles-reframing-20260712.zip`
- `packages/critical-questioning-20260712.zip`
- `packages/pyramid-communication-20260712.zip`

Older all-in-one packages may remain in `packages/` as history, but new releases should use one zip per skill.

## Manual Install From This Repository

Copy each folder under `skills/` into:

```powershell
$env:USERPROFILE\.codex\skills
```

Each skill folder must keep its internal structure, including `SKILL.md`, `agents/`, and `references/`.
