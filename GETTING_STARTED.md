# Getting Started With Mnemos

This guide is for people who are new to GitHub, new to AI-assisted project work, or both.

You do not need to understand coding to use Mnemos.

## What Mnemos Is

Mnemos is a collaborative project memory system.

Together, you and the AI cultivate a repository that preserves knowledge, decisions, context, and continuity over time.

The repository is the project's durable memory. The AI helps organize, maintain, and build upon that memory.

When the AI needs something only you can do, such as changing a GitHub setting or granting access, it should explain exactly what is needed and why. When it can do the work itself, it should.

## What You Need

You need:

1. A GitHub account.
2. A ChatGPT account or another AI assistant that can access GitHub or repository files.
3. A project you want to maintain over time.

Examples:

- family history;
- genealogy;
- local history;
- writing a book;
- worldbuilding;
- software planning;
- nonprofit planning;
- research;
- business notes;
- personal archives.

## The Basic Idea

GitHub stores the project files.

The AI reads and updates those files.

You guide the project, make decisions, and do any manual steps the AI cannot do.

You do not need to manage the repository alone. Treat the repository as the AI's workspace inside your project. You own it, but the AI helps maintain it.

## Step 1 — Create Your Own Repository

Create a new repository from the Mnemos template.

Make it private unless you are sure you want the world to see it.

Use a clear name, such as:

```text
family-history
kirkby-genealogy
local-history
novel-notes
project-archive
```

## Step 2 — Connect the AI to GitHub

When you want the AI to work with the repository, make sure the GitHub connector or repository access tool is available.

In ChatGPT, this may mean adding `@GitHub` to the conversation or selecting GitHub from the tools/connectors list.

If the AI cannot access the repository, it should tell you. It can still help from the conversation, but it cannot properly run the Mnemos startup sequence.

## Step 3 — Ask the AI to Cultivate the Repository

Use this prompt:

```text
@GitHub

Help me cultivate this Mnemos repository for my project.

I do not know GitHub well, so please guide me step by step. Read the repository startup files, ask me what you need to know, and then set up the project memory system for my project.
```

The AI should ask questions such as:

- What is the project for?
- Who owns it?
- Is it private?
- What kind of information will it contain?
- What will you want to find later?
- What decisions should be remembered?
- Are there privacy concerns?

## Step 4 — Work Normally

Once the repository is cultivated, you can start a session with:

```text
@GitHub

Catch me up on this project.
```

The AI should read the repository and tell you where things stand.

## Step 5 — End With Bookkeeping

At the end of a significant session, say:

```text
Ok, let's do our bookkeeping.
```

The AI should update the current state, journal, indexes, and any related files so the next session can resume quickly.

## What Not To Worry About

You do not need to know:

- how Git works;
- how Markdown works;
- how repository architecture works;
- how the journal is formatted;
- how the indexes are maintained.

The AI should handle those details or explain them when needed.

## Things To Watch Out For

### Public vs Private

Private means only you and invited collaborators can see the repository.

Public means anyone may be able to see it.

When in doubt, choose private.

### Living People

For genealogy and family projects, be careful with information about living people.

Do not store sensitive personal details unless you are sure it is appropriate.

### Repository Access

If the AI has not been given repository access, it cannot read or update the project memory. Always attach or enable the repository connector when asking for repository-aware work.

### Core Mnemos Files

Do not delete these unless you know what you are doing:

- `IDENTITY.md`
- `CURRENT_STATE.md`
- `PROJECT_MAP.md`
- `docs/INDEX.md`
- `docs/memory/PROJECT_JOURNAL.md`
- `docs/constitution/PROJECT_CONSTITUTION.md`
- `docs/process/BOOKKEEPING_PROTOCOL.md`

These are the core systems that make Mnemos work.

## If Something Goes Wrong

Ask the AI:

```text
Please audit this Mnemos repository and tell me what is missing, broken, confusing, or out of date.
```

GitHub keeps file history, so mistakes can often be repaired.

## The Most Important Habit

Use the repository as the memory.

If something matters for the future, ask the AI to record it in the appropriate Mnemos file.
