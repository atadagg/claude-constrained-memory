# claude-constrained-memory

A single slash command for Claude Code that maintains compressed project state across sessions.

## The problem

Claude loses context every session. CLAUDE.md is the fix, but it is not automatically maintained.

## The solution

Run `/update-memory` at the end of a session. Claude rewrites CLAUDE.md in a structured, word-limited format. Next session starts with exactly what matters, nothing more.

## Install

Copy `.claude/commands/update-memory.md` into your project's `.claude/commands/` directory.

## Usage

At the end of a working session, run:

```
/update-memory
```

Claude will rewrite your `CLAUDE.md` to reflect current project state, decisions made, dead-ends to avoid, and next steps — kept under 150 words.

## Format

```
goal: what we're doing
stack: tech picks
decisions: what was decided and why
blocked: current blockers
dead: abandoned approaches (never revisit)
next: concrete next steps
```
