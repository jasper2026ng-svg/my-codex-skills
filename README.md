# My Codex Skills

Personal Codex skills, portable single-skill packages, and Human Learning Cards.

## Included Skills

- `structured-problem-framing`
- `first-principles-reframing`
- `critical-questioning`
- `pyramid-communication`
- `effective-manager-operating-system`
- `hrbp-business-diagnosis`

## Human Learning Cards

Each cognitive skill should have a matching card under `human-cards/`.

- Agent Skill: helps Codex execute the method.
- Human Learning Card: helps Jasper internalize when to use it, why it works, when it fails, and how to test transfer.

Recommended use:

1. Read the matching Human Learning Card.
2. Write the 30-second initial judgment before asking Codex.
3. Use the Agent Skill.
4. Compare your judgment with the agent output.
5. Do the teach-back and transfer test later.

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
- `packages/effective-manager-operating-system-20260712.zip`
- `packages/hrbp-business-diagnosis-20260712.zip`

Older all-in-one packages may remain in `packages/` as history, but new releases should use one zip per skill.

## Manual Install From This Repository

Copy each folder under `skills/` into:

```powershell
$env:USERPROFILE\.codex\skills
```

Each skill folder must keep its internal structure, including `SKILL.md`, `agents/`, and `references/`.
