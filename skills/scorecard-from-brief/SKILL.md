---
name: scorecard-from-brief
description: Builds a weighted hiring scorecard from a role brief - 6 to 8 criteria, each with a weight, one evidence question and 1 to 4 anchors written for this role - and, if candidate evidence is given, scores it on evidence only with quotes and an auditable scores line. Use when a recruiter or hiring manager says 'build a scorecard', 'weighted criteria', 'assessment matrix', 'how should we score candidates for this', 'score this candidate against the scorecard'. BOUNDARY - this sets the criteria and scores evidence already gathered, and informs a person's decision; for interview questions and probes, use structured-interview-kit; to screen a CV against must-haves, use cv-evidence-screen; to combine several interviewers' views, use interview-debrief.
license: MIT
metadata:
  category: scorecards
  author: will-grady
  version: "1.1"
  checked: "2026-10-22"
---

# Scorecard from brief

You turn a role brief into a scorecard that every candidate is measured against in the same way. A good scorecard is agreed before anyone meets a candidate, so the criteria can't drift towards whoever made the best impression. If the recruiter also gives evidence about a candidate, you score it against the scorecard. You never make the decision: a person does.

## What you need

1. **The brief:** job title, must-haves, nice-to-haves, deal-breakers, and what the person will do in the first year.
2. **Optional: candidate evidence** to score: a CV, call notes or interview notes. If given, refer to the candidate as "the candidate", not by name.

**Draft first.** If you have enough to make a useful first version, write it now, in this reply: mark anything missing as "To confirm", state any assumption you made in one line, and put your questions at the end. Only stop to ask before writing when something essential is missing entirely.

## Part 1: Build the scorecard

1. **Pick 6 to 8 criteria** from the brief. Each must be something a person does in the job and can show evidence of. Say in one line where in the brief it came from. Don't add criteria the brief doesn't support.
2. **Turn proxies into abilities.** A degree, a number of years, a "top company" or "native speaker" is a proxy. Ask what it stands for and write that instead ("can build a three-statement model unaided", not "5+ years in FP&A"). Note each change so the client can confirm it.
3. **Leave out what isn't a criterion:** "culture fit" with no stated behaviour, "presence", "energy", "polish", and anything that tracks age, sex, race, religion, disability, pregnancy, marital status or another protected characteristic. If the brief asks for one of these, flag it under "To confirm with the client" and suggest the behaviour it might stand for.
4. **Keep logistics off the scorecard:** notice, salary, location and office days, right to work. List them as pass-or-check items underneath.
5. **Weight the criteria** so the weights add up to 100. Must-haves carry more than nice-to-haves. No single criterion above 30. If the client hasn't said how they rank the criteria, propose weights and mark them "proposed".
6. **Write one evidence question per criterion:** what the assessor is looking for evidence of, phrased as a "Tell me about a time…" or "Where on the CV…" prompt.
7. **Write the anchors for each criterion,** in this role's terms, built on this scale (Hikari's structured interview kit, 21 October 2026):
   - **1, No evidence:** No real example, or the example shows the opposite. Talks in general terms ("I always...").
   - **2, Some evidence:** A real example, but thin: "we" not "I", needed prompting, or no clear result.
   - **3, Clear evidence:** A specific example, their own actions, and a result they can describe. Meets the bar for the role.
   - **4, Strong evidence:** Several specific examples, a measurable result, and what they would do differently. Above the bar.

   Each anchor says what that level looks like for this criterion, in one line. Don't invent benchmark figures for the anchors; if a measurable bar is needed (a target, a volume), ask the client for it and write "To confirm".

## Part 2: Score a candidate (only if evidence is given)

Before scoring, set aside and never let affect a score: the name, titles and pronouns, age and education years, any personal characteristic, photos, how polished the English is, spelling, layout and length (unless written English or design is a criterion), and self-praise adjectives. Only what the person did counts. Career breaks and gaps are neutral.

For each criterion, write the evidence in **2 to 4 sentences**: quote or closely paraphrase the source, naming the **employer and dates**; say how directly it meets the anchor; name what is missing and what to ask. Never a bare verdict. If the source doesn't cover a criterion, score 1 and say "not covered", so an unknown is visible as an unknown.

Then:
- **Weighted score** = the sum of (score × weight) ÷ 4, giving a figure out of 100. Show the working.
- **Outcome**, following the scores, never adjusted to fit: **Meets the bar** (every must-have criterion 3 or 4, no deal-breaker), **Check further** (no 1 on a must-have, but at least one 2), **Below the bar** (a 1 on a must-have, or a deal-breaker applies).

The weighted score never overrides a 1 on a must-have. Don't compare candidates with each other here; each is scored against the scorecard.

## Output format

**Scorecard: [Job title], [Client]**

| # | Criterion | From the brief | Weight | Evidence question |
|---|---|---|---|---|

**Anchors**
| Criterion | 1 | 2 | 3 | 4 |
|---|---|---|---|---|

**Pass-or-check (not scored):** logistics and deal-breakers.
**Changes from the brief:** proxies rewritten, items left out, each with a one-line reason.
**To confirm with the client:** numbered questions, including any proposed weights.

If a candidate was scored, add:

**Scored: the candidate**
| Criterion | Weight | Score (1–4) | Evidence |
|---|---|---|---|

**Weighted score:** x/100, with the working. **Outcome:** with one or two sentences of why.

Finish with this line exactly, so scores can be compared and audited:
`SCORES: K1=x; K2=x; ... TOTAL=sum/max; WEIGHTED=x/100; RECOMMENDATION=Meets the bar|Check further|Below the bar`

Number criteria K1, K2 in the scorecard's order. Keep the scorecard to one printed page and any scoring to about 500 words. Work in UK English. A person makes the hiring decision.
