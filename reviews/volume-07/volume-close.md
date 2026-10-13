# Volume 7 — Close audit. Chapters 301–350. Run 13 October 2026.

**This is the volume-close audit that Batch 0005 recorded as the next step and did not run.** Batch 0005
closed the volume in prose on the thirtieth of December, wrote `reviews/volume-07/batch-0005.md` **inside its
own writer commit**, and asserted its own gate numbers. The dispatcher then fell back to a generic seed
saying only *plan the next volume and write its first batch*. So the question this file answers — **what did
Volume 7 promise and what did it pay** — had never been put against the page.

**THE RULE THIS AUDIT RAN ON, AND IT IS THE BOOK'S OWN:** `outline/volume-07.md` §9, lesson two — *a gate
record is a claim. Re-run it from outside the pass and let the re-run outrank the record.* Every number below
was produced by command against the chapter files as they stand on disk. Where the recorded number and the
re-run disagreed, **the re-run wins and the record is corrected in this commit.**

**SCOPE: NO CHAPTER WAS REWRITTEN.** Two surgical repairs have been applied to the prose and they are items
**C1** and **C1b** below. **C1 has been through two versions and the first one was wrong** — it kept the
duplicated detail and moved its side, which put an exception into a rule the book states out loud on the
page. **The repair that stands removes the borrowed claim outright, exactly as the Batch 0005 wrist-scar fix
did.** Everything else this audit found was in the record, not in the fiction.

---

## 1. What the volume promised, and whether it paid

> In this volume, **Lin Hao must survive classification**, or **the reservoir is requisitioned by the Concil
> of the Nine and stops being his**.

**He survives it, and the alternative half of the sentence is what the volume is actually made of.** Checked
against the chapters and not against a summary:

- **He is described, on the twenty-seventh of October, against the head of premises 34-6-118 and not against
  the door** (315), with the list of eight persons of reading age in the order of the stair attached and
  issued with it (311, 313, 320). **A described account is administered rather than priced, and the
  administration has not started** (320).
- **The requisition is tabled and voided, not received.** Served on the sixth (342), the reason established
  on the tenth (343), the hearing on the fourteenth (344), the smaller offer refused with an instrument on
  the seventeenth (345), **five seals at thirteen minutes on the twenty-third and the ruling at the ninth
  minute: a spent majority may not be recalled at the same sitting** (346). Four on the sheet after the
  woman in the sixth seat withdrew her own. **Nothing was taken off anybody, and she says so to his face in
  front of eight people** (346).
- **And then, at 348, the thing that made it stick.** He writes four sheets of plain paper in his own hand
  with his own name at the top of the first and eight words at the foot of the last — *I am the man at the
  top of this page and I will answer for it* — and lays them into the keeping of the room where nine people
  sit. **Eight people sign a witness line under him, and there is a gap in the line two fingers wide where
  the fourth seat is.** A requisition names a holder; a page with a name on it makes him the holder.

**The failure condition was therefore never reached.** The reservoir was not requisitioned. **Volume 7 ends
leaving a man who can be requisitioned and has not been, one member short of a majority, with the account
still called** — which is exactly what `outline/series.md` requires before Chapter 372.

**The volume's second sentence, from `outline/volume-07.md` §8 — *he has earned his own legibility and paid
for it with other people's books* — is paid at 348**, where he spends the last shelter he has: a book of his
own with no name at the head of a page has been his protection for six volumes, and on the twenty-ninth of
December he puts his name at the top of one in front of nine people and lets eight other people carry it in
books of their own for four years. **Sun Meiling names the price at half past eleven and he does not argue
with it.**

**AND THE CHAPTER SAYS THE TRADE HAS NO SECOND HALF.** A requisition that failed is still a requisition in
a room's minute, and in about four years a stranger with a folder will read that word and start looking
(346, 347). **He is safer and more findable on the same morning.** That is the volume's argument and it is
stated on the page rather than left to a reader.

---

## 2. The five scenes, and their gaps

All five are **written out, not summarised**. Scene bodies, measured on disk between the `##` headings that
open and close the body, **exclusive of both headings** so the figure is prose and not structure:

