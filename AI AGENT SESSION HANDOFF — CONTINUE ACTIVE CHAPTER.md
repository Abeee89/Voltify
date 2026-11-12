# AI AGENT SESSION HANDOFF — CONTINUE ACTIVE CHAPTER

You are continuing an existing project session.

## Objective

Continue only the active chapter without repeating completed work.

## First: Load Minimal Context

Read:
1. `AGENTS.md`
2. `docs/PROJECT-BRIEF.md`
3. `docs/implementation/BUILD-STATUS.md`
4. `docs/implementation/CHAPTER-TRACKER.md`
5. The active chapter specification.
6. The latest implementation or test report.
7. Only direct dependencies relevant to the active chapter.

Do not reread the entire repository documentation.

## Verify Current State

Determine:
- Current phase.
- Active chapter.
- Current mode: SPECIFY, BUILD, or TEST.
- Last completed task.
- Remaining work.
- Blockers.
- Approval status.

Inspect the actual repository state before assuming that previous work is complete.

## Continue

Continue only the explicitly active task.

Do not repeat completed work.
Do not modify unrelated chapters.
Do not introduce new requirements.
Do not skip required tests.

If the current state conflicts with documentation, report the conflict and request clarification.

## Update Handoff Documentation

At the end, update or create:

`docs/implementation/SESSION-HANDOFF.md`

Include:
- Current phase and chapter.
- Current mode.
- Completed work.
- Files modified.
- Commands executed.
- Test status.
- Remaining tasks.
- Blockers.
- Next exact action.
- Relevant specification references.

Keep the handoff concise and actionable.

Stop after the active task.