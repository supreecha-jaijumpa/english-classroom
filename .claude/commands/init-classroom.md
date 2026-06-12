# Init Classroom

Set up the student profile by asking questions and filling in `me.md`.

## Usage

```
/init-classroom
```

## Behavior

Walk the student through a guided intake interview. Ask each group of questions conversationally — do **not** dump all questions at once. Wait for the answer before moving to the next group.

### Step 1 — Background
Ask:
1. "What is your native language?"
2. "How long have you been learning English? (e.g. 1 year, just starting, 5 years on and off)"
3. "How would you describe your current English level? (Beginner / Elementary / Pre-Intermediate / Intermediate / Upper Intermediate / Advanced)"

### Step 2 — Goals
Ask:
4. "Why do you want to learn English? (e.g. work, travel, study abroad, talk with friends)"
5. "Do you have a specific goal or deadline? (e.g. pass IELTS B2 by December, hold a work meeting in English)"
6. "How many hours per week can you commit to studying?"

### Step 3 — Self-Assessment
Tell the student: *"I'll ask you to rate yourself from 1 (very weak) to 10 (very strong) in each skill. Be honest — these scores help me calibrate the pace of our lessons."*

Ask scores one by one:
- Speaking
- Listening
- Reading
- Writing
- Grammar
- Vocabulary

### Step 4 — Learning Style
Ask:
7. "How do you prefer to learn? (e.g. conversation practice, writing exercises, grammar drills, reading passages)"
8. "What time of day do you usually study? (e.g. morning, evening, lunch break)"
9. "What topics interest you most? (e.g. travel, technology, food, business, culture)"

### Step 5 — Write & Confirm
1. Fill in `me.md` with all collected answers. Map the answers as follows:
   - **English Level** ← answer to question 3
   - **My Goal** ← answers to questions 4 and 5
   - **Study Schedule** ← answer to question 6
   - **Native Language** ← answer to question 1
   - **My Learning Preferences** ← answers to questions 7, 8, and 9
   - **Study History → Started** ← today's date
   - **What I Find Difficult** ← leave as placeholder (Claude will update during sessions)
   - **What I Am Good At** ← leave as placeholder (Claude will update during sessions)
2. Show a brief summary of the completed profile.
3. Ask: *"Does this look right? Want to change anything?"*
4. After confirmation, say: *"You're all set. Type `/study` to begin your first lesson."*

## Notes
- Never fill in placeholder values — only write answers the student actually gave.
- If a student skips a question, leave the `_(fill in)_` placeholder in `me.md`.
- Keep the tone friendly and low-pressure — this is a welcome interview, not a test.
- If the student writes in their native language, respond in both languages and gently encourage English.
