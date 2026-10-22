# The swap test, supplier questions and records

## The swap test

The idea: if a tool judges evidence and nothing else, changing only something that isn't evidence should not change its answer. So you run the tool over CVs and change one thing at a time, with everything else word for word the same. If the scores move when only the name changed, the tool has a problem.

**1. Prepare the CVs.** Use fictional CVs, not real candidates' data. Write them for the kinds of role the agency fills, with a spread of strong, middling and weak fits, so the test covers more than one kind of decision.

**2. Decide what to swap.** One thing per version:
- **Names:** the same CV under names that suggest different genders and ethnic backgrounds.
- **Gender:** pronouns and titles (Mr, Ms, Mx; he, she, they).
- **Age:** the year of graduation and any date of birth, with the career history left as it is.
Add others if they matter to the agency's roles, such as a career break, or signs of a disability or a non-UK education, changing only that.

**3. Measure the noise first.** AI tools don't give exactly the same answer twice. Run the same, unchanged CV through the tool again and again, with the same settings and instructions. That shows how much the scores move on their own. Without this baseline you can't tell a real effect from chance.

**4. Set the pass limit before you run anything, and write it down.** Decide how big a difference would count as a failure and which statistical test will judge it. If nobody in the agency is comfortable choosing a test, ask someone who is before starting, not after seeing the results.

**5. Run the swaps.** Same tool, same version, same settings and instructions as in real use. Run each version enough times to compare with the baseline. Record every score.

**6. Read the result.** A swap only counts as an effect if it moves scores by more than the noise does and the test says the difference is unlikely to be chance. Report every swap, including the ones that showed nothing.

**7. If it fails,** stop using the tool for that decision, fix it (for example by blinding, or changing the instructions), and test again. Don't change the pass limit after the fact.

**8. Re-test** when the tool, its underlying model, its settings or the agency's instructions change, and at a regular interval the agency chooses.

**What a pass doesn't prove.** A pass means the tool treated those fictional CVs the same when those things were swapped, on that version, on that date. It doesn't promise the same for every CV, and it doesn't test everything (for example, whether the criteria themselves are fair). A person still makes every hiring decision.

## Questions for a supplier

1. Has the tool been tested for different results by sex, race, age or disability? With what method, how many CVs and runs, and when?
2. Did the test include a noise baseline (the same input run repeatedly), and was the pass limit set before testing?
3. Can we see the results, including any swap that failed?
4. Which model version does the tool use, and will you tell us when it changes?
5. Can the tool run without names, photos, dates of birth and graduation years?
6. Can a person see why the tool scored someone as it did, and override it?
7. Does the tool ever reject, or hide, a candidate without a person seeing them?
8. Where is candidate data processed and stored, how long is it kept, and is it used to train anything?

## Records to keep

- Each AI tool used on candidates: what it does, supplier, version, date started.
- The process map: which steps it assists, and who decides at each.
- The blinding applied, and when it was last checked.
- Each bias test: date, tool and version, CVs used, runs, swaps, the noise baseline, the pass limit set beforehand, the result, and who signed it off.
- Decisions on candidates: who made them, and the reason, especially where a person overrode the tool.
- Requests from candidates for a person's review, an adjustment or an explanation, and what was done.
- The candidate-facing wording, with the date it was published.
- The DPIA, where one was done, and its review date.

Keep these for as long as the agency's own retention policy and privacy notice say. Don't invent a retention period: if the agency hasn't set one, that is a question for its data protection lead or lawyer.
