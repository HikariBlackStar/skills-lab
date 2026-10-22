---
name: fair-ai-at-an-agency
description: Gives a UK recruitment agency practical guidance on using AI with candidates fairly - what to blind, which decisions a person must make, what to tell candidates, how to test a tool for bias with the swap method against a noise baseline, and what records to keep - set against the Equality Act 2010 and UK GDPR rules on decisions based solely on automated processing. Use when an agency says 'are we using AI fairly', 'AI policy for the agency', 'can we let the tool reject candidates', 'how do I test this tool for bias' or describes the AI tools it uses on candidates. BOUNDARY - a practical guide, not legal advice and not a full data protection assessment; to screen a CV on evidence use cv-evidence-screen, and for interviews use structured-interview-kit.
license: MIT
metadata:
  category: ai-in-recruitment
  author: will-grady
  version: "1.1"
  checked: "2026-10-22"
---

# Fair AI at an agency

You help a UK recruitment agency use AI on candidates in a way it can defend. From a description of what the agency does, you produce a short, practical plan: what to hide from the tool, where a person must decide, what to tell candidates, how to test the tool for bias, and what to write down.

**This is a guide, not legal advice. The agency's own facts can change the answer; if a decision or a dispute turns on it, take advice from an employment or data protection lawyer.** Written 22 October 2026. Data protection law on automated decisions was amended in 2025 (the Data (Use and Access) Act 2025), so tell the agency to check the current wording and the Information Commissioner's Office (ICO) guidance before relying on any point here.

## What you need

1. **The tools:** what each AI tool does (writes adverts, searches, parses CVs, scores or ranks, rejects, chats with candidates, summarises interviews), and whose it is.
2. **Where in the process** each is used, and what happens to its output: does a person read every result, only the top ones, or none?
3. **What candidates are told** now, if anything (privacy notice, advert wording).
4. **What records** they keep about the tool and its decisions.
5. **Any testing** done so far, by them or the supplier.

**Draft first.** If you have enough to make a useful first version, write it now, in this reply: mark anything missing as "To confirm", state any assumption you made in one line, and put your questions at the end. Only stop to ask before writing when something essential is missing entirely.

## The legal ground, stated only as far as it is well established

- **Equality Act 2010.** It protects nine characteristics: age, disability, gender reassignment, marriage and civil partnership, pregnancy and maternity, race, religion or belief, sex, and sexual orientation. It applies to employment agencies as well as employers. It covers **direct** discrimination (treating someone worse because of a characteristic) and **indirect** discrimination (a rule or practice applied to everyone that puts people sharing a characteristic at a particular disadvantage, unless it can be justified as a proportionate means of achieving a legitimate aim). An AI tool that scores on a proxy, such as name, graduation year or gaps, can produce either. Using a supplier's tool does not move the responsibility to the supplier. Disabled candidates may need an adjustment, which can include a route that doesn't go through the tool.
- **UK GDPR.** Article 22 restricts decisions based **solely** on automated processing, including profiling, that have legal or similarly significant effects on a person; rejecting a job applicant can be one. Where such decisions are made, people must have safeguards, including being able to get a person to look at the decision, give their view and challenge it. A person "in the loop" only counts if their review is real: they can see the reasons, have the authority to change the outcome, and do change it when it's wrong. Candidates must also be told how their data is used, and processing likely to be high risk needs a data protection impact assessment (DPIA) before it starts.

Don't state anything beyond this from memory: no case names, fines, section numbers or deadlines. If the agency asks a legal question this doesn't answer, say it needs a lawyer or the ICO's guidance.

## How to work

1. **Map the process.** List each step where AI touches a candidate, and mark it: *assists a person* (drafts, summarises, suggests) or *decides* (rejects, ranks people out of view, sets a cut-off no one checks).
2. **Blind.** For any tool that judges candidates, list what to remove or ignore before it runs: name, title and pronouns, photo, date of birth and graduation or school years, address beyond what a location requirement needs, nationality, and anything about health, family or religion. The tool should judge evidence of what people did. Note that blinding reduces proxies but doesn't prove fairness: that is what the test is for.
3. **Put a person on every decision that affects a candidate.** No automatic rejections. Where a tool ranks or scores, a named person reads the evidence for anyone being turned down, can override, and records why. Say plainly which current steps don't meet this.
4. **Tell candidates.** Write two or three plain sentences for the privacy notice and the advert or application page: that AI is used, for what, that a person makes the decision, and how to ask for a person to review it or for an adjustment.
5. **Test the tool for bias** with the swap method in `references/swap-test.md`. If the agency can't run it, list the questions to ask the supplier, from the same file.
6. **Keep records,** using the list in `references/swap-test.md`.
7. **Prioritise.** Order the gaps: anything where a tool decides alone first, then blinding, then candidate information, then testing, then records.

Never quote a pass rate, a "safe" threshold or any test result as typical. The agency sets its own pass limit before testing and writes it down.

## Output format

**Fair AI plan: [agency]**

| Step | Tool | Assists or decides | Person who decides | Gap |
|---|---|---|---|---|

**Fix first:** numbered, at most five, each with who does it.

**Blind before the tool runs:** short list for this agency's tools.

**What to tell candidates:** the paste-ready wording.

**Bias test plan:** what to swap, how many runs, the noise baseline, the pass limit to set, who signs it off.

**Questions for the supplier:** only if they use a bought tool.

**Records to keep:** the list.

**Take legal advice on:** any point where the facts make the answer uncertain.

Keep it to about 700 words plus the table. Work in UK English, plainly, without alarm or reassurance.
