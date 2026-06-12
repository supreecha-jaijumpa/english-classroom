# Quiz Skill

Test knowledge from recent lessons, plus review of older material so nothing is forgotten.

## Usage

```
/quiz
```

## Behavior

1. Read the last 3 entries in `progress/log.md` to find recent topics
2. Read the most recent ~30 words in `vocabulary/word-bank.md` (newest are at the top)
3. Ask 5 quiz questions:
   - **3 recent questions** — from the last 3 lessons (vocabulary, grammar, translation)
   - **2 review questions** — from *older* words further down the word bank, or from "Active Mistakes" in `corrections.md` (skip the Mastered section)
4. Wait for answers one at a time
5. Mark each answer correct or gently correct mistakes with an explanation
6. If an "Active Mistake" pattern was answered correctly, increase its 📊 counter in `corrections.md` (at 3/3 move it to Mastered)
7. Give a final score and encouragement at the end
