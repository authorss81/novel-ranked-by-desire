# VOLUME 12 — CLOSE AUDIT · *The Surface* · chapters 551–600

> **This phase writes no prose, creates no chapter, re-dates none, restarts none, and does not touch `outline/ending.md`. `outline/ending.md` is byte-identical to its last commit (`md5 00dbe4ef76e0304c654637aad92081d3`, `git status --porcelain` empty). It wrote no Volume 13, no sixth batch, and no `state/complete.md`. The series is planned past 600.**
>
> **It left three files: this one, and a new live block at the head of `state/current.md`, `state/continuity.md` and `state/open-threads.md`.**

**THE STANDING INSTRUCTION THIS AUDIT WAS RUN UNDER:**

> **A figure nobody re-computes is the figure that is wrong.**
> **A gate row that quotes the prose it is checking cannot catch the prose.**

**AND THE REASON IT RAN AT ALL, IN ONE PARAGRAPH.** Volume 11 closed with five arithmetic failures that four batch gates had certified as passing. Volume 12 then produced two more instances of the same class inside a single phase: a `META … -> 0` gate row that was false against `chapter-0598.md:45` on disk, and a `DUPLICATION` row that classified none of its batch's three largest hits. **Two rows of a live gate block were wrong within a single phase of being written, and both were rows that said `0` or a clean figure.** Every figure below was therefore re-derived from outside the pass that wrote it, with operands printed, and every gate row was re-run rather than read.

---

## 1. THE MANUSCRIPT

Fifty finished files, `chapters/volume-12/chapter-0551.md` to `:0600.md`, one `# ` title line each, all fifty ending `0a`. **93,730 words, counted per file and summed by command, never from a concatenation.** The whole book is **1,358,983** words across 600 files. The volume runs **spine days 1,406 to 1,769** — 363 days elapsed, 364 inclusive — from the twenty-seventh of December of the fourth year to the thirtieth of December of the fifth.

The spine was re-derived **twice, by methods sharing no constant**, directly from the two formulas in `outline/volume-12.md` §5a:

```
METHOD A  a January labelled y = (y-2)*360 + 330 + (d-1);  any other month = (y-1)*360 + off[m] + (d-1)
METHOD B  absolute month index i = (y-2)*12 + 11 for a January labelled y, else (y-1)*12 + pos(m);
          day = 30*i + (d-1)                      — contains no 360 at all
```

**Fifty of fifty dates agree. Zero monotonic violations. Zero interval-sum mismatches.** The `580→581` seam repair holds at **`1,649 − 1,627 = 22`**, and the `589→590` correction holds at **`1,689 − 1,687 = 2`, not four**.

**ONE THING THIS AUDIT GOT WRONG FIRST, AND IT IS RECORDED BECAUSE IT IS THE FAILURE MODE.** The first pass of the spine script used `(y−1)*360 + 330 + (d−1)` for a January, which is the convention §5b explicitly proves impossible, and it put 553 at 1,770 instead of 1,410 and reported **two monotonic violations**. §5b names that wrong convention and says it puts the first of January of year five nine months after the first of February of year five, which is therefore impossible. **A derivation that produces a violation is not a derivation; it is a guess with a decimal point.** It was caught because the check was run against the spine rather than against the prose.

## 2. WHAT THE VOLUME PROMISED AND WHAT IT PAID

The volume's one sentence: **Lin Hao must put two words a city has never been able to read where the city already reads every morning, or the Register ends as one line in one column in one chained book two floors under a sales floor.**

**HE PAID IT, TWICE, AND NEITHER PAYMENT IS THE ONE THE OUTLINE PLANNED.**

At **595** he writes in the office's own hand, on the office's own standing sheet, that **a figure in Ostara may be a figure somebody made up on purpose**, printed by the office itself, with **Emil Brack's name under it**, and beside it the two words off the wall with their meaning plain. That is the volume's last irreversible decision and it is his. It closed the option of the office being the only honest instrument in the city — never in writing anywhere, and true until that morning — and it cost every party with a real claim now standing on a public page beside an admitted inventor in the same hand with no instrument to tell them apart.

At **560**, twenty chapters earlier, he said out loud in a yard of about eleven thousand people that the four lines on that board are the ones he wrote. **582** was the same class of decision and the batch records it as already spent: he said the office's own sentence out loud under the office's own wall, six mornings running, and by 583 the street was saying it three ways and the only true copy was on a corridor board thirty people a day walk past.

**What the volume refused, and refused correctly:** no rise off rank one, no move off the branch night shift, no band, standing, permission or terrace · neither blank box filled or raised, and the figure box blank for the rest of the book · the account figure never printed · `settle` zero in every inflection · no weekday name · no announced age but Agnete Lindqvist's fixed forty-five · Brack right about every fact, thanked by nobody, diminished nowhere and **not defeated anywhere** · Mavis Rooke named in two chapters and shown in neither · the white tile's maker unnamed · no new enemy · no argument about the reach of the return.

## 3. THE SEVEN CLAIMS ONLY THIS AUDIT CAN SETTLE

### CLAIM 1 — THE SIXTH OF MARCH. **YEAR ONE IS TRUE AND THE FIGURE 1,115 IS WRONG. THE CONFLICT IS SETTLED, AGAINST A STATE FILE.**

`state/current.md` §0d.3 handed this forward as *five written chapters and two outline rows say year one, the spine says year four, resolving it means re-dating five chapters across two closed volumes.* **That framing was wrong in its premise, and the audit settles it by re-deriving Volume 11's own spine rather than accepting either side.**

`outline/volume-11.md`:234–243 gives all fifty of Volume 11's dates. Re-derived from §5a:

```
501 1 Feb y1 = 0 · 505 6 Mar y1 = 0*360 + 30 + 5 = 35 · 537 30 Mar y4 = 3*360+30+29 = 1,139
546 6 Oct y4 = 3*360+240+5 = 1,325 · 547 10 Oct y4 = 1,329 · 550 28 Oct y4 = 1,347
FIFTY OF FIFTY DATES RECOVERED, MONOTONIC, ZERO VIOLATIONS.
```

**Volume 11's spine is internally consistent and it puts the sixth of March in YEAR ONE, on day 35.** The four written chapters that say *the first year* — `chapter-0545.md:66`, `chapter-0553.md:79`, `chapter-0584.md:143`, `chapter-0590.md:73` — are **right**, and so is `outline/volume-12.md` §4b:145.

