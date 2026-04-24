Update the project's CLAUDE.md to reflect current state. This is a full rewrite, not an append.

Follow these steps:

1. Read the existing CLAUDE.md if it exists
2. Look at recent files, decisions, and what was discussed in this session
3. Rewrite CLAUDE.md using the structured format below
4. Keep the entire file under 150 words — ruthlessly cut anything that won't matter next session

Use this format:

```
goal: [what we're trying to ship right now]
stack: [languages, frameworks, key dependencies]

decisions:
- [decision made and brief why]
- [another decision]

blocked:
- [current blockers]

dead:
- [approaches tried and abandoned, so we don't revisit them]

next:
- [concrete next steps]
```

Rules:
- Full rewrite every time, never append
- If something is resolved, remove it
- If a decision is now obvious from the code, remove it
- Dead-ends are the most important section — always keep them
- No filler words, no full sentences where a fragment works
