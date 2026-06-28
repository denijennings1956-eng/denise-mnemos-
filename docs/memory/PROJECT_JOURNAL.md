# Project Journal

## Purpose

The Project Journal preserves the reasoning history of the project.

It records why decisions happened, what was tried, what was rejected, what should not be forgotten, and what future sessions should search for.

The journal is not optional in Mnemos. It is one of the core systems that preserves continuity.

## Journal vs Constitution

Use the journal for ideas, reasoning, experiments, and decision history.

Use the constitution for stable principles that have been accepted and should guide future work.

A principle usually begins in the journal before it graduates into the constitution.

---

# Journal Entry Template

Copy this structure when adding a new major entry.

```markdown
## MJ-0000 — Entry Title

Timestamp: YYYY-MM-DD HH:MM Timezone

Status: Proposed | Testing | Accepted | Superseded | Rejected | Historical

Significance: Low | Medium | High | Core

Tags: #tag-one #tag-two

Keywords: keyword, search phrase, old term, related concept

Related Files:

- `path/to/file.md`

Related Entries:

- `MJ-0000 — Related Entry`

### Summary

One or two paragraphs explaining what happened.

### Decision / Idea / Finding

State the decision, idea, or finding clearly.

### Why This Matters

Explain why this should be preserved for future sessions.

### Reasoning

Explain the reasoning that led here.

### Alternatives Considered

List meaningful alternatives and why they were not chosen.

### Rejected Paths / Warnings

Record mistakes, dead ends, or paths future sessions should avoid repeating.

### Evidence / Context

Record what evidence, session context, project state, or user preference informed the entry.

### Impact

Explain what files, workflows, terminology, or future decisions this affects.

### What Would Change This

Explain what evidence or project change could cause this decision to be revised.

### Next Steps

List follow-up actions.
```

---

# Seed Entry

## MJ-0001 — Founding Principles

Timestamp: 2026-06-28 NZST

Status: Accepted

Significance: Core

Tags: #mnemos #founding-principles #cultivation #contract #continuity #findability

Keywords: Mnemos, founding principles, durable memory, cultivation, human-AI contract, repository memory, journal, constitution, current state, project map, indexes, bookkeeping, drift refresher

Related Files:

- `MNEMOS_CONTRACT.md`
- `README.md`
- `GETTING_STARTED.md`
- `IDENTITY.md`
- `CURRENT_STATE.md`
- `PROJECT_MAP.md`
- `docs/process/BOOKKEEPING_PROTOCOL.md`
- `docs/constitution/PROJECT_CONSTITUTION.md`

Related Entries:

- None yet.

### Summary

Mnemos was created as a reusable project-memory system based on practical experience using GitHub and AI to maintain continuity for long-running projects.

Its central insight is that a repository can act as durable memory while an AI acts as a reasoning and maintenance partner. The system exists to reduce the time required to reorient an AI session, preserve project reasoning, and make long-term collaboration easier.

### Decision / Idea / Finding

Mnemos will use a small required core and a flexible cultivation layer.

The required core includes identity, current state, project map, journal, constitution, indexes, bookkeeping, and the Mnemos Contract.

Everything beyond the core is cultivation: optional project-specific structure developed through dialogue between the user and the AI.

### Why This Matters

The system must be flexible enough for software, genealogy, writing, worldbuilding, research, and other long-running projects, but structured enough that users can reliably say they are using Mnemos.

If everything is optional, the system fails.

If everything is fixed, the system becomes brittle.

The solution is a small contractually required core plus adaptive cultivation.

### Reasoning

The founding project that inspired Mnemos showed that project startup time dropped dramatically once the AI had a reliable repository startup path. Instead of spending half an hour reconstructing context from chat, the AI could read current state, maps, journals, and indexes, then become useful quickly.

The most valuable parts were not just the documents themselves, but the pattern of maintaining them: recording reasoning, updating handovers, preserving terminology, and making everything findable.

### Alternatives Considered

A rigid template was considered but rejected because different projects need different structures.

A loose collection of suggestions was considered but rejected because it would not provide enough reliability.

A pure wiki approach was rejected because it does not automatically define startup, handover, decision history, and AI behaviour.

### Rejected Paths / Warnings

Do not make the journal optional.

Do not let the constitution become a scratchpad.

Do not create complex folder systems before the project needs them.

Do not assume users understand GitHub.

Do not let the AI claim repository-aware certainty without repository access.

Do not create files without indexing them.

### Evidence / Context

Mnemos emerged from repeated use of AI-assisted GitHub project continuity. The system was shaped by observing what reduced reorientation time, preserved reasoning, and prevented future sessions from losing important context.

### Impact

This entry establishes the baseline philosophy for Mnemos v0.1.

Future changes should be judged against these principles before being promoted to core.

### What Would Change This

Real users may show that some parts of the core are unclear, too burdensome, or need renaming.

If repeated use shows that a core capability can be preserved in a better way, Mnemos may evolve.

### Next Steps

- Test Mnemos with a real nontechnical user.
- Record points of confusion.
- Record what the AI handles well.
- Record what the user expects the AI to do automatically.
- Promote only proven improvements into the constitution or future versions.