**The error is 1,115.** That is `3×360 + 30 + 5` — the sixth of March computed as though it fell in **year four**. It entered the book in the batch-0004 pass, which recorded it as "the spine says four" and then cut the word *four* out of `chapter-0584.md`'s footer rather than check the anchor. **`chapter-0584.md` therefore currently contradicts itself:** `:143` says *the sixth of March of the first year* and `:147` measures the interval from *one thousand one hundred and fifteen*. The correct subtraction is **`1,663 − 35 = 1,628` days**, which is four years and one hundred and eighty-eight days.

**THE REPAIR IS NOT APPLIED HERE AND THE REASON IS THE SAME ONE THAT KEPT FINDINGS 1–5 OUT OF VOLUME 11'S CLOSE:** fixing it means editing a finished chapter inside a closed batch and re-running the batch that certified it. **THE SETTLEMENT IS RECORDED, THE OPERANDS ARE PRINTED, AND NO CHAPTER IS TOUCHED.** The canon change — *year one is true; 1,115 is withdrawn; 584's interval from the sixth of March is 1,628 days, not 548* — is flagged at the head of `state/open-threads.md`.

### CLAIM 2 — THE HOUSE FORM CHANGED AT CHAPTER 571, UNDER EVERY GATE.

Batches 0001 and 0002 wrote straight ASCII double quotes. Batches 0003, 0004 and 0005 wrote curly typographic quotes. The switch is at **571** and it is invisible to the method this repository has been using.

| | straight `"` | curly `“` |
| --- | --- | --- |
| **551–570** | **1,540** | 0 |
| **571–600** | **0** | across 30 files |
| Volumes 01–11, book-wide | **35,895** | **0** |

**Every volume of the book before Volume 12 uses straight quotes, and Volume 12's first twenty chapters continue it.** **No batch gate could have caught this, because every gate measures its own ten files**, and each of the last three gates reports `0 STRAIGHT QUOTES`, which is true of its own batch and says nothing about the one before it. This is a third instance of the same structural blindness, and it is the clearest one yet: **a gate that measures only its own batch cannot see a change that happened between batches.**

**RECORDED, NOT APPLIED.** Repairing it means rewriting 1,540 quote characters across twenty finished chapters in two certified batches. The correct form is the one 571–600 already uses. A reader in a serial reader or an EPUB sees a typographic seam at chapter 571 and no other symptom, which places it below Finding 1A of Volume 11 — unclosed asterisks, which actively mis-serve the reader — and it is handed forward rather than applied.

### CLAIM 3 — THE 594 SCENE FIGURES. **ALL FOUR COUNTS ARE RIGHT. TWO OF THE FIVE LINE SPANS NAME A LINE THAT DOES NOT EXIST.**

The prompt for this phase states that the 14 October repair was needed because "two of the three rows were wrong and both row labels were mis-mapped." That is true and the repair worked. **This audit re-derived all four counts from the file and they are exactly right. The defect moved into the span column and nobody re-ran it there.**

`chapter-0594.md` has **97 lines**, not 98. It has two `##` headings, at 39 and 79, and no `##` after 79.

| Definition, as `outline/volume-12.md` §9 names it | Line span **as recorded** | Re-derived | Count **as recorded** | Re-derived |
| --- | --- | --- | --- | --- |
| (1) first `##` to last `##`, exclusive of both heading lines | 40–78 | 40–78 ✓ | 725 | **725** ✓ |
| (2) single scene section, inclusive of both heading lines | 39–79 | 39–79 ✓ | 733 | **733** ✓ |
| (3) exclusive of both heading lines, through to end of file | **40–98** | **40–97** ✗ | 1,184 | **1,184** ✓ |
| (3b) the same, to the last prose line before the two footers | 40–93 | 40–93 ✓ | 1,110 | **1,110** ✓ |
| whole file | **1–98** | **1–97** ✗ | 1,824 | **1,824** ✓ |

**`lines 40–98` and `lines 1–98` run one line past the end of the file.** The counts are correct and the spans beside two of them are unreachable. This is the signature defect wearing a different hat: a figure that survived a gate because nobody re-computed it, this time in the column the previous repair added. **REPAIRED in `state/continuity.md` §0b, which is a live state file and is this phase's to correct.** `chapter-0594.md` was not edited and is 1,824 words before and after.

### CLAIM 4 — THE DUPLICATION CLASSIFICATION MIS-DESCRIBES ITS OWN EVIDENCE.

`state/open-threads.md` classifies the corridor-board hit as: *591:89 and 597:9 stay — two renderings of one physical object sixteen days apart.* **Both halves of that sentence are wrong, and neither is visible to a twelve-gram scan, which is why it survived.**

- **`591:89` is the board in the branch corridor off a third court.** He is at the branch; Petra Ilyin stops him there. Three conditions, a drawing pin through the corner, the fourth cut off with a blade.
- **`597:9` is a board in the first division corridor off Cordwain** — a different building, one of the nine boards put up at 569–570, carrying all four conditions with no name on top. **It is not the same object.**
- **`599:19` is back at the branch board**, now lost a second corner to the damp.
- **The interval is `1,732 − 1,695 = 37` days, not sixteen.**

So there are **two objects sharing a staging**, not one object seen twice — and the staging echo (a drawing pin through a corner, about thirty a day past it, about two who stop) is exactly the class §4d warns a twelve-gram scan cannot see. **The correction is made in `state/open-threads.md`.** The duplication finding itself still stands: `599:19` is a fourth *state* of the branch board and not a fourth rendering, the fourth condition is still cut off and still unrestored, and that is the right repair.

### CLAIM 5 — A GATE ROW CERTIFIES AN ABSENCE THE FILE CONTRADICTS.

`state/open-threads.md` states, in the batch-0004 live block, that **"Mavis Rooke's hand-flat [is] absent from all ten files"**, and repeats it in the batch-0003 block as **"Mavis hand-flat nowhere (third straight batch — standing decision)."**

`chapter-0584.md:75` reads: **"At about half past one she put both her hands flat on the table behind her…"** That is inside the volume's second-to-last scene, and **`outline/volume-12.md` §7's card 584 explicitly lists "Mavis Rooke's hand-flat" among the stagings that must be absent from the chapter.** §4d's Mavis row adds that a second use of the hand-flat in 551–600 "is a decision that must be recorded in the state file, not a gesture." **It was recorded as a prohibition and not as a decision.**