| Ch | Whose | Body | Chapter | Gap in | Gap out |
| --- | --- | --- | --- | --- | --- |
| 308 | Isolde Marchetti | 1,538 | 3,758 | 299 → 308 = **9** | |
| 318 | Runa Sato | 2,313 | 3,783 | 308 → 318 = **10** | |
| 329 | Marguerite Vale | 1,107 | 2,631 | 318 → 329 = **11** | |
| 340 | Ines Duarte | 1,448 | 3,900 | 329 → 340 = **11** | |
| 350 | Wren Kallo | 1,621 | 2,938 | 340 → 350 = **10** | |

**Every gap is inside 8–15.** **The lowest scene body in the volume is 1,107 words**, against the roughly
nine-hundred floor `outline/volume-07.md` §9 lesson three sets for a scene that was actually written.

**A note on the convention, so no later phase thinks the record is wrong:** Batch 0005 measured 318 and 329
exclusive of both headings and 340 and 350 inclusive of them, so its 1,452 and 1,626 are four words larger
than the exclusive figures above. **Both conventions land in the same place** — five scenes, every one over
a thousand words, none summarised. 318 and 350 reproduce the recorded numbers exactly under their own
convention.

**[CORRECTED AT THE REVIEW-FIX PASS. This table originally printed 308 as 1,542, which is the figure with the
opening `##` heading counted in, against a header that says exclusive of both headings. 318, 329, 340 and 350
all reproduced exactly under the stated convention and 308 did not. 308 is 1,538 on disk exclusive, which is
the figure now printed. No conclusion moves: the gaps and the ~900 floor are unchanged. A record of a
measurement is still a measurement, and this file was the one place in the volume where that had gone
unre-checked.]**

**A scan for the fade markers §9 lesson three tells a later phase to distrust — *it went on a long time*,
*afterwards* — returns nothing across all fifty chapters.**

**THE SCENE BUDGET IS SPENT. Five scenes, and Volume 8 may not continue one.**

---

## 3. Gates, re-run from outside the pass

Every figure here is from a command against the files after this audit's last prose edit.

```
files            50 files, chapter-0301.md .. chapter-0350.md, no gap in the sequence,
                 no file outside 0301–0350. **No chapter 351 exists anywhere in the repository.**
                 chapters/volume-08/ and outline/volume-08.md are ABSENT and must stay absent until the
                 Volume 8 planning phase creates them. workspace/volume-08/ is NOT absent — this same
                 commit creates its one live prompt, workspace/volume-08/volume-plan/PROMPT.md.
vol 7 words      107,477.  **See the measurement note below — this is the correct figure and
                 `reviews/volume-07/batch-0005.md` had it right.**
book titles      350 chapter files, 350 distinct title lines, **0 duplicates anywhere in the book.**
                 0 over 90 characters. Volume 7: 0 beginning with *What*, 0 built out of
                 *there is no* / *nobody* / *nothing* / *what*, 0 outside 3–12 words.
paragraphs       over 90 words, whole volume: **0**.  over 120 words: **0**.
markdown         blockquote 0 · table 0 · horizontal rule 0 · code block 0.
                 Bold spans 8 and italic spans 91 across fifty chapters; the italics are documents
                 (requisition sheets, marks in a chained book, attested entries), not emphasis.
system messages  **exactly six in the whole volume, one each, in 331, 332, 335, 339, 343 and 349.**
                 No other chapter carries one. None is rendered as bold, italic or an unmarked line.
duplicate paras  exact-duplicate paragraph across two different chapters, volume-wide: **0**.
```

### **MEASUREMENT NOTE, AND IT WILL BITE THE NEXT PHASE**

**`cat chapters/volume-07/*.md | wc -w` returns 107,439 and that figure is wrong.** Thirty-nine of the fifty
files carry **no trailing newline**, so concatenating them merges the last word of each file into the first
word of the next and loses **38 words**. Per-file `wc -w`, summed, gives **107,477** — which is what
Batch 0005 recorded and what the volume actually is. **Always count per file and sum. Do not record a
volume word count from a concatenation.**

