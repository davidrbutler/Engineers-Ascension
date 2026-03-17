# System Ledger

## Purpose

This document is the major-change history for the project.

It exists to record:

- material system changes
- cross-document changes that belong together
- why those changes happened
- which files were affected
- and how the project’s build model evolved over time

This file is the project’s **major revision memory**.

It is **not**:

- the live state document
- the day-to-day work log
- the handoff layer between chats
- or a place to record every tiny edit

When in conflict, this document only governs its owned area.

---

## Ownership boundary

### This document owns

- major cross-document change history
- ledger change IDs
- doc-local revision references for major changes
- the rationale behind material system changes
- major naming resets
- major workflow resets
- phase changes that materially affect how the project is built
- archival / superseded status for older major-history systems

### This document does **not** own

- live quest progress
- active next steps
- detailed build standards
- day-to-day work journaling
- operational handoff between chats
- minor typo-level or wording-level edits
- roadmap order
- campaign law
- prep rules
- quest or note content itself

---

## Update rule

Update this file only when a **material project change** happens.

Examples:

- a system-wide workflow change
- a naming reset
- a phase shift
- a major ownership-boundary change
- a major artifact-model change
- a major documentation reset
- a meaningful shift in how notes or quests are built
- a clean-slate baseline reset like this one

Do **not** update this file for:

- minor wording tweaks
- typo fixes
- formatting cleanup
- small local edits that do not materially change the system
- routine progress inside one quest unless it changed the project model itself

---

## Related docs

- **Prep System**: owns execution rules and operating behavior
- **Campaign**: owns the project shell, artifact roles, and end-goal framing
- **Roadmap**: owns sequencing and broad coverage
- **Project State**: owns what is active right now
- **Building a Skill Note**: owns detailed note-construction rules
- **Building A Quest**: owns detailed quest-construction rules

---

## Ledger conventions

### 1. One material session-level change = one ledger change ID

The project uses **one major ledger ID per material session-level change**.

Example:

- `chg000001`
- `chg000002`

This prevents fake precision and avoids turning tiny edits into noisy pseudo-commits.

### 2. Doc-local revision IDs track major versions of each file

Each major document uses its own revision ID.

Examples:

- `prepsystem000001`
- `campaign000001`
- `roadmap000001`

These should increment only when that file changes **materially**.

### 3. Google Docs handles fine-grained history

Google Docs version history is the raw edit history.

This ledger exists for:

- semantic history
- major changes
- and cross-file reasoning

### 4. Session Handoffs are separate

A **Session Handoff** is not the same as a ledger entry.

- **System Ledger** = historical memory
- **Session Handoff** = operational baton pass

### 5. Build Lessons are optional

If a durable process lesson emerges during a chat, it may appear as an **optional Build Lesson** in the handoff.

It does **not** need a dedicated ledger entry unless it caused a material system change.

---

## What counts as a material change

A change is material if it changes one or more of the following:

- how the project is built
- how the docs are organized
- how artifact ownership is defined
- how phases are interpreted
- how skill notes are built
- how quests are built
- how major history is tracked
- how handoffs are handled
- how the project is expected to operate across chats

If the answer to “will this change how future work should be done?” is **yes**, it probably belongs here.

---

## What does not count as a material change

These should usually stay out of the ledger:

- typo fixes
- spacing cleanup
- small wording cleanup with no behavior change
- a single problem added to a quest list unless it changes the model
- tiny edits that only improve readability
- local refinements that do not change the system

---

## Entry template

Use this structure for new ledger entries:

### `chgxxxxx` — [short title]

- **Date:** YYYY-MM-DD
- **Files touched:**
  - File Name → revision id
- **Summary:**
  - bullet
  - bullet
  - bullet
- **Why:**
  - short explanation of why this material change was necessary

---

## Superseded systems

### Shared history / terminology log

The older shared-history / terminology-log approach is now superseded by this ledger.

Reason:

- this ledger more clearly separates:
  - major change history
  - live state
  - and session handoffs

The old shared-history log should now be treated as:

- archive-only
- historical reference
- or superseded material

It should not continue to compete with this document as the main source of major project history.

---

## Current baseline interpretation

This ledger begins at the first coherent material baseline of the current system.

That means:

- earlier messy intermediate states are not being preserved as authoritative revision history
- this ledger starts from the first trustworthy system reset
- this reset defines the baseline for future major changes

Interpretation rule:

This is not “throwing away history.”
It is refusing to pretend that unstable intermediate models were the true baseline.

---

## Change log

### chg000001 — Clean-slate reset and shift to Alpha / Graybox pedagogy-first build model

- **Date:** 2026-03-17
- **Files touched:**

  - System Ledger → systemledger000001
  - Prep System → prepsystem000001
  - Building a Skill Note → buildskillnote000001
  - Building A Quest → buildquest000001
  - Campaign → campaign000001
  - Project State → projectstate000001
  - Roadmap → roadmap000001

- **Summary:**

  - reset the revision system so this session becomes the first real material baseline
  - adopted the rule that one material session-level change equals one ledger change ID
  - adopted doc-local revision IDs that start at `000001` for the clean-slate baseline
  - clarified the split between:
    - System Ledger
    - Session Handoff
    - and optional Build Lesson
  - formally shifted the active production posture to **Alpha / Graybox pedagogy-first**
  - explicitly backgrounded theming during active build
  - redefined skill notes around a top-section-only educational foundation:
    - Problem Signatures / Recognition Signals
    - Core Insight & Mental Model
    - What This Pattern Does Well
    - What This Pattern Does Not Do / Where It Breaks
    - Variant Map
  - removed question curation responsibility from skill notes during the current phase
  - redefined quests as smaller prep containers centered on:
    - learning goals
    - representative questions
    - interview-quality questions
    - optional harder reps
    - exit signals
    - quest-log support
  - clarified that Campaign owns the shell and end-goal framing, while educational clarity outranks thematic expression during active build
  - clarified that Project State owns the live phase and near-term front
  - adopted Session Handoffs as a formal end-of-chat output requirement for meaningful build sessions
  - adopted a chat hierarchy:
    - meta chat
    - region chat
    - quest chat
  - clarified that quest chats should split by phase / goal when the job changes meaningfully
  - established that Quest 1 should later be cemented as the **Alpha reference quest**
  - established that Quest 2 should be the first cleaner quest built fully under the new standard

- **Why:**
  - the project had accumulated naming drift, mixed artifact models, and partial standards that no longer worked cleanly together
  - theming and shell structure were obscuring the educational object instead of supporting it
  - the foundation needed to be stabilized before further content expansion
  - a clean baseline was necessary so future work could build on a trustworthy system instead of carrying forward messy intermediate history
