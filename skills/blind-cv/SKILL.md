---
name: blind-cv
description: Prepares a CV to be shared or assessed blind - takes out the name, contact details, address, photo, pronouns and titles, age clues such as date of birth and education years, nationality, marital and family status - while keeping every piece of work evidence intact, then lists exactly what was removed and what a person should still check by hand. Use when a recruiter says 'blind this CV', 'anonymise this CV', 'redact the CV', 'take the name off', 'remove personal details before I send it' or wants a CV assessed on evidence only. BOUNDARY - this removes details and changes nothing else; to judge the blind CV against a brief, use cv-evidence-screen, and to write the client summary, use shortlist-write-up.
license: MIT
metadata:
  category: cv-screening
  author: will-grady
  version: "1.1"
  checked: "2026-10-22"
---

# Blind CV

You prepare a CV so it can be read on what the person has done. You take out the details that identify them or hint at a protected characteristic, keep every piece of work evidence exactly as written, and list what you removed so the recruiter can check it. You don't assess the candidate. A person decides what happens next, and a person reads the result before it is sent.

This follows the method of Hikari's free Blind CV tool (checked 22 October 2026), which works by pattern and says plainly: "Patterns miss things: a name spelt differently, a club or school that gives away background, a photo inside a PDF. Read it before you send it." The same is true of you.

## What you need

- **The CV, as text.**
- **The candidate's name,** if the recruiter can give it. Otherwise take it from the first line if that line reads like a name.
- **Two choices,** both on unless the recruiter says otherwise: make pronouns neutral, and hide the years on education lines.

One line to the recruiter, once: pasting a CV into an AI chat sends it to that AI provider. If their agency's data policy doesn't allow that, Hikari's free Blind CV tool does the same job in the browser without uploading the CV.

**Draft first.** If you have enough to make a useful first version, write it now, in this reply: mark anything missing as "To confirm", state any assumption you made in one line, and put your questions at the end. Only stop to ask before writing when something essential is missing entirely.

## What to take out

Replace each item with the tag shown, so every change can be seen:

| Remove | Tag |
|---|---|
| The name, and every use of each part of it (including "Sarah's") | [Candidate] |
| Email addresses | [email] |
| Phone numbers | [phone] |
| Web, LinkedIn, GitHub and social links | [link] |
| Address lines, any short line with a UK postcode, lines starting "Address" | [address] |
| Lines for date of birth, place of birth, age, nationality, citizenship, marital status, gender or sex, religion, ethnicity, sexual orientation, pronouns, dependants or children, next of kin, NI number, passport number | [personal detail removed] |
| Ages written in the text ("aged 42", "35 years old") | [age] |
| Titles: Mr, Mrs, Ms, Miss, Mx | [title] |
| Years on school, college, degree, diploma and qualification lines | [year] |
| A photo, or any mention of one | [photo removed] |

**Pronouns:** change he and she to they, him to them, his and her to their, himself and herself to themselves, and fix the verb ("she manages" becomes "they manage", "he is" becomes "they are").

**Personal interests:** take out any item that reveals a protected characteristic or family status (a place of worship, "coaching my children's team", a cultural or national society) and tag it [personal detail removed]. Leave other interests as they are.

**Right to work:** if the CV names a visa type or a nationality to explain it, replace the line with "Right to work: stated on the original CV, check in the standard way". Right to work is checked the same way for everyone, not from a CV.

## What to keep, word for word

- Every employer, job title, and the start and end dates of each job. These are evidence. Don't round, merge or reword them.
- Every achievement, responsibility, number, tool, skill, certification and project.
- The names of qualifications and the institutions that awarded them (the years go, the qualification stays).
- Languages and the level the CV states, because they can be a job skill.
- Career breaks and gaps, as written. They are neutral. Don't explain, fill or hide them.
- The person's spelling, grammar and wording. Don't correct or polish anything. Blinding is not editing, and a blind CV that has been tidied is no longer the candidate's CV.

## Then check by hand

After the replacements, read the result once more for anything a pattern would miss, and list each one under "Check by hand" rather than guessing. Typical examples:

- a nickname or a different spelling of the name, or the name inside an email signature or file name
- a school, club, society, scholarship or award whose name gives away background, faith, sex or age
- "native" or "mother tongue" next to a language, which can suggest origin
- employment dates long enough to hint at age (keep them: they are evidence, but say so)
- a photo that may be in the original file even if it isn't in the pasted text

## Output format

**Blind CV**
The full CV text with every change tagged as above, in the original order and layout as far as plain text allows.

**What was removed**
| Kind | How many | Examples (tags only, never the removed text) |
|---|---|---|

Give a total, and say whether a name was found. If no name was found, say so and ask for it.

**Check by hand**
A numbered list of what you were unsure about, each with where it sits in the CV.

**Not changed:** one line confirming that employers, job dates, achievements and wording are as the candidate wrote them.

Never repeat the removed details anywhere in your answer. Work in UK English. Keep everything outside the CV itself to about 200 words.
