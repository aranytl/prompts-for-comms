# Prompts for Comms

Agent skills for communication, editorial judgment, and spoken-language adaptation.

## Skills

- `detox-hook`: Generate, rewrite, compare, or analyze emotionally tuned headlines, hooks, subheadlines, taglines, and title variants.
- `detox-pulse`: Analyze text as an audience emotional journey, finding emotional beats, likely reader response, resonance gaps, and high-leverage improvements.
- `detox-voxford`: Convert written articles, announcements, blog posts, formal drafts, or internal communications into natural teleprompter-ready scripts.

## Installation

Copy the skill folders you want into your Codex skills directory:

```bash
mkdir -p ~/.codex/skills
cp -R skills/detox-hook ~/.codex/skills/
cp -R skills/detox-pulse ~/.codex/skills/
cp -R skills/detox-voxford ~/.codex/skills/
```

Restart Codex or reload skills after copying.

## Usage

Invoke the skills by name in Codex:

- `$detox-hook`
- `$detox-pulse`
- `$detox-voxford`

Each skill also includes natural-language trigger phrases in its `SKILL.md`.

## License

See `LICENSE`.