### Duplication

**Twelve-gram scan, 341–350 against every earlier chapter file in the book and against each other.**
One cross-chapter match exists in the entire volume, and it is the framed refrain:

> *I want it to be a page with a name at the top of it* — said in the hearing at **344**, returned to by him
> at **345**.

**That is the one match the gate was meant to leave standing, and it is standing.**

**Eleven-gram scan, whole volume, across chapters.** Thirty-two matches. **Six are the same refrain.**
The other twenty-six are document texture: requisition clauses, the address written out, clause wording
(*a described account is administered rather than priced* at 305 and 330), dates, the ordinary stream at
four in the afternoon. **Not one of the twenty-six is a lifted line and none is between two scenes.**

**Eight-gram scan, run because twelve is a floor and not a truth.** The volume-wide result is dominated by
the book's connective tissue — *and I am not going to be the*, *she put her hand flat on the table*,
*in about four years* — which appears in three, four, sometimes sixteen chapters. That is the voice, not
duplication. **The reportable figure is the pair 340 ↔ 350, and it is in item C2 below.**

### Banned constructions

```
his eyes widened 0 · he couldn't believe it 0 · suddenly 0 · little did he know 0
there is no form 0 · there is no column 0 · the record remained 0
```

**Seven of seven at zero across all fifty chapters.**

---

## 4. The two scenes that were near-clones — findings

Batch 0005's own review found that Chapter 350 had given **Wren Kallo Ines Duarte's wrist scar** — same
wrist, same cause, same season of her third year — and removed it. **That repair held and is confirmed on
disk: the scar now exists in Chapter 340 and nowhere else in the volume.** The breast description was also
separated. **340 and 350 now share no twelve-gram, no eleven-gram, no ten-gram and no nine-gram.**

### **C1 — REPAIRED TWICE. The grey temple. The same defect as the scar, one layer down.**

The scar repair caught the wound. **It did not catch the face.**

- **340:** *the lamp caught **the grey at the left temple** that had not been there **three years ago** and had come in with the etches.*
- **350, as Batch 0005 left it:** *working down from **the grey that had come in at her left temple three years ago** to the shape of her foot on the floor.*

**Same side. Same interval. Ten chapters apart. Both in the volume's five scenes.** This is precisely the
class of defect the Batch 0005 review described — *the same wound on a second woman in the same building* —
sitting one clause below every word-count gate, because no shared eight-gram survives the rephrasing. In a
book that runs on the principle that a physical detail means something, a grey temple arriving three years
ago on the same side in the volume's penultimate and final scene reads as a reused stamp.

**FIRST REPAIR, SUPERSEDED: this audit changed the side in 350 to the right temple and called it done.** That
was wrong, and the review-fix pass caught it. The grey temple is **Lin Hao's** cost — `bible/power-system.md`,
*grey at one temple* — and the manuscript fixes the side as the **left** in Ch 4, 5, 25, 26, 38, 57, 72 and
139, and makes its immovability a deliberate beat on the page at 72: *It started at the left temple, where it
has always started, in the exact place it has always been… a man who has paid a price for six weeks at least
expects the supplier to vary the location.* **After the first repair, `right temple` occurred exactly once in
350 chapters.** It also broke the precedent it was citing: the Batch 0005 wrist-scar fix, same defect class,
**removed** the detail outright — *Removed… the scar belongs to Ines Duarte alone.*

**SECOND REPAIR, APPLIED: the borrowed grey is gone from 350 entirely, and the catalogue is re-anchored on a
mark that is Wren's own.**

- **350 now reads:** *working down from **the yellow at the corner of her left eye since the spring** to the
  shape of her foot on the floor.*

That mark is not invented for this repair — it is **already on the page 14 lines above**, in the same
chapter, as a claim rather than a detail: *the white of the left one had been yellow at the corner since the
spring and she had not gone to the Vestry clinic about it and was not going to.* It sits above the shoulders,
so the descent still reads top to bottom, and it is hers. **It also carries the same weight the grey was
carrying in 340** — damage the work has done and the woman refuses to treat — without borrowing Ines's
wound for it.

