# Lesson Template — Spanish Made Easy for Marathi & Hindi Speakers

> Reusable template for generating **every lesson** (A1 → A2) with AI.
> Fill in the placeholders below and paste the prompt into any LLM (ChatGPT / Claude / Gemini).

---

## 1. Master Lesson Prompt (copy-paste)

```
You are a Spanish teacher for Marathi (मराठी) and Hindi (हिंदी) speakers.
Create Lesson {N} — Topic: {TOPIC} — CEFR level {A1/A2}.

Explain everything FIRST in Marathi, THEN in Hindi, then show Spanish examples.

Include, in this exact order:

1. Lesson objectives (in Marathi and Hindi)
2. New vocabulary — exactly 20 words:
   Columns: Spanish | Marathi | Hindi | Pronunciation (Devanagari)
3. One dialogue (6–8 lines) with:
   Spanish | Pronunciation | Marathi translation | Hindi translation
4. Grammar notes for this lesson (A1: simple, A2: with examples)
5. 10 practice sentences (Spanish + Marathi + Hindi)
6. 10 exercises: fill blanks, matching, true/false, correct-the-error
7. 5 MCQ questions with answer marked ✔
8. 5 translation sentences (Marathi/Hindi → Spanish)
9. Speaking practice (3 tasks)
10. Writing practice (1 task)

Rules:
- Pronunciation must use ONLY Devanagari script (आ से ज्ञ)
- Spanish must be 100% grammatically correct with accents
- Marathi and Hindi translations must be natural, not literal
- Add "Answer Key" for all exercises and MCQ
- Keep within A1/A2 CEFR vocabulary
```

---

## 2. Lesson File Structure

```
Lesson-{NN}-{topic}.md
├── 1. Objectives (ध्येय / लक्ष्य)
├── 2. Vocabulary (20 words) — Spanish | Marathi | Hindi | Pronunciation
├── 3. Dialogue — Spanish | Pronunciation | Marathi | Hindi
├── 4. Grammar notes
├── 5. Practice sentences (10)
├── 6. Exercises (10) + Answer Key
├── 7. MCQ (5) + Answer Key
├── 8. Translation practice (5) + Answer Key
├── 9. Speaking practice
├── 10. Writing practice
└── 11. Lesson Quiz (10 points) + Answer Key
```

---

## 3. Standard Column Headers (use everywhere)

| Spanish | Marathi | Hindi | Pronunciation |

> Keep this exact column order in **every** table in the book for consistency (Phase 14 AI review will check this).

---

## 4. Quality Checklist (run after every lesson)

- [ ] Spanish accents correct: ¿ ¡ á é í ó ú ü ñ
- [ ] H silent everywhere (hola → ओला, never होला)
- [ ] J → ख़, LL → य, Ñ → न्य, RR → rolled र
- [ ] Stress marks on exceptions: está, café, jamón
- [ ] Articles (el/la/un/una) present on all nouns
- [ ] Marathi is मराठी, Hindi is हिंदी — never mixed
- [ ] Pronunciation column uses only Devanagari
- [ ] 20 vocabulary words per lesson
- [ ] All exercises have an answer key
- [ ] CEFR level respected (no A2 grammar in A1 lessons)

---

## 5. How to Use (Phases 3–7)

1. **Phase 3** — paste Master Prompt with Lesson {N} and {TOPIC} from the A1/A2 curriculum
2. **Phase 6** — check the dialogue is natural; fix translations via DeepL
3. **Phase 7** — verify exercises; answer key must match
4. **Phase 14** — paste the lesson into the AI Review prompt below
5. **Phase 15** — assemble into the book with the TOC

---

## 6. AI Review Prompt (Phase 14)

```
Review this Spanish lesson for a book for Marathi/Hindi speakers.
Check:
1. Spanish grammar and accents (must be error-free)
2. Marathi translation naturalness
3. Hindi translation naturalness
4. Pronunciation accuracy (Devanagari)
5. CEFR A1/A2 compliance
6. Exercise answer-key correctness
7. Table consistency (column order)
8. No English needed as bridge language

Report errors as: Location | Issue | Suggested fix
```

---

## 7. Naming Conventions

| Item | Format | Example |
| --- | --- | --- |
| Lesson file | `Lesson-03-Greetings.md` | — |
| Audio clip | `audio/l03-vocab.mp3`, `audio/l03-dialogue.mp3` | — |
| Image | `images/greetings.svg` | — |
| Flashcards | `flashcards/l03.md` | — |
| Quiz | `quizzes/l03-quiz.md` | — |
