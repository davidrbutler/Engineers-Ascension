# Iron Guild Roadmap — Source of Truth

## Purpose
This document defines the **roadmap layer** of the project:
- what comes next,
- in what order,
- why that order exists,
- what gets promoted or deferred,
- and how broad curriculum coverage is staged.

This file is about **sequence, scope, and pacing**.
It is **not** the place for campaign worldbuilding, day-to-day training protocol, or live quest status.

When in conflict, this document only governs its owned area.

---

## Ownership boundary

### This document owns
- the ordered region map
- region and quest sequencing
- structural promotions or demotions of topics
- roadmap-level readiness and pacing logic
- broad curriculum inventory behind the campaign
- staging of later or advanced topic families
- broad note-coverage status by region or quest

### This document does **not** own
- quest-floor definitions or campaign artifact roles
- detailed execution rules for solving, shutdown, or Prompt Lock
- live progress, active quest state, or open implementation tasks
- static-page or presentation-layer development
- detailed per-quest enemy / boss lists
- detailed artifact-construction rules

---

## Update rule
Update this file when the **ordering, grouping, scope, pacing, or broad coverage model** of the route changes.

Examples:
- moving a region earlier or later,
- splitting or merging a region,
- adding or removing a quest family,
- promoting a side family into the main path,
- changing broad note-coverage status,
- or changing how a region is internally staged.

Do **not** update this file just because a quest page got built or a single study session happened.

---

## Related docs
- **Iron Guild Campaign — Source of Truth**: owns campaign framing, quest architecture, and artifact roles
- **Iron Guild Prep System — Source of Truth**: owns training method and execution rules
- **Iron Guild Quest State — Source of Truth**: owns what is active right now
- **Quest Content Build Guide**: owns detailed quest-artifact construction rules
- **Skill Note Development Build Guide**: owns detailed skill-note construction rules
- **After MVP Feature Backlog**: owns future ideas that should not enter active scope yet
- **Iron Guild Shared Decision and Terminology Log**: owns major historical changes and naming lineage

---

## What this roadmap is
The roadmap is the sequencing layer behind the campaign.

Its job is to answer:
- what should come next,
- why that order is justified,
- what should stay embedded instead of split into its own region,
- and which parts of the broader curriculum are active now versus staged for later.

The roadmap is **not** a day planner.
It is a route through the work.

---

## Non-negotiable roadmap philosophy

### 1) Interview ROI over completeness
The roadmap is designed around actual interview payoff.
That means:
- common coding patterns come first,
- systems work appears earlier than a traditional pure-DS&A grind,
- design judgment and code review stay live,
- deep DP moves later,
- and application / mocks can begin before total mastery.

### 2) Interleaving is intentional
The route should never become:
- all coding first,
- all systems later,
- and judgment work only at the end.

The roadmap should reflect the real mixed shape of interview loops.

### 3) The route is a sequence of work units, not days
Progression is based on **solid enough to move on**, not calendar perfection.
Exact reps are chosen closer to execution time.

### 4) Skeleton first, polish later
The roadmap should first support a usable prep system.
That means:
- core route clarity before aesthetic refinement,
- usable quest skeletons before polished presentation,
- and broad coverage before perfectionist note overwork.

### 5) Do not overbuild the kingdom
The roadmap should stay high-leverage and executable.
It should not become a giant speculative backlog.
Promising later ideas should be preserved, but not allowed to crowd current build scope.

---

## Current ordered region map
This is the current live route.

1. The Hashing Frontier
2. Trial of Twin Paths
3. The Protocol Forge
4. Pass of the Sliding Window
5. Ruins of the Prefix Sum
6. The Searchspace Citadel
7. The Greedy Road
8. The Interval Marches
9. The Monotonic Tower
10. The Linked Chain
11. The Arbor Gate
12. The Heapforge
13. The Forest of Traversals
14. The Scalelord’s Primer
15. The Graph Labyrinth
16. The Craftsman’s Code
17. Vault of Systems
18. The Acyclic Spire
19. The Modelmaker’s Workshop
20. The Distributed Realm
21. The Backtracking Wilds
22. The Refactorer’s Lens
23. The Trie Archive
24. The Union Basin
25. The Architect’s Judgment
26. The First Trial of Iron
27. The Great Systems Atlas
28. The Dynamic Depths I
29. The Dynamic Depths II
30. The Second Trial of Iron
31. The Optional Abyss
32. The Final Ascent

