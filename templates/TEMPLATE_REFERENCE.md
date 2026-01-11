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

## Codex Scope Rule (MANDATORY)

The Codex is a reference system only.

The following are NOT permitted in any Codex file:
- Full prose scenes or chapters
- Batch text
- Dialogue blocks
- Verbatim source material (e.g., Dragonlance novels)
- Narrative written for reader immersion

All Codex entries must be:
- Summarized
- Structured
- Non-prose
- Canon-referential only

Story prose belongs exclusively in /story/.
Source inspiration belongs outside the repository or in /sources/.

---

# Universal Metadata Header (REQUIRED FOR ALL FILES)

Every Codex file must begin with a YAML metadata block using the following fields:

title  
type  
status  
version  
last_updated  
author  
source  
related_entries  
tags  

Rules:
- `related_entries` is always a YAML list
- `tags` is always a YAML list with at least two values
- `type` determines which template structure below must be used

---

# Template Type: world_bible_entry

Use for doctrine, lore summaries, concepts, and high-level reference entries.

Sections required:
- Summary
- Canon Notes
- Details
- Cultural Impact
- Known Conflicts / Tensions
- References

---

# Template Type: system_magic_or_anomaly

Use for Resonance tiers, rift mechanics, testing systems, constraints, and rules.

Sections required:
- Summary
- Definitions
- Rules / Constraints
- Observable Effects
- Failure Modes
- Institutional Use / Exploitation
- Canon Notes
- References

---

# Template Type: faction

Use for families, corporations, institutions, gangs, and councils.

Sections required:
- Overview
- Structure
- Goals
- Methods
- Relationships
- Notable Members
- Canon Notes
- References

---

# Template Type: character

Use for any named character.

Sections required:
- Quick Identity
- Appearance
- Personality
- Background
- Motivations
- Relationships
- Arc
- Secrets / Reveals
- Canon Notes
- References

---

# Template Type: location

Use for districts, zones, landmarks, and facilities.

Sections required:
- Summary
- Description
- Environment / Conditions
- Population / Control
- Risks
- Narrative Use
- Canon Notes
- References

---

# Template Type: timeline_entry

Use for historical or era-defining events.

Sections required:
- Summary
- Date / Era
- What Happened
- Consequences
- What People Are Taught
- Canon Notes
- References

---

# Template Type: scene

Use for isolated story scenes only.

Sections required:
- Summary
- Scene
- References

Note: Scenes may contain prose, but must live outside the Codex unless explicitly referenced.

---

# Template Type: chapter

Use for full chapter files only.

Sections required:
- Chapter Summary
- Chapter
- References

Note: Chapters never belong in the Codex.