# Gap method and UK rates (2026/27)

Source: Hikari's salary negotiation method, which takes the UK figures from GOV.UK, "Rates and thresholds for employers 2026 to 2027" (checked 21 October 2026). Use these figures exactly. Don't add others.

## UK rates

**Income tax** is charged on income after the candidate's own pension contribution (a net pay pension).

- Personal allowance: £12,570. Above £100,000 of income, it falls by £1 for every £2 over £100,000.
- Taxable income = income less the personal allowance. The bands below are on TAXABLE income.
- **England, Wales and Northern Ireland:** 20% on the first £37,700; 40% from £37,700 to £125,140; 45% above £125,140.
- **Scotland:** 19% on the first £3,967; 20% to £16,956; 21% to £31,092; 42% to £62,430; 45% to £125,140; 48% above.

**Employee National Insurance** is on gross pay (salary plus any bonus), before the pension contribution: 8% between £12,570 and £50,270, and 2% above £50,270.

**Employer National Insurance:** 15%. The tool assumes pay is above the employer NI threshold, so every extra £1 of salary or bonus costs the client £1.15 plus pension.

**Assumptions to state:** net pay pension, standard tax code, pay above the NI thresholds, no student loan.

## The sums

Write the client offer as OFFER, the ask as ASK, the client pension as ER%, the candidate pension as EE%, and holiday days as HOL.

**Package at a salary S, with a one-off bonus B and client pension ER% (UK):**
- Candidate pension = S × EE%. Client pension = S × ER%. (No pension on a bonus.)
- Income tax on (S + B − candidate pension).
- Employee NI on (S + B).
- Take-home = S + B − candidate pension − income tax − NI.
- **Worth to the candidate = take-home + candidate pension + client pension.**

**Outside the UK** (T = tax on extra pay, entered; ON = on-costs, entered):
- Take-home = (S × (1 − EE%) + B) × (1 − T). Candidate pension = S × EE%. Client pension = S × ER%.
- Worth = the same three added together.
- Use ON in place of the 15% employer NI everywhere below.

**The gap**
- On paper = ASK − OFFER.
- Take-home gap = take-home at ASK − take-home at OFFER.
- Worth gap = worth at ASK − worth at OFFER. This is "the gap the candidate feels".
- Cost to the client = (ASK − OFFER) × (1 + 15% + ER%).

**One unit of each option, on top of OFFER**
- Working days a year, WD = 260 − HOL.
- **£1,000 salary:** worth = worth at (OFFER + 1,000) − worth at OFFER. Cost = 1,000 × (1 + 15% + ER%).
- **£1,000 signing bonus, once:** worth = take-home at OFFER with B = 1,000 − take-home at OFFER. Cost = 1,000 × 1.15. No pension on it.
- **One more point of client pension:** worth = cost = OFFER ÷ 100. Client pension carries no NI, so it reaches the candidate whole.
- **One more day of holiday:** worth = take-home at OFFER ÷ WD (their take-home day rate). Costs no extra cash; it is a day not worked. Label it time.
- **One more WFH day a week:** worth = (WD ÷ 5) × commute cost a day. Hours saved = (WD ÷ 5) × commute minutes ÷ 60. Costs no cash. Label it time. Only possible if they're in the office at least one day a week now.
- **Per £1** = worth ÷ cost, for the cash options only.

**The package on the table** (extra salary X, bonus B, extra pension points P, extra holiday days H, extra WFH days a week W, review R% after M months)
- New salary S2 = OFFER + X. New client pension ER2 = ER% + P. Salary after review S3 = S2 × (1 + R%).
- Share of year one after the review = (12 − M) ÷ 12. M must be 0 to 12.
- Review, year one: worth = (worth at S3 − worth at S2, both with ER2 and no bonus) × share; cost = (S3 − S2) × (1 + 15% + ER2) × share.
- Time = H × day rate + W × (WD ÷ 5) × commute cost a day.
- **Year one worth** = (worth at S2 with bonus B and ER2 − worth at OFFER) + review worth + time.
- **Year one cost** = X × (1 + 15% + ER%) + S2 × P ÷ 100 + B × 1.15 + review cost.
- **Year two worth** = (worth at S3 with ER2, no bonus − worth at OFFER) + time.
- **Year two cost** = (S3 − OFFER) × (1 + 15% + ER%) + S3 × P ÷ 100.
- **% closed** = worth ÷ worth gap. **Still short** = worth gap − worth (or "Closed"). **Less than paying the full ask, by** = cost to the client of the full ask − package cost (negative means the package costs more).

## Worked example (England, from the calculator)

Ask £60,000, offer £55,000, client pension 5%, candidate pension 5%, 33 days' holiday, 3 office days, £15 a day and 90 minutes commute.

- At £55,000: candidate pension £2,750; tax on £52,250 = £8,332; NI £3,110.60; take-home £40,807.40; worth £46,307.40.
- At £60,000: candidate pension £3,000; tax on £57,000 = £10,232; NI £3,210.60; take-home £43,557.40; worth £49,557.40.
- Gap: on paper £5,000; take-home £2,750; worth £3,250; cost to the client £5,000 × 1.20 = £6,000.
- Options: £1,000 salary worth £650, costs £1,200 (£0.54 per £1). £1,000 signing bonus worth £580, costs £1,150 (£0.50). One pension point worth £550, costs £550 (£1.00). One holiday day worth £179.77 (227 working days). One WFH day a week worth £681 and 68.1 hours.
- Package of £2,000 salary, £2,000 signing bonus and one pension point: year one worth £3,030, cost £5,270, 93% closed, £220 short, £730 less than the full ask. Year two worth £1,870, cost £2,970, 58% closed, £1,380 short.

If your figures for this example don't match, recheck your method before working the recruiter's case.
