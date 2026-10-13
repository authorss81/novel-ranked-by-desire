# Prompt — Volume 5 Close (after Ch 250): The Auditor's Price

Volume 5 is closed in prose at Chapter 250. **Do not write chapters. Do not start Volume 6 prose. This
is a verification pass with a mechanical hand-off at the end.**

---

## 1. WHAT THIS PHASE IS

Volume 5 ran 201–250 in five batches. Batch 0005 (241–250) shipped on the first of July and closed the
volume on the tenth. Its independent review returned eleven findings and five minors and all sixteen were
fixed; the record is `reviews/volume-05/batch-0005.md` and the reviewer's own log stays at
`logs/batch-0005.review.log`. **Neither is superseded by this phase.** The chapters on disk are the
repaired ones and the numbers below were re-run against them.

A close phase earns its run by proving the volume is finished, not by writing anything new.

## 2. FILES TO VERIFY, IN THIS ORDER

**The manuscript.** `chapters/volume-01/` … `chapters/volume-05/`. Confirm 250 chapters exist, each a
finished scene with a title, a date, an ending. Confirm **no chapter 251 exists anywhere** and that
`chapters/volume-06/` does not exist.

**The volume's five fixed promises.** Check each against the chapters, not against a summary:

1. **Ch 241 is Agnete Lindqvist's scene** — Volume 5's fourth, gap 228 → 241 = 13. Second reading room at
   Cobb Street, one true sentence given voluntarily, nothing compelled, certificate in the next house and
   not in the room. Confirm its 12-gram scan against all 24 earlier scene chapters returns **zero**, and
   that its ground, hand, name-exchange and aftermath are fresh against 205's floor laid with record,
   214's collecting room and 228's night wall.
2. **Ch 246 is Ines Duarte leaving** — true report filed, then a walkout of a flat she is still in. Not a
   death, not a betrayal. Confirm she has not resolved or nearly resolved anything in 231–240, and that
   nobody asks her about it before 246.
3. **Ch 249 is the fifth scene**, gap 241 → 249 = 8. Lantern Row. Confirm its scene scan returns **zero**
   and that **241 ↔ 249 share zero twelve-grams and zero ten-grams** — the two scenes must not be one
   scene twice.
4. **The first of July** — valuation, hundred and thirty-third mark in ink in the broker's own hand at
   nine, Petra at the bottom of the sixty-one steps at ten to nine with the bundle, two hearings in the
   same morning, side board repainted by the monthly crew.
5. **The fourth of July** — dead list up at ten, the account not on it, plate stays lodged, Beatrix stays
   encumbered, the guild's tail stays on the fourth page.