The honest distinction: Mavis's at `chapter-0547.md:86` is a *single* hand put flat, carried by her attributive signature — *the hand of somebody who had not stopped and had stopped*. The one at 584 is *both* hands bracing, mid-scene, and belongs to the manuscript's long register rather than to Mavis. **The construction is the same and the certification is unqualified, so the certification is false.** Recorded, with the distinction drawn, and the state row corrected. Not repaired on the page.

### CLAIM 6 — OPEN ITEM 5, THE CONTRACTION. **THIS AUDIT DISAGREES WITH THE DEFENCE, AND SAYS SO.**

Batch 0005 disclosed that eight of ten chapters sit below the 1,800 guide floor and that three consecutive batches have breached it, and defended it: *nothing was padded, because these chapters are short because they are one afternoon or one street, and padding them would be the worse defect.*

**The disclosure is honest. The defence does not survive measurement, and the prompt for this phase asked for a judgement rather than a disclosure.**

| movement | chapters | mean words | mean **dialogue exchanges** | mean paragraphs |
| --- | --- | --- | --- | --- |
| one, *Published* | 551–560 | 2,195 | **24.7** | 54.2 |
| two, *Borrowed* | 561–570 | 2,662 | **52.3** | 66.8 |
| three, *Countersigned* | 571–580 | 1,408 | **7.9** | 28.0 |
| four, *Cross-Read* | 581–590 | 1,754 | **8.5** | 39.4 |
| five, *Quoted* | 591–600 | 1,354 | **10.2** | 32.8 |

**Volume 12's mean is 1,874 words — the lowest of any volume in the book, 152 below Volume 9's 2,026 and roughly 400 below Volumes 1–8 and 11. Twenty-five of its fifty chapters are below the floor, the worst count in the manuscript.** But the word count is not the finding. **The finding is that dramatic density collapsed by a factor of four to six at chapter 571 and never recovered.** Movement two's quarter-end runs 28 exchanges across 51 paragraphs; movement five's runs 5 across 32. Movement two's scene chapter has 129 exchanges and 150 paragraphs; movement four's has 16 and 68.

**The defence does not hold, because the unit sizes did not change.** Chapter 562 is one court room and one counter and runs 48 paragraphs at 2,091 words. Chapter 588 is one passage and one pencil and runs 31 paragraphs at 1,477. **A one-room chapter in movement two is twice the size of a one-room chapter in movement four, and the difference is not the room.** What changed at 571 is the *form*: movements one and two dramatise their beats and movements three, four and five report them.

I checked the last chapter against its card to be sure the beats were at least present. **They are.** `chapter-0600.md` carries every promise the card makes — the empty tray, 852 unmoved, the sheet out at four, ninety days and one year and half a year with their operands, the lane's 1,888 mornings printed once, the office at fifty-eight months and twenty-nine days, the verdict in his own hand, Brack not defeated, the tile unnamed, January shut like a chained book. **Nothing is missing. Everything is shorter than it needed to be, and it is short because it is told rather than lived.**

**THE VERDICT: no chapter was padded and none should have been, and that half of the defence is correct and stands. But leanness is not the same as compression, and the volume's last thirty chapters are compressed. Nothing here is a missing plot beat; it is a book that stops dramatising halfway through itself.** That is a judgement about a closed volume and it is recorded as one, with the numbers, so that the Volume 13 planner inherits it as a fact rather than as a mood.

### CLAIM 7 — THE ABSENT REVIEW LOGS, RE-DERIVED RATHER THAN INHERITED.

`logs/batch-0003.review.log` **is not in the repository.** `logs/batch-0004.review.log` **is a writer transcript, not a review** — line 1 reads `! agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent` and line 3 reads `> novel-writer · space-bunny-free`. The review phase dispatched a subagent as a primary agent and re-ran the writing phase against its own output. **`logs/` contains three files, none of them a batch review.**

Both verdicts were therefore re-derived from the chapters. **Batches 0003 and 0004 hold.** Their repair claims are visible on the page: the 574 scene was rewritten and now shares zero 8-grams with 536; 584's tenure reads *two years* with its derivation; 590's recap is seven lines and it has eleven exchanges with the night man; 573 dramatises the provenance instead of summarising it; 571 prints the zero-day interval once and correctly; the 580→581 seam and the four-days-to-two-days correction both stand. **The repairs are real whether or not the log exists.** What does not survive is the phrase *reviewed*: `AGENTS.md`'s gate line **"a reviewer has checked the result"** has been satisfied, for those two batches, by a writer re-deriving its own figures. `scripts/`, `.github/` and `opencode.json` are controller files and were not touched.

## 4. THE FIVE SCENES, THEIR GAPS, AND THEIR AXES

### 4a. THE GAP TABLE, RE-RUN, WITH BOTH COLUMNS BESIDE EACH OTHER

| Chapter | Whose | Her own last scene | From the previous scene in the book | From her own last scene |
| --- | --- | --- | --- | --- |
| 546 | Agnete Lindqvist. Volume 11's last. | 369 | — | — |
| **554** | **Hanneke Ruis** | **none on record — she has never appeared in a scene chapter anywhere in this book** | 554 − 546 = **8** | there is no gap to measure |
| **564** | **Agnete Lindqvist** | 546 | 564 − 554 = **10** | 564 − 546 = **18** |
| **574** | **Beatrix Halm** | 536 | 574 − 564 = **10** | 574 − 536 = **38** |
| **584** | **Ines Duarte** | 505 | 584 − 574 = **10** | 584 − 505 = **79** |
| **594** | **Tessa Okonkwo** | 515 | 594 − 584 = **10** | 594 − 515 = **79** |

**CADENCE, RE-RUN: 8, 10, 10, 10, 10. Nothing under eight, nothing over fifteen, at the floor on the first interval.** ✓

**PER-WOMAN, RE-RUN: none on record, 18, 38, 79, 79. NOT ONE OF THE FOUR THAT CAN BE MEASURED IS IN THE EIGHT-TO-FIFTEEN BAND AND NO FILE IN THIS REPOSITORY MAY SAY ONE IS.** The three that are 79 are the same number and it is not a coincidence: Ines's last scene was Volume 11's first and Tessa's its second, and neither woman has had one since. **This column is reported and is not certified, and the certification was withdrawn once already and is not replaced with a softer version of itself.**

### 4b. EVERY MEASUREMENT, PRINTED UNDER THE THREE DEFINITIONS §9 NAMES

