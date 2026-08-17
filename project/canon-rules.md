---
title: "Canon Rules"
type: "project_governance"
status: "canon"
version: "1.0"
last_updated: "2026-08-17"
author: "Yoshua Israel"
source: "Rift Breakers Project"
related_entries:
  - project/repository-guide.md
  - README.md
tags:
  - canon
  - governance
  - continuity
---

# Canon Rules

## Purpose

These rules determine what is authoritative, how information becomes canon, and how contradictions are resolved across the trilogy, atlas, and future novels.

## Authority order

When information conflicts, use this order:

1. A decision approved by Yoshua Israel and recorded in the current repository.
2. A current file marked status: canon.
3. Facts established in an approved manuscript.
4. A current file marked status: provisional or planned.
5. Material inside LEGACY.

Chat discussions, memory, drafts, and LEGACY material are not permanent canon until the decision is recorded in the current repository.

## Status definitions

- canon — approved and authoritative.
- provisional — accepted for development but still changeable.
- planned — intended future material that has not been finalized.
- draft — incomplete working material.
- deprecated — intentionally replaced; retained only for reference.

## Single-source rule

- Every character, location, artifact, faction, creature, system, family, and historical event has one authoritative atlas entry.
- Other files link to that entry instead of copying its full information.
- Character profiles and growth records may remain separate because they serve different purposes.
- Duplicate authoritative entries are not permitted.

## Manuscript rule

- Full prose belongs only in manuscripts.
- Atlas entries summarize facts and never duplicate full scenes or chapters.
- A draft chapter does not automatically change canon.
- Facts introduced by an approved chapter must be checked against the atlas and continuity files.

## Atlas rule

- Atlas entries contain world facts, not reader-facing prose.
- Hidden truths must be clearly separated from what characters and societies believe.
- Planned reveals must link to the continuity records controlling when they appear.

## Legacy migration rule

- LEGACY is reference material only.
- Files are reviewed individually.
- Material may be migrated as canon, provisional, planned, or deprecated.
- No folder or file is copied into the new structure without checking for contradictions and duplicates.

## Conflict procedure

When a contradiction is found:

1. Do not silently choose a version.
2. Record the conflict in continuity/open-questions.md.
3. Compare the current canon, manuscript needs, and latest approved decision.
4. Ask Yoshua Israel when the intended answer is uncertain.
5. Update every affected current file after the decision.
6. Increase the version number and update last_updated.

## Revelation control

- True information and publicly believed information must not be confused.
- Secrets affecting multiple books belong in continuity/revelation-map.md.
- Atlas entries may record hidden canon, but manuscripts reveal it only at the approved story point.
- Future-novel material must not accidentally spoil the core trilogy.

## File rules

- Use lowercase filenames with hyphens.
- Avoid spaces, temporary labels, and names such as final-final or revised-2.
- Use Markdown for project text.
- Every governed Markdown file begins with YAML metadata.
- related_entries must link to current repository paths.
- Files in LEGACY are never used as current references.

## Change approval

- Structural changes may be drafted on a branch for review.
- New canon requires Yoshua Israel's approval.
- Editing wording without changing meaning may increase the minor version.
- Changing established meaning requires explicit approval and a major version review.

## References

- README.md
- project/repository-guide.md
- LEGACY/TEMPLATE_REFERENCE material, retained only for historical comparison
