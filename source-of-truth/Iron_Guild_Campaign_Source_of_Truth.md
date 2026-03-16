# Iron Guild Campaign — Source of Truth

## Purpose
This document defines the **campaign layer** of the interview-prep system:
- the world model,
- the narrative framing,
- what a quest is,
- how quests are structured,
- and how campaign artifacts should feel.

This file is about **what the campaign is**.
It is **not** the place to store the detailed roadmap order, daily training protocol, or live quest progress.

When in conflict, this document only governs its owned area.

---

## Ownership boundary

### This document owns
- Iron Guild framing
- Rowan Vale / mentor role
- hidden Blessing concept
- campaign philosophy at a high level
- region / quest / room definitions
- quest architecture at the campaign level
- Field Guide / Quest Brief / Quest Log / skill-note role definitions
- artifact and immersion philosophy

### This document does **not** own
- the literal ordered roadmap and sequencing changes
- day-to-day operating rules and solving protocol details
- current quest progress and open implementation tasks
- detailed curriculum inventory
- detailed artifact-construction rules
- per-quest state
- shared terminology history or cross-document decision memory

---

## Update rule
Update this file only when the **campaign model itself** changes.

Examples:
- changing what a quest contains,
- replacing the readiness model,
- changing how campaign artifacts are conceptually divided,
- changing the artifact philosophy,
- changing the world framing.

Do **not** update this file just because a new quest is started or completed.

---

## Related docs
- **Iron Guild Roadmap — Source of Truth**: owns quest order and progression
- **Iron Guild Prep System — Source of Truth**: owns training method and execution rules
- **Iron Guild Quest State — Source of Truth**: owns what is active right now
- **Quest Content Build Guide**: owns detailed quest-artifact construction rules
- **Skill Note Development Build Guide**: owns detailed skill-note construction rules
- **Iron Guild Shared Decision and Terminology Log**: owns cross-document lineage and change memory
- **After MVP Feature Backlog**: owns future expansion ideas that should not enter current MVP scope

---

## What this system is
The campaign is a structured interview-prep system designed around **modern interview ROI**, not textbook completeness.

It is intentionally framed as an RPG-style journey because that makes the work:
- more legible,
- more motivating,
- more emotionally sustainable,
- and easier to re-enter after friction or self-doubt.

The campaign is not meant to outsource learning.
It exists to create a better training environment:
- clear progression,
- reduced ambiguity,
- stronger note structure,
- better sequencing,
- and active practice still owned by the learner.

---

## Non-negotiable campaign philosophy

### 1) Optimize for readiness, not completeness
The campaign is built around what improves real interview performance.
That means:
- common coding patterns come first,
- system design appears earlier than a traditional “finish DS&A first” path,
- code review / modeling / judgment are part of the route,
- lower-frequency topics like deep DP move later,
- and the learner should apply before feeling “100% done.”

### 2) Keep the path interleaved
The campaign should **not** become:
- all coding first,
- then all system design,
- then all code review.

Instead:
- coding is the backbone,
- systems work appears early and repeatedly,
- design judgment is woven in,
- and later reps become more mixed and realistic.

### 3) Do not overbuild the kingdom
A repeated guard rail:
- do not design the whole campaign at once,
- do not let roadmap-building become its own hobby,
- get the process right,
- build the current and near-future quests well,
- expand only when needed.

### 4) Preserve ownership and judgment
Templates and frameworks are useful, but they must not replace real understanding.
The campaign exists to improve:
- recognition,
- reasoning,
- execution under pressure,
- and judgment about what the prompt is actually asking.

---

## Campaign world model

### World structure
- **Campaign** = the full interview-prep journey
- **Region** = a major terrain / topic family
- **Quest** = one interleaved module inside a region
- **Room / Space** = one traversed layer inside a quest

### What a quest is
A quest is the smallest meaningful unit of campaign progression.
A strong quest is:
- narrow enough to feel concrete,
- large enough to teach a real family of skills,
- interleaved enough to feel like interview prep rather than isolated theory study.

A quest is **not**:
- a giant theory dump,
- a full course,
- or a random bundle of problems with no identity.

---

## Campaign artifact roles
These artifacts have different jobs. They should not be collapsed into each other.

### Field Guide
The world-facing campaign explanation.
It explains what the Iron Guild is, how the road works, and how the learner should understand the journey.

### Quest Brief
The forward-looking operational setup for a quest.
It explains:
- what this quest is for,
- which skill note(s) support it,
- which enemies / bosses / optional content belong to it,
- and what the Exit Gate will require.

### Quest Log
The retrospective operational record of a quest clear.
It captures:
- what was actually done,
- which enemies / bosses / optional content were attempted or cleared,
- how the Exit Gate was satisfied,
- what evidence exists of the clear,
- what was learned,
- and what still feels weak after completion.

### Skill / Pattern Note
The skill / pattern note is the pre-entry learning artifact for a quest.

Its purpose is to equip the learner with:
- the core mental model,
- recognition signals,
- major variants,
- and the style of structured reasoning needed to face the quest honestly.

It is not the quest itself.
It is the technique / skill-acquisition artifact that prepares the learner for the quest.

Detailed note-construction philosophy, worked-example standards, and refinement rules belong in the **Skill Note Development Build Guide**, not here.

Historical note:
Earlier discussions often called these **lore notes**. That older term remains understandable context, but the live model treats them more like skill / pattern notes than environmental lore.

### Campaign artifacts
Campaign artifacts preserve the immersive and motivational layer of the project.

