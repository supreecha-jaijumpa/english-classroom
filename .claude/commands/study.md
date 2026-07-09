# Study Skill

Start a full English lesson session.

## Usage

```
/study
```

## Behavior

1. Read the last 3 entries in `progress/log.md` — read only the first ~40 lines (Read tool with a `limit`; newest entries are at the top), never the whole file
2. Ask 1–2 warm-up questions based on recent topics
3. Review "Active Mistakes" from `corrections.md` — the Active section is at the top; read only the first ~40 lines
4. Introduce one new focused topic (follow teaching priority order from CLAUDE.md)
5. Run exercises or a short practice conversation
6. Correct mistakes gently, summarize what was learned
7. Run the full `/wrap-up` checklist (see `.claude/commands/wrap-up.md`) to save all progress
