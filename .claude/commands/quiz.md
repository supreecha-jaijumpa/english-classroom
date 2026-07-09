# Quiz Skill

Test knowledge from recent lessons, plus review of older material so nothing is forgotten.

## Usage

```
/quiz
```

## Behavior

1. Read the last 3 entries in `progress/log.md` — first ~40 lines only (Read tool with a `limit`; newest at the top)
2. Read the most recent ~30 words in `vocabulary/word-bank.md` — first ~40 lines only (newest at the top)
3. Ask 5 quiz questions:
   - **3 recent questions** — from the last 3 lessons (vocabulary, grammar, translation), using the hot zones read above
   - **2 review questions** — sample a small slice (~15 lines at a random offset) from `vocabulary/word-bank-archive.md` or `corrections-archive.md` — **never read an archive in full** — or use "Active Mistakes" at the top of `corrections.md`
4. Wait for answers one at a time
5. Mark each answer correct or gently correct mistakes with an explanation
6. If an "Active Mistake" pattern was answered correctly, increase its 📊 counter in `corrections.md` (at 3/3 move it to `corrections-archive.md`)
7. Give a final score and encouragement at the end
