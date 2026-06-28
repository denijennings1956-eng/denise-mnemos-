# Initialization and Cultivation Guide

## Purpose

This guide is for the AI when a user first creates a project from the Mnemos template.

The task is not merely to fill in blanks.

The task is to cultivate the repository with the user.

Cultivation means asking the right questions, understanding the project context, adapting the repository to the user's needs, and preserving the Mnemos core.

## First Principle

Assume the user may not know how GitHub works.

The user owns the repository, but the AI should help manage it as the project's durable memory.

The AI should do what it can directly. When it needs the user to perform a manual action, it should explain exactly what to do and why.

## Opening Script

When beginning first cultivation, the AI may say:

```text
We'll build this repository together. I'll help organize, maintain, and cultivate the project's memory. Whenever I need you to perform a step that only you can do, such as changing a GitHub setting or granting access, I'll explain exactly what to do and why. Whenever I can do the work myself, I will.
```

## Required Startup Reading

Before changing the repository, read:

1. `MNEMOS_CONTRACT.md`
2. `README.md`
3. `GETTING_STARTED.md`
4. `USER_SETUP.md`
5. `IDENTITY.md`
6. `CURRENT_STATE.md`
7. `PROJECT_MAP.md`
8. `docs/INDEX.md`
9. `docs/process/BOOKKEEPING_PROTOCOL.md`
10. `docs/memory/PROJECT_JOURNAL.md`
11. `docs/constitution/PROJECT_CONSTITUTION.md`

Do not read every repository file unless necessary. Read enough to understand the Mnemos core and the user's requested project.

## First Cultivation Interview

Ask questions one at a time or in small groups. Do not overwhelm the user.

Recommended questions:

1. What is the project called?
2. What kind of project is it?
3. What do you want this repository to help you remember?
4. Who owns or uses the project?
5. Should the repository be private?
6. Will it include information about living people or sensitive material?
7. What kinds of files or notes do you expect to collect?
8. What would be hardest to recreate if lost?
9. What will you want the AI to know at the start of each future session?
10. What decisions should future sessions remember?
11. What words, names, or terms must be preserved carefully?
12. What would make the system feel easy to use?

## Repository Setup Tasks

After the user answers enough questions, update the repository.

At minimum:

1. Rewrite `IDENTITY.md` for the project.
2. Rewrite `CURRENT_STATE.md` with the first active handover.
3. Rewrite `PROJECT_MAP.md` so it describes the repository as actually cultivated.
4. Update `docs/INDEX.md` if navigation changed.
5. Add a first project-specific journal entry.
6. Update `docs/memory/INDEX.md` if needed.
7. Update `docs/constitution/PROJECT_CONSTITUTION.md` only if project-specific principles are already accepted.
8. Create new folders only when they are clearly useful.
9. Index every new folder and file locally.

## Do Not Overbuild

Do not create a complex folder system just because it might be useful later.

Prefer small, obvious structures.

Examples:

- A genealogy project may need `people/`, `families/`, `places/`, `sources/`, or `media/`, but only create them when the user expects to use them.
- A writing project may need `characters/`, `setting/`, `chapters/`, or `research/`, but only create what helps the project now.
- A software project may need `docs/architecture/`, `docs/specs/`, or `src/`, but only after understanding the project.

## Required Mnemos Core

Do not remove or ignore these core systems:

- `MNEMOS_CONTRACT.md`
- `IDENTITY.md`
- `CURRENT_STATE.md`
- `PROJECT_MAP.md`
- `docs/INDEX.md`
- `docs/memory/PROJECT_JOURNAL.md`
- `docs/constitution/PROJECT_CONSTITUTION.md`
- `docs/process/BOOKKEEPING_PROTOCOL.md`
- local `INDEX.md` files for significant folders

If the user intentionally changes or removes a core capability, warn them that the repository may no longer fully operate as Mnemos unless that capability is replaced somewhere else.

## First Journal Entry

Create a first project-specific journal entry recording:

- what the project is;
- why the user wants Mnemos;
- what structure was chosen;
- what alternatives were considered;
- what privacy assumptions apply;
- what should happen next;
- useful search terms.

Do not delete the seed entry unless the user asks. It may remain as a legacy example or be moved/renamed later.

## User Setup Help

During initialization, help the user set up their own working habit.

Recommend a personal instruction if appropriate:

```text
When I refer to this Mnemos repository, treat it as the project's durable memory. If repository access is available, read the Mnemos startup files before making assumptions. Preserve canonical terminology, search before inventing new structures, and maintain the Mnemos core systems automatically. If repository access is missing, tell me rather than guessing.
```

Recommend this normal startup prompt:

```text
@GitHub

Catch me up on this project and tell me what matters next.
```

Recommend this bookkeeping prompt:

```text
@GitHub

Ok, let's do our bookkeeping.
```

Recommend this drift prompt:

```text
@GitHub

Refresh on MNEMOS_CONTRACT.md and audit your last actions against it before continuing.
```

## Manual GitHub Actions

The AI may need the user to perform manual steps.

When that happens, give clear instructions.

Common manual actions:

- create a GitHub account;
- create a repository from the template;
- set repository visibility to private;
- enable GitHub access for the AI;
- invite a collaborator;
- enable template repository mode;
- confirm privacy boundaries.

Do not assume the user knows where these settings are.

## Completion Criteria

First cultivation is complete when:

1. `IDENTITY.md` describes the user's project.
2. `CURRENT_STATE.md` gives a useful handover.
3. `PROJECT_MAP.md` describes where information belongs.
4. The journal contains a first project-specific entry.
5. Required folders have local indexes.
6. The user knows the startup prompt.
7. The user knows the bookkeeping prompt.
8. The AI has not removed the Mnemos core.

## Final Message To User

When first cultivation is complete, summarize:

- what was set up;
- what files were changed;
- what the user should type next time;
- what the user should type at the end of a session;
- any manual GitHub actions still needed.
