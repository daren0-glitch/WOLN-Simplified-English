# WOLN — GPT-6 Blind Test: Part B Grading Report

## Test record

| Field | Record |
|---|---|
| Project | WOLN — Simplified English |
| Test | Blind Understanding Test + AI Self-Score |
| Test version | v0.9 |
| Specification | `WOLN_01_IDEAL_AND_RULES_v0.9.md` |
| Test items | 20 |
| Evaluator | GPT-6 (ChatGPT) |
| Evaluation date | 2026-11-11 |
| Stage | **Part B completed — original Part A answers graded** |
| Initial self-confidence | 87/100 |
| Appendix A semantic-anchor score | **98/100** |
| Verification status | **AI self-grading against the supplied key; not independently human-verified** |

## 1. Overall result

**Key-based semantic score: 98/100 (98%).**

The score is based on the supplied Appendix A rubric: 20 items × 5 semantic anchors, one point per correctly conveyed anchor. The original Part A paraphrases and uncertainty notes were assessed as submitted. They have not been rewritten for this evaluation.

The two points not earned are:

- **Item 10:** The source/key expects the plural meaning “games,” but the original paraphrase said “a game.”
- **Item 18:** The answer correctly inferred “analyze 3 photos” and “compare,” and flagged `cmp` as uncertain, but it did not mention the specified possible reading “composition.”

## 2. Item-by-item scoring

| # | Original Part A meaning (unchanged) | Score | Scoring notes |
|---|---|---:|---|
| 01 | I bought 2 apps yesterday. | 5/5 | All anchors conveyed: I, buy/purchase, 2, apps, yesterday. |
| 02 | She is working on 3 photos now. | 5/5 | All anchors conveyed, including ongoing action, now, on, and 3 photos. |
| 03 | We will meet at the office tomorrow at 9:00. | 5/5 | All anchors conveyed, including office, tomorrow, and 09:00. |
| 04 | He does not need 1 new phone. | 5/5 | All anchors conveyed, including the explicit quantity 1. The uncertainty note was unnecessary, but the paraphrase retained the exact number. |
| 05 | If it rains tomorrow, we will stay home. | 5/5 | The conditional remains conditional; rain, tomorrow, we, and stay home are preserved. |
| 06 | Send 2 files to Ana before 18:00. | 5/5 | Imperative, quantity, files, recipient, and deadline all preserved. |
| 07 | The book is in the box, not on the box. | 5/5 | Correctly preserves the important inside-versus-on-top distinction and negation. |
| 08 | I do not want 3 apps. I want 1 app. | 5/5 | Both quantities and the contrast between what is not wanted and what is wanted are preserved. |
| 09 | This app is faster than that app. | 5/5 | Correct relative comparison and both comparison targets are preserved. |
| 10 | Three children played a game in the park yesterday. | **4/5** | The answer says “a game,” while the key's anchor is “games.” The other four anchors are conveyed. |
| 11 | My friend sent me a message about AI technology. | 5/5 | Sender, message, topic, and AI technology are conveyed. The uncertainty note correctly flags that the time is not specified. “Me” was added as a recipient although the source does not state one; this is an unsupported detail, but it does not remove any of the five listed anchors. |
| 12 | She was happy yesterday, but she is sad now. | 5/5 | Person, both emotional states, yesterday, contrast, and now are preserved. |
| 13 | Where did you put 2 books? | 5/5 | Preserves the where-question, you, put, quantity 2, and books. |
| 14 | We can use complete English words in WOLN. | 5/5 | All five anchors are conveyed. “Complete English words” is a natural rendering of “full English word.” |
| 15 | I need a photo with a red car, not a blue car. | 5/5 | Need, photo, red car, negated blue car, and color contrast are preserved. |
| 16 | Do not share the key. Keep it private. | 5/5 | Prohibition, share, key, keep it, and private are all conveyed. The answer appropriately did not decide what kind of key it is. |
| 17 | We are going to the market on Monday. | 5/5 | We, go, market, and Monday are conveyed. The uncertainty note explicitly recognizes that tense is not specified, satisfying the temporal-ambiguity anchor despite the future/planned wording in the paraphrase. |
| 18 | Analyze 3 photos and compare them. | **4/5** | The answer gives the plausible `alyz` = analyze reading, preserves 3 photos, and identifies compare as a possible reading of `cmp`. It flags `cmp` as uncertain, but does not mention “composition” as another possible reading or explicitly ask for clarification. |
| 19 | Send the year-to-date report. | 5/5 | Correctly identifies a send request and report, notes `ytd` ambiguity, gives the established year-to-date meaning, and does not assert that it means yesterday. |
| 20 | There are 2 apps on the phone and 1 app on the web. Which is better? | 5/5 | Both quantities, both platforms, and the “which is better?” question are preserved. |
| **Total** |  | **98/100** | **Two missed anchors: item 10 and item 18.** |

