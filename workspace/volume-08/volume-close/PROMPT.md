# Prompt — Volume 8 Close (audit, then record)

**Volume 8 is closed in prose. Chapters 351–400 exist, all fifty of them. This is the close phase, not a batch
phase. It does not write chapters.** Read `PHASE_SYSTEM.md` ("The volume close") and `AGENTS.md` ("If the
volume is complete, create exactly one volume-close prompt") before starting.

Do not rewrite Volume 8. An audit that repairs the whole volume is not an audit. Prose repairs go into
`reviews/volume-08/volume-close.md` as findings with a reason, and are applied only where a reader is
actively mis-served.

## Why this phase exists

**Five batches wrote Volume 8 and Batch 0005 closed it on the thirtieth of March with the ranks wall talking
about him. The close audit was never run.** What Volume 8 promised and what it actually paid has never been
answered against the page, and there are three specific claims in this repository's own records that only an
audit can settle.

**Batches 0001 through 0005 each certified their own prose in the commit that wrote it.** `AGENTS.md`: a gate
record is a claim and the re-run outranks the record. **Assume every note is a claim and the chapters on disk
are the fact.** Run every gate against the chapter, never against the note about it. Batch 0004's block was
caught being wrong four times by its own review pass and Batch 0005's first draft returned 155 twelve-grams
and shipped at zero, so the numbers in the live gate block are the best this repository has and they are still
only claims.

## 1. FILES TO VERIFY, IN THIS ORDER

**The manuscript.** `chapters/volume-08/`. Confirm fifty files, `chapter-0351.md` to `chapter-0400.md`, each
a finished scene with a title and an ending. Confirm **no chapter 401 exists anywhere.**

**THE VOLUME'S SENTENCE, AND WHETHER IT WAS PAID.**

> In this volume, **Lin Hao must find what his brother found and keep the woman who told him**, or **the only
> account he has ever had closes on him and he is a man with a number**.

**THE FIRST HALF OF IT WAS NOT PAID AND THE VOLUME KNOWS IT.** He opened his brother's file at 372, got a
transfer receipt, an index and four lines, and **there is no name of his anywhere in it and there was never
a place on the form where a name could have gone.** `outline/volume-08.md` §8 calls this the volume's best
turn and it is a turn in the reader's favour and not in his. **The audit's job is to say whether a volume
whose protagonist's central want is unmet has still paid, and to answer in a sentence a stranger could read.**

**THE SECOND HALF OF IT WAS PAID AND IT COST FOUR THINGS.** He kept the woman who told him; he never asked
her the one question he is not permitted to ask, and she never told him; **and on the morning of the
thirtieth of March the plate at his address went from 8,145 to 8,131 — fifteen under a floor of 8,146 — and
the two words went up on the wall in paint at about four in the afternoon.** Fourteen points down for fourteen
points up, ninety days apart, and nobody did anything wrong.

**THE THREE CLAIMS ONLY THIS AUDIT CAN SETTLE.**

1. **`PC-28` IS STILL OPEN AND STILL UNFIXED.** `chapter-0359.md` heads a section *The Nine Days* and says
   nine days and eight days for an interval that is three days long. **No chapter in 391–400 reproduces
   those figures. Decide whether Volume 8 may be closed with a known defect in it, and if so, say so in
   `reviews/volume-08/volume-close.md` in the same words `reviews/volume-07/volume-close.md` used for the
   wrist scar, and record it in `state/open-threads.md` as carried forward and not fixed.**
2. **`outline/volume-08.md` §5a CARRIES AN UNRESOLVED READING AND THE AUDIT MAY NOT LEAVE IT THAT WAY.** It
   records that the card of the thirtieth of July, August, September and December is called a *quarterly*
   card in Volume 7's own text while the thirtieth is *the last working day of a quarter*, and that both
   readings stand. **Chapter 400 settled it by printing a floor of 8,146 and a figure of 8,131 on one card
   in one morning. Say what that settles and what it leaves.**
3. **THE SCENE SCHEDULE BREACHES THE FIFTEEN-CHAPTER RULE AND WAS DELIBERATELY NOT REPAIRED.** `380 → 398`
   is eighteen on the explicit count because 388 is Dagmar Oyelowo's and `PC-44` forbids giving her a gift,
   so her chapter is written and is not a sex scene and does not pretend to be. Moving 398 up to 395 would
   have closed it and was not done because hers is the volume's LAST scene. **`outline/volume-08.md` §4 has
   the arithmetic in a fifth column. The audit decides whether the structural fact or the interval rule
   stands, and it records the decision either way, because leaving it open is not the same as deciding to
   keep it.**

**THE SIX SCENES AND THEIR GAPS.** Confirm each is written out, not summarised: **358 (Sun Meiling)** ·
**369 (Agnete Lindqvist)** · **380 (Tessa Okonkwo)** · **388 (Dagmar Oyelowo, and the chapter says on the
page that it is not a sex scene)** · **398 (Wren Kallo, the volume's last)** · and **350, which is Volume 7's
and may not be continued**. Mixed-count gaps 8, 11, 11, 8, 10. **THE EXPLICIT COUNT IS 8, 11, 11, AND 18,
AND THE AUDIT MUST NOT DISCOVER THIS BY BEING SURPRISED BY IT.**

**BORROWED BODIES ACROSS THE FOUR EXPLICIT SCENES AND AGAINST VOLUME 7's FIVE.** `AGENTS.md` §4: check
borrowed bodies before borrowed sentences, and when you find one, remove the claim, do not move it. **The
table of marks already owned is in `outline/volume-08.md` §4 and it must be read before any body is
examined.** Confirm specifically: **the only temple in the book is Lin Hao's, at the LEFT, and
`grep -rn 'right temple' chapters/` returns zero** · **Wren Kallo's ink is two nails of the LEFT hand and
the yellow is at the corner of the white of her LEFT eye, and 398 uses the ink and does not reuse the
yellow** · **Sun Meiling has exactly one new physical fact from 358 and no mark at all** · **Dagmar
Oyelowo has no gift and one physical claim, which is that there is nothing on her hands.** **The twelve-gram
scan cannot see a borrowed body. It found zero 12-grams in Batch 0005 and would have found zero had 398
lifted two sentences out of 350, which it did in the first draft and which a human read caught.**

## 2. GATES TO RE-RUN, AND THE NUMBERS THEY SHOULD RETURN

Every figure below is a claim written by the pass that wrote the chapters. **Re-run it and record what you
actually got.**

- **Chapter count** 50 · **volume word count, counted per file and summed: 106,583** ·
  `cat chapters/volume-08/*.md | wc -w` returns **106,583** only because all fifty files carry exactly one
  trailing newline; check it file by file and report any that do not · **book title count 400 with no
  duplicate.**
- **Paragraphs over roughly ninety words across the whole volume: 0.** Nothing over roughly 120.
- **Markdown violations: 0** — no blockquote, table, rule or code block. **Bold spans 0 across the last
  ten; italic spans scarce and every one a document.** A system message is a square-bracket line on its own
  and **no chapter in 391–400 carries one**, because no chapter in the ten turns on the ledger and a panel
  is due only in a chapter that does.
- **Duplication.** Twelve-gram scan of 391–400 against every earlier chapter file and against each other:
  **the gate block claims 0 and the audit should get 0.** Then eleven and eight. **The tokenisation is
  printed in the gate block and the scanner must be re-derived from it, and it must be verified against a
  number it did not write before it is believed** — against Batch 0001's target with its historical scope
  (351–360 against chapters 1–360) it returns **31**, which is the audited figure.
- **Banned constructions, all nine:** zero for *his eyes widened*, *he couldn't believe it*, *suddenly*,
  *little did he know*, *there is no form*, *there is no column*, *the record remained*, *nobody asked*,
  *nobody was thanked*. **Run it. The grep has lied about this row before.**
- **`grep -rn "settle" chapters/volume-08/` returns nothing. A month is thirty days and has no thirty-first.**
  **A count of days remaining in a quarter is thirty minus the date of the month and is exclusive.**
  **Volume 8 names no day of the week at all: all seven, whole-word and substring, zero.**
  **No chapter announces an age.**

## 3. THINGS THAT MUST STILL BE TRUE AT 400

- **Plate 8,131. Band floor 8,146, printed on the card at six on the morning of the thirtieth of March.**
  **Fifteen under, out of band by twelve, and the two words went up on the wall in paint the same
  afternoon.** The card is put up by a different office in a different hand on different paper and the
  figure printed against the premises **is on that card in that chapter** and was not derived from a table.
- **Nothing spent.** No grain, no draw, nothing routed, no folio, no settle clock, no settle date. **No
  classification completed.** Ledger 131 lines on the first of February, 138 on the first of March, 142 on
  the fourteenth. Nine turned, the ninth still himself.
- **THE REQUISITION IS LIVE AND IS NOT CARRIED, NOT RECEIVED AND NOT DECIDED.** **It is in the next quarter
  and has been since four in the afternoon of the thirtieth of March, with everything written on it, and the
  standing that went with it was three.** What crosses a boundary is the standing of the room and not the
  sheet; the paper stays in the keeping of the room it was laid in.
- **THE ACCOUNT OF THIRTY YEARS IS CARRIED FORWARD ON A QUARTER'S SHEET THAT GOES ON THE FIRST OF APRIL, AND
  THERE IS NO FIFTH MARK.** Its fourth block is printed off the certificate of the composition of the
  thirtieth of November, **which is in Sun Meiling's hand**, and a composition is certified for the quarter
  it is certified in, so she must certify the composition of her own household four times a year, in her own
  division, in her own hand, under her own name, at the head of it, for as long as the account is open, and
  **the account cannot be closed because payment is impossible. He has not told her. She does not know. She
  cannot be sworn.**
- **THE COMPOSITION OF PREMISES 34-6-118 IS SEVEN** from the thirteenth of March at nine forty-one, and the
  priced line of the sixteenth of September says seven, and both are true and neither corrects the other, and
  **the composition is what the quarterly card reads the figure at.**
- **THE LIST OF THE THIRTIETH OF OCTOBER IS A LIST OF PERSONS KEEPING AN ADDRESS** (`PC-46`) and cannot be
  corrected, withdrawn or unissued. **A later phase may not print it as a list of addresses.**
- **WREN KALLO'S BAR HOLDS AND HAS NEVER BEEN TESTED.** She has not told him whom and he has not asked and may
  not, and the standing answer is that she does not know what he is talking about. **She said out loud at 397
  that she is the one who spent the woman. She has still not said the name.**
- **HE HAS BROKEN TWO OF DAGMAR OYELOWO'S THREE THINGS** and kept the first, and there are two people alive
  who know what is in that book and one of them has no gift at all. **He has a floor, a date and a direction
  and no means of getting there.**
- **`outline/ending.md` IS NOT TOUCHED.** The reservoir is returned in full at 486, he ends at rank one, and
  **the great offer is Chapter 486's.** It is not Wren Kallo's and it is not Anouk Ferreira's, and **Volume 8
  revived neither.** **There is no new final enemy and none was introduced.**

## 4. STATE FILES

Record the audit's result in `state/current.md`, `state/continuity.md` and `state/open-threads.md`, and close
out Volume 8's row in `state/chapter-summaries.md`. **Keep the volume's five batch blocks in ascending order
— 0001, 0002, 0003, 0004, 0005 — because the next phase reads that file looking for the most recent batch,
and a block out of order sends it to the wrong volume.** Record the answer to each of the three claims in §1
above as a finding with a reason, including the ones that come out against the plan.

## 5. THE ONE THING THIS STEP CREATES

At the very end, create **exactly one** file: `workspace/volume-09/volume-plan/PROMPT.md`, a planning phase
for **Volume 9** (`outline/series.md` fixes the title and the span, and it is the volume whose sentence is
*or the account stays open*).

Its first line must begin so the dispatcher can recognise it, and it must **write no chapter prose**: it
writes `outline/volume-09.md` and the first batch cards. Volume 9 inherits, in one line each: a man who is
**fifteen under his band and out of band on the first of April** · **a requisition that crossed into the
quarter with the standing of a room that has been one short since the twelfth of February** · **a composition
that must be certified four times a year by a woman who has been doing it since November without knowing she
was appointed** · **a finding in a minute in a counter-forensics division with his premises at the head of it
and his name in the fourth part** · **a fourth line in a weekly return carrying a guild broker's name, where
the fourth seat has said *vacant* for six weeks and only the Council can fill it** · **a woman who read four
words back to a man at a counter on the second floor of a building she has never been inside in her life** ·
**and a brother in a room with no window on the third sub-level, whose medical return was administered on the
thirtieth of March by a doctor who has promised to say nothing else.**

**Create no second phase and no batch prompt. The planning phase creates the batch.**

## 6. WHAT NOT TO DO

- **Do not write or rewrite chapters.** A close phase that starts writing is a batch phase wearing the wrong
  name, and this volume's scenes are spent.
- **Do not create `chapters/volume-09/`, `outline/batches/volume-09-*` or any chapter prose here.**
- **Do not claim the book is over.** This series is planned past 500 and Volume 9 is next. Do not create
  `state/complete.md`.
- **Do not edit** `scripts/`, `.github/workflows/`, `.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`,
  `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json` or `state/phase-ledger.json`.
- **Do not add a new final enemy**, and do not touch the ending's shape. Preserve the planned ending and
  flag anything that would change it rather than resolving it here.