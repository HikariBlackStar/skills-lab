# Word lists for the job advert check

These are the lists Hikari's free job advert checker uses (hikari-ai.co.uk/tools, word lists dated 21 October 2026). Copy them exactly; don't add words from memory.

## How matching works

- **Gender-coded lists are word stems.** A word counts if it **starts with** a stem, ignoring case. "compet" catches "competitive", "competition" and "competent". "lead" catches "leader", "leadership" and also "lead time". Every match is listed so the writer can judge whether it is used in the coded sense.
- **Clichés and age words are phrases.** They count only as whole words or phrases. A hyphen and a space are treated as the same, so "fast-paced" also catches "fast paced".
- **Years of experience:** any number of one or two digits followed by "years" or "yrs", with or without a "+", such as "5 years", "10+ years", "3 yrs".

## Masculine-coded stems

Source: Gaucher, Friesen and Kay (2011), "Evidence that gendered wording in job advertisements exists and sustains gender inequality", Journal of Personality and Social Psychology 101(1), 109-128, as extended in Kat Matfield's open-source Gender Decoder (github.com/lovedaybrooke/gender-decoder).

active, adventurous, aggress, ambitio, analy, assert, athlet, autonom, battle, boast, challeng, champion, compet, confident, courag, decid, decision, decisive, defend, determin, domina, dominant, driven, fearless, fight, force, greedy, head-strong, headstrong, hierarch, hostil, impulsive, independen, individual, intellect, lead, logic, objective, opinion, outspoken, persist, principle, reckless, self-confiden, self-relian, self-sufficien, selfconfiden, selfrelian, selfsufficien, stubborn, superior, unreasonab

## Feminine-coded stems

Same source.

agree, affectionate, child, cheer, collab, commit, communal, compassion, connect, considerate, cooperat, co-operat, depend, emotiona, empath, feel, flatterable, gentle, honest, interpersonal, interdependen, interpersona, inter-personal, inter-dependen, inter-persona, kind, kinship, loyal, modesty, nag, nurtur, pleasant, polite, quiet, respon, sensitiv, submissive, support, sympath, tender, together, trust, understand, warm, whin, enthusias, inclusive, yield, share, sharin

Note: "respon" catches "responsible" and "responsibilities", and "depend" catches "dependent" and "depending". These are common in adverts in a neutral sense. Count them, list them, and say which look neutral in context.

## Clichés (phrases)

Hikari's own list of phrases that tell the reader little. A judgement, shown as a prompt, not a rule.

rockstar, rock star, ninja, guru, superstar, wizard, work hard play hard, fast-paced, self-starter, hit the ground running, wear many hats, synergy, go-getter, thick skin, like a family, passionate, dynamic, results-driven, proactive, team player, think outside the box, go the extra mile, competitive salary, ad hoc duties

## Words that can signal age (phrases)

Under the Equality Act 2010 an advert can be evidence of age discrimination unless the requirement can be justified. So can asking for a set number of years' experience. Shown so the writer can check each one is needed.

young, youthful, recent graduate, recent graduates, digital native, digital natives, mature, energetic, school leaver, school leavers, early career, newly qualified

## Reading ease (Flesch)

Score = 206.835 − 1.015 × (words ÷ sentences) − 84.6 × (syllables ÷ words)

| Score | Band |
|---|---|
| 60 and above | plain English |
| 50 to 59 | fairly hard |
| 30 to 49 | hard |
| below 30 | very hard |

How the checker counts:
- **Words:** runs of letters, including apostrophes and hyphens inside a word.
- **Sentences:** split at ".", "!" or "?" followed by a space or the end, and at every new line (so each bullet point is a sentence).
- **Syllables per word:** words of three letters or fewer count as 1. Otherwise drop a final "es", "ed" or "e" (unless it follows an "l" or a vowel), drop a leading "y", then count groups of one or two vowels (a, e, i, o, u, y). Minimum 1.
- **Long sentences:** more than 25 words.

The score counts words per sentence and syllables per word only, so treat it as a guide.