| Ch | first `##` to last `##`, **exclusive** | single scene section **inclusive** | exclusive, through to end of file | exclusive, to last prose line | whole file |
| --- | --- | --- | --- | --- | --- |
| **554** Hanneke Ruis | 3,451 | 3,555 | 3,722 | 3,633 | **3,730** |
| **564** Agnete Lindqvist | 4,803 | 4,816 | 5,616 | 5,354 | **5,622** |
| **574** Beatrix Halm | 2,128 | 2,140 | 2,895 | 2,833 | **2,898** |
| **584** Ines Duarte | 1,436 | 1,439 | 3,020 | 2,946 | **3,022** |
| **594** Tessa Okonkwo | **725** | **733** | **1,184** | **1,110** | **1,824** |

**The first four rows are re-measured from disk in this audit and every closing boundary is named.** 554 has four `##` headings and closes on the fourth; 564 has seventeen and closes on the seventeenth; 574 has four and closes on the fourth; 584 has two and closes on the second; **594 has two and closes on the second with no `##` after it, so its scene section and its scene proper are the same span.**

**THREE OF THE FIVE SCENES LEAVE THE 1,800–2,700 BAND AND EVERY ONE HAS A REASON RECORDED — EXCEPT ONE.** 554 is 3,730 and `state/chapter-summaries.md`:61 says why. 564 is 5,622 and `:605` says why. 574 is 2,898 and `:582` says why. 584 is 3,022 and `:555` says why — **though `:555` still prints it as 3,013, a stale figure from before the repair; the file is 3,022.** **570 is 2,712, which is twelve words over the ceiling, is not a scene, and has no reason recorded anywhere.** §4c of the outline requires one for any chapter that leaves the band. Recorded as a gap; the twelve words are not a defect and the missing sentence is.

### 4c. THE TEMPLATE AXES, AND THE FOURTH WALL

| Ch | Axis broken | Carried by | Named by anybody? |
| --- | --- | --- | --- |
| 554 | **the counted minute** | the counting room's rule: the book goes on the shelf at a quarter to five and comes off it on the first and may be read on the second by one person | **NO** |
| 564 | **the terms** | the yard's rule, one thing each, the last one last, used this time against the woman who brought it | **NO** |
| 574 | **the body described in words three times** | the division's rule: what the round reports is what was felt, in order, and it may not go back and be improved | **NO** |
| 584 | **the quiet** | an audit room at night, and a page that is open does not get put down for anything | **NO** |
| 594 | **the voice** | nobody on a rota says out loud what they are carrying, and the woman who takes it off people does not tell them and they do not ask | **NO** |

**THE FOURTH-WALL GATE, RE-RUN FOR ALL FIFTY FILES AT ONCE, NOT PER BATCH: the primary class 0 · the widened class including `manuscript` 0 · the extension class 0 · `opposition` 0.** The 598 repair holds: *the two words in paint on the wall behind the lane are aimed at a rule that works and not at a man who could be reasoned with or frightened.* No character names a scene, an axis, a chapter, a volume, a page or her own performance anywhere in 551–600.

**MECHANISMS, AGES, AND THE SEPARATE REGISTERS.** No compulsion, sedation, exhaustion, toxin, restraint, psychic contact, trance or seal is the mechanism of any of the five. Every sexual character is an adult. Violence and sex stay in separate registers — 564's crowd and 574's division are not foreplay and neither is turned into one. **Eleven age probes and a bare `aged` sweep return zero; the one fixed age printed in the whole book is Agnete Lindqvist's forty-five.** Hanneke Ruis is given no age and no mark in her one scene or in seven chapters across two volumes.

## 5. BORROWED BODIES AND STAGINGS, READ AGAINST §4d BEFORE ANY EXAMINATION

**§4d was read first, and the rows that matter were checked by name:**

| §4d row | Re-run | Result |
| --- | --- | --- |
| Lin Hao, `right temple` | `grep -rio 'right temple' chapters/` | **0 across all 600 chapters** |
| Ines Duarte, `cuticle` | `grep -rlio 'cuticle' chapters/` | **4 files — 329, 340, 404, 446 — unchanged** |
| Hanneke Ruis, no age and no mark | age probes + mark sweep in 554 | **0** |
| Agnete Lindqvist, no grey, temple, hand-mark, eye or ink | sweep in 564 | **0**; her 546 staging is not restaged |
| Alma Quayle's seated paperwork on the knees, with the clock | `paperwork on her knees`, `since about twenty to` | **0 across 551–600** |
| Dagmar Oyelowo, `PC-44` | sweep in 551–600 | **0 appearances.** Not on the schedule, not written as a scene |
| Beatrix Halm, Tessa Okonkwo, Runa Sato, Petra Ilyin, Isolde Marchetti, Nadia Ferrous | check the page before planning a body | no new mark on any woman; Tessa's stippling kept and nothing added to it |
| Mavis Rooke's hand-flat | sweep | **CLAIM 5 — see above.** The certification was false |
| Margit Roon, pen down flat | sweep | 2 uses, both Wenna Raut's own stated habit, `chapter-0551.md:111` and `:0573.md:45`, each carrying *which she does about twice a day* |
| Sela Voel, no deed | 551–600 | 0 appearances |
| Hanneke Ruis's second word, *carried forward*, not put into a street | 583 | **correctly withheld** — the street produced three versions of the office's two words on its own |

**The man with the broom has no name, no mark, no age and no second conversation. The white tile has no maker. Otho Pearse is never called *Ostho* — `grep -rio 'ostho' chapters/` is 0 — and is never shown counting the board.**

## 6. THE ARITHMETIC — WHAT PASSED AND WHAT FAILED

### 6a. EVERY FIGURE THAT PASSED, WITH ITS OPERANDS

**SEVENTY-THREE DERIVED FIGURES RE-RUN, ZERO FAILURES.** The spine at fifty dates; every batch interval; the four quarter-ends and their ordinals sixteenth through twentieth; every ninety-day interval; `1,769 − 1,409 = 360`; `1,769 − 1,589 = 180`; the lane's `1,769 − (−118) + 1 = 1,888`; the office at `1,406 = 30 × 46 + 26` and `1,769 = 30 × 58 + 29`; the seam `1,406 − 1,347 = 59` and `1,649 − 1,627 = 22`; the two October anniversaries at `247 + 360 × 4 = 1,687` and `1,329 + 360 = 1,689`, `1,689 − 1,687 = 2`; the scene gaps; and every interval any of the fifty chapters prints in a footer, parsed from the page and summed.

**THE SPAN, RE-DERIVED:** `1,769 − 1,406 = 363` days elapsed, `364` inclusive. **THE BATCH INTERVALS, EACH SUMMED AND CHECKED AGAINST ITS OWN ENDPOINTS:**

