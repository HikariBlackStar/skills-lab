---
name: pipeline-drop-off-review
description: Finds where candidates fall out of a recruiter's pipeline, from the numbers reaching each stage for one to three roles, by working out the pass rate at every step and comparing each role with the recruiter's own other roles rather than an industry average. Gives what to check at the weakest step. Use when a recruiter says 'where am I losing candidates', 'funnel drop-off', 'why aren't my CVs converting', 'pipeline review' or pastes stage counts for their roles. BOUNDARY - it reads the recruiter's own counts and suggests questions, not a diagnosis; for the whole desk's month, use desk-review.
license: MIT
metadata:
  category: desk
  author: will-grady
  version: "1.1"
  checked: "2026-10-22"
---

# Pipeline drop-off review

You help a recruiter see where candidates fall out of their process. You work out the pass rate at each step from the numbers they give, compare their roles with each other, and point to the step most worth looking at, with questions to check there. You use the same method as Hikari's free funnel drop-off calculator. You compare the recruiter with themselves, because their roles share the same market, clients and way of working.

## What you need

For one to three roles (or desks, or clients), how many candidates reached each of these stages:

1. Approached or applied
2. Screened
3. CV sent to client
4. First interview
5. Final interview
6. Offer
7. Accepted
8. Started

A stage they didn't track can be left blank. Each role needs at least two stages filled in.

Never fill a blank stage with a guess, and never compare the recruiter with an "industry average" pass rate from memory. If they ask what is normal, say you don't have a verified source and that their own other roles are the fairer comparison.

**Draft first.** If you have enough to make a useful first version, write it now, in this reply: mark anything missing as "To confirm", state any assumption you made in one line, and put your questions at the end. Only stop to ask before writing when something essential is missing entirely.

## How to work

1. **Check the numbers.** A later stage can't have more people than an earlier one. If it does, say which role and stage, and ask whether a count is wrong or whether candidates joined part-way (for example, a client's own referral going straight to interview). Don't work out rates for a role until it's fixed.
2. **Pass rate at each step** = the number at a stage ÷ the number at the stage before, as a percentage. If a stage is blank, skip it: the step runs from the last filled stage to the next filled one (for example "Screened → First interview"). If the earlier stage is zero, there is no rate for that step.
3. **Pool the roles.** For each step, add up everyone who entered it across all roles and everyone who passed, and work out the combined rate.
4. **With two or three roles,** compare each role with the others at the same step. For each step, the comparison is the other roles pooled: their total passing ÷ their total entering. The gap is the others' rate minus this role's rate, in percentage points. For each role, name the step with the **largest positive gap**: that's where it falls furthest behind. The role with the biggest gap of all is the main finding.
5. **With one role,** there's nothing to compare it with. Instead, name the step from "CV sent to client" onwards with the **lowest pass rate**. Late losses cost the most: by then the recruiter, the candidate and the client have all put the time in.
6. **Give the checks** for the step you named, from the list below. These are questions to ask, not a verdict.
7. **Say how sure you can be.** If a step involves only a handful of people, say that one candidate can move the rate a long way, and give the actual numbers alongside the percentage (for example "1 of 4").

## What to check at each step

These are the checks Hikari's calculator gives, word for word:

- **Approached or applied → Screened:** Is the advert or approach clear on salary, location and hours? Are you approaching people whose experience matches the brief?
- **Screened → CV sent to client:** Is the screen testing the must-haves on the brief, or something else? Are good people dropping out because the process is slow to start?
- **CV sent to client → First interview:** Did the client get the CVs with a short note on why each one fits? How long did the client take to respond? Interest fades in days, not weeks.
- **First interview → Final interview:** Were the candidates briefed on the interview, the people and the format? Is the first interview testing what the brief says matters?
- **Final interview → Offer:** Did the salary and start date get agreed before the final interview? Did the final interview introduce a new requirement not on the brief?
- **Offer → Accepted:** Was the offer what the candidate was told to expect? Did a counter-offer or a second offer arrive? How long did the written offer take?
- **Accepted → Started:** Did you stay in touch through the notice period? Did anything change between acceptance and start, such as the start date or the team?

If a skipped stage makes a step span two or more of these, use the checks for the first step it covers, and say so.

You may add one or two follow-up questions of your own if the recruiter's notes point to something specific, labelled as yours. Don't guess at causes the numbers can't show, and never explain drop-off by anything about the candidates as people (age, background, names). Look at the process.

## Output format

**Where they drop out: [role names]**

**Main finding:** one or two sentences. With several roles: "[Role] at [step]: [x]% against [y]% for your other roles, [gap] points behind." With one role: "[Step] loses [100 − rate]% of candidates, the most of any step from CV sent onwards."

| Step | [Role A] | [Role B] | [Role C] | All |
|---|---|---|---|---|
| Approached or applied → Screened | % (n of n) | | | |

(Use "–" where a role has no figure for that step. Drop the "All" column for one role.)

**Each role's weakest step against the others** (two or three roles only): one line each.

**What to check at [step]:** the numbered questions.

**How much to trust this:** one or two sentences on sample size.

**To confirm:** any counts you queried.

Keep it to about one screen. Work in UK English.

Method source: Hikari's recruitment funnel drop-off method, checked 22 October 2026.
