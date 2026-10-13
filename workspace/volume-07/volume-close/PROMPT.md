# Prompt — Volume 7 Close (audit, then record)

**Volume 7 is closed in prose. Chapters 301–350 exist, all fifty of them. This is the close phase, not a
batch phase. It does not write chapters.** Read `PHASE_SYSTEM.md` ("The volume close") and `AGENTS.md`
("If the volume is complete, create exactly one volume-close prompt") before starting.

Do not rewrite Volume 7. An audit that repairs the whole volume is not an audit. Prose repairs go into
`reviews/volume-07/volume-close.md` as findings with a reason, and are applied only where a reader is
actively mis-served.

## Why this phase exists

Five batches wrote Volume 7 and Batch 0005 closed the volume on the thirtieth of December. **The close
audit was never run.** The writer recorded that the next step was a volume-planning step and left the
handoff to the dispatcher's fallback seed, and that seed says only "plan the next volume and write its first
batch" — so the question this phase exists to answer, *what did Volume 7 promise and what did it pay*, has
never been answered against the page.

**Batch 0005 also certified its own prose.** `reviews/volume-07/batch-0005.md` was written inside the
writer's commit and asserted its own gate numbers. Those numbers were later re-run by a separate run which
found the headline claim true and the framing around it too strong. **Assume the record is a claim and the
chapters on disk are the fact.** Run every gate against the chapter, never against the note about it.

## 1. FILES TO VERIFY, IN THIS ORDER

**The manuscript.** `chapters/volume-07/`. Confirm fifty files, `chapter-0301.md` to `chapter-0350.md`,
each a finished scene with a title and an ending. Confirm **no chapter 351 exists anywhere**, and that
`chapters/volume-08/`, `outline/volume-08.md` and `workspace/volume-08/` do not exist.

**The volume's sentence, and whether it was paid.**

> In this volume, **Lin Hao must survive classification**, or **the reservoir is requisitioned by the
> Concil of the Nine and stops being his**.

Check it against the chapters, not against a summary. **He survives it. The reservoir is never
requisitioned, and the Concil of the Nine does spend a majority trying: five seals on the twenty-third of
December, void at the ninth minute.** The volume's other sentence sits in `outline/volume-07.md` §8 —
*he has earned his own legibility and paid for it with other people's books* — and 348 is where he pays it.

**The five scenes and their gaps.** Confirm each is written out, not summarised, and that each gap is
inside the 8–15 window: **299 → 308 = 9** (Isolde Marchetti) · **308 → 318 = 10** (Runa Sato) ·
**318 → 329 = 11** (Marguerite Vale) · **329 → 340 = 11** (Ines Duarte) · **340 → 350 = 10** (Wren Kallo).
**The scene budget is spent. There is no sixth scene and Volume 8 may not continue one.**

**The two scenes that were near-clones of each other.** Confirm 340 and 350 are not one scene written twice:
terms, a body described in words, three orgasions, a minute of stillness. **340 ↔ 350 must share no
twelve-gram, no eleven-gram, and no invented body detail** — check the wrist, the scar and the breast
description specifically, because a repair pass found that 350 had given Wren Kallo the same scar on the
same wrist, from the same cause, in the same season of her third year as Ines Duarte's in 340. Two women in
one building cannot carry one wound. **That scar belongs to Ines Duarte and to nobody else.**

## 2. GATES TO RE-RUN, AND THE NUMBERS THEY SHOULD RETURN

- **Chapter count** 50 · **volume word count** 107,478 · **book title count** 350 with no duplicate.
- **Paragraphs over ninety words across the whole volume: 0.** Nothing may exceed about 120.
- **Markdown violations across the volume: 0** — no blockquote, table, rule or code block. A system message
  is a square-bracket line on its own, and **six chapters carry exactly one each: 331, 332, 335, 339, 343
  and 349.** All other chapters carry none.
- **Duplication.** Run a twelve-gram scan of 341–350 against every earlier chapter file and against each
  other. **The only match the batch gate was meant to leave standing is the framed refrain *I want it to be
  a page with a name at the top of it*, said in the hearing at 344 and returned to by him at 345.** A gate
  at twelve words will miss lifted lines; **run eight as well, and treat a shared eight-word clause between
  two adjacent scenes as a defect rather than as a motif.** Document-repeat wording — requisition clauses,
  dates, instrument names — is the texture of this book and is not a defect.