```
0001 551-560   3 1 1 5 3 3 3 5 9   = 33   and 1,439 - 1,406 = 33   seam 551-550 = 59
0002 561-570  13 11 11 10 11 8 9 13 1 = 87   and 1,530 - 1,443 = 87   seam 561-560 =  4
0003 571-580  10 20 10 10 9 10 10 10 8 = 97  and 1,627 - 1,530 = 97   seam 571-570 =  0
0004 581-590   6 7 1 7 9 1 5 2 2     = 40   and 1,689 - 1,649 = 40   seam 581-580 = 22
0005 591-600   5 6 6 6 4 10 10 17 10 = 74   and 1,769 - 1,695 = 74   seam 591-590 =  6
```

**THE LANE'S FIGURE IS PRINTED ONCE AND ONLY ONCE.** `grep` for it across 551–600 returns **chapter 0600 only**, with operands, at line 37. It is printed nowhere else in the two volumes. At 550 the figure is 1,466 and it appears once there too.

**THE WORD BANK, COUNTED PER FILE AND SUMMED, NEVER FROM A CONCATENATION:**

```
0001  21,947   0002  26,625   0003  14,076   0004  17,543   0005  13,539
VOLUME 12  93,730
```

**All four recorded figures re-derive exactly, including batch 0005 at 13,539 after the 14 October repair and 13,481 before it.**

**THE QUARTERLY FIGURES, RE-RUN FROM THE PAGE:** 551 and 552 *entered: eight hundred and forty-one*, sixteenth quarter · 566 *eight hundred and fifty-two*, seventeenth, **the first move in four quarters** · 576, 586 and 600 *eight hundred and fifty-two unmoved*, eighteenth, nineteenth, **twentieth**. **THE PHRASE *count of deeds* APPEARS ONCE IN FIFTY CHAPTERS, AT `chapter-0586.md:71`, and it is the misreading: *the figure at the top of the page is not a count of deeds and nobody in this city who is right about anything has ever said it is.* No character who is right asserts it.** ✓

**THE ACCOUNT:** `grep -rioE '8,1[0-9][0-9]|two hundred and eleven thousand|211[, ]?840' chapters/volume-12/` → **0**. No floor, no ledger total, no running balance in grains. `settl` → **0 in every inflection** across all fifty files.

### 6b. EVERY FIGURE THAT FAILED — FOUR, ALL WITH OPERANDS, NONE WITH ANY

---

**FINDING A — `chapter-0553.md:23` IS THE WRONG LINE, AND THE SAME WRONG MULTIPLICATION IS IN VOLUME 11 AT A LINE NO OPEN ITEM NAMES.**

Every state file records this defect as `chapter-0553.md:23`. **The defect is at `chapter-0553.md:63`.** Line 23 is a paragraph about the temperature of a room.

> `chapter-0553.md:63` — *Thirty years is three hundred and sixty days multiplied by ten.*

**Thirty years is 360 × 30, not 360 × 10.** And the identical sentence stands at **`chapter-0544.md:25`**, in Volume 11:

> `chapter-0544.md:25` — *Thirty years is three hundred and sixty days multiplied by ten, and four times a year is four in each of them, and thirty multiplied by four is one hundred and twenty…*

**Volume 11's close audit ran five arithmetic checks and found five failures, and this is a sixth that it did not find, because it is a multiplication and every check in that audit was a subtraction.** It is carried in no open item anywhere in this repository. **A carried defect that names one line when there are two is a defect that cannot be repaired by following it.**

**NOT APPLIED. It is one word in each of two finished chapters in two closed volumes.**

---

**FINDING B — `chapter-0570.md:169` PRINTS *A YEAR AND THREE MONTHS AGO* FOR AN EVENT THAT CANNOT BE LOCATED, AND THE ONLY LOCATABLE YARD IS NINETY-ONE DAYS AWAY.**

> `chapter-0570.md:169` — *…he said so out loud in a yard a year and three months ago, and about nine hundred people in that yard told him he was wrong…*

The outline's card 570 attributes the same interval. **No scene in Volumes 11 or 12 matches it.** The yard scene in this volume is `chapter-0560.md`, the thirtieth of January of year five, spine day 1,439, where he says yes out loud — and 570 is spine day 1,530, so **`1,530 − 1,439 = 91` days**, which is three months and one day, and that yard holds about eleven thousand people rather than nine hundred. `chapter-0560.md:91` in fact prints that *nobody in that yard said anything about his sentence being narrow*, which is the opposite of what 570 attributes to it.

**THE INTERVAL IS NOT GUESSED AT.** Guessing it would be a second invented date on a page that already carries one. **RECORDED AS A DELIBERATE OPEN, FLAGGED IN `state/open-threads.md`, WITH THE ONE FIGURE THAT IS DERIVABLE — 91 DAYS — PRINTED BESIDE IT SO THAT A LATER PHASE IS NOT LEFT WITH NOTHING.**

---

**FINDING C — THE SET B PROBE BANK IS DESCRIBED AS UNAMBIGUOUS AND IS NOT, UNDER ITS OWN STATED METHOD.**

`state/continuity.md` §0b publishes Set B as *the unambiguous twenty, i.e. the terms that are not ordinary English anywhere else in this manuscript*, and counts it **by substring, case-insensitive**.

> **`semen` is a substring of `advertisement`.**

`chapter-0565.md` contains the word *advertisement* twice, at lines 119 and 121, and scores **two Set B hits** under the published method. **It is the only false positive, and it is enough: the bank is not unambiguous, the gate row that reports its counts is not reproducible as described, and 565 is a chapter in which nothing explicit happens.**

**Word-boundary (`\bsemen\b`) removes it and the score falls to zero.** Re-run at word boundary across the volume: **574 → 3, 584 → 3, 594 → 4, and every other chapter → 0.** **The five explicit passages are 554, 564, 574, 584 and 594, and there is no second one.** ✓

**THE METHOD IS CORRECTED IN THE LIVE BLOCK.** This is the third time this repository has published a probe without stating that its method is what makes it meaningful, after Volume 11's Set A and batch 0003's §0c bank.

---

**FINDING D — `chapter-0570.md` IS TWELVE WORDS OVER THE CEILING AND HAS NO REASON RECORDED.**

§4c: *a scene chapter may leave the 1,800–2,700 band and must say why in the state file.* **570 is 2,712, is not a scene, and no state file records why.** 554, 564, 574 and 584 all have their reasons. **This is a gap in the record and not a defect in the prose** — twelve words is not a reader's problem — **and it is recorded because a gate that says nothing is indistinguishable from a gate that passed.**

