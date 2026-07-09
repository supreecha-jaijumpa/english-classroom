# Wrap Up Skill

End the current lesson and save all progress. This is the **single authoritative end-of-session checklist** — every file update happens here, and only here.

## Usage

```
/wrap-up
```

## Read & Write Rules

- **Read only the top** — every file keeps newest content first. Read only the first ~40 lines (use the Read tool with a `limit`), never the whole file.
- **Write small** — log entries max ~6 lines (Notes max 3 sentences); word-bank entries one line each.
- **Optional steps** (7–10 below) — decide from the session itself whether anything changed; do **not** open the file if nothing did.

## Behavior

Work through this checklist in order:

1. **Correct** any remaining mistakes from this session
2. **Summarize**: what was practiced, what was learned
3. **`progress/log.md`** — add a new entry at the top (max ~6 lines, Notes max 3 sentences); apply rotation (table below)
4. **`vocabulary/word-bank.md`** — add new words at the top, one line per word, and update the total counter (the only place the word count lives); apply rotation
5. **`corrections.md`** — add repeated mistakes to "Active Mistakes"; if a recorded mistake was used correctly, increase its counter — at **3/3** move it to `corrections-archive.md` immediately
6. **`progress/streaks.md`** — update total sessions, current streak, best streak, the calendar mark, and tick any milestones reached; keep only the current-month calendar
7. *(optional)* **`plan/this-week.md`** — tick today's daily task; add a short note only if useful. On a new week, move the finished week to `plan/weeks-archive.md`
8. *(optional)* **`grammar/notes.md`** — if a grammar topic was taught, add a short plain-language note at the top
9. *(optional)* **`plan/roadmap.md`** — tick the topic checkbox if it is now finished; update "Current Stage" if a stage is complete
10. *(optional)* **`me.md`** — update "What I Find Difficult" / "What I Am Good At" only if something new was noticed this session
11. End with one encouraging sentence

## Rotation

Every growing file has a capped **hot zone**; overflow rotates (cut and paste — never delete content) to an `-archive.md` file in the same folder. Archives are **write-only during sessions** — only `/quiz` may sample a small slice for review questions.

| File | Hot zone cap | Rotates to |
|---|---|---|
| `progress/log.md` | 10 newest sessions | `progress/log-archive.md` |
| `vocabulary/word-bank.md` | 50 newest words (total counter stays at top) | `vocabulary/word-bank-archive.md` |
| `corrections.md` | Active Mistakes only, max ~10 | `corrections-archive.md` (mastered move immediately at 3/3) |
| `grammar/notes.md` | 5 newest lessons + one-line index of archived topics | `grammar/notes-archive.md` |
| `plan/this-week.md` | current week only | `plan/weeks-archive.md` |
| `progress/streaks.md` | current-month calendar only; keep milestones | trim in place |
| `me.md` | "What I Find Difficult" max ~10 items; remove mastered | self-pruning, no archive |

## Notes

- Only update files that actually changed this session — but always do steps 3 and 6.
- Other commands (`/study`, `/teach`, `/practice`) should point here instead of keeping their own save steps.
