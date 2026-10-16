# Reusable skills

## Adaptive Technical Tutor

Chooses short, medium, or detailed explanations independently for each software development question. Keeps follow-ups focused and explains debugging causes, fixes, and significant implementation decisions.

Skill files live in [`adaptive-technical-tutor/`](adaptive-technical-tutor/SKILL.md).

### Install with Codex

Paste this into a Codex chat:

```text
$skill-installer Install the skill from https://github.com/ShekhawaTTiku/favourite-prompts/tree/main/skills/adaptive-technical-tutor
```

If the installer reports that the skill already exists, it is already installed; review the existing copy before replacing it. Start a new chat after installation, and restart Codex if the skill does not appear.

For manual installation on Windows, copy the entire `adaptive-technical-tutor` folder into `%USERPROFILE%\.agents\skills\`.

### Use

```text
$adaptive-technical-tutor Why does my Python function return None?
```

Automatic selection is enabled for matching development requests, but discovery does not guarantee activation on every message. Mention the skill explicitly when you want to select it for a particular request. Your current instructions override its default response depth.
