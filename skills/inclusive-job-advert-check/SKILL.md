---
name: inclusive-job-advert-check
description: Checks a job advert for gender-coded wording, words that can signal an age preference, demands for years of experience, cliches, long sentences and reading ease, using the published word lists and Flesch method behind Hikari's free advert checker, and suggests a neutral swap for each finding. Use when the recruiter says 'check this advert', 'is this job ad inclusive', 'gender decoder', 'is this ad biased', 'readability of my job post' or pastes an advert for review. BOUNDARY - it marks where to look and suggests swaps but does not rewrite the whole advert; to write a new advert from a brief use job-advert-from-brief, and to fix the brief behind it use client-intake-brief.
license: MIT
metadata:
  category: job-adverts
  author: will-grady
  version: "1.1"
  checked: "2026-10-22"
---

# Inclusive job advert check

You check a job advert the way Hikari's free advert checker does, so the recruiter can see which words research links to who applies, which words could signal an age preference, and how hard the advert is to read. You show every finding with the word in context, so the recruiter decides. You don't rewrite the advert.

This is a guide, not legal advice. Whether a requirement can be justified depends on the job and the facts; if a dispute could turn on it, check with an employment lawyer.

## What you need

- **The whole advert,** as text. If it is under about 20 words, ask for the full advert.
- Optionally, **the brief or must-haves,** so you can tell whether a flagged requirement is really needed.

**Draft first.** If you have enough to make a useful first version, write it now, in this reply: mark anything missing as "To confirm", state any assumption you made in one line, and put your questions at the end. Only stop to ask before writing when something essential is missing entirely.

## The method

The word lists, matching rules and the Flesch formula are in `references/word-lists.md`. Use those lists exactly. Don't add words from your own knowledge, and if you think a word outside the lists is a problem, put it under "Other things to look at", labelled as your judgement.

1. **Gender-coded words.** Go through the advert word by word. A word counts if it starts with a stem on the masculine or feminine list. Count each list. The advert **leans masculine** if masculine-coded words outnumber feminine-coded, **leans feminine** if the reverse, and is **balanced** if they are equal. List every match with its count and say if a match is clearly used in another sense ("lead time", "responsibilities").
2. **What the research found.** Gaucher, Friesen and Kay (2011) found that adverts in male-dominated fields used more masculine-coded words, and that women found adverts written that way less appealing and felt they would belong less, while men's ratings barely moved. If the advert leans masculine, say this in one sentence and suggest swapping the words that aren't essential. Don't claim more than this.
3. **Age.** List any phrase from the age list and any "[number] years" requirement. Under the Equality Act 2010 an advert can be evidence of age discrimination unless the requirement can be justified, and so can asking for a set number of years' experience. For each, ask what it stands for and suggest wording about what the person needs to be able to do.
4. **Clichés.** List any phrase from the cliché list.
5. **Reading ease.** Count words, sentences and syllables as `references/word-lists.md` describes and give the Flesch score and band. Your count is an estimate; say so. List every sentence over 25 words.
6. **"You" against "the candidate".** Count "you", "your", "you'll", "you're" against "the candidate", "the successful candidate", "the ideal candidate", "the applicant" and "the post-holder". If "the candidate" wins, note that writing to "you" usually reads as more of an invitation.
7. **Swaps.** For each finding that isn't essential to the job, suggest a plain alternative that says what the job involves. Don't just swap a masculine word for a feminine one; say what the work is.

## Rules

- Don't tell the recruiter to remove a word that describes a real requirement. "Leads a team of six" is fine if the job leads a team of six.
- Don't guess who the advert is aimed at, or who will apply.
- Don't supply salary data or say whether pay is competitive.

## Output format

**Advert check: [job title]**

| Check | Result |
|---|---|
| Reading ease | score out of 100: band, words per sentence (estimate) |
| Gender-coded | leans masculine / leans feminine / balanced: x masculine, y feminine |
| Can signal age | count |
| Clichés | count |
| Sentences over 25 words | count |
| "You" against "the candidate" | x : y |

**Masculine-coded:** each word, with count. **Feminine-coded:** each word, with count. Mark neutral uses.

**Can signal age: check each is needed:** each phrase, with the question to ask and a suggested swap.

**Clichés:** each, with a suggested swap.

**Long sentences:** quoted, each with a shorter version.

**Suggested swaps:** a table of "Was" and "Could be", for the findings worth changing.

**Other things to look at:** your own observations, labelled as judgement (for example, no salary shown), or "None".

Keep it to about one screen. Work in UK English.
