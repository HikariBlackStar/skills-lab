---
name: cost-of-vacancy
description: Works out what an unfilled role costs a client for each working day and week it stays open, using only figures the client supplies, and shows every step so the client can check it. Uses the method of Hikari's free cost-of-vacancy calculator - the role's yearly value divided by 232 working days, plus any cover costs. Use when the recruiter says 'cost of vacancy', 'what is this empty seat costing them', 'cost of an unfilled role', 'make the case to move faster' or 'the client is dragging their feet'. BOUNDARY - it is an estimate from the client's own numbers, not a forecast or a fee proposal; to take the brief use client-intake-brief, and to plan the wider account use client-account-plan.
license: MIT
metadata:
  category: client-briefs
  author: will-grady
  version: "1.1"
  checked: "2026-10-22"
---

# Cost of an unfilled vacancy

You help an agency recruiter show a hiring client what an open role is costing them, worked out from the client's own figures. The point isn't to frighten the client. It is to put a fair number on the delay, with the workings shown, so the client can decide how much a faster process is worth to them. The method is the one in Hikari's free cost-of-vacancy calculator (hikari-ai.co.uk/tools, last checked 21 October 2026).

## What you need

1. **The role** and the client's name.
2. **One way to value the role,** chosen by the recruiter or the client:
   - **Salary:** the yearly salary. The cautious figure, and the default.
   - **Revenue per employee:** the client's yearly turnover and their headcount.
   - **The client's own figure:** a yearly value the client puts on the role.
3. **Cover costs,** in £ a week, if any: overtime, an interim or contractor, agency temps. Zero if none.
4. **Working days the role has been open so far.**
5. **Working days still to go,** as the recruiter's or client's estimate.

Never supply any of these from your own knowledge. If a figure is missing, ask for it or mark it "To confirm" and leave that line out of the sum.

**Draft first.** If you have enough to make a useful first version, write it now, in this reply: mark anything missing as "To confirm", state any assumption you made in one line, and put your questions at the end. Only stop to ask before writing when something essential is missing entirely. A yearly value for the role is essential.

## The method

1. **Yearly value of the role:**
   - Salary basis: the salary. It is the least the role must be worth to the business, or the client wouldn't pay it.
   - Revenue basis: turnover ÷ headcount. Both are in the client's published accounts at Companies House. Better for roles that earn money directly.
   - Client's figure: as given.
2. **Per working day:** yearly value ÷ **232**. That is 260 weekdays in a year less 28 days of statutory holiday.
3. **Cover per day:** weekly cover costs ÷ 5.
4. **Each working day open:** step 2 + step 3.
5. **Each week open:** step 4 × 5.
6. **So far:** step 4 × working days open so far.
7. **Still to go:** step 4 × working days still to go.
8. **Total:** so far + still to go.

Work from unrounded figures and round only what you show: money to the penny for daily and weekly figures and to the nearest pound for totals. Show every step, with the numbers, so the client can check it.

Worked example (salary basis): £45,000 ÷ 232 = £193.97 a day. With £500 a week of overtime cover, add £100.00 a day: £293.97 a working day, £1,469.83 a week (worked from the unrounded daily figure, as the calculator does).

## Caveats you must keep

- **It's an estimate built from the client's numbers, not yours.** Say so on the sheet.
- **Don't add multipliers.** No "a vacancy costs three times salary", no lost-productivity percentages, no industry averages. None of them are in the method, and the client can't check them.
- **Name the basis used.** The salary figure is a floor; the revenue figure can be much higher and suits revenue-earning roles better. Don't present the revenue figure as the cost for a role that doesn't earn revenue directly.
- **"Still to go" is an estimate.** Label it that way.
- **Use working days, not calendar days.** If the recruiter gives calendar days or weeks, convert at five working days a week and say you did.
- **Don't link the figure to your fee** or suggest the client is losing money because of anyone in particular. State the number, and let the client draw the conclusion.

## Output format

**[Role]: what the empty seat costs**
Prepared for [Client], [date].

**Each week open: £[x]**

| Step | Figure |
|---|---|
| [Basis, with its numbers] | £ a year |
| ÷ 232 working days | £ a day |
| + cover costs (if any) | £ a day |
| **Each working day open** | **£** |
| Each week open | £ |
| So far ([n] working days) | £ |
| Still to go ([n] working days, estimated) | £ |
| **Total** | **£** |

**Note for the sheet:** "An estimate from the figures above, supplied by [Client]. Working days: 260 weekdays less 28 days' statutory holiday."

**Covering note:** two or three plain sentences the recruiter can send with it. Inform, don't push: no urgency, no "every day you wait".

Work in UK English. Keep the whole output to one screen.
