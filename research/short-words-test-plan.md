# Written short-word test plan

**Status** · NOT RUN

Evaluate familiar short forms and experimental shorthand separately. Start with [curated candidates](../lexicon/short-words-candidates.csv) and add fresh, balanced messages with full-word controls. Keep grammar comparable between versions. Include both clear contexts and collision contexts.

| Material | Example probes | What to record |
| --- | --- | --- |
| Familiar written forms | `tmr`, `yday`, `msg` | First-pass expansion, meaning and reading effort |
| Established forms in specific domains | `app`, `govt`, `appt` | Correct sense and dependency on audience or context |
| Experimental forms | `ALYZ`, `CMPSTN` | Recognition, competing readings and clarification rate |
| Collision controls | `cmp`, `YTD` | Appropriate uncertainty, expansions and unsupported guesses |

1. Build a new keyed set with a mix of sentences that resolve an abbreviation and sentences that leave it open. For an unresolved form, predefine plausible alternatives and accept a clarifying question.
2. Test full-word, blind abbreviation and context-assisted abbreviation conditions with matched items. Assign participants to conditions or counterbalance different item forms so one exposure does not reveal the answer to another.
3. Collect human responses by language background and proficiency. For AI, use isolated runs, record model, version, date and prompt, and provide the [portable context](../WOLN_CONTEXT.md) only in the assisted condition. Avoid using pilot sentences as fresh items.
4. Use independent scoring. Record correct expansion, meaning preservation, appropriate uncertainty, false confident guesses and collision pairs. Report confidence separately, with exact sample sizes and task conditions.
5. Review findings before changing vocabulary status. Record sources, domain and limits of use. Keep speech and ASR validation in the [spoken research plan](../docs/spoken-language.md).
