# Project Map

This file is the root navigation and authority guide for the repository.

_Last updated: YYYY-MM-DD HH:MM <timezone>_

## Purpose

Use this file to understand where information belongs and which documents have authority.

## Start Here

1. Read `IDENTITY.md` for the project profile.
2. Read `CURRENT_STATE.md` for the active workstream.
3. Read this file for repository navigation and authority.
4. Read `docs/INDEX.md` for documentation navigation.
5. Read relevant local `INDEX.md` files before changing a folder.
6. Read `docs/memory/PROJECT_JOURNAL.md` when historical reasoning is needed.
7. Read `docs/process/BOOKKEEPING_PROTOCOL.md` before ending a significant session.

## Authority Hierarchy

```text
IDENTITY.md
    What project is this?

CURRENT_STATE.md
    Where did we leave off?

PROJECT_MAP.md
    Where does information belong?

docs/INDEX.md
    How is documentation organized?

Local INDEX.md files
    How does this folder work?

Project Constitution
    What has been accepted as stable law or principle?

Project Journal
    Why did we make decisions? What was tried, rejected, or deferred?

Working files / source material
    Current drafts, evidence, code, notes, assets, or implementation.
```

## Repository Structure

```text
/
  README.md
  IDENTITY.md
  CURRENT_STATE.md
  PROJECT_MAP.md
  GPOS_VERSION.md
  docs/
    INDEX.md
    constitution/
    memory/
    process/
  prompts/
```

## Core Rules

- The repository is the durable memory.
- Chat history is not the durable memory.
- Every significant folder should have an `INDEX.md`.
- Every major decision should be findable through title, timestamp, tags, keywords, and related files.
- Journal entries preserve reasoning, alternatives, rejected paths, and lessons learned.
- Constitution entries record principles that have been tested and accepted.
- `CURRENT_STATE.md` should stay short enough to resume work quickly.

## Search Guidance

When searching the repository, try:

- exact file names;
- canonical terms;
- old terms and aliases;
- tags from journal entries;
- keywords from `CURRENT_STATE.md`;
- related file paths;
- decision titles;
- project-specific names.

## Bookkeeping Rule

After significant work, run the bookkeeping protocol.

User phrase:

```text
Ok, let's do our bookkeeping.
```