**The escalation.** `outline/volume-05.md` records five steps and a volume-level sacrifice. Confirm each
is on the page and not only in the outline: Ch 217 (he spends, and it costs him the only thing he has),
Ch 224 (he spends his own reliability), Ch 229 (a woman destroys the household's only copy), Ch 246
(opposition as a person walking out), and the volume's sacrifice — Ines's, made deliberately, in public,
in her own hand. Confirm **the irreversible decisions at 217, 224, 238 and 243 are all irreversible** and
that 243's is correctly dated: it is the **first of August** docket refused on the third of July, with
**the twelfth of July** as the date after which the broker will not offer again.

**The volume's promise.** `outline/series.md` line for Volume 5: *Lin Hao must keep Ines Duarte off his
file while she starts wanting to be off her own.* Confirm it is answered and not restated.

## 3. GATES TO RE-RUN, AND WHAT THE NUMBERS SHOULD BE

If any number below disagrees with the disk, **fix the disk or record the disagreement in this phase's
output**. Do not report a number you have not run.

```
files                       chapters/volume-05/ -> 50;  no chapter-0251.md anywhere
titles                      unique across all 250 -> NONE;  over 90 chars -> 0
wc 241-250   2730 / 1928 / 2310 / 1973 / 1875 / 1957 / 2106 / 1884 / 2795 / 2138
markup                      bold / italic / blockquote / table / rule / code -> 0
system panels               0
paragraphs over 90 / 120    0 / 0
exact-duplicate paragraphs  0 at 6+ words, batch and neighbours
nobody 1 (242)   no person 0   He understood 0   He also understood 0
He had woken wanting 4 of 10   He felt 9
weekday                     Thursday 11, all pointing at the sixth;  every other weekday -> 0
meta / fourth wall / ages   0
241 scene 12-gram vs 24 earlier scenes   -> 0 chapters
249 scene 12-gram vs 24 earlier scenes   -> 0 chapters
241 vs 249                  12-gram 0   10-gram 0
intra-batch 12-gram in 3+ chapters       0
cross-batch 12-gram overlaps             290, adjudicated canon beats, listed in the review
```

**A gate that returns zero is a claim to be tested, not a result to be reported.** Read three sentences
around every hit. Batch 0004 was repaired for satisfying a ration by switching to a synonym the regex
does not catch — `no person` thirty times against a reported zero. If a ration looks clean, grep for the
synonym before you believe it.

## 4. THINGS THAT MUST STILL BE TRUE

- **Five debts stand and the pricer is out.** The examination passes to whoever holds the book in about
  four years. The open-ended security with no named holder stands in a public return. The thirty-year
  account stands live. The household stands certified on a figure the index denies. The clinic stands
  counted. **No book in the city will price them now Ines is out of the room with a true document behind
  her.** Confirm all five are named on the page in Ch 250 and not only in the outline.
- **Wren's finding: seventeen days on Hadewig's desk on the tenth, unacted.** The true report: four days
  in the audit intake. Two divisions holding the household without speaking to each other. Derive every
  day from the anchors — the finding went in on **23 June**, the report was filed on **6 July** — and
  check the printed counts, do not read them.
- **Petra has been on no roll since the fourth of June** — thirty-six days on the tenth.
- **The twelfth of July is unwritten and is the volume's forward hook.** Two days past the close. The
  broker's offer does not come round again.

## 5. STATE FILES

Confirm each of these has been brought current and agrees with the chapters. If a fact in state files
disagrees with a chapter, **the chapter wins and the state file is corrected.**

- `state/current.md` — the head block must describe **Batch 0005**, not Batch 0004. It must record the
  irreversible decision as **the first of August docket refused on the third, with the twelfth of July as
  the expiry**, not as a decision about the dead list on the fourth.
- `state/continuity.md` — the three new date corrections (the August docket, the twelfth of July, the
  division entry against Ines) and the retirement of `hearing tail` and of the `Volume Five` / `Volume
  Six` / `first chapter of his life` meta.
- `state/chapter-summaries.md` — an entry for each of 241–250, matching the repaired chapters.
- `state/open-threads.md` — exactly one live gate block, and it is Batch 0005's, with the numbers from
  §3 above rather than the pre-repair numbers.
- `outline/volume-05.md` §6 movement 5 — marked **WRITTEN**, with current word counts, and no new final
  enemy.

## 6. THE ONE THING THIS PHASE CREATES

After the verification, open **Volume 6, Batch 0001** with its own prompt directory and its own detailed
prompt. Volume 6 is **The Broker's Terms, chapters 251–300**, and its sentence is fixed by
`outline/series.md`:

> In this volume, **Lin Hao must call in every debt he owes before the creditors call in him**, or **the
> Vant's books put a price on the reservoir that he cannot refuse**.

The prompt must inherit, and must not re-open:

- **The broker's terms are live and now belong to him.** Ch 243's standing instruction is a standing
  instruction. The first docket it governs is **the first of August**, drawn and marked by the woman who
  wrote it, in the account he has now committed to for the life of thirty years.
- **The debts are five and they are unpriced.** They need a pricer. The pricer is in two rooms above a
  laundry on Lantern Row, on no roll, on her own time, with a fortnight of answering between her and
  being able to refuse a desk where she is the subject.
- **A woman has set a term.** No paper is read to her in her own rooms. He has agreed to it in the dark
  and it cost him the only thing he has. He will break it or he will keep it, and the batch should not
  decide which in its first chapter.
- **Ines still holds an address at Ferrier Street and a name on the cut roll.** She is out of the body and
  in it on paper, and she signs when signing is what it needs.
- **Beatrix's hearing is encumbered and the guild's tail is on the fourth page, with no price left on the
  table to strike it with.** That is the cost he chose in daylight and cannot buy back.
- **Five debts stand, the pricer is out of the room, and the account is examined in about four years.**

The Volume 6 prompt inherits every do-not-open and do-not-close in `outline/volume-05.md` §7 unless
Volume 6's own outline lifts one, and it repeats the whole gate list including the two gates Batch 0004
and 0005 got wrong: **run the 12-gram scan before the 8-word sentence scan, and run it against all
chapters including the current batch**, and **treat any run over ten words as a defect until it has been
read.**

## 7. WHAT NOT TO DO

- Do not write or rewrite any chapter.
- Do not edit `scripts/`, `.github/workflows/`, `.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`,
  `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json`, or `state/phase-ledger.json`. Those belong to CI.
- Do not change the volume's ending, its promise, or the shape of its irreversible decisions.
- Do not open anything on the do-not-open list, in this phase or in the prompt it writes.
- **Create nothing else.** One close prompt already exists. Volume 6 Batch 0001 is the single next
  phase and the self-dispatch workflow will select it.