This includes things like:
- the intro / invitation,
- quest briefs,
- mentor-facing or world-facing framing,
- and other visible campaign materials that help the work feel like an adventure.

These artifacts should preserve immersion, continuity, and motivational framing.

Detailed construction rules for campaign artifacts belong in the **Quest Content Build Guide**, not here.

---

## Campaign presentation and immersion philosophy
The campaign should feel like an adventure, not like a product overview.

Important rules:
- avoid “acts” framing,
- avoid meta language that breaks immersion,
- the entry experience should feel like both an invitation and a mentor’s speech,
- the tone should be warm, grounded, invitational, and respectful of the learner’s real ability,
- and the campaign should feel closer to a tabletop / RPG journey than to a sterile curriculum page.

Format choice does **not** define immersion by itself.
Immersion is governed by tone, framing, and continuity first.
Detailed implementation rules belong in the build guides.

---

## Quest structure
A quest is supported by pre-entry artifacts and then traversed through its main spaces.

### Pre-entry support
Before or at the threshold of the quest, the learner may receive:
- the **Quest Brief**,
- the relevant **skill / pattern note(s)**,
- and any campaign-facing orientation needed to enter the area correctly.

These are not the same thing as the traversed rooms.

### Traversed quest spaces
Each quest may contain these spaces:

#### Enemy Floor
Canonical reps tied directly to the supported mechanic.
These are the cleanest “fight the core mechanic” problems.

#### Architect’s Wing
The system-design slot.
This keeps architecture work live and prevents long avoidance cycles.

#### Trial Room
The judgment slot.
This is where engineering-adjacent interview skills are interleaved into the quest, such as:
- prompt deconstruction,
- requirement locking,
- code review judgment,
- OOD / interface judgment,
- modeling decisions,
- and “what is this really asking?” translation.

The purpose of the Trial Room is not just novelty.
It exists because real interview performance is often damaged by poor framing, poor reading, or weak judgment even when the underlying algorithm knowledge is present.

#### Boss Chamber
The main proving ground.
Boss reps are the curated, high-quality interview-caliber representatives of the quest.
They do not need to be unseen, but they do need to strongly express what the quest is really training.

#### Side Hunts
Optional supported variation reps.
These exist for:
- disguise,
- refresh,
- confidence-building,
- reserve examples,
- and extra pattern exposure when the learner needs more reps before the Exit Gate is honestly satisfied.

They should not be presented in a way that implies the learner is defective for needing more than an initial starter batch.
The Exit Gate, not a quota, determines readiness to leave.

#### Side Bosses
Optional stretch boss-tier content.
These are harder or sharper boss-level reps beyond the main Boss Chamber.
They are not required for an honest quest clear unless a quest explicitly says otherwise.

#### Exit Gate
The visible move-on criteria for the quest.
The Exit Gate exists so completion is based on observable clears rather than on mood, bargaining, or perfectionist drift.
It should distinguish required clears from optional stretch content.

---

## Early-campaign exception
In the early campaign, the **Architect’s Wing** may be heavier than normal.
This is intentional.
The goal is to reduce system-design anxiety and rebuild comfort instead of leaving systems work untouched until later.

---

## Narrative framing and readiness model

### Rowan Vale
**Master Rowan Vale** is the mentor figure and steadying voice of the campaign.
He represents:
- guidance,
- calm authority,
- honest readiness judgment,
- and a refusal to let anxious self-negotiation define progress.

### The Blessing
An earlier visible readiness milestone existed:
- **The Gate of Readiness**

The live in-world model replaced that visible gate with:
- **The Blessing**

Rules for the Blessing:
- it exists,
- it is not shown on the roadmap,
- the learner should not know where it is,
- Rowan grants it when the clears show enough consistency and readiness.

Why this matters:
A visible readiness gate encourages anxious bargaining.
The hidden Blessing preserves readiness as a real thing without turning it into a visible pressure checkpoint.

Interpretation rule:
- the old Gate of Readiness is historical context,
- the authoritative live campaign model uses the **hidden Blessing**.

---

## Artifact strategy

### Current MVP rule
The current MVP priority is:
- stable source-of-truth docs,
- quest skeletons,
- usable question blocks,
- and enough structure to actually prep now.

Because of that, the live build rule is:
- **markdown first for quest content**,
- **no active presentation-layer development during MVP**.

### Presentation-layer boundary
Static HTML or other presentation-layer artifacts may become valuable later, but they are **not active scope during MVP**.

Presentation work should stay in **After_MVP_Feature_Backlog.md** unless it materially improves current prep execution or unlocks a blocked part of the build.

If presentation work becomes tempting because it feels motivating or visually satisfying, that is **not by itself** a reason to promote it into current scope.

The project should finish the core prep system first:
- source-of-truth stability,
- quest skeleton coverage,
- usable question blocks,
- and practical prep usability.

Only after that should presentation-layer refinement be considered for active development.

---

## Practical campaign philosophy
The campaign should stay operational.

Working rules:
- work one quest at a time
- keep summaries sufficient but not bloated
- expand only when the next quest needs to exist
- preserve immersion because it lowers friction and improves willingness to engage
- do not let campaign artifacts become theory dumps

---

## After-MVP boundary
The project will continue to generate promising ideas that may be worth building later.

If an idea does not materially improve current prep execution, current curriculum structure, or the current MVP build phase, it should not become active scope.

Those ideas belong in **After_MVP_Feature_Backlog.md** until they are deliberately promoted.

This includes things like:
- post-offer growth extensions,
- community or collaboration features,
- possible future regions or chapters,
- optional expansion systems,
- and other ideas that are real but not necessary yet.