## 3. Errors and learning observations

### Item 10 — noun number

Original: `3 child play game in park yday.`

Original answer: “Three children played a game in the park yesterday.”

The WOLN rules allow a base noun after an explicit number, as in `3 child`. The answer correctly interpreted “3 child” as three children. However, Appendix A specifically expects the activity/object anchor “games.” The paraphrase introduced the singular article “a” and therefore narrowed the meaning to one game. This is the clearest semantic mismatch in the response.

### Item 18 — open and experimental vocabulary

Original: `Alyz 3 photo, compare cmp.`

The answer's interpretation of `Alyz` as “analyze” was a reasonable inference. It also correctly recognized that `cmp` was uncertain and could mean “compare” or “comparison.” The specification and answer key additionally call out “composition” as a possible reading of `cmp`. That alternative was not included in the original response, so one anchor was missed.

### Other details worth noting (not deducted under the five-anchor score)

- **Item 04:** The original answer questioned whether `1` meant exactly one or was functioning like an article. Under the WOLN rules, an explicit number is meaningful; the paraphrase itself did preserve “1.”
- **Item 11:** The paraphrase added “me” as the message recipient, but the source does not state who received the message. The answer did correctly flag the tense as uncertain. Avoid adding an unstated recipient in future interpretations.
- **Item 17:** The paraphrase used “are going to,” which leans toward a planned future action. The uncertainty note correctly stated that the source does not specify tense. A safer paraphrase would retain the neutral time reference: “We go to the market on Monday,” followed by a note that the tense depends on context.
- **Item 19:** The response handled `ytd` cautiously. This is important because the supplied vocabulary explicitly identifies YTD as the established finance abbreviation “year to date” and says not to silently interpret it as yesterday.

## 4. Confidence versus semantic score

| Measure | Result | What it measures |
|---|---:|---|
| Initial self-confidence | 87/100 | The model's own confidence estimate before seeing the WOLN specification. |
| Appendix A semantic score | 98/100 | A later self-grade of the original responses against the supplied five-anchor-per-item key. |

The numerical difference is **11 points**, but these figures are not the same kind of measurement. The first is subjective confidence; the second is a rubric-based self-assessment after the answer key became available. The difference must **not** be described as an 11-point improvement in comprehension.

The supplied specification also states that an independent human reviewer is preferable. Therefore, 98/100 is a key-based AI self-grading result, not an independently verified score.

## 5. Model evaluation and comments

### What worked well

1. The model generally recovered intended meaning from shortened English without requiring standard grammar.
2. Numbers, names, times, negation, conditions, directions, and comparisons were mostly preserved.
3. The model often recognized when tense or abbreviations were uncertain rather than treating every sentence as fully specified.
4. The model correctly interpreted several core WOLN conventions, including optional verb inflection, optional articles, explicit number with base nouns, and physical `in` versus `on` distinctions.

### What needs improvement

1. **Do not over-apply Standard English grammar.** Adding an article such as “a” can change the quantity or scope of a short WOLN sentence.
2. **Keep unstated information unstated.** Do not add a message recipient, tense, or other detail unless the sentence or context supports it.
3. **Handle experimental abbreviations with a wider uncertainty range.** For `cmp`, list plausible readings such as “compare,” “comparison,” and “composition” rather than selecting only the most contextually attractive one.
4. **Use neutral paraphrases when time is unmarked.** Do not force past or future when no time word or context establishes it.

### Overall comment

The blind response shows that a general-purpose language model can infer much of this WOLN sample from familiar English vocabulary, word order, numbers, and context. The strongest result is not simply grammatical fluency; it is the preservation of most semantic anchors despite omitted inflections and function words. The remaining errors illustrate two useful design pressures for WOLN: preserve number without silently normalizing it, and clearly mark experimental abbreviations whose meanings are not yet stable.

This is a result on one 20-item sample using one AI model. It does not establish general comprehension across models, human learners, domains, or spoken language. Fresh unseen items and independent scoring would be needed for stronger claims.

## 6. Current project status

- [x] Part A blind test completed before the WOLN rulebook was supplied.
- [x] Original answers and initial confidence ratings retained for grading.
- [x] WOLN v0.9 specification and Appendix A received.
- [x] Part B key-based scoring completed.
- [ ] Independent human review of the 100-point grading.
- [ ] Fresh unseen test set for any future comparison or learning claim.

**Current status: Part B self-grading complete — 98/100. Pending independent review.**

---

**Record note:** This report evaluates the original Part A response. It does not replace or revise that blind response, and it does not claim a measured before/after improvement.