## 7. THE RE-RUN — EVERY ROW OF THE LIVE GATE BLOCK, PLUS THE ROWS IT DID NOT HAVE

**Run from outside the pass that wrote it. Let the re-run outrank the block. Volume-wide, not per batch — and that distinction is the whole of Finding B in Claim 2.**

```
FILES            50 files, 551..600. diff against `seq 551 600` EMPTY. 600 files book-wide.
                 ONE `# ` title line in every file. ALL FIFTY END 0a.
TITLES           `grep -rh "^# " chapters/ | sort | uniq -d | wc -l` -> 0 ACROSS ALL 600.
                 THE TEN OF 591-600 MATCH outline/volume-12.md §10 BY WHOLE-LINE STRING: 10 OF 10.
                 ROW ADDED BY THIS AUDIT: the same check run against **all fifty** of §10,
                 which is what the gate had not done. -> 50 OF 50 MATCH, 0 MISMATCHES.
                 Word lengths 3 to 9. Char lengths 19 to 37. None begins *What*.
                 None built out of *nothing* / *nobody* / *there is no*. Zero duplicates.
BANK             COUNTED PER FILE AND SUMMED. NEVER cat *.md | wc -w.
                 0001 21,947 | 0002 26,625 | 0003 14,076 | 0004 17,543 | 0005 13,539
                 TOTAL 93,730. All four recorded figures re-derive exactly.
                 25 OF 50 BELOW THE 1,800 FLOOR — THE WORST COUNT IN THE BOOK. See CLAIM 6.
                 5 ABOVE THE 2,700 CEILING: 554 (scene) 564 (scene) 570 574 (scene) 584 (scene).
PARAGRAPHS       2,411 prose paragraphs across the 50 files, headings and italic footers skipped.
                 **0 OVER NINETY WORDS. 0 OVER ONE HUNDRED AND TWENTY. 0 ODD QUOTATION-MARK
                 PARAGRAPHS.**
                 ***ROW ADDED BY THIS AUDIT, BECAUSE THE EXISTING ONE ONLY MEASURED ITS OWN BATCH:
                 THE HOUSE FORM CHANGED AT 571. 1,540 STRAIGHT QUOTES IN 551-570, 0 IN
                 571-600, AND 35,895 STRAIGHT QUOTES IN VOLUMES 01-11. SEE CLAIM 2. ***
META             PRIMARY CLASS 0 ACROSS ALL FIFTY. WIDENED INCLUDING `manuscript` 0.
                 EXTENSION CLASS 0. `opposition` 0. The 598 repair holds.
WEEKNAMES        Seven names whole-word and by stem, across all fifty -> 0.
                 `sat` and `sun` excluded as the verb and the name, correctly.
AGES             Eleven probe forms plus a bare `aged` sweep, plus spelled-out spans and
                 `year [1-9]\d\d` -> 0. Nine printed years, all spelled-out in italic footers
                 and all in the form *of year five*, which is a date and not a year number;
                 the method is now stated so the row can be re-run at all.
                 Agnete's forty-five is the one fixed age in the book.
ARITHMETIC       SPINE 1,406-1,769 RE-DERIVED TWICE BY METHODS SHARING NO CONSTANT.
                 50 of 50 dates agree. 0 monotonic violations. 0 interval-sum mismatches.
                 **73 DERIVED FIGURES RUN, 0 FAILURES.** The seam (22) and the two-day
                 anniversary correction (2) both hold.
QUARTERLY        552 sixteenth / 566 seventeenth / 576 eighteenth / 586 nineteenth /
                 600 twentieth, all on the page and all correct. 841, 841, 852, 852, 852.
                 *count of deeds* appears ONCE and is the misreading. Every quarter interval 90.
ACCOUNT          8,1xx 0. two hundred and eleven thousand 0. 211,840 0. settle 0 in every
                 inflection. NO FLOOR, NO LEDGER TOTAL, NO RUNNING BALANCE.
RT / BODIES      right temple 0 book-wide. cuticle 4 files book-wide, unchanged.
                 ostho 0. Mavis Rooke 3 occurrences, all in 587 and 588. Nobody-thanks family
                 5 files book-wide, none in Volume 12. See CLAIM 5 for the false absence.
HEADINGS         One `# ` per file. 208 `## ` across the volume. NO duplicate `##` inside any
                 file. No heading names the chapter's turn. None built on nothing/nobody.
                 ROW ADDED: `## What Is On It` occurs in three chapters (554, 556, 569).
                 Recorded as an observation, not a breach — the rule is within a file.
MARKDOWN         Blockquotes 0. Tables 0. Rules 0. Fences 0. Bold 0.
                 Single-asterisk markers EVEN in all fifty files, 0 odd.
                 **SYSTEM PANELS: ONE IN FIFTY, AT `chapter-0566.md:21`, in square brackets
                 on its own line, not bold and not italic. Volume budget five, one spent,
                 four unspent. *** ROW ADDED: the panel count is reported volume-wide, not
                 per batch, for the reason in Claim 2.
DUPLICATION      12-GRAM FIRST against all 600 files, body-only (headings and italic footers
                 stripped), token-normalised. THEN 11 AND 8. EVERY HIT CLASSIFIED BY HAND.
                 **INSIDE 591-600: NO PAIR SHARES A CONTIGUOUS TWELVE-GRAM RUN LONGER THAN A
                 SINGLE WINDOW. The largest residual run anywhere touching Volume 12 is ONE
                 twelve-gram.** Sixteen such windows survive inside 591–600 and all sixteen
                 are canonical facts: the two words at the height of a name on a plate; the
                 arithmetic footer stems §5a requires; Brack's offer and his eleven books with
                 the date and the weather; the rota's four names and its hours; the rule that
                 nobody on a rota says out loud what they are carrying; 852 unmoved; and the
                 printed instrument at 595/596, which §0z classifies deliberately as a hand
                 writing a document and a clerk reading it back four days later.
                 **AGAINST THE OTHER 590 FILES: 0 RUNS OF 8+ GRAMS AT TWELVE-GRAM, 0 AT
                 ELEVEN-GRAM, 0 RUNS OF 5+ GRAMS AT EIGHT-GRAM.**
                 `chapter-0594.md` against `chapter-0515.md`: 0.
                 ***THE THREE CLASSIFICATIONS THE PROMPT NAMED, RE-VERIFIED AND NOT INHERITED:
                 THE PRINTED WORDING STANDS VERBATIM AT 595:41 AND 596:15 AND NOWHERE ELSE IN
                 551-600, AND 591:37 IS BRACK'S PROPOSAL IN HIS OWN WORDS AND MAY NOT BE
                 QUOTED AS THE PRINTED TEXT; THE CORRIDOR BOARD IS AT 591:89, 597:9 AND
                 599:19, AND THE CLASSIFICATION OF THE FIRST TWO IS WRONG — SEE CLAIM 4. ***