Interpretation rule:
This list is the live sequencing backbone.
Detailed quest execution and live progress belong elsewhere.

---

## Important structural judgments

### Counting is not one region
Counting problems are distributed according to the mechanic that actually drives them.

- **Hashing Frontier** = frequency, grouping, complement lookup, ordered complement logic, first-unique-after-counting style work
- **Ruins of the Prefix Sum** = count subarrays / ranges / prefix remainder counts
- **Searchspace Citadel / Greedy Road** = counting inside feasibility or optimization
- **Dynamic Depths** = count ways, count valid constructions, combinational counting

### Matrix / 2D implementation has earned an early place
Matrix traversal and grid-style implementation discipline are not being treated as a late afterthought.
They were promoted into the early route because real OA evidence and implementation demands justify them.
In the live route, that work currently sits inside the **Hashing Frontier** rather than waiting for a separate late region.

### Math is not yet a standalone region
Math should stay embedded where it naturally belongs unless it clearly earns a dedicated region later.
A possible future dedicated math region remains a valid later consideration, but it is **not** current active scope.

### Systems, code review, and judgment are not deferred to the end
The roadmap intentionally keeps these live before the late game.
That is a structural decision, not a side preference.

### Advanced material should be staged, not dumped into the opening route
Later curriculum families exist, but they should be introduced when the route is ready for them.
The early roadmap should not be bloated by proving that the full kingdom exists.

---

## Region I — The Hashing Frontier

### Purpose
This is the early practical implementation region.
It trains:
- frequency counting,
- grouping,
- set membership,
- complement lookup,
- simulation and state tracking,
- 2D / matrix implementation discipline,
- and prompt deconstruction on disguised prompts.

### Current internal quest line
1. **Quest I — Frequency & Grouping**
2. **Quest II — Existence Checking with Sets**
3. **Quest III — Simulation & State Tracking**
4. **Quest IV — The Cartographer’s Table**
5. **Quest V — Frontier Boss Hunts**

### Internal progression logic
- Quest I teaches how to summarize and query data
- Quest II teaches membership, complements, and seen-before logic
- Quest III teaches evolving state and prompt-to-state translation
- Quest IV teaches 2D / matrix implementation discipline
- Quest V synthesizes the region under less guidance

### Interpretation rule
The Hashing Frontier is **not** just a tiny opening hash-map bucket.
It is a structured five-quest region with a real early-game job.

Detailed quest execution, problem lists, and active build state belong in **Quest State** and the quest artifacts, not here.

---

## Broad note-coverage model
The roadmap owns **broad note-coverage status** by region or quest.
It does not own day-to-day note work.

### Status labels
- **Missing** = no usable note yet
- **Rough legacy** = earlier material exists but does not meet the current standard
- **Stable enough** = good enough to support active progress
- **Refined current standard** = meets the current target quality for reusable prep

### Workflow rule
Note development should follow the active roadmap.
The system should **not** stop practical prep to batch-create or mass-refine every note at once.

Instead:
- notes are upgraded incrementally,
- note work usually happens one quest or one region at a time,
- and note refinement should support progress rather than replace it.

### Current broad note-coverage snapshot
- **Hashing Frontier**: partial coverage. **Frequency & Grouping** is the first note at refined current-standard quality; the remaining regional note set still needs creation or upgrade.
- **Later regions**: not yet upgraded to the current note standard and should be handled as they become active.

Interpretation rule:
- **Roadmap** owns broad coverage visibility
- **Quest State** owns what note work is active right now

---

## Preserved downstream curriculum families
These families remain part of the broader roadmap scope, but they should not bloat the early MVP path.

- Cache Design
- Iterator & Stream Design
- Snapshot & Versioning
- Real-World Modeling
- State Machine / Parsing
- Trie-Based System Modeling

Interpretation rule:
These are preserved because they reflect real interview and engineering-value territory.
They should be promoted deliberately, not just because they exist.

---

## Promotion and demotion rule
A topic, region, or family should move upward in the route only if it earns that place through real leverage.

Examples of good reasons:
- repeated interview evidence,
- repeated OA evidence,
- a recurring real weakness,
- strong transfer value,
- or a clear gap in the current route.

Weak reasons:
- the topic is interesting,
- the topic is advanced,
- the topic is famous,
- or the topic makes the roadmap look more impressive.

The roadmap should optimize for **useful sequence**, not prestige.
