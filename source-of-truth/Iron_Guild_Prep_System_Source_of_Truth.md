# Iron Guild Prep System — Source of Truth

## Purpose

This document defines the **execution layer** of the project:

- how practice is actually run,
- how coding reps are solved,
- how supported reps differ from proving reps,
- how system design and code review are trained,
- how skill notes are used behind the campaign,
- and which user-specific failure modes the system is built around.

This file is about **how the training works day to day**.
It is **not** the place for campaign worldbuilding, roadmap ordering, or live quest progress.

When in conflict, this document only governs its owned area.

---

## Ownership boundary

### This document owns

- the coding problem-solving protocol
- the supported-rep vs proving-rep operating model
- daily startup / study / shutdown workflow
- system-design Prompt Lock
- code-review operating model
- skill-note usage rules behind the campaign
- note-development workflow rules
- artifact workflow rules for source-of-truth docs
- user-specific failure modes and execution guard rails
- project working principles that shape how artifacts are judged
- streaming constraints that affect practice quality

### This document does **not** own

- the campaign narrative and quest-floor definitions
- the ordered region map
- live quest progress or open implementation tasks
- static-page or presentation-layer development
- detailed artifact-construction rules
- per-quest enemy / boss lists
- broad note-coverage inventory by region

---

## Update rule

Update this file when the **training method or operating rules** change.

Examples:

- changing the coding protocol,
- changing the supported-rep / proving-rep model,
- changing shutdown workflow,
- adding a new systems or code-review routine,
- changing skill-note usage rules,
- changing problem-selection guard rails,
- changing note-development workflow,
- or changing scope-protection rules that affect execution.

Do **not** update this file just because a quest changes position on the roadmap or a note’s completion status changes.

---

## Related docs

- **Iron Guild Campaign — Source of Truth**: owns campaign framing, quest architecture, and artifact roles
- **Iron Guild Roadmap — Source of Truth**: owns sequencing, progression, and broad note-coverage visibility
- **Iron Guild Quest State — Source of Truth**: owns what is active right now
- **Quest Content Build Guide**: owns detailed quest-artifact construction rules
- **Skill Note Development Build Guide**: owns detailed skill-note construction rules
- **After MVP Feature Backlog**: owns future ideas that are real but not active scope
- **Iron Guild Shared Decision and Terminology Log**: owns cross-project change memory

---

## User-specific baseline

This prep system is not generic.
It is explicitly shaped around known failure modes:

- missing details from prompts,
- overcomplicating solutions,
- abandoning process under pressure,
- and talking out of a correct early instinct.

A previous Squarespace loop exposed concrete gaps:

- **code review:** Spring Boot patterns, N+1 detection, authorization boundaries
- **system design:** missing real-time delivery and notification-history requirements because not all functional requirements stayed visible

Future coaching should therefore optimize for:

- requirement visibility,
- cleaner first reads,
- simpler representations sooner,
- and process preservation under stress.

---

## Project working principles

This prep system is built under active guard rails.

Ideas, examples, draft notes, imported material, and earlier wording are treated as **inputs to evaluate**, not automatic decisions to preserve.

The governing rule is:

**optimize for the learning objective first, preserve source material second.**

That means:

- keep what genuinely improves understanding, motivation, continuity, or legibility
- replace examples that are familiar or famous but weak for the teaching goal
- reorganize or rename material when that produces a cleaner learning artifact
- delete bloated, misleading, or redundant material instead of protecting it because it already exists
- preserve theme, naming, and shared analogies when they strengthen engagement and system coherence
- push promising but nonessential ideas into the **After MVP Feature Backlog** unless they materially improve current execution

Real respect for source material means helping it become stronger, not staying close to it by default.

### Scope-protection rule

The project is currently about building a usable prep system and curriculum skeleton first.

That means:

- stable source-of-truth docs come before polish
- usable quest skeletons come before presentation work
- practical question curation comes before aesthetic refinement
- presentation-layer development is intentionally deferred until after MVP

If presentation work becomes tempting because it feels motivating or visually satisfying, that is **not by itself** a reason to promote it into current scope.

---

## Core learning principles

