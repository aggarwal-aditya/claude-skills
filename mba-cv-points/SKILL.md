---
name: mba-cv-points
description: >-
  Write, rewrite, review, or draft bullet points for MBA placement and internship CVs/resumes in
  the IIM-style one-page "summers" format - strong action-verb openers, heavy quantification, and
  thematic side-labels. Use this skill whenever the user wants to write or improve a CV/resume point,
  bullet, or section; polish a rough achievement line; quantify an accomplishment; turn a job
  description or rough sentence into a CV-ready bullet; review or score existing CV points; or draft
  Education, Scholastic/Academic Achievements, Work Experience, Internship, Projects, Positions of
  Responsibility (PoR), or Extra-Curricular sections. Trigger on any mention of CV, resume, placement
  CV, summers CV, bullet point, PoR, B-school/MBA application, or asks like "make this sound better",
  "make it CV-ready", or "quantify this" - even if the word "skill" is never used.
---

# MBA CV Points Writer

This skill writes CV bullet points in the house style of a large corpus of IIM MBA summer-placement
CVs (~2,000 real CVs analysed). That style is specific and learnable. Your job is to make any input -
a rough sentence, a job description, a paragraph, or nothing but a verbal description of what someone
did - come out sounding like it belongs on one of these CVs.

The four things users ask for, and where to go:

| Mode | User says something like... | What you do |
|------|---------------------------|-------------|
| **Polish** | "make this better", "fix this bullet", "CV-ify this" | Rewrite their line into house style (see The Formula) |
| **Generate** | "I did X, write a bullet", here's my JD/experience | Produce 1-3 bullets from raw facts |
| **Review & score** | "rate my CV points", "what's wrong with these" | Score against references/review-rubric.md and give fixes |
| **Full section draft** | "write my PoR section", "draft my work experience" | Draft a whole section using references/section-playbook.md |

Most requests are Polish or Generate. Always read `references/section-playbook.md` before drafting,
because the verb palette and what-to-quantify change section by section - that is the single most
important thing this skill teaches.

---

## The Formula

Every strong bullet in the corpus follows the same underlying shape. Internalise it:

> **[Strong past-tense action verb] + [quantified outcome] + [by/via/through/using + method] + [scope/scale]**

**Worked examples (real, from the corpus):**

- `Reduced false alerts by 50% in transaction monitoring rule in partnership with Financial Investigation Unit`
- `Drove Rs50L+ annual saving by leading negotiation with 5+ vendors for heat exchanger procurement`
- `Boosted in-store revenue by 15% and footfall by 10% in three weeks via localized marketing`
- `Led 80+ students as House Captain, securing top-3 rank in 5+ inter-house cultural & sports events`
- `Secured 99.97%ile in CAT (VARC 99.8, QA 99.92) - top 100 out of 2.93 lakh candidates`

### The seven rules (these are what make it sound right)

1. **Open with a strong past-tense action verb.** Never "Responsible for", never a gerund
   ("Managing..."), never first person ("I led..."). The first word does the heavy lifting. Pick the
   verb from the section's palette (see the cheat-sheet below; full list in `references/verb-bank.md`).

2. **Front-load a number.** ~3 of every 4 bullets put a figure in the first six words. Lead with the
   result, not the activity. "Reduced cost by 18%..." beats "Worked on a project that reduced cost...".

3. **Quantify everything quantifiable.** ~87% of corpus bullets contain a digit. Percentages, money
   (Rs/$/EUR), multiples (3x), counts, time saved, people/teams/users, scale. If a line has no number,
   that is the first thing to fix. See `references/quantification.md` for the full toolkit.

4. **Show the method.** After the outcome, say *how* - usually with **by** (by far the most common
   connector), or via / through / using / leveraging. This separates a claim from a credible
   achievement: "Boosted revenue 15% **by** launching localized campaigns across 3 stores".

5. **One line, ~12-18 words (~100 characters).** These are one-page CVs; every bullet is a single
   line. Median bullet is 15 words. If it wraps to two lines, cut it.

6. **Compress with symbols and abbreviations.** Use `&` not "and" inside lists, `|` to join two
   facts in one line, `Rs2Cr+ / Rs50L+ / 10k+` for scale, `%ile`, `YoY`, `AIR`, `1/N` for selectivity,
   `5+` for "at least five". Drop articles (a/the) where the line still reads cleanly.

