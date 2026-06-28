# Mnemos Contract

## Purpose

This document defines the working agreement that makes a repository recognizably Mnemos.

Use it as the drift refresher.

If the AI begins to lose the method, skip core steps, forget indexing, invent structure too freely, or stop maintaining continuity, the user can say:

```text
Refresh on the Mnemos Contract and audit your work against it.
```

The AI should then read this document, correct course, and continue according to the Mnemos method.

## Core Statement

Mnemos is a collaborative project memory system in which the human owns the project, the AI helps maintain continuity, and both cultivate the repository together according to a shared contract.

The repository is the durable memory.

The AI is the reasoning and maintenance partner.

The user's current prompt is the task, not the whole memory.

## Conceptual Anchors

These terms are intentional AI-calibration anchors for Mnemos.

They are included early because they compress the system's architectural intent into a small amount of boot context. Human users do not need to memorize them, but AI assistants should use them to stay aligned with the spirit and structure of the system.

- **Fractal** — the same organizational principles repeat at multiple scales throughout the repository.
- **Recursive** — navigation and maintenance should reuse established patterns rather than inventing new ones unnecessarily.
- **Canonical** — each important concept, decision, or source of truth should have one clear authoritative home.
- **Authority** — documents have defined responsibilities and precedence; know which file governs which question.
- **Provenance** — preserve where information, evidence, ideas, and decisions came from.
- **Ontology** — maintain coherent terminology and relationships between concepts.
- **Immutable History** — preserve historical reasoning rather than silently rewriting why decisions happened.
- **Idempotent** — repeated startup, audit, or bookkeeping should converge on the same correct state rather than creating duplicates or drift.
- **Cultivation** — repositories evolve collaboratively through observation, dialogue, and use.
- **Continuity** — preserve enough context that future sessions can resume efficiently.
- **Findability** — optimize for retrieval through indexes, links, keywords, aliases, related files, and search terms.
- **Locality** — information should live close to where it is used, with links outward when needed.
- **Hierarchy** — navigation should flow from general to specific, with explicit authority at each level.
- **Composability** — new project structures should be built from existing Mnemos patterns where possible.
- **Traceability** — important outcomes should be traceable back to reasoning, evidence, and related files.
- **Self-Audit** — the AI should periodically compare its work against this contract.
- **Stewardship** — the AI is responsible for helping maintain continuity, not merely generating content.
- **Convergence** — each meaningful interaction should leave the repository more organized, consistent, and discoverable than before.
- **Progressive Disclosure** — expose complexity only when it becomes useful; do not overwhelm the user.
- **Least Surprise** — prefer extending existing patterns over introducing surprising new structures.

## Fractal Organization

Mnemos is intentionally fractal.

The same organizational principles repeat at multiple scales:

- repository -> project map;
- folder -> local index;
- document -> related files;
- journal entry -> related entries;
- current state -> next reading path;
- decision -> reasoning -> provenance;
- core contract -> local practice.

This recursive self-similarity is intentional.

When extending a Mnemos repository, prefer repeating established patterns rather than inventing a new organizational model.

Before introducing a new structure, ask:

```text
Can this be expressed using the existing fractal Mnemos pattern instead?
```

## The Mnemos Contract

A repository is using Mnemos only when these core capabilities are actively maintained.

### 1. Identity

The project must be able to answer:

- What is this project?
- Who owns it?
- What is it for?
- What privacy level applies?
- What role does this repository play?

Primary file:

- `IDENTITY.md`

### 2. Current State

The project must be able to answer:

- Where did we leave off?
- What matters next?
- What should not be lost?
- What files are most relevant now?
- What decisions or risks are active?

Primary file:

- `CURRENT_STATE.md`

### 3. Project Map

The project must be able to answer:

- Where does information belong?
- What files are authoritative?
- What should be read first?
- Where are the local indexes?

Primary file:

- `PROJECT_MAP.md`

### 4. Journal

The project must preserve reasoning, not just outcomes.

The journal records:

- why decisions were made;
- what was tried;
- what was rejected;
- what should not be repeated;
- what remains uncertain;
- what future sessions should search for.

Primary file:

- `docs/memory/PROJECT_JOURNAL.md`

### 5. Constitution

The project must preserve accepted principles separately from temporary ideas.

The constitution records:

- stable rules;
- accepted standards;
- project boundaries;
- durable principles;
- non-negotiable practices.

Primary file:

- `docs/constitution/PROJECT_CONSTITUTION.md`

### 6. Indexes

The project must remain findable.

Every significant folder should have an `INDEX.md` explaining what belongs there and linking to important files.

New files must be indexed in the most local relevant index.

Parent indexes should only be updated when the new file changes the parent-level navigation.

Primary files:

- `docs/INDEX.md`
- local `INDEX.md` files inside significant folders

### 7. Bookkeeping

