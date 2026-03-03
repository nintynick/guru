# Guru

A [Claude Code skill](https://docs.anthropic.com/en/docs/claude-code/skills) that acts as a developmental process facilitator and guide for human psychological growth.

Guru uses Spiral Dynamics, Kegan's Orders of Consciousness, Cook-Greuter's Ego Development Theory, and other integrative developmental frameworks — not as content to teach, but as an internal compass for meeting people exactly where they are.

## What It Does

Guru helps with personal growth, self-understanding, life transitions, meaning-making, and inner work. It activates for everything from "I'm feeling lost" to deep questions about developmental psychology.

Key principles:

- **Meets you where you are** — calibrates language, depth, and pacing to your actual experience, not where theory says you should be
- **Frameworks stay invisible** — developmental models inform how Guru listens, not what it teaches (unless you ask)
- **Invites, never pushes** — growth happens through invitation, not pressure
- **Listens first, always** — the relationship is the work

## Installation

Copy `guru.skill` into your Claude Code skills directory, or install the skill folder directly:

```
cp -r guru/guru ~/.claude/skills/guru
```

## Project Structure

```
guru.skill                 # Packaged skill file
guru/guru/
  SKILL.md                 # Core skill instructions
  references/
    developmental-frameworks.md   # Spiral Dynamics, Kegan, Cook-Greuter, Maslow, and cross-framework mapping
    practices-by-stage.md         # Stage-appropriate practices and suggestions
  evals/
    evals.json             # Evaluation scenarios and assertions
    eval-1-output.md       # Orange-to-Green transition scenario
    eval-2-output.md       # Survival/crisis grounding scenario
    eval-3-output.md       # Advanced integrative practitioner scenario
```

## Evals

Three evaluation scenarios test Guru across the developmental spectrum:

1. **Successful executive feeling empty** — tests meeting someone at an achievement-to-meaning transition without framework jargon
2. **Person in crisis needing practical grounding** — tests prioritizing safety and concrete support over psychological exploration
3. **Advanced practitioner seeking "what's next"** — tests peer-level engagement and gentle shadow work without reinforcing stage pride
