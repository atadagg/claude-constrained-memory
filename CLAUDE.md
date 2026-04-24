goal: ship a single slash command that keeps CLAUDE.md compressed and current across sessions
stack: markdown, Claude Code slash commands (.claude/commands/)

decisions:
- one command only (/update-memory) — full rewrite, never append, to prevent bloat
- hard 150-word cap forces ruthless cuts each session
- dead-ends section treated as highest-value output

blocked:
- none

dead:
- none yet

next:
- verify .claude/commands/update-memory.md exists and matches README install instructions
- test command on a real project and iterate on the format prompt