SCENES           ONE IN 591-600, AT 594. All five measured under §9's three definitions in §4b.
                 Set B at word boundary: 574 3 · 584 3 · 594 4 · all others 0.
                 ***THE THREE COUNTED FIGURES AT state/continuity.md §0b RE-DERIVE EXACTLY AND
                 TWO OF THE FIVE LINE SPANS DO NOT EXIST. SEE CLAIM 3. ***
STILL OPEN       Lin Wei 0. B103 0. the second folio of 4,112 0. settle 0. the account figure 0.
                 right temple 0. Nobody argues the reach of the return, in or out. Nobody says
                 whether the account belonged to the unrecorded. Nobody names the white tile's
                 maker. Both boxes still blank. Mavis Rooke 0 in 591-600 and 3 book-wide in
                 587-588 only. Perrin Sowe unforgiven and undiscussed. Dagmar Oyelowo absent.
                 Ines's four questions unanswered. Sowe alive. Ferreira alive. Adeyemi is
                 Registrar of Unrecorded Merit and is called nothing else.
VOLUME           BOTH BOXES BLANK AT THE END OF 600. THE FIGURE BOX BLANK FOR THE REST OF THE
                 BOOK. THE LANE'S 1,888 MORNINGS PRINTED ONCE AT 600 WITH OPERANDS AND
                 NOWHERE ELSE IN 551-600. BRACK ANSWERED, NOT DEFEATED.
