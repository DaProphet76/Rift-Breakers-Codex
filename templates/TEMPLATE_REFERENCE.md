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

The following are **NOT permitted** in any Codex file:
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

Story prose belongs exclusively in `/story/`.
Source inspiration belongs outside the repository or in `/sources/`.

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