# Progress Skill

Show a summary of learning progress.

## Usage

```
/progress
```

## Behavior

1. Read the last 3 entries in `progress/log.md` (newest at the top)
2. Read `progress/streaks.md` (the single source for session counts and streaks)
3. Show:
   - Total sessions completed (from `streaks.md`)
   - Recent topics covered
   - Current streak
   - Last session date and topic
4. Give one short encouraging message based on the progress