The project must preserve continuity before context is lost.

Bookkeeping updates:

- current state;
- journal;
- indexes;
- project map when navigation changes;
- constitution when a principle becomes accepted.

Primary file:

- `docs/process/BOOKKEEPING_PROTOCOL.md`

## Required AI Behaviour

When working in a Mnemos repository, the AI should:

1. Treat the repository as durable memory.
2. Read the startup path before making assumptions.
3. Preserve canonical terminology unless the user explicitly changes it.
4. Search existing files before inventing new structures.
5. Maintain the Mnemos core automatically.
6. Explain manual steps the user must perform.
7. Avoid pretending to have done work it could not do.
8. Minimize user effort by doing what it can do directly.
9. Preserve reasoning in the journal when decisions matter.
10. Preserve findability through indexes, links, tags, aliases, and search terms.

## Required Startup Behaviour

At the beginning of repository-aware work, the AI should read or check:

1. `MNEMOS_CONTRACT.md`
2. `IDENTITY.md`
3. `CURRENT_STATE.md`
4. `PROJECT_MAP.md`
5. `docs/INDEX.md`
6. relevant local indexes;
7. files named by the current state or project map that are relevant to the task.

The AI does not need to read every file every time. It should read enough to work accurately while preserving context.

## Required File Creation Behaviour

When creating a new file, the AI should:

1. Place it in the most appropriate folder.
2. Update the local `INDEX.md` for that folder.
3. Update a parent index only if parent-level navigation changes.
4. Update `PROJECT_MAP.md` only if repository-level navigation changes.
5. Consider whether the decision belongs in the journal.
6. Consider whether the current state needs to change.
7. Preserve useful search terms and related links.

## Required Decision Behaviour

When making or recording a significant decision, the AI should preserve:

- what was decided;
- why it was decided;
- what alternatives were considered;
- what was rejected and why;
- what evidence or context mattered;
- what would change the decision;
- related files;
- useful search terms.

A decision should usually enter the journal before it graduates into the constitution.

## Cultivation Rule

The Mnemos core is required.

Everything beyond the core is cultivation.

Cultivation means the AI and user adapt the repository to the actual project through dialogue and observation.

The AI may suggest folders, workflows, prompts, glossaries, timelines, evidence systems, source logs, or other structures when the project context calls for them.

Those suggestions should not be treated as core unless they later prove broadly necessary and are deliberately promoted.

## Drift Warning Signs

The AI may be drifting if it:

- creates files without indexing them;
- forgets to update `CURRENT_STATE.md` after important work;
- records conclusions without reasoning;
- treats the journal as optional;
- treats the constitution as a scratchpad;
- invents terminology without checking existing usage;
- ignores the startup path;
- adds elaborate structures without user need;
- asks the user to do work the AI could do directly;
- claims repository-aware certainty without repository access;
- forgets privacy and ownership boundaries.

## Contract Audit

Before saying significant repository work is complete, the AI should ask:

1. Did I read the relevant startup files?
2. Did I preserve the Mnemos core?
3. Did I index every new file locally?
4. Did I update parent indexes only when appropriate?
5. Is `CURRENT_STATE.md` still accurate?
6. Does this session need a journal entry?
7. Did any idea graduate to the constitution, or is it still only a journal idea?
8. Did I preserve reasoning, rejected alternatives, and search terms?
9. Can a future AI find this work?
10. Can a future human understand why it exists?

## Project Audit

A project audit checks the repository itself.

It should look for:

- missing indexes;
- broken or stale links;
- outdated current state;
- unrecorded decisions;
- unclear file purposes;
- duplicated or conflicting terminology;
- privacy risks;
- missing related-file references;
- orphaned files.

Suggested prompt:

```text
Audit this Mnemos repository for missing indexes, stale current state, unclear navigation, unrecorded decisions, and drift from the Mnemos Contract.
```

## Contract Audit

A contract audit checks the AI's behaviour.

It should look for:

- skipped startup steps;
- unindexed files;
- missing journal updates;
- weak reasoning records;
- overbuilt structures;
- unsupported assumptions;
- failure to ask for necessary repository access;
- failure to explain manual user actions.

Suggested prompt:

```text
Refresh on MNEMOS_CONTRACT.md and audit your last actions against it before continuing.
```

## If The User Changes The System

The user owns the repository and may change anything.

The AI should not forbid changes.

However, if a change removes or weakens a Mnemos core capability, the AI should clearly warn the user.

Suggested wording:

```text
We can do that, but it changes the Mnemos contract. If we remove this part, the repository may still be useful, but it will no longer fully operate as Mnemos unless we replace that capability somewhere else.
```

## Minimal Mnemos Rule

If nothing else is remembered, remember this:

```text
Read the contract. Preserve the core. Index the work. Record the reasoning. Update the handover.
```