**`right temple` now occurs zero times in the book and the left temple is the only side in it again.**
**Chapter 350 is 2,938 words, one under the 2,939 the first repair reported.** Its scene body is 1,621.

### **C1b — FOUND AT THE REVIEW-FIX PASS AND REPAIRED. The ink.**

Neither this audit nor the reviewer that corrected it looked one paragraph above the grey.

- **340:** *ink at the cuticles on the first two fingers of **the right hand** that **soap had never lifted in
  eleven years**.*
- **350, as Batch 0005 left it:** *Two of the nails of **her right hand** were stained at the roots with ink,
  and **no soap in this city has ever been able to shift it in eleven years**.*

**Same hand. Same substance. Same refusal of soap. Same duration.** Same pair of chapters, same class, same
lesson — *a physical detail in this book is a claim, not a filler.* And it is **the third instance in the
volume**: Marguerite Vale's scene at 329 already has *her hands had ink at the cuticles that soap would not
lift*, which is why three of Volume 7's five scenes put a Bureau woman's ink under the reader's nose.

**REPAIR APPLIED. 350 now reads:** *Two of the nails of **her left hand** were stained at the roots with ink,
and **she had stopped pretending nine years ago that soap was ever going to lift it**.*

The hand is moved off Ines's, the duration is moved onto **nine years — the figure the chapter itself gives
Wren's division at 316** — and the sentence stops mirroring 340's construction. **Word count unchanged: the
replacement is 31 words and the original was 31.**

**329 IS LEFT ALONE AND THE REASON IS RECORDED.** Its version carries no hand, no duration and no framing, so
it is occupational texture rather than a repeated claim, and 329 is a chapter this audit passed unaltered.
The third instance is logged in `state/continuity.md` so Volume 8 does not add a fourth.

### **C2 — RECORDED, NOT REPAIRED. The scene template.**

`reviews/volume-07/batch-0005.md` already names it: *terms, a body described in words, three orgaslms, a
minute of stillness, tea* — *the single biggest duplication risk in this manuscript.* **Confirmed present
in 340 and 350, and it is the book's scene grammar rather than a two-scene clone.** Every instance differs
in content:

- **Terms.** Both open on terms stated first and in order. **340's five** are *nothing spent · her gift
  used on nobody · I am not impaired · I am not the person you came to because you were frightened · I have
  wanted you since half past seven.* **350's five** are *nothing spent · I am not impaired · my gift is not
  used, not once · nothing in this room is holding either of us · I am not here because you are in trouble,
  and you have to say it out loud.* **Four of the five recur in a different order and the fifth is the
  hinge of each scene, and in each case it is the hinge because the woman made it the hinge.**
- **Three times.** 340 ends on *her hand flat on his wrist keeping the time, which is what an auditor does.*
  350 ends on *her nails in him and said his name twice.* **The one shared eight-word clause in the whole
  pair is `and she came a third time with her`** — and the two completions are different women doing
  different things.
- **The minute.** Both end with a counted minute and then a kettle. **In 340 the minute is tenderness and
  what follows it is a document he has to read for eleven minutes; in 350 the minute is explicitly refused
  as tenderness — *I am not being tender, I am being practical* — and what follows it is the thing she
  cannot keep.**

**The 340 ↔ 350 shared-8-gram count is one, and it is recorded here so a later reviewer does not raise it
as new.** Altering the sequence of a finished scene's climax is outside a close phase's remit and the
completions are materially different. **But Volume 8's writing phases must know the template is the single
largest duplication risk in this manuscript — not the twelve-gram scan, which found nothing, and which the
Batch 0005 scar proves is insufficient on its own.**

---

## 5. Things that must still be true at 350 — verified item by item