7. **No closing period. No pronouns. No fluff words** ("various", "successfully", "responsible for",
   "helped with"). Every word earns its place - if you can delete a word and keep the meaning, delete it.

---

## Section cheat-sheet

Different sections have a different *job*, so they use different verbs and quantify different things.
This is a summary; **read `references/section-playbook.md` for the per-section detail and examples.**

| Section | Its job is to show... | Lead verbs | Quantify with |
|---------|---------------------|-----------|---------------|
| **Education** | Pedigree & rank | (table, not bullets) | Score/10 or %, rank, "≥X in N/M subjects" |
| **Scholastic / Academic Achievements** | Selectivity & brilliance | Secured, Achieved, Awarded, Ranked, Scored | %ile, AIR, 1/N, out-of-pool size |
| **Work / Professional Experience** | Business impact | Led, Reduced, Drove, Built, Delivered, Saved | Rs/$/EUR, %, time, x-multiples |
| **Internships** | Deliverables + impact | Achieved, Developed, Built, Analysed, Boosted | %, units shipped, scale |
| **Projects / Research** | Technical method + result | Built, Developed, Designed, Achieved, Analysed | accuracy %, x-speedup, data size |
| **Positions of Responsibility** | Leadership scale | Led, Managed, Organized, Spearheaded, Mentored, Raised, Elected | team size, Rs budget, people impacted, 1/N selection |
| **Extra-Curricular** | Distinction & breadth | Won, Secured, Ranked, Finalist, Volunteered, Represented | rank, "1/N of M teams", participants |

**The mindset shift per section:** Experience/Internship/Projects = *"what changed because of me, in numbers?"*
PoR = *"how big was what I ran?"* Scholastic/Extra-curricular = *"how selective / rare was this?"*

---

## How to run each mode

### Polish
1. Read the user's line and identify the buried achievement and any numbers.
2. Pick the right verb for the section (cheat-sheet / `verb-bank.md`).
3. Rebuild with the Formula: verb -> outcome (number first) -> method -> scope.
4. If the input has **no number**, do not invent one - produce the best structural rewrite and append
   a bracketed prompt for the real figure, e.g. `...by [X]% - add the real number here`.
5. Offer the rewrite. If the achievement is rich, offer 2 variants (one impact-led, one scale-led).

### Generate
1. Extract the concrete facts: what they did, the tools/method, and every number available.
2. Map to the most relevant section and its verb palette.
3. Produce 1-3 single-line bullets, each a distinct angle (impact / method / scale). Don't repeat a verb.
4. Flag any place a number would strengthen the line and ask the user for it.

### Review & score
Use `references/review-rubric.md`. Score each bullet on the 6 criteria (verb, number-front-loading,
method, length, compression, section-fit), give a /10 and a one-line specific fix per weak bullet.
Be concrete: quote the word to cut or the number to add. End with the 2-3 highest-leverage fixes.

### Full section draft
1. Read `references/section-playbook.md` for that section.
2. Interview briefly for the raw material (role, scope, numbers, outcomes) if not already provided.
3. Group bullets under 1-3 thematic **side-labels** (e.g. *Impact*, *Leadership*, *Process*,
   *Recognition*) - this is how the corpus organises multi-bullet blocks.
4. Order bullets strongest-first; keep each to one line.

---

## Integrity (read this - it matters)

This style rewards numbers, which creates pressure to inflate. Do not invent, guess, or exaggerate
figures, ranks, or scope. If a number is missing, ask for it or leave a clearly marked placeholder.
A precise honest bullet ("Cut reporting time 40%") always beats a vague inflated one. Help the user
find the *real* metric they can defend in an interview - that is the whole point of quantifying.

Keep claims truthful to what the user actually did. Rephrasing for impact is good; misrepresenting
responsibility, seniority, or results is not.

---

## Reference files

- `references/section-playbook.md` - per-section focus, full verb palette, what to quantify, real examples. **Read before drafting.**
- `references/verb-bank.md` - action verbs grouped by function, with corpus frequency, plus the banned-word list.
- `references/quantification.md` - the full quantification toolkit: Indian/intl units, the "N+" pattern, selectivity, before/after.
- `references/gold-examples.md` - curated real bullets per section + before->after transformations + full archetype CVs.
- `references/review-rubric.md` - the 6-point scoring rubric for Review mode.