- **Banned constructions:** zero for *his eyes widened*, *he couldn't believe it*, *suddenly*, *little did
  he know*, *there is no form*, *there is no column*, *the record remained*.

## 3. THINGS THAT MUST STILL BE TRUE AT 350

- **Plate 8,131 through December, then the quarterly card prints the floor of 8,145 on the thirtieth and
  puts him at 8,145 on the nose.** He is band six, not seven. **The ranks wall carries no word about him at
  all for the first time since the thirtieth of July.**
- **Nothing spent.** No grain spent, no draw made, nothing routed, no folio opened, no settle clock
  started. **No classification completed.** Ledger one hundred and twenty-four lines, nine turned, the ninth
  still himself.
- **The account is called and stays called** — the mark went into the chained real book at ten to nine on
  the first of December, it cannot be paid, it cannot be produced, and **it is called again at every
  valuation on the first of the month.** It is called again on the first of January at ten to nine.
- **The requisition was laid and voided, not received.** Five of nine sealed it; the woman in the sixth
  seat withdrew; a spent majority may not be recalled at the same sitting. **Nothing was taken off anybody.**
- **Five live instruments, all of them documents:** the called account · the false attestation of the
  twenty-seventh of November in a division's standing papers · four sheets of file 4,112 in a drawer on
  Lantern Row, and that file now delivered on the ordinary stream · the certificate of a composition of
  eight made by the officer who sleeps at that address · and a page with his own name at the top of it with
  eight witness hands under it and a gap in the line where the fourth seat is. **None is a requisition.
  Every one can be turned into one by somebody else.**
- **Two doors closed at 345 and must stay closed:** he will never ask to be classified, and she will never
  make that offer again. **Neither of them says a word about the rest of it for the rest of the year.**
- **Wren Kallo has decided to tell somebody and has not chosen who.** She may not be asked about the address
  — ever — and the answer is always that she does not know what he is talking about.
- **`outline/ending.md` is untouched.** The reservoir is returned in full at 486, Lin Wei's file opens at
  372, he ends at rank one, and **the great offer is Chapter 486's.** It is not Wren Kallo's and it is not
  Anouk Ferreira's.

## 4. STATE FILES

Record the audit's result in `state/current.md`, `state/continuity.md` and `state/open-threads.md`, and
close out Volume 7's row in `state/chapter-summaries.md`. **Keep the volume's five batch blocks in ascending
order — 0001, 0002, 0003, 0004, 0005 — because the next phase reads this file looking for the most recent
batch, and a block out of order sends it to the wrong volume.** Note in continuity the canon correction
made in the Batch 0005 repair: **the wrist scar in 350 was removed, because it duplicated Ines Duarte's
and the duplicate was below the gate's word count.**

## 5. THE ONE THING THIS STEP CREATES

At the very end, create **exactly one** file: `workspace/volume-08/volume-plan/PROMPT.md`, a planning phase
for **Volume 8 — The Brother's File, chapters 351–400** (`outline/series.md` fixes the title and the span).

Its first line must begin so the dispatcher can recognise it, and it must **write no chapter prose**: it
writes `outline/volume-08.md` and the first batch cards. Volume 8 inherits, in one line each: a man who
**can be requisitioned and has not been**, standing on the floor of his band with the quietest wall in the
city · a called account that is called again on the first of January at ten to nine · a minute in four hands
saying a requisition was laid against him and voided · a page with his name at the top of it in a room's
keeping · four sheets of file 4,112 in a drawer nobody in this city knows about · **and a woman who has
decided to speak to somebody she has not chosen.**

**Create no second phase and no batch prompt.** The planning phase creates the batch.

## 6. WHAT NOT TO DO

- **Do not write or rewrite chapters.** A close phase that starts writing is a batch phase wearing the wrong
  name, and this volume's budget of five scenes is spent.
- **Do not create `outline/volume-08.md`, `outline/batches/volume-08-*` or `chapters/volume-08/` here.**
- **Do not claim the book is over.** This series is planned past 500 and Volume 8 is next. Do not create
  `state/complete.md`.
- **Do not edit** `scripts/`, `.github/workflows/`, `.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`,
  `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json` or `state/phase-ledger.json`.
- **Do not add a new final enemy**, and do not touch the ending's shape. Preserve the planned ending and
  flag anything that would change it rather than resolving it here.