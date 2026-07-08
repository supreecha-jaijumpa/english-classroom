# Last Session Skill

Show a quick recap of the most recent study session.

## Usage

```
/last-session
```

## Behavior

1. Read only the first ~40 lines of `progress/log.md` (Read tool with a `limit`; newest entries are at the top)
2. Show only the latest entry (date, topic, what was practiced)
3. Read the "Active Mistakes" section of `corrections.md` (top ~40 lines of the file) and show any mistakes noted from that session
4. End with one sentence suggesting what to focus on next
