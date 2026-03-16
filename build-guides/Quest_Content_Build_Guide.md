# Quest Content Build Guide

## Purpose
This guide defines **how quest artifacts are built**.
It exists to keep detailed construction rules out of the source-of-truth docs while still preserving a repeatable build standard.

This file is about **production method**, not campaign law.

When in conflict, this document only governs its owned area.

---

## Ownership boundary

### This document owns
- the quest skeleton template
- quest-artifact role distinctions
- room-by-room content expectations
- question-block structure
- enemy / boss / side-content writeup standards
- supported variation-rep structure
- Exit Gate writing rules
- markdown-first vs HTML-later build guidance
- what belongs in a quest file vs what stays out

### This document does **not** own
- the campaign model itself
- roadmap ordering
- solving protocol rules
- live quest state
- deep skill-note construction rules

---

## Update rule
Update this guide when the **artifact-construction standard** for quest pages changes.

Examples:
- changing the quest skeleton template
- changing how Boss Chambers should be written
- changing how Side Hunts should be presented
- changing when markdown vs HTML should be used

Do **not** update this file just because a specific quest changed content.

---

## Related docs
- **Iron Guild Campaign — Source of Truth**: owns what each campaign artifact means
- **Iron Guild Roadmap — Source of Truth**: owns quest ordering
- **Iron Guild Prep System — Source of Truth**: owns how reps are run
- **Iron Guild Quest State — Source of Truth**: owns what is active
- **Lore Note Development Build Guide**: owns skill-note construction

---

## Build philosophy
The quest artifact should be:
- usable,
- legible,
- lightweight enough to ship,
- and strong enough to prep from.

The current MVP rule is:
**markdown first, polish later.**

Static HTML is still the preferred presentation layer long-term, but it should not slow down the playable structure.

---

## Artifact-role split
Do not collapse these artifacts into one blob.

### Field Guide
Campaign/world explanation.
This is not the same thing as a quest file.

### Quest Brief
Forward-looking quest setup.
This is the main quest artifact during build mode.

### Quest Log
Retrospective proof-of-work record.
This should capture how the quest was actually cleared, not act like the setup document.

### Skill / Pattern Note
The trainer-given learning artifact that teaches the technique or pattern.
Quest files should link to it, not replace it.

Historical note:
Older project language often called these **lore notes**. That older term is still understandable, but the live build model treats them more like skill / pattern notes.

---

## Core quest skeleton template
Every quest should be buildable from a lean structure like this:

1. Quest Name
2. Purpose
3. Core Pattern / Mechanic
4. Recognition Signals
5. Linked Skill / Pattern Notes
6. Canonical Enemies
7. Trial Room
8. Architect’s Wing
9. Boss Chamber
10. Optional Side Hunts
11. Optional Side Bosses
12. Exit Gate
13. Notes Status
14. Curation Concerns

This is enough to make the quest real without turning it into an encyclopedia.

---

## Quest Brief build rules
A Quest Brief should explain:
- what the quest is for,
- what mechanic or family it is training,
- which skill note(s) support it,
- which enemies / bosses / optional content belong here,
- and what the Exit Gate will require.

A Quest Brief should **not** become:
- the full skill note,
- a giant solution archive,
- or a retrospective diary.

---

## Quest Log build rules
A Quest Log should capture:
- what was actually attempted,
- what was cleared,
- how the Exit Gate was satisfied,
- what evidence of the clear exists,
- what was learned,
- and what still feels weak after the run.

The Quest Log is not the same as the Quest Brief.
If a document is mostly explaining what the quest contains and what to do, it is a Quest Brief, not a Quest Log.

---

## Room-by-room build rules

### Linked skill / pattern notes
Include:
- the linked skill note(s)
- a short statement of what each note teaches

Do not paste the entire note into the quest file.
The quest file should point to the note, not replace it.