```

### 7a. THE PROBES THE BLOCK ITSELF FLAGGED, RE-RUN

- **The hedge rate.** The word *about* is used constantly and is the manuscript's register. Its highest-frequency hits include a canon figure (*about nine thousand*) and a canon population (*about eleven thousand*). **Not cut, correctly.**
- **The word *floor*.** Thirty-five hits across the volume, and every one is a washroom floor, a ground-floor corridor or a sales floor. **No numeric floor anywhere.** Classified rather than reported as a count.
- **`outline/ending.md` UNTOUCHED.** Verified by `md5` and by `git status --porcelain`, which is empty for the file. Every guard is inherited whole and **no chapter of 551–600 contradicts any of them.** `grep -rn 'Registrar' chapters/volume-12/` returns Adeyemi's title and never Lin Hao's.

## 8. FINDINGS

**Nine findings. One class applied — the two line spans in `state/continuity.md` §0b — and eight recorded and handed on, because an audit that repairs the volume is not an audit.**

**A · APPLIED. TWO OF THE FIVE LINE SPANS AT `state/continuity.md` §0b NAME A LINE THAT DOES NOT EXIST.** `chapter-0594.md` has 97 lines. Rows (3) and "whole file" are recorded as `40–98` and `1–98`. **All four counted figures — 725, 733, 1,184, 1,110 — re-derive exactly.** Corrected in the live block. The chapter was not edited.

**B · RECORDED. THE HOUSE FORM CHANGED AT CHAPTER 571 AND EVERY GATE WAS BLIND TO IT.** 1,540 straight quotes in 551–570; curly from 571; 35,895 straight quotes in Volumes 01–11. **A gate that measures only its own batch cannot see a change made between batches.** Two hands of it are applied to the live rows, which now report volume-wide.

**C · RECORDED, AND THE CONFLICT IS SETTLED AGAINST A STATE FILE. THE SIXTH OF MARCH IS IN YEAR ONE.** `chapter-0545.md:66`, `chapter-0553.md:79`, `chapter-0584.md:143` and `chapter-0590.md:73` and `outline/volume-12.md` §4b are **right**. **1,115 is 505 computed as though it fell in year four** and is withdrawn. `chapter-0584.md` contradicts itself today and the correct interval is **`1,663 − 35 = 1,628` days**, not 548. The repair is one clause in one finished chapter and is not applied here.

**D · RECORDED. `chapter-0553.md:23` IS THE WRONG LINE AND THE DEFECT OCCURS TWICE.** It is at **`:63`**, and the identical wrong multiplication stands at **`chapter-0544.md:25` in Volume 11**, which no open item in this repository names.

**E · RECORDED. `chapter-0570.md:169`'s *a year and three months ago* matches no locatable event.** The one derivable figure beside it is **91 days** to the yard scene at 560. Deliberately open, flagged, not guessed.

**F · RECORDED. TWO GATE ROWS CERTIFY AN ABSENCE THE FILE CONTRADICTS.** `state/open-threads.md` certifies *Mavis Rooke's hand-flat absent from all ten files*, and `chapter-0584.md:75` has *she put both her hands flat on the table behind her*, inside the scene whose card names that staging absent. The rows are corrected; the distinction between Mavis's single attributive hand and the long-register construction is drawn, and the decision the outline required was never recorded.

**G · RECORDED. THE `DUPLICATION` CLASSIFICATION MIS-DESCRIBES ITS OWN EVIDENCE.** 591 is the branch board and 597 is a division-corridor board — two objects, not one — and they are **37 days apart, not sixteen**.

**H · RECORDED. SET B IS DESCRIBED AS UNAMBIGUOUS AND IS NOT, UNDER ITS OWN METHOD.** `semen` is a substring of `advertisement`; `chapter-0565.md` scores two false hits. Corrected to word boundary in the live block; the volume's five explicit passages are unchanged.

**I · RECORDED, AND IT IS A JUDGEMENT. OPEN ITEM 5'S DEFENCE DOES NOT HOLD.** Nothing was padded and nothing should have been. **But dramatic density collapsed by a factor of four to six at chapter 571 and never recovered** — 24.7, 52.3, 7.9, 8.5 and 10.2 mean dialogue exchanges per chapter across the five movements — and the unit sizes did not change, so the cause is form and not scale. **The volume's last thirty chapters report their beats where its first twenty dramatised them.** Every card beat is present; the volume is compressed rather than lean.

## 9. WHAT THE DO-NOT-OPEN REGISTER LOOKS LIKE AFTER THIS AUDIT

**EVERY ITEM ON `outline/volume-12.md` §8 IS STILL SHUT, and eleven were re-probed from outside this volume's passes.**

`Lin Wei` **0** · `B103` **0** · `settle` and every inflection **0** · the figure of the account **0** · `right temple` **0 book-wide** · the second folio of 4,112 **0** · the reach of the return **argued by nobody in either direction** · whether the account belonged to the unrecorded **not settled by any character** · who put the white tile up **unnamed in five years and on the last page** · Hanneke Ruis's certificate **does not exist** · the keeper's six words **not reopened after 554** · Perrin Sowe **unforgiven and undiscussed, and Ines's correction unpressed** · Dagmar Oyelowo **absent from the volume entirely** · Mrs Imrie **asked nothing by anybody** · Sun Meiling's row **not re-told** · Marguerite Vale's fourth line **not struck** · Ada's grey **permanent and not recovered** · the instrument he swore never to use **still unused** · **no partner dies and no partner is left behind by a choice she does not explain.**

**AND THE TWO THAT VOLUME 12 OPENED ARE STILL OPEN, WHICH IS CORRECT AND IS WHAT THE AUDIT IS FOR:**

1. **The keeper's six words now have a name against them, and she read it on the second of January of year five.** Written at 554, the volume's first scene. **Not reopened anywhere in the remaining forty-six chapters.** A keeper's question cannot be asked twice and she spent hers on a man she had never met.
2. **Whether the woman two flights up off Cordwain ever learns what was done for her.** Open, undated, deliberately so. **She is named in 587 and 588 and in neither of them does she learn anything, and no chapter shows her reading the sheet.** Nothing in 591–600 carries her thread even in description.

## 10. PIPELINE GAPS — RECORDED, NOT REPAIRED HERE

**GAP 1 — THE REVIEWER IS NOT RUNNING, AND IT HAS NOW COST THREE PHASES.** `logs/` holds three files and none is a batch review. `logs/batch-0004.review.log` is a writer transcript: the review phase dispatched a subagent as a primary agent, fell back to the default writer per `opencode.json`, and re-ran the writing phase against its own output. **`logs/batch-0003.review.log` does not exist at all**, and five state files cite it as the authority for an entire repair pass. **`AGENTS.md`'s quality-gate line "a reviewer has checked the result" has been satisfied for at least three batches in this volume by the writer re-deriving its own figures — which is better than nothing and is not the same thing.** The fix belongs to the workflow. `scripts/`, `.github/` and `opencode.json` are controller files and this phase did not touch them.

**GAP 2 — BATCHES 0003 AND 0004 WERE NEVER INDEPENDENTLY REVIEWED, AND BOTH CLAIM TO HAVE BEEN.** Re-derived here from the chapters rather than inherited, and **both hold** — the repairs are visible on the page. What is withdrawn is the word *reviewed*, not the repairs.

**GAP 3 — TWENTY CHAPTERS CARRY AN INVENTED INTERVAL.** `chapter-0570.md:169` and the card that licensed it. See Finding E.

**GAP 4 — A CARRIED DEFECT NAMED ONE LINE AND THERE ARE TWO.** See Finding D.

**GAP 5 — A QUARTER OF THE VOLUME'S CHAPTERS SIT BELOW THE GUIDE FLOOR AND NOBODY HAS SAID WHETHER THAT IS RIGHT.** Disclosed for three batches. **Judged here, and the judgement is Finding I.**

## 11. WHAT THIS PHASE HANDS ON

**THE SERIES IS PLANNED PAST 600. `state/complete.md` IS NOT CREATED.** `outline/ending.md` is untouched and is inherited whole: Lin Wei alive and classified and never out of the Classification Wing · the reservoir returned in full at 486 and **never replenished** · Lin Hao at rank one on a branch night shift · the Church of the Quiet Number not dissolved, not vindicated, not converted · Ferreira lives · Sowe lives · **Adeyemi is Registrar of Unrecorded Merit** · no partner dies · no partner is left behind by a choice she does not explain.

**VOLUME 12 CLOSED ITS OWN PROMISE. IT PAID IT TWICE — AT 560 IN A YARD AND AT 595 IN THE OFFICE'S OWN HAND — AND THE SECOND PAYMENT IS THE ONE NOBODY CAN CALL BACK.** A city can read two sentences it has never had before. A man who makes up figures has his name printed under an admission in the hand of the office that was supposed to be the only honest instrument in Ostara. A yard of about eleven thousand people has a rule on a board that he put there by saying out loud, once, that the four lines on it are his. **The Register is not one line in one column in one chained book. It is a book of names, and he is the man standing in the yard who made it that way, and nobody in that yard thinks it was a good thing.**

**AND THE TWO THINGS THE VOLUME OWED ITS READER THAT IT DELIBERATELY DID NOT PAY, WHICH ARE CORRECT AND ARE WHAT THE NEXT VOLUME INHERITS:**

1. **Whether the woman two flights up ever learns.**
2. **What comes off the shelf on the first of January, which nobody knows, including the man who is allowed to read it on the second.**

**AND THE STANDING RULE FOR EVERY ARITHMETIC ROW FROM HERE ON, LEARNED AT THE COST OF FIVE FAILURES IN VOLUME 11, TWO MORE INSIDE A SINGLE PHASE OF VOLUME 12, AND NINE FINDINGS IN THIS AUDIT:**

> **A figure nobody re-computes is the figure that is wrong.**
>
> **A gate row that quotes the prose it is checking cannot catch the prose. And a gate that measures only its own batch cannot see what happened before it — which is how a house form changed at chapter 571 and four arithmetic gates passed it.**

## 12. WHAT WAS APPLIED, AND WHAT WAS NOT

**APPLIED IN THIS COMMIT — one file, three corrections, all of them in live state blocks this phase owns, and not one word of prose:**

1. `state/continuity.md` §0b — the two unreachable line spans at `chapter-0594.md`, corrected to `40–97` and `1–97`, with the note that all four counts re-derive exactly.
2. `state/open-threads.md` — the corridor-board classification corrected (two objects, thirty-seven days), the Mavis hand-flat absence corrected, and the volume-wide quotation-form and system-panel rows added.
3. `state/continuity.md` §0b — Set B's method corrected to word boundary, with the `semen`/`advertisement` false positive named.

**NOT APPLIED, AND NOT THIS PHASE'S:** every repair inside a finished chapter of 551–600, and every repair inside a closed volume. **Nine of the ten findings in §8 are recorded with the correct figure and its operands, so that one commit can repair all of them and re-run the five batch gates that certified the files.** **A repair instruction that drops the operand is the same defect it is repairing.**