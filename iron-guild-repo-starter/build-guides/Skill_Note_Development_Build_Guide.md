
# Skill Note Development Build Guide

## Purpose

This guide defines **how skill / pattern notes are built and refined**.

It exists to keep detailed note-construction rules out of the Campaign and Prep System source-of-truth docs while preserving a repeatable quality standard.

This file is about **production method**, not campaign law.

When in conflict, this document only governs its owned area.

Historical note:
Older project language and older filenames may use **lore note**.
The live model treats these as **skill / pattern notes**, and this guide governs that live note model.

---

## Ownership boundary

### This document owns

- skill / pattern note template rules
- note identity and variant-boundary rules
- canonical example expectations
- depth and compression rules
- note refinement workflow
- what belongs in a skill / pattern note vs what should stay in quest structure
- how visible note clarity relates to the deeper reasoning standard behind it

### This document does **not** own

- campaign architecture
- roadmap ordering
- solving protocol rules
- live quest state
- quest-page construction rules beyond note linkage
- note-usage rules during active prep
- cross-document decision memory
- presentation-layer development beyond minimal note legibility

---

## Update rule

Update this guide when the **note-development standard** changes.

Examples:

- changing the note template
- changing how variants should be explained
- changing how much detail belongs in examples
- changing note-compression rules
- changing the refinement workflow

Do **not** update this file just because one specific note changed.

---

## Related docs

- **Iron Guild Campaign — Source of Truth**: owns what skill / pattern notes are for in the campaign
- **Iron Guild Prep System — Source of Truth**: owns how notes are used during prep
- **Iron Guild Roadmap — Source of Truth**: owns broad note-coverage status and sequencing
- **Iron Guild Quest State — Source of Truth**: owns what note work is active right now
- **Quest Content Build Guide**: owns how quest files link to notes
- **Iron Guild Shared Decision and Terminology Log**: owns cross-document lineage and durable decision memory

---

## Note philosophy

A strong skill / pattern note should capture the **soul of the pattern**.

It should help answer:

- what kind of problem this really is
- why this pattern fits
- what the important variants are
- what strong structured reasoning looks like

A skill / pattern note is a **pre-entry technical learning artifact**.

Its job is to make the learner better at:

- recognizing the pattern
- choosing the right representation
- explaining why the pattern fits
- and walking through the move with interview-grade clarity

A skill / pattern note is **not**:

- a full problem archive
- a code dump
- a textbook chapter
- or a flavor-first artifact

Interpretation rule:
The note should feel clean and usable, but teaching quality comes before aesthetic neatness.

---

## Two-layer note model

The project preserves two layers inside a strong note.

### Layer 1: visible note layer

This is the campaign-facing note the learner actually reads.

It should be:

- clean
- readable
- efficient
- low-flavor
- and compatible with the campaign presentation without becoming decorative

### Layer 2: deeper reasoning standard behind the visible note

This preserves the stronger reasoning expectations underneath the cleaner presentation:

- clear recognition signals
- explicit variant discrimination
- WHY-heavy complexity explanations
- enough detail that the note teaches rather than gestures

Working rule:

- the visible note can stay cleaner and more compact
- the deeper reasoning standard must not be lost
- any flavor should stay tiny and should never slow teaching

---

## Core note template

A strong skill / pattern note should generally include:

### Top of note

- Problem Signatures / Recognition Signals
- Core Insight & Mental Model
- Variant Map

### Variant section

For each important variant, preserve:

- When to use
- Example problem
- Goal
- Input / Output shape
- Clarifying Questions / Constraints
- Why this variant fits
- Key Variables / State
- Steps
- Time / Space with WHY
- Adaptation notes where useful

### Bottom of note

- Notes
- Mentor Notes
- Caveats
- Specialized Exceptions

Interpretation rules:

- signatures are heuristics, not laws
- “strong candidate for this pattern” is better than rigid certainty
- the visible note should stay efficient without becoming thin
- the note style should match the soul of the pattern, not force every pattern into the same personality

---

## Deeper reasoning standard to preserve

Even when the visible note is cleaner, it should still preserve enough signal to teach.

Important standards:

- mechanic-first naming
- one note should have a clear identity
- variants should be meaningfully different, not cosmetic rearrangements
- complexity explanations should explain **why**
- steps should read like an implementation checklist, not a vague summary
- worked examples should teach the reasoning, not just narrate the answer

Interpretation rule:
A clean-looking note that fails to teach transfer is still a weak note.

---

## Variant expectations

Each important variant should be self-contained enough to stand on its own.

At minimum, preserve:

- Goal
- Example Problem
- Input / Output shape
- Key variables / state
- Step structure
- Time / Space with WHY
- adaptation notes where useful

Do not let one variant lean so hard on another that it becomes unreadable in isolation.

Do not split variants so aggressively that cosmetic differences become fake new sections.

---

## Canonical example rules

A good canonical example should include enough detail to protect against shallow understanding.

Preserve:

- condensed restatement / goal
- inputs / outputs
- clarifying questions / constraints where useful
- why the variant fits
- key variables
- steps
- time / space with WHY when that explanation matters

Do not turn every example into an oversized trace dump.
Include enough to teach, then stop.

Interpretation rule:
A worked example should function like a mental interview rep, not just a decorative sample.

---

## Depth and compression rules

Good compression:

- removes redundancy that adds no teaching value
- keeps the note readable
- preserves the move, the why, and the transfer logic

Bad compression:

- deletes the reasoning that explains why the variant fits
- handwaves complexity
- collapses variant boundaries until they blur
- turns implementation steps into vague slogans

Good detail:

- makes the reasoning easier to follow
- preserves the logic of the move
- models how to communicate in an interview
- helps the learner transfer the pattern to a new problem

Bad detail:

- bloats the note without teaching more
- preserves weak sections just because they already exist
- turns the note into an archive instead of a learning artifact

---

## What stays out of the note

Keep these out unless they are truly essential:

- giant extra problem lists
- full code archives
- repetitive trap sections
- oversized trace dumps
- every niche edge case in the universe
- quest progression rules
- room-by-room quest content
- backlog material that is only “maybe useful later”

These belong in active practice, quest structure, mentor commentary, or later backlog handling when appropriate.

Short pseudocode or implementation cues are acceptable only when they materially teach the move.

---

## Refinement workflow

Use a staged approach instead of trying to perfect every note immediately.

### Rough

- pattern identity exists
- variants roughly exist
- examples are present
- structure is usable but messy

### Stable

- top section is clear
- variant map makes sense
- examples are representative
- obvious bloat is removed

### Refined

- wording is clean
- examples are strong representatives
- variant boundaries are sharp
- mentor notes / caveats are useful rather than decorative

Current project rule:

**do not try to refine every note before the playable skeleton exists.**

---

## Common failure modes to guard against

- the note becomes an encyclopedia
- the note becomes so compressed it stops teaching
- variant boundaries blur
- examples are famous but not representative
- complexity explanations handwave the WHY
- niche exceptions dominate the core lesson
- visible cleanliness hides weak reasoning underneath
- the note starts doing the quest’s job instead of its own

---

## Final interpretation rule

The standard is not:

- maximum detail
- maximum compression
- or maximum elegance

The standard is:

**enough signal to teach the move cleanly, enough structure to transfer it, and enough compression to keep the note usable.**
