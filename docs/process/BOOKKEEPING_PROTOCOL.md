# Bookkeeping Protocol

## Purpose

Bookkeeping is the maintenance work that keeps a Mnemos repository usable between sessions.

The goal is continuity:

```text
The next session should quickly know where we left off, what changed, why it changed, and what to do next.
```

## Required Mnemos Core

A repository is using Mnemos only if these core capabilities are maintained:

1. **Identity** — the project can say what it is.
2. **Current State** — the project can say where it left off.
3. **Project Map** — the project can say where information belongs.
4. **Journal** — the project can say why decisions were made, what was tried, and what should not be forgotten.
5. **Constitution** — the project can say what principles, standards, or rules are accepted.
6. **Indexes** — significant folders explain themselves.
7. **Bookkeeping** — important changes are preserved before context is lost.

If a user removes or ignores one of these systems, the repository may still be useful, but it is no longer fully following the Mnemos contract.

## What Bookkeeping Does

Bookkeeping means:

- updating `CURRENT_STATE.md`;
- adding or updating journal entries for durable reasoning;
- updating indexes when files or folders change;
- updating `PROJECT_MAP.md` if repository navigation changes;
- preserving links to related files;
- preserving search terms, aliases, and old terminology;
- recording why obvious alternatives were rejected;
- noting unresolved questions or next steps.

Bookkeeping does not mean expanding the project into unrelated new work.

## Journal vs Constitution

Use the journal for:

- ideas;
- proposals;
- experiments;
- why-decisions;
- rejected alternatives;
- lessons learned;
- warnings for future sessions.

Use the constitution for:

- accepted principles;
- stable standards;
- durable rules;
- project boundaries;
- decisions that have been tested and should guide future work.

A good idea should usually go to the journal before it graduates into the constitution.

## Standard End-of-Session Checklist

When the user says:

```text
Ok, let's do our bookkeeping.
```

or equivalent, do this:

1. Identify what changed during the session.
2. Identify decisions, rejected alternatives, lessons, risks, and next steps.
3. Update `CURRENT_STATE.md` with the active handover.
4. Add or update journal entries for durable reasoning.
5. Update affected `INDEX.md` files.
6. Update `PROJECT_MAP.md` only if root navigation or authority changed.
7. Update the constitution only if a principle has clearly become accepted.
8. Preserve related files and useful search terms.
9. Do not broaden into unrelated work.
10. Summarize what was updated.

## Current State Requirements

`CURRENT_STATE.md` should include:

- timestamp;
- current phase;
- current priority;
- active next step;
- recent decisions;
- do-not-lose notes;
- files most likely to matter next;
- related journal entries;
- useful search terms;
- blockers or risks;
- loose ends.

## Journal Entry Requirements

Every major journal entry should include:

- entry number or stable title;
- timestamp including time zone;
- status;
- significance;
- tags;
- keywords and search terms;
- summary;
- decision or finding;
- reasoning;
- rejected alternatives;
- lessons learned;
- related files;
- related entries;
- next steps.

## Findability Rule

Optimize for future retrieval.

Every important entry should leave multiple ways to find it later:

- title;
- timestamp;
- tags;
- keywords;
- aliases;
- related files;
- related entries;
- old terms;
- search phrases.

## Startup Rule

At the beginning of a session, the assistant should:

1. Confirm it has repository access if repository work is requested.
2. Read `IDENTITY.md`.
3. Read `CURRENT_STATE.md`.
4. Read `PROJECT_MAP.md`.
5. Read `docs/INDEX.md`.
6. Read any files named by `CURRENT_STATE.md` that are relevant to the task.
7. Search before inventing new structures.
8. Preserve canonical terminology unless the user explicitly changes it.

## If Repository Access Is Missing

If the assistant cannot access the repository, it should say so plainly.

It may still help from the conversation, but it should not pretend to have read the Mnemos files.
