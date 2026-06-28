# User Setup

## Purpose

This guide helps a user configure their AI assistant and GitHub access so Mnemos works smoothly.

Assume the user may not know how GitHub works.

The user owns the repository. The AI helps manage it as the project's durable memory.

## The Basic Relationship

Mnemos works best when the user and AI share a clear working agreement:

- The user owns the project and decides what matters.
- The repository stores the durable memory.
- The AI reads, organizes, maintains, and updates the repository where it has access.
- The user performs actions the AI cannot perform, such as changing GitHub settings, granting access, or enabling template mode.

The AI should minimize user effort. If it can do the work directly, it should. If it cannot, it should explain exactly what the user needs to do and why.

## Required Habit

When asking the AI to work from the repository, make sure the repository access tool is available.

In ChatGPT, this may mean adding:

```text
@GitHub
```

at the start of the message, or selecting GitHub from the available tools/connectors.

If repository access is missing, the AI cannot properly read or update Mnemos.

## Recommended Personal Instruction

If your AI supports custom instructions, personal instructions, or a user profile prompt, add a short Mnemos bootloader.

Use this as a starting point:

```text
When I refer to a Mnemos repository, treat the repository as the project's durable memory.

If repository access is available, read the repository startup files before making assumptions:

1. MNEMOS_CONTRACT.md
2. IDENTITY.md
3. CURRENT_STATE.md
4. PROJECT_MAP.md
5. docs/INDEX.md
6. relevant local indexes and files named by the current state or project map

Preserve canonical terminology unless I explicitly change it.

Search existing files before proposing new structures.

Maintain the Mnemos core systems automatically: current state, journal, constitution, indexes, project map, and bookkeeping.

If repository access is missing, tell me rather than guessing.
```

## Project-Specific Bootloader

For a specific project, you may add the repository URL:

```text
Primary Mnemos repository:
https://github.com/OWNER/REPOSITORY

When beginning work on this repository, follow its Mnemos startup path and preserve its established terminology.
```

Replace `OWNER/REPOSITORY` with the real repository path.

## First Session Prompt

Use this when setting up a new project:

```text
@GitHub

Help me cultivate this Mnemos repository for my project.

Assume I know very little about GitHub. Read the Mnemos startup documents, explain what you are doing as we go, ask me questions one step at a time, and set this repository up for my project.

Whenever there is something only I can do, explain exactly what I need to click and why. Whenever you can do the work yourself, please do it.
```

## Normal Startup Prompt

Use this at the start of a normal work session:

```text
@GitHub

Catch me up on this project and tell me what matters next.
```

## Bookkeeping Prompt

Use this at the end of a meaningful session:

```text
@GitHub

Ok, let's do our bookkeeping.
```

The AI should update the current state, journal, indexes, and any other affected Mnemos files.

## Drift Correction Prompt

Use this if the AI seems to be forgetting the Mnemos method:

```text
@GitHub

Refresh on MNEMOS_CONTRACT.md and audit your last actions against it before continuing.
```

## Repository Audit Prompt

Use this if the repository seems stale, confusing, or broken:

```text
@GitHub

Audit this Mnemos repository for missing indexes, stale current state, unclear navigation, unrecorded decisions, and drift from the Mnemos Contract.
```

## What The User Should Not Need To Do

The user should not normally need to:

- understand Git internals;
- manually maintain indexes;
- manually format journal entries;
- know where every file belongs;
- remember every Mnemos rule;
- explain the whole project every session.

The AI should handle or explain these things.

## Manual Actions The AI May Ask For

The AI may ask the user to:

- grant repository access;
- add `@GitHub` or enable a connector;
- create a GitHub account;
- create a new repository from the template;
- make a repository private;
- invite a collaborator;
- enable template mode;
- confirm whether sensitive information should be stored.

When asking for manual action, the AI should give precise, step-by-step instructions.

## Privacy Reminder

If the project contains personal, family, client, medical, financial, legal, or sensitive information, keep the repository private unless you are certain it should be public.

For genealogy projects, be especially careful with information about living people.