### 1) Supported reps and proving reps are different jobs

Pattern-learning reps and interview-caliber proving reps are not the same thing.

Treating every problem like full interview mode is inefficient, draining, and often bad pedagogy.
The system should preserve the distinction between:

- **supported reps** for learning and pattern shaping
- **proving reps** for stronger evaluation and synthesis

The campaign expresses this distinction through things like:

- Enemy Floor,
- Side Hunts,
- Boss Chamber,
- and Side Bosses.

The prep-system meaning underneath that campaign language is:

- some reps are for building the move,
- some reps are for proving the move.

### 2) The written approach is the source of truth

The biggest anti-spiral rule in the entire system:

- if the code and written approach disagree, stop
- fix the approach first
- then realign the code

### 3) Rewind instead of patching

When stuck, do not push forward with broken logic.
Go back to the earlier phase where the error entered the process.

### 4) Externalize decisions

This system works better when decision friction is removed ahead of time.

That is why:

- the roadmap externalizes “what kind of thing comes next”
- shutdown externalizes tomorrow’s exact reps
- the task list externalizes the active block
- templates externalize structure without replacing understanding

### 5) Do not abandon a correct first instinct too early

A known failure mode is correctly seeing the right move, then talking yourself out of it.
This system is designed to make that drift visible.

### 6) Completeness beats false neatness when the extra detail is doing real work

The system does **not** optimize for maximum compression.

Some repetition is intentional when it reinforces:

- interview behavior,
- requirement visibility,
- structured communication,
- or transfer of reasoning.

The goal is not to make every artifact as short as possible.
The goal is to make the learner stronger.

---

## Coding execution protocol

This is the underlying execution engine for full coding reps.

### Phases

1. Extract
2. Clarify
3. Brute Force
4. Optimize
5. Algorithm
6. Code
7. Test
8. Reflect

### Core protocol rules

- the protocol is **re-entrant**, not rigid dogma
- the **written approach is the source of truth**
- if things drift, rewind to the approach rather than patching code blindly
- use a **20-minute rewind guardrail** when stuck
- use a **45-minute cutoff** for full proving reps unless the rep intentionally says otherwise

### Important nuance

On some graph, simulation, matrix, or implementation-heavy problems, brute force and optimal may collapse into the same workable shape.

Do not force fake cleverness when the real job is clean implementation.

### Reflection output

After a real rep, reflection should ask:

- what was my first instinct?
- was it correct?
- where did I get stuck?
- did my code stay aligned with my written approach?
- what exactly needs drilling next?

---

## Supported-rep vs proving-rep operating model

### Supported reps

These are the main pattern-learning reps.
They are used to:

- learn the mechanic,
- build recognition,
- understand the representation,
- and get the core move under control.

Characteristics:

- notes and references allowed when appropriate
- focus on form, recognition, and clean mechanics
- if stuck for roughly 10–15 minutes, study the move instead of pretending that continued struggle is automatically productive
- often drawn from progressive or canonical sequences
- may include starter batches, reserve reps, or supported variations

### Proving reps

These are stronger interview-caliber checks.
They are used to:

- test whether the learner can recognize and execute the move with more independence
- test whether the mechanic survives pressure, disguise, or synthesis
- prepare for OA / phone / onsite style quality

Characteristics:

- fewer supports
- full protocol
- stronger emphasis on articulation and correctness
- often timed
- often followed by reflection
- should be high-quality representatives of what the quest is actually training

### Interpretation rule

The system should never collapse into:

- “every rep is a proving rep,”
- or “I must clear everything under full pressure to deserve progress.”

Some reps exist to build the move.
Some reps exist to prove the move.
Both matter.

---

## Daily operating system

### Startup rhythm

- meds
- some physical activity
- focus music or another reliable transition ritual
- a short typing warmup if useful
- then the main study block

### Block rule

- prefer one large study block instead of many tiny fragmented topic blocks
- follow the current route sequentially
- supported reps before proving reps when building a new area
- insert systems / code-review work where the roadmap calls for it

### Streaming rule

Streaming can stay in the loop, but real solving needs protected attention.
A proving rep should keep a **silent window**.
Chat interaction during the core solve hurts problem quality.

