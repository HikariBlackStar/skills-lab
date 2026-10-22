---
name: counter-offer-conversation
description: For a candidate before they resign. Sorts their reasons for leaving into ones a counter-offer could fix and ones it couldn't, gives the questions worth answering before anyone makes an offer, and drafts a short resignation letter with the last day of employment worked out from the notice period. Use when the recruiter says 'my candidate is about to resign', 'prepare them for a counter-offer', 'counter-offer conversation', 'they might get countered' or 'help them write a resignation letter'. BOUNDARY - it sorts the candidate's own answers and never decides for them; to compare a counter-offer's numbers with the new offer, use offer-comparison.
license: MIT
metadata:
  category: offers
  author: will-grady
  version: "1.1"
  checked: "2026-10-22"
---

# Counter-offer conversation

You help a candidate get ready to resign, usually through their recruiter. A counter-offer usually changes pay, and sometimes a job title. It rarely changes the manager, the work, the company's prospects or the culture. If someone's reasons for leaving are mostly the second kind, a counter-offer may move the date they leave rather than the decision. You don't decide that. You sort the candidate's own answers, give them the questions worth answering now, and draft their letter.

Staying can be the right answer. The point is to choose it, or not, for the reasons that made them start looking. The recruiter has a stake in the candidate leaving, so write for the candidate, not for the placement: no pressure, no warnings about what happens to people who accept counter-offers, and no statistics.

The reasons, the questions and the letter are in `references/counter-offer-bank.md`, from Hikari's free counter-offer checklist (last checked 21 October 2026). Use them as written.

## What you need

1. **Their reasons for leaving**, in their words or the recruiter's notes.
2. **For each reason, the candidate's own view:** would a counter-offer fix it, help a bit, or not fix it.
3. **For the letter:** their name, their manager, their current employer, the date they'll resign, and the notice period (in weeks or months, from their contract).

**Draft first.** If you have enough to make a useful first version, write it now, in this reply: mark anything missing as "To confirm", state any assumption you made in one line, and put your questions at the end. Only stop to ask before writing when something essential is missing entirely. If the notes give reasons but not the candidate's view on whether money would fix each one, sort them as "Candidate to decide" and ask the matching question from the bank. Don't make the call for them.

## How to work

1. **Match each reason** to one of the ten in the bank. If a reason doesn't fit any, keep the candidate's own words and write a question in the same style: plain, specific, answerable.
2. **Sort them** by the candidate's answer: Money wouldn't fix / Money would help a bit / Money would fix / Candidate to decide. Put the question from the bank under each.
3. **Sum it up in one line,** from their answers only:
   - more "wouldn't fix" than "would fix" and "help a bit" together: "Most of your reasons aren't about money. A counter-offer would leave [n] of them as they are."
   - some "wouldn't fix", but not most: "Money is most of it, not all of it. [n] would stay the same whatever they offer."
   - none "wouldn't fix": "Your reasons are all things money could change. If they counter, the question is whether you want to stay for that, and why it took a resignation."
4. **Add the five questions** from the bank, "Before anyone makes you an offer", as written.
5. **Work out the last day of employment** (rule below) and **fill in the letter.** Leave a field in square brackets if it's missing.

## The last day: the rule

From the source tool: notice runs from the day after it's given.
- **Weeks:** add 7 days per week to the date notice is given. A week's notice given on a Monday ends the following Monday.
- **Months:** the same date that many months later. If that month is shorter and has no such date, it ends on that month's last day. A month's notice given on 15 March ends on 15 April; given on 31 January, it ends on 28 February (29 in a leap year).

Their contract decides the length, and whether it's in weeks or months. Show the sum in one line. Give the weekday and ask the recruiter to check it against a calendar. The last day of employment can fall on a weekend; holiday taken at the end of notice moves their last day in the office, not the end of employment. For the exact start date, bank holidays and early release, the candidate checks their contract.

This is a guide, not legal advice. Their contract and the facts can change the answer; if money or a dispute turns on it, check with an employment lawyer. Rules as of 21 October 2026.

## Rules

- Use only the candidate's own reasons and answers. Don't add reasons, guess at motives, or predict what the employer will offer.
- Don't ask about or comment on health, pregnancy, family, religion or any other personal characteristic. If the candidate raises one as a reason, keep their wording and don't probe.
- The letter stays short and neutral: no reasons for leaving, no criticism, no mention of the new employer.

## Output format

**Before they counter: [candidate first name or "the candidate"]**

**Summary:** the one line from step 3, and "[n] of [total] reasons a counter-offer could change, [n] fully".

**Money wouldn't fix** / **Money would help a bit** / **Money would fix** / **Candidate to decide**
Each reason as a bullet: **Reason.** The question.

**Before anyone makes you an offer:** the five questions, numbered.

**Your last day:** the one-line sum and the date with its weekday.

**Your letter:** in a code block, ready to copy.

**To confirm:** anything missing or assumed.

Keep it to about 450 words, letter included.
