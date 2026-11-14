# WOLN — Blind Understanding Test + AI Self-Score

**Test version:** v0.9 · **20 items** · **Max later verified score: 100**  
**Purpose:** Test whether an AI can understand simplified, informal English *without being taught its grammar first*.

## IMPORTANT: Run this file FIRST

You are an AI taking a blind comprehension test. **Do not request or read any WOLN rulebook, glossary, or other WOLN Markdown document until after you finish and return your full first response.** Do not browse the web or use external tools. Use only your own language knowledge and the sentences below.

Treat these as messages from people chatting in shortened English. Your task is to infer **meaning**, not correct grammar for its own sake.

### Instructions

1. For **each of the 20 messages**, write a **natural Standard English paraphrase** of what you think it means.
2. Preserve exact **numbers, times, people, conditions, negatives, comparisons, and locations**. Do not add facts that are not stated.
3. If a short word has multiple possible meanings, say **uncertain** and give the best alternative readings. It is fine to ask for clarification.
4. For each message, give **confidence 0–5** in your own understanding: 0 = cannot infer, 5 = very confident. **This is a self-estimate, not an accuracy score.**
5. After all answers, add your **provisional self-confidence total out of 100**, the **three hardest items**, and any ambiguous terms.
6. **Do not claim a verified comprehension score yet.** The test creator will provide the WOLN specification and an explicit 100-point answer key *after* your blind response.

## Part A — Read and interpret (no glossary supplied)

| # | Message to interpret |
|---|---|
| 01 | `I buy 2 app yday.` |
| 02 | `She working now on 3 photo.` |
| 03 | `We meet at office tmr 9:00.` |
| 04 | `He don't need 1 new phone.` |
| 05 | `If rain tmr, we stay home.` |
| 06 | `Send 2 file to Ana before 18:00.` |
| 07 | `Book in box, not on box.` |
| 08 | `I no want 3 app, I want 1 app.` |
| 09 | `This app more fast than that app.` |
| 10 | `3 child play game in park yday.` |
| 11 | `My friend send msg about AI tech.` |
| 12 | `She happy yday, but sad now.` |
| 13 | `Where you put 2 book?` |
| 14 | `We can use full English word in WOLN.` |
| 15 | `I need photo with red car, not blue car.` |
| 16 | `No share key. Keep it private.` |
| 17 | `We go market Monday.` |
| 18 | `Alyz 3 photo, compare cmp.` |
| 19 | `Send report ytd.` |
| 20 | `2 app in phone, 1 app on web. Which better?` |

## Required response format

Return a table:

| # | Your Standard English meaning | Uncertain? Why? | Confidence (0–5) |
|---|---|---|---|
| 01 | ... | ... | ... |
| ... | ... | ... | ... |
| 20 | ... | ... | ... |

Then return:

- **Initial self-confidence:** `__/100` (sum of the twenty 0–5 confidence ratings).
- **Hardest three items:** item numbers and explanations.
- **Potentially ambiguous abbreviations:** list them.
- **Honest statement:** "My self-confidence is not a verified accuracy score."

## Part B — After the first response (do not execute yet)

**Stop after Part A.** Save the exact, unchanged answers and confidence scores. The user will send a separate Markdown document describing WOLN and an evaluation key.

When the user sends that document:

1. Read its principles, grammar and short-word conventions.
2. Use its **Appendix A** to grade your **original Part A answer**, not a revised answer.
3. Score **5 semantic anchors per item**, 0 or 1 point per anchor; total **/100**.
4. Provide a 20-row scoring table showing earned points, errors and uncertain abbreviations.
5. Compare the **initial self-confidence /100** with the **key-based semantic score /100** without pretending they measure the same thing.
6. Do **not** claim a measured before/after improvement: seeing the answer key makes the original questions unsuitable as a fresh post-test.

**End of blind-test file. No reference answers are included here.**
