# Git Commit Skill

Save today's study session to git with a clear, journal-style commit message.

## Usage

```
/commit
```

## Behavior

1. Run `git status` and `git diff` to see which study files changed
2. Stage the changed files
3. Create a commit with a short message describing the session

## Commit Format

```
<type>: <date> — <short description>
```

## Types

- **study**: a completed study session (most common)
- **vocab**: vocabulary-only updates
- **writing**: journal entries or writing practice
- **setup**: changes to profile, plan, or workspace structure
- **docs**: changes to README or instructions

## Examples

```
study: 2026-06-12 — past simple tense lesson
vocab: 2026-06-13 — added 8 food words
writing: 2026-06-14 — journal entry about my weekend
setup: updated weekly plan for week of June 15
```