### Enemy Floor
Include:
- the canonical problems
- a short line on why each one is here
- only the most useful mechanic-facing reps

Enemy Floor is for the clearest pattern reps.
Do not clutter it with every remotely related problem.

### Trial Room
Include:
- the judgment target
- why it belongs in this quest
- what skill it is training beyond raw pattern execution

Typical examples:
- prompt deconstruction
- requirement locking
- code review judgment
- modeling decisions
- OOD / interface judgment
- “what is this really asking?” recognition

### Architect’s Wing
Include:
- the systems / architecture insertion
- what artifact should be produced
- why it belongs here

The key test is whether this wing produces something real, not whether it sounds impressive.

### Boss Chamber
Include:
- the required high-quality reps
- a short line on why each rep represents the quest well
- only problems that feel interview-caliber and pattern-representative

Boss Chamber is not for random hard problems.
It is the main proving ground for the quest.

### Side Hunts
Include:
- optional supported reps
- why they are useful
- whether they are disguise, refresh, confidence-building, or reserve examples

A useful pattern is to present these as a starter batch plus reserve pool rather than a fake promise that a fixed count should always be enough.
Exit Gates, not quotas, determine whether more supported reps are needed.

### Side Bosses
Include:
- optional stretch boss-tier reps
- why they are harder
- and why they are still relevant rather than random suffering

### Exit Gate
Include observable move-on signals.
Avoid vague wording like:
- “feel comfortable”
- “be confident enough”
- “do a few more if needed”

Prefer signals like:
- can explain the mechanic cleanly
- can map a supported variation back to the base pattern
- clears the Boss Chamber at the intended standard
- completes the Trial Room honestly
- produces the Architect’s Wing artifact

---

## Question-block construction rules
Question blocks should distinguish between:
- canonical enemies
- boss reps
- side hunts
- side bosses

For each problem, capture at least:
- title
- why it belongs here
- what mechanic or disguise it represents
- whether it is required or optional

Do not let “problem list” become a giant graveyard of related problems.
Curation matters more than volume.

---

## Supported variation-rep structure
For Side Hunts and other supported reps, include a short translation prompt:
- what is the base mechanic?
- what is the disguise?
- what stayed the same?
- what changed?
- why did the solution change?

This prevents optional reps from becoming shallow exposure.

---

## Exit Gate writing rules
An Exit Gate should answer:
**“What must be true to leave this quest honestly?”**

A good Exit Gate:
- is visible
- is observable
- distinguishes required from optional
- prevents perfectionist overrun
- does not shame the learner for needing more supported reps

A bad Exit Gate:
- is vague
- is purely emotional
- is secretly inflated by optional content
- or acts like the learner is defective for needing extra examples

---

## Markdown-first build rule
During MVP build mode:
- default to lightweight markdown skeletons
- refine the structure and question blocks first
- only push to HTML when the content is stable enough that presentation work is not slowing down the system

---

## What stays out of quest files
Do not let a quest file become:
- the full skill note
- a code archive
- a giant solution bank
- a region-wide roadmap explanation
- a diary of every thought from chat

Quest files should stay operational.

---

## Decision log
| Date | Decision | Why | Updated by |
|---|---|---|---|
| 2026-03-14 | Keep detailed quest-artifact construction rules out of the Campaign source-of-truth doc | Prevents source-of-truth sprawl | Boundary + build-guide pass |
| 2026-03-14 | Use markdown-first quest skeletons during MVP build mode | Keeps polish from outrunning usable prep structure | Boundary + build-guide pass |
| 2026-03-14 | Separate Quest Brief from Quest Log in quest-artifact construction | Prevents setup and retrospective evidence from blurring together | Campaign audit lock-in |
| 2026-03-14 | Treat Side Hunts as supported optional reps and Side Bosses as optional stretch boss-tier reps | Preserves clearer quest-layer progression and cleaner Exit Gates | Campaign audit lock-in |