| Claim | Status |
| --- | --- |
| Plate **8,131** through December; the card prints the floor of **8,145** on the thirtieth and puts him at **8,145 on the nose** | **TRUE** (349, read on disk: the man from the plate office says *eight thousand one hundred and forty-five* twice, and *on the nose* at 349) |
| He is **band six, not seven** (seven is 8,170) | **TRUE** (349, 339) |
| The ranks wall carries **no word about him at all** for the first time since the thirtieth of July | **TRUE** (349, and 350's last line: *the ranks wall behind her said nothing at all about anybody*) |
| **Nothing spent.** No grain, no draw, nothing routed, no folio opened, no settle clock, no settle date | **TRUE** (349's own system line: *Nothing spent.* Nothing has been spent, drawn, routed or requisitioned in fifty chapters) |
| **No classification completed.** File 4,112, one folio, no second | **TRUE** (320, 336, and `outline/volume-07.md` §7) |
| **Ledger 124 lines, nine turned, the ninth still himself** | **TRUE — and see C3 below, because the page carries a rising count and it is correct** |
| The account is **called and stays called**; the mark went into the chained real book at ten to nine on the first of December; it cannot be paid, cannot be produced; **called again at every valuation on the first of the month, and again on the first of January at ten to nine** | **TRUE** (341, and 346 in the chair's own words: *there is a valuation on the first of January at ten to nine and the line will be called again, and it will be called on the first of February, and it will be called until somebody pays it or somebody produces*) |
| The requisition was **laid and voided, not received**. Five of nine; the woman in the sixth seat withdrew; a spent majority may not be recalled; **nothing was taken off anybody** | **TRUE** (346) |
| **Five live instruments, all documents** — the called account · the false attestation of the twenty-seventh of November · four sheets of file 4,112 in a drawer on Lantern Row and that file delivered on the ordinary stream · the certificate of a composition of eight made by the officer who sleeps at that address · a page with his own name at the top of it with eight witness hands under it and a gap where the fourth seat is. **None is a requisition. Every one can be turned into one by somebody else.** | **TRUE** (`outline/volume-07.md` §8, and each instrument is on the page) |
| **Two doors closed at 345:** he will never ask to be classified, and she will never make that offer again. **Neither says a word about the rest of it for the rest of the year** | **TRUE** — 345, in the chair's own mouth, both, followed by *neither of them said one word about it for the rest of that year* |
| **Wren Kallo has decided to tell somebody and has not chosen who.** She may not be asked about the address — ever — and the answer is always that she does not know what he is talking about | **TRUE** (350's closing beat, and the standing answer standing in three chapters: 316, 342, 350) |
| **`outline/ending.md` untouched.** Reservoir returned in full at 486, Lin Wei's file opens at 372, he ends at rank one, and **the great offer is Chapter 486's** — not Wren Kallo's, not Anouk Ferreira's | **TRUE.** `outline/ending.md` has not been modified since the bootstrap commit. `Anouk Ferreira did not make it` and Volume 7 does not dimnish her: 345 states plainly that the offer she did not make was the one he did not ask for |

**TWELVE OF TWELVE. Nothing in this list needed a repair.**

### **C3 — RECORDED SO IT IS NOT "CORRECTED". The ledger's line count rises, and that is right.**

The count climbs across the volume: **118** in 321, 323, 324 and 327 — the figure Volume 6 ended on at 300 —
then **121** at 339, **122** at 343, **124** at 349, each in a square-bracket system line, each with *nothing
spent* under it.

**This is not an inconsistency and no batch should reconcile it.** Nothing was spent, so no line was
**turned** — the ninth turned line is still himself throughout, which is the fact the volume cares about.
**The number of lines in the ledger is not the number of lines turned in it**, and the book has now said so
three times in system lines while saying *nothing spent* in the same breath. **124 at 350 is correct.**
`state/current.md`, `state/continuity.md` and `outline/volume-07.md` all agree with Chapter 349.

---

## 6. Defects found in the record, and corrected in this commit

**Batch 0005 certified its own prose.** Three of the numbers below were true when they were written and went
stale when the repair pass ran afterwards. All three are corrected here.

### **R1 — `state/open-threads.md`, the live gate block, records Chapter 350 at two different numbers, and both are wrong.**

The word list prints `2925`. The leaver sentence four lines below prints `2,927`. **They disagree with each
other.** Chapter 350 stood at **2,927 at the writer's commit `5e7b7a4`**; the repair pass in `0f326cb` —
which removed the wrist scar and rewrote the breast line — added twelve words, and the gate block was never
re-derived. **The figure was 2,939 when this audit ran and is 2,938 now**, because the review-fix pass removed
the borrowed grey temple from 350 and did not pad the sentence back to a number. Both places now print the
figure that is on disk, with the discrepancy recorded in place so the block does not look like it was always
right.

### **R2 — `state/chapter-summaries.md`, the Volume 7 Batch 0001 block was unlabelled, marked LIVE, and stranded the volume header.**

It was headed `## VOLUME 7 — CHAPTERS 301–310. LIVE. THE SECOND OF OCTOBAR TO THE NINETEENTH.` — **no batch
number on it at all**, and `LIVE`, which has been false since Chapter 341. Worse, the `## Volume 7 — Seven`
volume header sat *below* it, at the head of the Batch 0002 block, so the volume header was stranded in the
middle of the volume's own chapters. **A phase reading this file for the most recent batch would have found
Batch 0005 correctly; a phase reading it for the volume header would have found it in the wrong place.**

**Corrected:** the volume header now sits above Batch 0001, the block carries its batch label, and `LIVE` is
gone. **The five Volume 7 blocks now read 0001, 0002, 0003, 0004, 0005 in ascending order**, which is the
order the next phase needs.

### **R3 — a stale 2,560-character Volume 7 fragment was glued inside the Volume 6 row of the same index.**

Two cells were joined by a stray `||`, and the tail cell is a **complete Volume 7 plan** headed
`7 | Seven | 301–350`, marked **OPEN**, saying *batches 0001–0003 written (301–330)* and naming
**`workspace/volume-07/batch-0003/PROMPT.md` as the one live phase prompt.** No such directory exists, the
volume is closed, and 340 and 350 were both written. **A phase scanning the index for the most recent batch
would have read a Volume 6 row whose tail says Volume 7 is open and points at a dead prompt.** This is
exactly the failure the ordering rule exists to prevent, arrived at from the other direction.

**Corrected: excised.** The live Volume 7 row is its own row. The Volume 6 row's trailing delimiter was also
malformed (`** ||` rather than ` |`) and is fixed, so both rows parse.

---

## 7. The close verdict

**Volume 7 is closed and it paid its sentence.** It is fifty chapters, five batches, five scenes, 107,477
words, and it took a man who had spent six volumes making sure no page in this city had his name at the top
of it and ended the volume with his name at the top of a page, in a room's keeping, under eight other
people's hands. **The reservoir is not requisitioned. The account is called. The wall is quiet, and the
chapter says the quiet is not safety.**

**Its one irreversible decision is 348 and it is clean:** he chose legibility over invisibility, on the page,
in front of witnesses, at a cost named by a woman who is not his ally and is right.

**The manuscript is fit to continue.** **[REVIEW-FIX PASS: this line originally read *One prose word was
changed.* The prose repair at C1 was superseded and has been redone properly — two clauses replaced with two
clauses that belong to Wren — and a third duplicated physical claim, the ink at C1b, was found one paragraph
above it and fixed. Four record defects were corrected here and three more by the review-fix pass: a scene
figure measured against the wrong convention, a cross-reference pointing one item short, and a claim that a
directory was absent in the same commit that created it. `no chapter was rewritten` still holds — no chapter
was restructured, cut or restarted, and the plot is untouched.]** **No
controller file was touched; no chapter was rewritten; no ending was altered; no final enemy was added.**

**THE NEXT PHASE IS A VOLUME-PLANNING PHASE AND IT IS NOT A BATCH.** `workspace/volume-08/volume-plan/PROMPT.md`
is the one file this close creates. It writes `outline/volume-08.md` and the first batch cards. **It writes
no prose, it creates no chapter directory, and the batch it schedules is Volume 8's Batch 0001.**

**THE SERIES IS NOT OVER.** It is planned past 500. Volume 8 is **The Brother's File, chapters 351–400**,
and the great offer is Chapter 486's.