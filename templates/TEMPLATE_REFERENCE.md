---
title: "TEMPLATE_REFERENCE"
type: "template_reference"
status: "canon"
version: "1.0"
last_updated: "YYYY-MM-DD"
author: "Yoshua Israel"
source: "Codex"
related_entries: []
tags:
- templates
- reference
- frontmatter
- structure
---

# Universal Metadata Header (REQUIRED FOR ALL FILES)

Copy this block into every new file, then fill it in:

```md
---
title: "..."
type: "..."
status: "..."
version: "1.0"
last_updated: "YYYY-MM-DD"
author: "Yoshua Israel"
source: "Codex"
related_entries: []
tags:
- tag1
- tag2
---
```

Notes:
- `type` controls which body template below you use.
- `related_entries` is always a YAML list (even if empty).
- `tags` is always a YAML list (at least 2 tags).

---

# Template Type: world_bible_entry

Use for: doctrine, lore summaries, concepts, high-level reference entries.

```md
## Summary
[1–3 sentences. What this entry is.]

## Canon Notes
- **Confirmed:** [...]
- **Not revealed yet:** [...]
- **Open questions:** [...]

## Details
[The main explanation. Keep organized; use subsections if needed.]

## Cultural Impact
[How the world believes/talks about this.]

## Known Conflicts / Tensions
- [...]

## References
- [link to other entries]
```

---

# Template Type: system_magic_or_anomaly

Use for: Resonance tiers, rifts mechanics, testing, constraints, rules.

```md
## Summary
[What the system is and why it matters.]

## Definitions
- **Key Term:** definition
- **Key Term:** definition

## Rules / Constraints
1. [...]
2. [...]
3. [...]

## Observable Effects
- [...]

## Failure Modes
- [...]

## Institutional Use / Exploitation
[How corporations/governments weaponize or manage it.]

## Canon Notes
- **Confirmed:** [...]
- **Suppressed:** [...]
- **Open questions:** [...]

## References
- [...]
```

---

# Template Type: faction

Use for: families, corporations, institutions, gangs, councils.

```md
## Overview
[Who they are.]

## Structure
- Leadership: [...]
- Subgroups: [...]
- Reach: [...]

## Goals
- Public: [...]
- Private: [...]

## Methods
- [...]

## Relationships
- Allies: [...]
- Rivals: [...]
- Enemies: [...]

## Notable Members
- **Name:** role
- **Name:** role

## Canon Notes
- **Confirmed:** [...]
- **Not revealed yet:** [...]
- **Open questions:** [...]

## References
- [...]
```

---

# Template Type: character

Use for: any named character (including narrator once named).

```md
## Quick Identity
- **Full Name:** [...]
- **Aliases:** [...]
- **Origin / District:** [...]
- **Age:** [...]
- **Role in Story:** [...]

## Appearance
[Concrete, visual.]

## Personality
- Strengths: [...]
- Flaws: [...]
- Fears: [...]
- Desires: [...]

## Background
[What shaped them.]

## Motivations
- Short-term: [...]
- Long-term: [...]

## Relationships
- [...]

## Arc
- Start: [...]
- Pressure: [...]
- Change: [...]
- End state (planned): [...]

## Secrets / Reveals
- [...]

## Canon Notes
- **Confirmed:** [...]
- **Not revealed yet:** [...]
- **Open questions:** [...]

## References
- [...]
```

---

# Template Type: location

Use for: districts, zones, landmarks (e.g., The Scar), facilities.

```md
## Summary
[What and where.]

## Description
[Physical description and feel.]

## Environment / Conditions
- [...]

## Population / Control
- Who controls it: [...]
- Who lives there: [...]

## Risks
- [...]

## Narrative Use
[Why this place matters in-story.]

## Canon Notes
- **Confirmed:** [...]
- **Not revealed yet:** [...]
- **Open questions:** [...]

## References
- [...]
```

---

# Template Type: timeline_entry

Use for: Sundering Fall, wars, district formation era, Resonance event.

```md
## Summary
[Single paragraph.]

## Date / Era
- **Era Name:** [...]
- **Approx. Date:** [...]

## What Happened
1. [...]
2. [...]
3. [...]

## Consequences
- Social: [...]
- Political: [...]
- Geographic: [...]

## What People Are Taught
[Official narrative, if different.]

## Canon Notes
- **Confirmed:** [...]
- **Not revealed yet:** [...]
- **Open questions:** [...]

## References
- [...]
```

---

# Template Type: scene

Use for: story prose scenes (chapter files).

```md
## Summary
[2–4 lines: what happens in this scene.]

## Scene
[WRITE PROSE HERE — no bullet points.]

## References
- [Optional: only if you want the scene to point at world_bible entries.]
```

---

# Template Type: chapter

Use for: a full merged chapter file (e.g., Chapter 01).

```md
## Chapter Summary
[Short summary of the chapter.]

## Chapter
[WRITE THE FULL CHAPTER PROSE HERE — no batch breaks unless you label them.]

## References
- [Optional]
```
