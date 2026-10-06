# 🧩 Lesson-Generation Prompt

Copy-paste the **master prompt** below into Claude (or any AI) to generate lessons for this
course in the same style. Fill in the one line at the bottom (`### GENERATE`) with the
lesson you want.

Two versions: a **full prompt** (first time, or a fresh AI) and a **short prompt** (when the
AI already has the repo open).

---

## ⭐ Master prompt (full)

```
You are an expert children's English teacher creating lessons for my 8-year-old daughter,
Nika.

ABOUT NIKA
- Native Russian speaker, learning English.
- She knows the alphabet but is still a weak reader.
- She should SPEAK and READ simple English — and she enjoys FAST progress with real
  sentences, not endless sound-by-sound drills.
- A parent (me) runs each lesson with her, ~25 min, twice a week.

PACE & GOAL (important — this changed)
- Move FAST. Do NOT spend whole lessons on single letter-sounds.
- Every lesson blends THREE strands:
  1) a short reading/phonics warm-up (a few minutes, to keep building decoding),
  2) useful VOCABULARY (a themed set of words),
  3) a COMMUNICATION focus — real spoken English she can use immediately.
- The communication thread climbs quickly:
  greetings → pronouns (I, you, he, she, it, we, they) → the verb "to be" (am/is/are)
  → action verbs → PRESENT SIMPLE.
- Target: by LESSON 10 she can use the PRESENT SIMPLE to talk about her day.

HARD RULES
1. Output EXACTLY these 4 sections, in order, with these headers:
   ## 📋 Plan   (quick run-sheet with timings, ~4 steps, ≈25 min)
   ## 🎯 What we will learn   (2–3 bullet goals — name the pronoun/grammar + vocabulary)
   ## ✏️ Exercises for Nika   (5 numbered, hands-on exercises — mostly SPEAKING + a little
       reading; include at least one "say it about yourself / real life" exercise)
   ## 🏠 Homework   (a 5-min/day task she can do out loud)
2. Keep the lesson SHORT (about 45–60 lines).
3. ICONS — use an emoji ONLY to explain a new word, and ONLY in the "🎯 What we will learn"
   word list, written as `word 🖼️ (translation)`, e.g. ball 🏀 (мяч). Put NO icons anywhere
   else: not in the pattern box, exercises, plan, homework, or any sentence — keep all
   phrases plain text. (Only the section headers 📋 🎯 ✏️ 🏠 and the lesson title keep an emoji.)
4. In that "🎯 What we will learn" list, give each new word its Russian translation in
   brackets next to the icon: dog 🐕 (собака). This is the one place icons and translations live.
5. Reading warm-up words should stay simple and phonetic; but spoken vocabulary and
   sentence words can be ANY useful word (taught as a whole word with picture + translation).
6. Teach grammar through PATTERNS and examples, never with grammar jargon. Show the model
   sentence, then have her swap words into it. Example pattern box:
       I am Nika.   You are big.   He is happy.
7. Add a short "> 🇷🇺 ..." parent note on tricky points:
   - Russian has no "to be" in the present ("Я Ника", not "Я есть Ника") — so am/is/are
     feels strange; flag it.
   - Russian has no articles (a/the) — mention gently when it comes up.
   - Latin/Cyrillic look-alikes (p n c a e h y) and sounds Russian lacks (/æ/ /h/ /r/ /θ/ /w/).
8. Start the file with "# Lesson N — ..." and a one-line note on the lesson's focus.

PLANNED 10-LESSON ARC (use this for the GENERATE line)
   1  Hello! — greetings; pronoun I; "I am ___"
   2  You — "you are ___"; "What's your name?"; "How are you?"
   3  He & She — talk about family & friends; "He/She is ___"
   4  It & This — "It is a ___"; naming animals/objects
   5  We & They — groups & plurals; "We are ___"
   6  Review "to be" (am/is/are) + "I have ___"
   7  Action verbs — "I/you/we + verb" (run, eat, like, play)
   8  He/She + verb-s — "He runs", "She plays" (3rd-person present simple)
   9  Questions & negatives — "Do you ___?", "I don't ___"
   10 PRESENT SIMPLE — my day/routine: "I get up. I eat. She plays."

PHASE 2 ARC (Lessons 11–20, continue after present simple)
   11 Plurals — "a cat / three cats"; "These are ___"
   12 Numbers 1–20 — "How many ___?"
   13 Colours — "What colour is it? It is ___"
   14 "have got" — "I have got ___ / Have you got ___?"
   15 Can / can't — abilities; "I can ___"
   16 Present continuous — "I am ___ing" (right now)
   17 Food & drink — "I want ___ / Do you like ___?"
   18 Adjectives — "It is a big / small ___"
   19 Prepositions of place — in / on / under; "Where is ___?"
   20 Review — "All about me" (family, day, things, abilities)

Match the tone, length and formatting of the existing files in lessons/ and
resources/word-bank.md.

### GENERATE
Lesson 1 — greetings and the pronoun I; teach "I am ___".
```

---

## ⚡ Short prompt (when the AI already has this repo open)

```
Create a lesson for this course. Keep the 4 sections (📋 Plan / 🎯 What we will learn /
✏️ Exercises for Nika / 🏠 Homework), short and FAST, mostly SPEAKING with a short reading
warm-up. Blend: quick phonics + themed vocabulary + a communication focus. Use an emoji
ONLY to explain a new word in the "What we will learn" list (word 🖼️ (translation)) — keep
sentences, pattern boxes and exercises plain; teach grammar by
pattern + swap, no jargon; a 🇷🇺 parent note on tricky points. Follow the 10-lesson arc and
pace in PROMPT.md (greetings → pronouns → to be → present simple by Lesson 10).

### GENERATE
Lesson 1 — greetings and the pronoun I; teach "I am ___".
```

---

## 🛠️ How to use it well
- **Change only the last line** (`### GENERATE`) for each lesson, following the arc above.
- **Generate 1–2 lessons**, try them with Nika, then adjust the prompt before making more
  (e.g. "add a song each lesson", "more reading", "slower on verbs").
- The prompt is the **single source of truth** — edit a HARD RULE to change all future
  lessons at once.

## ✅ Quick quality check after generating
- [ ] All 4 sections, in order?
- [ ] Fast and mostly SPEAKING (not a pure phonics drill)?
- [ ] A clear pronoun/grammar focus taught by pattern + swap?
- [ ] Icons ONLY in the "What we will learn" word list (sentences & boxes stay plain)?
- [ ] At least one "say it about your real life" exercise?
- [ ] A 🇷🇺 parent note where Russian speakers trip up?
- [ ] Short (~45–60 lines)?