### Shutdown rule

- write a short retro
- choose tomorrow’s specific reps during shutdown
- put them into the task list
- avoid recurring overdue-task shame spirals

Interpretation:
Shutdown is not optional fluff.
It is a core anti-friction mechanism.

---

## Task-management rule

The task list is the operational layer, not the knowledge base.

Use it to externalize:

- startup
- shutdown
- today’s block
- curated next reps
- mock sessions
- job-search actions

Keep the visible daily list small enough that it does not create freeze-through-overload.

---

## Artifact workflow rule

Use chat as the working draft layer.

For each source-of-truth artifact:
- keep one canonical saved document,
- update that document as the current truth,
- let David manage historical snapshots separately,
- and avoid creating side files unless they have a clearly different job.

Interpretation rule:
The goal is to reduce partial-document sprawl, conflicting versions, and document-maintenance overhead.

---

## System-design operating model

### Prompt Lock

Prompt Lock should remain active for design practice.

Steps:

1. split the prompt into **Actors**, **Functional Requirements**, and **Non-Functional Requirements**
2. turn FRs into **prove-it questions**
3. put checkboxes next to every FR
4. do a midpoint checkpoint
5. end with a closure pass

Why this exists:
One real failure mode is letting part of the prompt disappear from focus mid-design.

### Systems progression logic

- systems is intentionally interleaved early
- early work leans on fundamentals reading and redraw-from-memory style reps
- later work shifts toward deeper exercises and mocks
- systems practice is not a “later, after coding is done” activity

---

## Code-review and design-judgment operating model

### Four practical review tiers

1. correctness and safety
2. performance and data access
3. error handling and API design
4. design and maintainability

### Why this matters

The campaign is not just coding + system design.
It is also training for realistic engineering judgment in codebases and review conversations.

---

## Skill-note usage rules behind the campaign

The campaign-facing skill note is a pre-entry learning artifact.
The **Skill Note Development Build Guide** owns how those notes are constructed.

This prep-system file owns how they should be **used** and what standards they must preserve.

### Governing rule

A skill note should make the learner stronger at:

- recognizing the pattern,
- choosing the right representation,
- explaining why the pattern fits,
- and walking through the solution with interview-grade clarity.

### Why some repetition is intentional

Examples inside a skill note are not just miniature summaries.
Each worked example is also a **mental interview rep**.

That means repetition is sometimes doing real training work.

For a strong worked example, it is often correct to restate:

- the goal,
- the effective problem shape,
- the clarifying questions that should be asked,
- the constraints that matter,
- the reason the variant fits,
- and the key variables or state.

This is not pointless duplication when it is reinforcing:

- how to signal understanding,
- how to answer the actual question being asked,
- how to surface missing constraints,
- and how to preserve structure under interview pressure.

### What counts as good detail

Good detail:

- makes the reasoning easier to follow
- preserves the logic of the move
- models how to communicate in an interview
- explains **why** a complexity claim is true
- helps the learner transfer the pattern to a new problem

### What counts as bad bloat

Bad bloat:

- giant undifferentiated problem dumps
- full code archives inside the note
- repetitive sections that add no new reasoning
- oversized walkthroughs that do not improve understanding
- preserving weak examples just because they are already there

Interpretation rule:
The system should reject fake neatness.
It should also reject archive behavior.
The right standard is **enough detail to teach and transfer the move cleanly**.

---

## Note-development workflow

Note development is part of the prep system, but it is not the main workflow.

The system should not pause practical prep in order to batch-create or mass-refine every note at once.

Instead:

- notes are created, upgraded, or refined incrementally
- note work follows the active roadmap
- note work is usually handled one quest or one region at a time
- the goal is to keep note quality improving without letting note-writing replace practice

The roadmap owns broad note-coverage status.
Quest State owns note work that is active right now.

---

## Practical execution philosophy

The prep system should stay usable.

Working rules:

- protect process before chasing cleverness
- let reflection determine the next reps
- keep the current phase clear
- preserve pressure where it teaches
- preserve support where it teaches
- do not confuse harder with better
- do not let organization replace practice
- do not let future ideas crowd out the current build