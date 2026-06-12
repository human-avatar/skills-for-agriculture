# skills-for-agriculture

Decision-making and guidance skills for farmers, growers, and land stewards. Each skill encodes a complete guidance methodology grounded in expert practitioner knowledge — not generic advice.

## Structure

```
skills/
  s4ag/               ← router, invoked as /s4ag
  s4ag-{domain}/      ← individual skill, invoked as /s4ag-{domain}
    SKILL.md

docs/
  superpowers/
    specs/            ← skill writing spec
    plans/            ← phase implementation plans
```

## Naming convention

- **Router:** `skills/s4ag/SKILL.md` → invoked as `/s4ag`
- **Domain skills:** `skills/s4ag-{domain}/SKILL.md` → invoked as `/s4ag-{domain}`

The folder name IS the command name.

## SKILL.md format

Every SKILL.md starts with YAML frontmatter:

```yaml
---
name: s4ag-{domain}
description: "Trigger description — natural phrases a farmer would use. Under 200 chars."
allowed-tools: [Read]
---
```

The body follows the fixed structure: opening paragraph → "How this skill works" → Expert Lineage → routing table → sub-tool sections. Each sub-tool has a **Checkpoint** (HITL — confirms assumptions before output) and **Next steps** (related skills to run next).

## Quality criteria

Every skill must be:
1. **Goal-oriented** — helps the user achieve a specific agricultural goal
2. **Sustainability-biased** — defaults to regenerative/sustainable, documents conventional without judgment
3. **Nature-aligned** — working with natural systems is almost always more effective long-term
4. **Soil-health grounded** — Ingham's soil food web is the biological lens underneath every skill
5. **Transition-aware** — meets users where they are on the conventional-to-regenerative spectrum
6. **Context-sensitive** — conventional farmer in a hurry gets the answer first

## Development

When creating or editing skills, follow the format of existing written skills (s4ag-soil, s4ag-pests, s4ag-seasons, s4ag-regenerative). The SKILL.md body should encode the *how* — a user should be able to make a better farm decision from the instructions alone.

The spec at `docs/superpowers/specs/2026-06-01-skills-for-agriculture-plan.md` has the authoritative content for each domain.
