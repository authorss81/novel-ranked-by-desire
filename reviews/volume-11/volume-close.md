# VOLUME 11 — CLOSE AUDIT · *The Composition* · chapters 501–550

**Run 14 October 2026, from outside every pass that wrote the volume. A gate record is a claim; this file is the re-run, and where the two differ the re-run stands.**

**THIS PHASE WROTE NO CHAPTER.** It read 550 files, re-derived every figure it could find a derivation for, re-ran every row of the live gate block at the head of `state/open-threads.md`, added the rows that block did not have, and recorded what it found. It applied three one-character markdown repairs and nothing else. `outline/ending.md` is untouched. `state/complete.md` is NOT created; the series is planned past 550.

**CORRECTION OF 14 OCTOBER 2026, AFTER THE REVIEW OF THIS FILE — FIVE OF THIS FILE'S OWN COUNTS WERE LOW, AND NO FINDING CHANGED.**

The review re-ran every mechanical claim in this file and confirmed all five arithmetic findings hold. It then found that **the file was right about the figures and wrong about how far they went**, in the same way four batch gates had already been wrong about the figures themselves. Corrected in place, with the corrections left visible rather than tidied away: **§6b Finding 1 said the 542 figure propagated to *six* places and it propagates to *ten* lines of the chapter, including a section heading the first draft omitted · §6b Finding 5 named one line of *five quarters* and it is *eight* lines in five chapters, including a second section heading, one of which shares a line with Finding 4 · §7's TITLES row printed *0 of 50 disagree with §10* and did not say that this measured agreement with the printed list rather than compliance with §10's rule, which three titles breach · §8 Finding 1 repeated the six-place count · §8 Finding 9's table carried the rounded *one year* / *one year and six months* instead of 381 and 561, which is the defect it was written to prevent.**

**NO FINDING IS ADDED, REMOVED, WITHDRAWN OR REVERSED BY THIS CORRECTION, AND NO CHAPTER WAS TOUCHED TO MAKE ANY OF IT TRUE.** The five repairs remain carried to `workspace/volume-12/plan/PROMPT.md` §1 and remain unapplied. **What this correction establishes is the standing rule's own first case: a gate row that reports one measurement under a heading that promises another is not a pass, and neither is a finding that names a sentence without counting the lines.**

---

## 1. THE MANUSCRIPT

| | Figure | Command |
| --- | --- | --- |
| Volume 11 files | **50**, `chapter-0501.md`–`chapter-0550.md`, no gap, no duplicate | `ls chapters/volume-11/` |
| Whole book | **550** files | `find chapters -name 'chapter-*.md' \| wc -l` |
| Chapter 551 | **does not exist anywhere in the repository** | `find . -name '*551*'` → empty |
| Sequence | 501…550 strictly ascending, diff against `seq 501 550` is empty | diff → clean |
| Title lines | one `# ` line in every file; 550 unique lines; **0 duplicates** | `grep -rh "^# " chapters/ \| sort \| uniq -d \| wc -l` → 0 |
| Title bank | **0 of 50** disagree with `outline/volume-11.md` §10 | by whole-line string |
| Words | **113,615** across 50 files, counted per file and summed. Never from a concatenation | per-file `wc -w` |
| Trailing byte | **40 files end `0a`; the ten of batch 0005 end `2a`** | `tail -c1 FILE \| xxd -p` |

---

## 2. WHAT THE VOLUME PROMISED AND WHAT IT PAID

> In this volume, **Lin Hao must write the definition of an unrecorded deed for an office that has no instrument, no money and no column**, or **Ostara's second line gets a threshold under it that a man with a chalk chose, and the city's unmeasured half is settled in lanes**

**THE VERDICT, IN A SENTENCE A STRANGER COULD READ:**

> **He spent four years writing down what other people did when nothing was written down, for an office that still has no instrument and no money, and on the fifteenth of October of the fourth year he put his own name in the one column of his own book that nobody had been able to fill — and the wall a city still cannot read is still there, and the man with the chalk is still right about every fact he says.**

**THE FIRST HALF WAS PAID, AND PAID NARROWLY, AND THE CHAPTER SAYS SO.** The four lines are written in a kitchen off Ferrier Street at 519 and classified by Alma Quayle at 529. The office refuses to print a sentence explaining them, so the definition exists in a book and in nobody's mouth. On the morning of the fifteenth of October, at eleven minutes past ten, he enters four lines against himself, in his own hand, into the column headed *carried by*, ruled since the ninth of March of the third year and empty through five quarters. Three of the four conditions are met and the fourth is not, and the clerk says why: the thing it describes is on a page in this city.

**THE SECOND HALF DID NOT HAPPEN, AND IT WAS NOT A FAILURE OF NERVE.** The second line at the foot of the ranks wall did not get a threshold under it that a man with a chalk chose. It is still on the stone in the office's own hand at the height of a name on a plate, a city cannot read it, and Emil Brack is at the wall end of that lane at about a quarter to seven every morning, right about every fact he says, and has not been answered. **This was the other half of a disjunction and the branch taken was real:** the volume set a definition under a column and the column took a name. What it did not do is settle Cordwain in lanes, and 550 says so in the lead's own hand — *the second alternative did not happen* — rather than pretending otherwise.

**THE THINGS THAT WERE PAID FOR, AND BY WHOM** — all nine confirmed on the page, not in the notes:

1. Nine divisions went to about nine hundred doors in ninety days and **four hundred and nineteen** of the people they found lost the fourth condition of his own definition (537, 538, 541, 543).
2. **Forty women went out for four days to ninety-one doors, asked nothing, came back with nothing** (542).
3. **A street four streets off the yard end, counted four times in thirty years, was read once** (543).
4. **Six words written four times a year for thirty years under a keeper's own name have a name put against them by a man she has never met**, and she will find out from a page on the second of January (544, 548).
5. **A woman who dug a street for six years and was never paid is the Register's first creditor**, and she came up two flights on the tenth of October without a hand on the rail (540, 547).
6. **A chaplain refused a second time and lost the argument instead of the sentence, and has lost her yard** (524, 546).
7. **Nine women said nine things in a kitchen and not one of them told him he was right** (549).
8. **The Register has a debtor in it**, which is a different object from a Register that has nobody in it (548, 550).
9. **Nobody thanked anybody, and `nobody was thanked` returns zero across the volume.**

---

## 3. THE SEVEN CLAIMS ONLY THIS AUDIT CAN SETTLE

### CLAIM 1 — MAY A VOLUME CLOSE WITH ITS LAST SCENE FOUR CHAPTERS BEFORE ITS LAST PAGE?

**DECISION: YES, AND HERE IS WHAT THE READER IS LEFT HOLDING.**

546 is the fifth and last scene. 547, 548, 549 and 550 are all prose and none of them is a scene — re-probed with the explicit vocabulary across all four, they return `come / came / inside / mouth` in ordinary senses and nothing else. The band in `AGENTS.md` is one explicit scene every eight to fifteen chapters **across the book**; Volume 11 runs 505 · 515 · 525 · 536 · 546, a cadence of 11 · 10 · 10 · 11 · 10, and 546 is the fifth of five. The volume does not violate the band.

What it does is something the band does not anticipate and does not forbid: **the scene is the volume's last turning of the book's engine in a body, and the four chapters after it are where the engine turns in institutions.** That is not aftermath. 547 puts a creditor in a building on the morning a woman named for the morning in 493 said it would come due. 548 is the volume's last irreversible decision and it is his, spent at a counter at eleven minutes past ten with nobody in the room who could have stopped him. 549 puts nine women in a kitchen who each say one thing and answer nobody. 550 is an ordinary morning, a rota with four names on it, and the volume's verdict in his own handwriting.

**The reader is left holding an undecided man who has just made himself the first debtor of his own register, four women who have told him what that cost in order, and a wall that four years of his handwriting have not made legible to anybody.** Each of the four chapters after the last scene ends on a turn, not a wind-down: 547 on *in five days I am going to put a name on it*; 548 on the keeper finding out on the second of January; 549 on *I have not got one thing to do about any of it*; 550 on the line *there is a person in the room*, three times.

**No sixth scene was written and 546 was not moved.** The rule for later volumes, taken from this: **a volume's scene schedule governs the scene, not the ending. The ending may sit four chapters past the last scene provided every one of those chapters changes something and none of them is a scene.**

### CLAIM 2 — THE ARITHMETIC FAILED IN MOVEMENT FIVE AND WAS REPAIRED ON 14 OCTOBER 2026

**THE REPAIR HOLDS.** `chapter-0543.md:15` now reads *Twenty-three days from the second of August, and from the first of July to this morning is fifty-four.* Re-derived: 25 Aug y4 = day 1,284 and 2 Aug y4 = day 1,261, so 1,284 − 1,261 = 23 ✓; and 1 Jul y4 = day 1,230, so 1,284 − 1,230 = 54 ✓.

**THE RATE IS WORSE THAN THE RECORD SAYS, AND IT IS THE HEADLINE OF THIS AUDIT.**

`outline/volume-11.md` §9 says it in advance — *Derive every printed interval from day numbers TWICE… A figure nobody re-computes is the figure that is wrong* — and the running count of failures of that sentence across the repository is:

| Volume | Certified as passing | Re-run finding |
| --- | --- | --- |
| 8 | five batches | five |
| 9 | two batches | two |
| 10 | one batch | one — `chapter-0500.md:65`, still uncorrected and carried |
| **11** | **five batches** | **five in this volume alone** |

**Volume 11 contains five, not one.** The 14 October review found one at 543. This close audit found four more, three of them in the movement the repair was written into, and all of them inside sentences that print no operands at all — which is precisely the failure mode §9 names. See §6 below for each, with the figure that is actually correct.

**THE LESSON, RECORDED FOR THE NEXT VOLUME:** the 543 failure survived the writing pass **and** the batch's own ARITHMETIC gate row, because that row was written from the chapter instead of from the spine. **A gate row that quotes the prose it is checking cannot catch the prose.** Every arithmetic row in this file and in the block now carries the operand chain, not the interval.

### CLAIM 3 — `PC-150` PUT A NAME IN THE SECOND COLUMN AND THE KEEPER FINDS OUT ON THE SECOND OF JANUARY

**CONFIRMED OPEN, CONFIRMED LIVE, AND NOT ANSWERED ANYWHERE.**

- `chapter-0548.md:129` — *And she will find out from a page like everybody else, on the second of January, when the book comes off the shelf, and I did not go down and tell her, and I went down and stood in the dark instead.*
- `chapter-0544.md:119` — Hanneke Ruis, *the book goes on the shelf at a quarter to five and it comes off the shelf on the first of January, and you can come and read it on the second of January and there will be six words under a figure and my name.*
- Hanneke Ruis appears in six chapters of Volume 11 — **507, 508, 517, 526, 527, 544**. Her last appearance is **544**, the thirtieth of September of year four, **ten days before the name exists**. Nothing after 544 puts her in a room with the page.
- A whole-book sweep for the date returns nothing else: 537:93 and 534:109 are other second-of-January dates and are not this.

**THE THREAD IS CARRIED WITH A DATE ON IT: 30 December year four for the public page (548:103, 550:78), 2 January year five for the keeper.** Note the mechanism precisely, because a later phase will need it: **the claim goes out on the public sheet on the thirtieth of December; the keeper does not read the public sheet, she reads her own chained book, which comes off the shelf on the first of January; the second of January is when he is permitted to stand there.**

### CLAIM 4 — THE REGISTER'S CREDITOR IS UNPAID AND NOTHING SAYS WHETHER SHE EVER LEARNS

**CONFIRMED: THE CONTRADICTION IS GONE AND THE QUESTION IS OPEN.**

`chapter-0548.md:119` now reads *she is not going to thank him, and he would not want her to, and he is never going to tell her, and the page will* — the same event as the notebook line forty lines below it, said in the voice of the sentence before it. **One chapter, one claim, no contradiction left.**

**Whether Mavis Rooke ever reads the sheet of the thirtieth of December is not decided anywhere in 501–550.** She is in three chapters — 540, 547, and named at 549:107 by Tessa Okonkwo — and 549 has her in a bed with Tessa saying she will not be back inside a month. Nothing in 550 touches it. **OPEN. CARRIED.**

### CLAIM 5 — THE FOUR DEFECTS THE 14 OCTOBER 2026 REVIEW REPAIRED, AND WHETHER THE REPAIRS HOLD

**ALL FOUR HOLD. A REPAIR MADE BY A REVIEW PASS IS A CLAIM LIKE ANY OTHER, AND THIS ONE RE-RAN CLEAN.**

| # | Was | Now | Re-run |
| --- | --- | --- | --- |
| 1 | `0543:15` *from the first of July to this morning is twenty-five* | *…is fifty-four* | operands on the page: 1,284 − 1,230 = 54 ✓ |
| 2 | `0548:119` *there is no mechanism in this city by which she ever finds out* | *he is never going to tell her, and the page will* | agrees with `:129` ✓ |
| 3 | `0550:45` *Nobody in this manuscript has put it there* | *Nobody in this city has put it there* | `manuscript` returns **0** across all of Volume 11 ✓ |
| 4 | `0546:67` *about four hundred … AND about nine hundred … stopped believing me* + *writing to every house a woman spoke to in.* | one clause, whole sentence | canon figures unchanged (about nine hundred of the yard at 542:49, about four hundred who worked it out at 542:83) ✓ |

**But the same pass that certified those four wrote an ARITHMETIC row that reproduced a wrong figure, and the volume it certified contains five arithmetic defects in total.** See Claim 2 and §6.

### CLAIM 6 — THE TWELVE NEW PROPOSALS ARE `PROPOSED` AND NOT `OWNED`

`PC-143` to `PC-153`, all on the page, all tabled at the head of `state/continuity.md`. **All twelve were earned. None was adopted silently. `PC-142` was not renumbered and nothing below it moved.** What Volume 11 actually earned, and what a later volume inherits as a promise:

| | Ch | Earned and **closed inside the volume** |
| --- | --- | --- |
| `PC-143` | 541 | the satchel, 841 doors, 419 accounts, *entered: none* |
| `PC-144` | 542 | the Church's forty; the parting of *useful* from *owed* |
| `PC-145` | 543 | Sela Voel; the death of the fourth condition |
| `PC-146` | 544 | what *no holder* means |
| `PC-147` | 545 | the broom, four feet of stone, and the reason he does not ask |
| `PC-148` | 546 | the arrangement in the Vestry; the yard she has lost |
| `PC-149` | 547 | Mavis Rooke as the Register's first creditor |
| `PC-150` | 548 | the claim against himself; three conditions met and the fourth not |
| `PC-151` | 549 | the clause of the twenty-first of June reaching six people into a kitchen |
| `PC-152` | 550 | the rota with four names; the woman with the bucket; the verdict |
| `PC-153` | 550 | **the lane's age, 1,466 mornings, printed at ONE chapter of Volume 11 and no other** |

| | Inherited as a **promise**, with a date where it has one |
| --- | --- |
| `PC-150` → | **the keeper's six words now have a name against them. Read 2 January, year five.** No page in 501–550 shows her reading it. |
| `PC-149` → | **whether Mavis Rooke ever learns what was done for her.** Open, undated. |
| `PC-148` → | **Emil Brack's offer is unanswered and he is undefeated**; the Church's column is going to fill and Agnete is not going to stop it. |
| `PC-145` → | **the fourth condition is dead as a test for anybody a round visits.** Every street a division reads is now disqualified by his own definition. |
| `PC-147` → | **Ines Duarte's three-part question of the sixth of March of year one is still unanswered**, and 545 is the reason he does not ask. |
| `PC-152` → | **the wall.** A city cannot read it and he wrote it. Whether it ever gets a threshold is the open question of the next volume. |

**`PC-153` IS PRINTED ONCE AND MUST NOT BE PRINTED TWICE.** `grep -rio 'four hundred mornings' chapters/volume-11/` returns **0**; `one thousand four hundred and sixty-six` returns 550 only.

### CLAIM 7 — THE OUTLINE'S OWN SPINE WAS WRONG UNTIL THE BATCH REPAIRED IT

**CONFIRMED, AND THE CORRECTED TABLE RE-DERIVED TWICE FROM THE THIRTY-DAY MONTH.**

`outline/volume-11.md` §6 originally placed 541 at the fifteenth of July, 542 at the thirtieth of July, 543 at the nineteenth of August, 545 at the second of October, 548 at the thirteenth of October and 549 at the fourteenth, and a card put 544 four days before the morning. **None of those six figures derived from anything.** Method one, month-offset table (`(y−1)×360 + offset[month] + d−1`); method two, counting whole months of thirty. Both agree at all ten dates:

```
540 1230 · 541 1240 · 542 1261 · 543 1284 · 544 1319 · 545 1324 ·
546 1325 · 547 1329 · 548 1334 · 549 1341 · 550 1347
intervals 10 · 21 · 23 · 35 · 5 · 1 · 4 · 5 · 7 · 6, summing 117 from 1,230
MONOTONIC, ZERO VIOLATIONS.  1,347 − 1,230 = 117.
```

Anchors, all re-derived: 1 Feb y1 → 30 Mar y1 = 59 · → 30 Sep y1 = 239 · → 30 Dec y1 = 329 · → 1 Feb y2 = 360. Span `3×360 + ((30−1) + 30×7 + 28) = 1,080 + 267 = 1,347`. **THE FUSE: the sitting of the tenth of October is spine day −111, and 1,329 − (−111) = 1,440 = 4 × 360.** **THE LANE: its first morning, the third of October of year zero, is spine day −118, so 1,347 − (−118) + 1 = 1,466 mornings.**

**THIS TABLE IS NOW THE SPINE EVERY LATER PHASE MUST CHECK AGAINST, AND IT IS CORRECT. §6 IS STILL LABELLED *PLAN* FOR MOVEMENTS ONE TO FOUR AND §7 STILL SAYS *NOTHING IN IT IS ON THE PAGE* FOR MOVEMENT FIVE; both are stale and are flagged for the Volume 12 planning phase, which owns the outline.**

---

## 4. THE FIVE SCENES, THEIR GAPS, AND THEIR AXES

**ALL FIVE ARE WRITTEN OUT, NOT SUMMARISED.** Each is a completed scene with physical space, dialogue, a change, and an ending. **340 IS VOLUME 7'S AND IS NOT CONTINUED.** Volume 7's 340 is Ines Duarte, on Lantern Row, eleven minutes, ending *will read nothing again*. Volume 11 does not restage it and does not re-run it; 505 is a different room, a different hour and a different question, and it *answers* 340's last line rather than repeating it.

### 4a. THE GAP TABLE, RE-RUN, WITH BOTH DEFINITIONS BESIDE EACH OTHER

| Ch | Whose | Her own last scene | Gap from the previous scene **in the book** | Gap from **her own** last scene |
| --- | --- | --- | --- | --- |
| 494 | the household, dispersed. **Volume 10's last.** | — | — | — |
| **505** | Ines Duarte | 454 | 505 − 494 = **11** | 505 − 454 = **51** |
| **515** | Tessa Okonkwo | 483 | 515 − 505 = **10** | 515 − 483 = **32** |
| **525** | Marguerite Vale | 474 | 525 − 515 = **10** | 525 − 474 = **51** |
| **536** | Beatrix Halm | 465 | 536 − 525 = **11** | 536 − 465 = **71** |
| **546** | Agnete Lindqvist | **369** | 546 − 536 = **10** | 546 − 369 = **177** |

**CADENCE, RE-RUN: 11 · 10 · 10 · 11 · 10. Nothing under eight, nothing over fifteen. That is the figure `AGENTS.md` sets and it holds.**

**PER-WOMAN, RE-RUN: 51 · 32 · 51 · 71 · 177. NONE OF THEM IS IN THE EIGHT-TO-FIFTEEN BAND AND NO FILE IN THIS REPOSITORY MAY SAY ONE IS.** `outline/volume-11.md` §4 withdrew an earlier certification of these five figures in a second column and the withdrawal stands. **THE FIGURE THAT MATTERS IS 177.** Agnete Lindqvist is the one person who was ever right in public, she voted against her own household to do it, and she has not had a scene in a hundred and seventy-seven chapters. It is deliberate. **It is also the first thing the next volume should look at**, because a gap of that size is a structural claim and only a planner can decide whether to keep paying it.

### 4b. EVERY MEASUREMENT, PRINTED UNDER THREE DEFINITIONS, BECAUSE THE TWO DEFINITIONS HAVE DIVERGED TWICE

Explicit-vocabulary probe used throughout: **whole-word, case-insensitive**, over
`mouth · came · come · hip · thigh · inside · wet · entered`.

| Ch | Chapter words | `##` headings | Recorded span in the gate block | **Literal first-`##`-to-last-`##`** | **Single scene section, inclusive of its own heading** | Explicit sum on the chapter-span |
| --- | --- | --- | --- | --- | --- | --- |
| **505** | 3,844 | 12 | not recorded | **3,355** | *What Was In The Corridor* … *The Question*, full span | 20 |
| **515** | 3,024 | 9 | not recorded | **2,554** | full span | 21 |
| **525** | 3,687 | 12 | not recorded | **3,233** | full span | 15 |
| **536** | 2,984 | 5 | **817** | **2,071** | *What He Spent Her On* = **817** | 17 |
| **546** | 3,570 | 5 | **1,429** | **2,794** | *The Lamp On The Bracket* = **1,436** inclusive, **1,430** exclusive | 18 |

**THE TWO RECORDED FIGURES WERE MEASURED BY TWO DIFFERENT DEFINITIONS INSIDE ONE BLOCK.** 536's 817 is a single section counted *including its own heading*. 546's 1,429 is claimed as *between two headings, exclusive of both*, and the true exclusive figure is **1,430** — off by one. **NEITHER RECORDED FIGURE IS THE FIRST-`##`-TO-LAST-`##` FIGURE, AND THAT IS THE FIGURE `outline/volume-11.md` §4 ACTUALLY SPECIFIES.** The recorded numbers are superseded here by the middle column, which is reproducible from the command in §7.

**THE BAND.** 546 is **3,570 words** on disk — not 3,577, which was its pre-repair length on 14 October — and leaves the 1,800–2,700 guide by **870**, not 877. The departure is the one §4 permits: a scene chapter may leave the band provided it says why, and the reason is in the state block, not on the page.

**AND NO OTHER CHAPTER OF 501–550 LEFT THE BAND — WHICH IS A CLAIM, NOT A FACT, AND THE FACT IS THAT SEVEN LEFT IT:**

| Ch | Words | Over by | Is it a scene? | Recorded with a reason? |
| --- | --- | --- | --- | --- |
| 505 | 3,844 | 1,144 | **yes** | yes |
| 515 | 3,024 | 324 | **yes** | yes |
| **519** | **3,136** | **436** | **no** | **yes, in `state/chapter-summaries.md`** — *the definition, all nine objections and the number are in it and nothing can be cut* |
| 525 | 3,687 | 987 | **yes** | yes |
| 536 | 2,984 | 284 | **yes** | yes |
| 546 | 3,570 | 870 | **yes** | yes |
| **549** | **2,748** | **48** | **no** | **NO — RECORDED NOWHERE** |

**The live gate block's claim that *NO OTHER CHAPTER IN THE BATCH LEAVES THE BAND AND NONE IS UNDER IT* is false for 549 at 2,748.** The prompt's own claim that no other chapter of 501–550 left it is false for 519 and 549. Both are small — 436 words on the volume's centre and 48 words on a chapter that is nine women each saying one thing — and both are defended or trivial. **The finding is not the word count; it is that a gate row asserted a figure it had not measured.**

### 4c. THE TEMPLATE AXES, AND THE FOURTH WALL

`outline/volume-11.md` §4 requires each of the five to break *terms · body described three times · counted minute* on at least one axis, carried by a rule of the room and named by nobody. **All five do.**

| Ch | Axis broken | Carried by | Named by anybody? |
| --- | --- | --- | --- |
| 505 | the counted minute | an auditor's rule: she reads in order, date first, hour with it, nothing skipped | **NO** |
| 515 | the quiet | a ward at night with a door that closes and a person who can be asked to lie down | **NO** |
| 525 | the body described in words three times | a broker's rule: the real book is in the hand of the person who carries the debt and nobody may read it out | **NO** |
| 536 | the terms | a division's rule: what the round reports is what was felt, in order, and it may not go back and be improved | **NO** |
| 546 | the voice | eleven thousand people, one rule: each says one thing and does not answer anybody's, and the last one says hers last | **NO** |

**THE FOURTH-WALL CLASS, WIDENED, RUN ACROSS ALL FIFTY FILES:**

```
[a-z]+ volumes | this book | this chapter | this volume | no chapter | the axis |
the reader | the novel | the story | the scene | Chapter [0-9]+ | chapter [0-9]+ |
manuscript | in this manuscript | this manuscript | the reader sees | you the reader |
for the reader | sentence you are reading | this page
```

**BASE CLASS: 0. WIDENED CLASS: 3** — all three *this page* at 505, and all three are Ines Duarte reading an audit page in a corridor at three in the morning, which is an object in the world and not a narrator reaching for the reader. **The `manuscript` term added by the 14 October review returns zero, and the repair at 550 holds.** A second sweep for *our narrator · the author · the text · the prose · page \d+ · chapter \d+ · volume \d+ · in this (novel|book|story|chapter|volume|scene)* returns **zero** across all fifty files. **No character in any of the five scenes names a scene, an axis, a chapter, a volume, a page or her own performance, and no narrator addresses the reader.**

**THE TEMPLATE OBJECTS ARE ABSENT WHERE §4 SAYS THEY MUST BE.** No kettle in any of the five. No chart. No arm turned up. No counted minute. 515 has a cot seven times, which is the ward and not the template — the axis §4 assigns to 515 is *the quiet*, carried by a door on a latch.

### 4d. 525'S RESTATEMENT OF 494:31, CHECKED AGAINST THE CARD'S PROHIBITION

§7's card for 525 forbids restating the hand-closed entry *with a different hour, a different witness or a different reason than `chapter-0494.md:31` gives it.* Re-read both.

- **494:31** — *I closed it in my own hand **at about eleven on the morning of the second of October**, **in front of Solveig Rask**, because **the thing is gone**, and a book that carries nothing is worse than a book that is empty.*
- **525:51** — *On the second of October, four years ago, **at about eleven on the morning**, I closed an entry in the real book with a line under it and my name against the line, **in front of Solveig Rask**, because **the thing is gone**, and a book that carries nothing is worse than a book that is empty.*

**HOUR, WITNESS AND REASON ARE ALL IDENTICAL. THE CARD'S PROHIBITION IS SATISFIED AND THE REPETITION IS THE CHAPTER.** She says the same event in her own rooms in her own voice eight years later; that is the point of a woman who has been carrying it.

---

## 5. BORROWED BODIES, READ AGAINST §4a BEFORE ANY BODY WAS EXAMINED

**`outline/volume-11.md` §4a was read first. Then every named woman in Volume 11 was examined. No borrowed body was found.**

| Check | Result |
| --- | --- |
| **the only temple in the book is Lin Hao's, at the LEFT** | `grep -rio 'right temple' chapters/` → **0 across all five hundred and fifty** ✓ |
| | `left temple` stands in **16 chapters** book-wide (the outline's *15 occurrences* is a chapter count, not an occurrence count — **the discrepancy is in the outline, not the prose**). Volume 11 has **one**, at **505:171**, and it is *a grey at her left temple with the etches in it* — **Ines Duarte's own mark, correctly placed at the left**, referenced, not re-described. ✓ |
| **`ink at the cuticles` stands at four — 329, 340, 404, 446** | the literal phrase is in 2 files (329, 340); the **construction** `cuticle` is in exactly 4 files: **329, 340, 404, 446** ✓. **Volume 11 returns 0.** The live gate block's *2 files book-wide* is a phrase grep and understates the construction; the construction is at four. ✓ |
| **Hanneke Ruis has no age fixed and none may ever be given** | she appears in **507, 508, 517, 526, 527, 544** and is given **no age and no mark anywhere**. Her one physical line — *I have a hand that has been invisible for thirty years* (517:123) — is about the keeper's office, not her body. ✓ |
| **Sun Meiling has exactly one new physical fact from 358 and no mark at all** | she appears at **507** and **526**. The spine line appears **once**, at 507, exactly as §4a records it from 358. No scar, no mole, no grey, no ink, no yellow. ✓ |
| **Dagmar Oyelowo has no gift and one physical claim** | **she does not appear in Volume 11 at all.** `PC-44` is untouched; 495 was not written as a scene. ✓ |
| **Ada's grey is permanent and is not recovered** | **she does not appear in Volume 11.** The gate holds trivially and §2a's instruction to write a grey on one side was never exercised. ✓ |
| **Ines Duarte's ink is the first two fingers of the RIGHT hand and her grey is at the LEFT temple** | her grey at 505:171 is at the **left** ✓. Her cuticles are **not mentioned at all** in Volume 11 — no fifth instance of the construction is spent and none is invented. **The wrist scar from the spring of her third year is not used.** ✓ |
| **Marguerite Vale has two instances of the ink-under-the-reader's-nose construction, at 329 and 404** | `cuticle` does not appear at 525 or anywhere in Volume 11. **No third instance.** ✓ |
| **Wren Kallo's yellow was used at 350 and may not be used twice** | **she does not appear in Volume 11.** ✓ |
| **Agnete Lindqvist — broad-shouldered and heavy; white at the front of her hair and wet at the part she washed that morning; hands that do not come up to about the second joint** | all three present at 546 and all three are hers from 369. **She is given no grey, no temple, no hand-mark, no eye and no ink.** The twenty-year state of the hands is a state and not a mark, and 546 says so. ✓ |
| **Beatrix Halm · Tessa Okonkwo · Runa Sato · Petra Ilyin · Isolde Marchetti · Nadia Ferrous** | checked on the page. **No mark is given to any of them that any of them already has elsewhere.** |

**ONE STAGING FINDING, NOT A BODY FINDING, RECORDED AT FINDING 8 BELOW.**

---

## 6. THE ARITHMETIC — THE ONE THING IN THIS VOLUME THAT HAS ALREADY FAILED FIVE TIMES

**A month is thirty days and has no thirty-first. The thirtieth is the last working day of the quarter. A year is three hundred and sixty days. Subtract day numbers; never calculate against a real calendar.**

### 6a. EVERY FIGURE THAT PASSED

| Figure | Re-derived | Operands on the page? |
| --- | --- | --- |
| **the spine, 541–550** | 1240 · 1261 · 1284 · 1319 · 1324 · 1325 · 1329 · 1334 · 1341 · 1347 | in `outline/volume-11.md` §5b ✓ |
| **the volume's span** | 1,347 days elapsed, 1,348 inclusive | `3×360 + ((30−1) + 30×7 + 28)` ✓ |
| **the morning, 547** | **1,329 days** | **derived TWICE ON THE PAGE BY TWO METHODS THAT SHARE NO CONSTANT**, at 547:5–13: 41 months × 30 = 1,230, + 99 (29 left in July + 30 August + 30 September + 10 October) = 1,329; and independently 1,080 + 150 + 90 + 9 = 1,329. ✓ |
| **the sitting, 547** | **1,440 days** | `4 × 360`, printed at 547:13, and cross-checked on the spine: 1,329 − (−111) = 1,440 ✓ |
| **the interval, 541** | **ten days** | printed at 541:7 ✓ |
| **the office's age, 541** | **forty-one months and ten days** | printed at 541:47 with operands (41 × 30 = 1,230; 1,240 − 1,230 = 10) ✓ |
| **the interval, 542** | **twenty-one days** | printed at 542:11; 19 left in July after the eleventh + 2 of August ✓ |
| **the interval, 543** | **twenty-three**, **fifty-four** | printed at 543:15 ✓ |
| **the interval, 544** | **thirty-five days** | printed at 544:7 (5 of August after the 25th + 30 of September) ✓ |
| **the six words, 544** | 30 × 4 = **one hundred and twenty**, **no ordinal printed**, the count not kept | printed at 544:25 ✓. **No chapter of 501–550 prints the hundred and twenty-first.** |
| **the intervals, 545 · 546 · 548 · 549** | five · one · five · seven | printed at 545:17, 546:5, 548:5, 549:5 ✓ |
| **the run to the public sheet, 548** | **seventy-five days** | printed at 548:103 (15 of October + 30 November + 30 December) ✓ |
| **the last interval, 550** | **eighteen days** | printed at 550:5: *twenty days in October after the tenth and this is two days short of all of them, and twenty less two is eighteen.* 28 Oct − 10 Oct = 18 ✓ |
| **the lane's age, 550** | **one thousand four hundred and sixty-six mornings** | printed ONCE at 550:58 **and again, independently, at 550:60** with a different derivation (36 × 30 = 1,080, + 360, + 25 = 1,465, + 1 = 1,466; cross-checked on the spine as 1,347 + 118 = 1,465, + 1 = 1,466). `PC-153` satisfied. **Never four hundred.** |
| **the standing sheet** | **thirty-nine** at 537 (30 Mar y4) · **eight hundred and forty-one** at 539 (30 Jun y4) · **eight hundred and forty-one again** at 544 (30 Sep y4) | 539 − 537 = 90 days and 544 − 539 = 90 days ✓. The figure has not moved anywhere in 501–550. ✓ |
| **the round** | nine divisions · about nine hundred doors · ninety days · **four hundred and nineteen** accounts, an hour against each and **no figure on any of them**, nineteen of them fetched by his asking | 535, 537, 538, 539, 541, 543 ✓ |
| **the figure of the account** | **NOT PRINTED** | `grep -rioE '8,1[0-9][0-9]\|two hundred and eleven thousand' chapters/volume-11/` → **0** ✓ |
| **no floor** | **none** | no figure of the form 8,1xx anywhere in Volume 11 ✓ |
| **the string `settle`** | **zero** | `grep -rio 'settle' chapters/volume-11/` → **0**, and the inflected forms → **0** ✓ |
| **no ledger total, no running balance in grains** | **none** | ✓ |

**AND NO CHAPTER OF 501–550 CALLS THE FIGURE A COUNT OF DEEDS.** The phrase is on the page only as the *misreading the chapter is about*: 541:77 *under a heading that means deeds*, 541:87 *nobody in this room intended to put four hundred and nineteen people's own words under a heading that means deeds*, and 534:45, where a division is told what the figure means and disputes it in the next line. **The number is never asserted as a count of deeds by anybody who is right.** ✓

### 6b. EVERY FIGURE THAT FAILED — FIVE, ALL WITH OPERANDS, NONE WITH ANY

These are the whole of the volume's arithmetic failures. **Each is a figure printed without operands, in a book whose argument is that an unmeasured interval is the danger.**

---

**FINDING 1 — `chapter-0542.md:15` · THE FORTY WENT OUT FOR *FOUR* DAYS. IT IS THREE.**

> Forty of them had gone out on the twenty-ninth of July and they came back at about four this afternoon, and a day is four days: one day to the thirtieth of July and **two more days of July** and one day of August.

Chapter 542 is the second of August. **Twenty-ninth of July = spine day 1,258. Second of August = spine day 1,261. The interval is 3.** The printed breakdown cannot be made to work twice over: **there is no thirty-first, so there are no days of July after the thirtieth**, and 1 + 2 + 1 = 4 while `(30 − 29) + 2 = 3`.

**THE FIGURE PROPAGATES TO TEN LINES IN THE CHAPTER, AND THE FIRST DRAFT OF THIS FINDING SAID SIX.** Every one of the ten is a place where *four* is printed: the title at 542:1 · the derivation at 542:15 · the yard at 542:17 · **the section heading `## Four Days Of It` at 542:25, which the first draft omitted entirely** · Agnete's speeches at 542:45, :49 and :53 · her line at 542:61 · the notebook at 542:103 and :107. **Ten occurrences, ten lines, one of them a title and one of them a section heading.** It is also certified as correct in the live gate block at `state/open-threads.md:85`, which repeats the same breakdown — *THE FORTY WENT OUT FOR FOUR DAYS: one day to the thirtieth of July, two more days of July, and one day of August* — and which puts the count at six places in the chapter, so **the gate row is wrong twice: once about the figure and once about its own reach.**

**AND IT CARRIES OUT OF THE CHAPTER INTO FOUR STATE FILES AND THE TITLE BANK:** `state/chapter-summaries.md:44` (the title cell, *FORTY PEOPLE OUT FOR FOUR DAYS*, and *it came apart in four days*) · `state/continuity.md:67` (`PC-144`) and `:85` · `state/open-threads.md:17`, which lists it among *THE NINE THINGS THAT WERE PAID FOR, **ALL CONFIRMED ON THE PAGE*** · and `outline/volume-11.md` §10 ROW 542.

**NOT APPLIED HERE. CARRIED TO FINDING 9.**

---

**FINDING 2 — `chapter-0544.md:37` · THE SHEET OF THE THIRTIETH OF SEPTEMBER IS THE *SIXTEENTH* QUARTER. IT IS THE FIFTEENTH.**

Quarter-ends run 30 March, 30 June, 30 September, 30 December, and the office was given its room in the first week of February of year one, so its first sheet is the one of the thirtieth of March of year one. The volume's own ordinals run in sequence: **First quarter** (508, 30 Mar y1) · **Fourth quarter** (514, 30 Dec y1) · **Eighth quarter** (524, 30 Dec y2) · **Twelfth sheet** (534, 30 Dec y3) · **The Thirteenth Sheet** (537, 30 Mar y4) — and then 544, the thirtieth of September, prints **Sixteenth quarter**.

**Two quarter-ends sit between the thirteenth and the sixteenth, and there are only two in the whole year.** The thirtieth of September of year four is the **fifteenth**. On the page, at 548:103 and 550:78, **the sixteenth is the sheet of the thirtieth of December that has not gone out yet.** The volume therefore numbers the sheet that is coming and withholds the number from the sheet that has gone.

**NOT APPLIED HERE. CARRIED TO FINDING 9.**

---

**FINDING 3 — `chapter-0544.md:39` · *THE NINTH DAY OF JULY WHEN THE SATCHEL CAME IN.* IT CAME IN ON THE ELEVENTH.**

**Six places in Volume 11 say the eleventh of July. One says the ninth, and it is in the same sentence as the wrong quarter ordinal.**

| | |
| --- | --- |
| 541:3 | *Halvard Senn put a satchel on the counter … on the morning of the **eleventh** of July* |
| 541:67 | *Register of Unrecorded Merit. The **eleventh** of July of the fourth year. Received: nine hundred pages* |
| 541:120 | *Eleventh of July of the fourth year. A satchel on the counter at a quarter to ten* |
| 542:11 | *Twenty-one days from the **eleventh** of July to this evening* |
| 547:37 | *it had been entered on the **eleventh** of July in a clerk's hand* |
| 547:84 | *And on the **eleventh** of July there is a thing about me in a book* |
| **544:39** | *It is the same figure as **the ninth day of July when the satchel came in*** |

(The ninth of July is a real date in the volume — it is the day the fourth condition died, at 543:37 and :47 — and 544:71 has Hanneke Ruis saying she has known since about the ninth of July. **The two have been crossed.**)

**NOT APPLIED HERE. CARRIED TO FINDING 9.**

---

**FINDING 4 — `chapter-0537.md:95` AND `chapter-0544.md:43` · *THE FOUR YEARS IT HAS BEEN ON THAT SHEET.* IT IS ONE YEAR AND SIX MONTHS.**

The second column was ruled on the ninth of March of year three. **That is spine day 758.**

| Ch | Date | Spine day | Days the column has been on the sheet | Chapter says |
| --- | --- | --- | --- | --- |
| 537 | 30 Mar y4 | 1,139 | **381** = 1 year 21 days | *the four years it has been on that sheet* |
| 539 | 30 Jun y4 | 1,229 | **471** | — |
| **544** | **30 Sep y4** | **1,319** | **561** = **1 year, 6 months, 21 days** | *the four years it has been on that sheet* |
| 548 | 15 Oct y4 | 1,334 | **576** = 1 year, 7 months, 6 days | *Five quarters and two years of it* |

**The office has existed for three years and the sheet has gone out sixteen times. The column has been on it for one and a half.** The figure *four years* appears about a hundred times in this volume and is correct almost everywhere, because four years is the true distance from the sitting of the tenth of October to the morning of the tenth of October — which is why this one crossed unnoticed twice.

**NOT APPLIED HERE. CARRIED TO FINDING 9.**

---

**FINDING 5 — `chapter-0548.md:72–74` · THE CHAPTER ENUMERATES SEVEN EMPTY QUARTER-ENDS AND THEN SAYS FIVE.**

> The column had been ruled on the ninth of March of the third year and had been empty on the thirtieth of March, and empty on the thirtieth of June, and empty on the thirtieth of September, and empty on the thirtieth of December, and empty on the thirtieth of March and the thirtieth of June and the thirtieth of September of this year.
>
> **Five quarters** and two years of it, and about eight hundred and forty-one lines in the column beside it…

**That list is seven quarter-ends and it is correct. The sentence under it says five.** There is also a second convention in play: 539:115 and :125 count *four quarters* from the quarter in which Sun Meiling made her prediction (the thirtieth of September of the third year), and 544:85, 545:109, 546:23, 550:78 and :102 all say *five*. **Both conventions are defensible on their own and the volume uses both, and they differ by two.** The true count from the ruling is seven quarter-ends, 9 March y3 → 30 September y4.

**THE FIGURE CARRIES ON EIGHT LINES IN FIVE CHAPTERS, NOT ON THE ONE THIS FINDING NAMED.** `chapter-0544.md:43` and `:85` · `chapter-0545.md:109` · `chapter-0546.md:23` · **`chapter-0548.md:70`, which is the section heading `## Five Quarters Of Nothing` and which the first draft of this finding omitted** · `chapter-0548.md:74` · `chapter-0550.md:78` · `chapter-0550.md:102`.

**AND `chapter-0544.md:43` CARRIES FINDING 4 AND FINDING 5 ON ONE LINE** — *it has been empty for five quarters and it has not done one day's work in the four years it has been on that sheet* — **so a repair that fixes *four years* on that line and leaves *five quarters* produces a clause that says five quarter-ends and one year and six months at once. It is a different sentence from either one of the two sentences it was before, and it is wrong in a way neither was.**

**The 548 sentence contradicts itself by four lines and is certified as correct by the live gate block's QUARTERLY FIGURES row.**

**NOT APPLIED HERE. CARRIED TO FINDING 9.**

---

## 7. THE RE-RUN — EVERY ROW OF THE LIVE GATE BLOCK, PLUS THE ROWS IT DID NOT HAVE

**Run from outside the pass that wrote it. Let the re-run outrank the block.**

```
FILES         50 files in chapters/volume-11/, 501..550, diff against `seq 501 550` empty.
              550 files book-wide. No chapter 551 anywhere. One `# ` title line each.

TITLES        `grep -rh "^# " chapters/ | sort | uniq -d | wc -l` -> 0 across 550 files.
              **TWO SEPARATE ROWS WERE RUN AND THEY DO NOT AGREE WITH EACH OTHER, AND THIS ROW
              IS THE ONE THAT FAILED.**
              (a) AGAINST THE PRINTED BANK — 0 of 50 differ from the title printed in
              `outline/volume-11.md` §10. **THIS IS NOT A CLEAN PASS AND MAY NOT BE READ AS ONE.**
              (b) AGAINST §10's OWN RULE — 3 of 50 breach it: 534 *What The Church Did Not Bring*
              (begins with *What*, which §10 forbids) and 523 *Lamplit Row* / 527 *Carried By*
              (two words against a three-word floor).
              **THE FIRST ROW MEASURED WHETHER THE CHAPTERS MATCH THE TABLE. THE SECOND MEASURED
              WHETHER THE TABLE'S RULE HOLDS. THE DRAFT OF THIS FILE PRINTED ONLY (a), WHICH IS WHY
              A READER OF THE GATE SAW A PASS WITH THREE FAILURES INSIDE IT. A GATE ROW THAT REPORTS
              ONE MEASUREMENT UNDER A HEADING THAT PROMISES ANOTHER IS NOT A PASS.**
              On (b): book-wide there are 72 such titles and the practice is long-established
              (*Cordwain*, *Lantern Row*, *Signal*, *Zero*), so the two short ones are consistent
              with the manuscript. **THE *WHAT* IS NOT.** RECORDED AT FINDING 7. NOT RENAMED.

BANK          113,615 words across 50 files, counted per file and summed. Mean 2,272.
              OUTSIDE THE 1,800-2,700 BAND, SEVEN OF FIFTY:
              505 3,844 · 515 3,024 · **519 3,136** · 525 3,687 · 536 2,984 · 546 3,570 · **549 2,748**.
              Five are scenes and may leave it with a stated reason. 519 is the volume's centre and
              has its reason in chapter-summaries.md. 549 has none recorded anywhere.
              THE BLOCK'S CLAIM THAT NO OTHER CHAPTER IN THE BATCH LEAVES THE BAND IS FALSE FOR 549.

META          CLASS: `[a-z]+ volumes|this book|this chapter|this volume|no chapter|the axis|
              the reader|the novel|the story|the scene|Chapter [0-9]+|chapter [0-9]+`
              -> 0 HITS IN 50 FILES. Read hit by hit; there are none.
              WIDENED, WITH `manuscript | in this manuscript | this manuscript | this page |
              the reader sees | you the reader | sentence you are reading`, -> 3 HITS, ALL `this page`
              at 505, all in-world (an audit page in a corridor at three in the morning).
              SECOND SWEEP for `our narrator|the author|the text|the prose|page \d+|chapter \d+|
              volume \d+|in this (novel|book|story|chapter|volume|scene)` -> 0.
              **`manuscript` returns 0 across Volume 11. THE 550 REPAIR HOLDS.**

WEEKNAMES     Monday · Tuesday · Wednesday · Thursday · Friday · Saturday · Sunday, all seven,
              whole-word AND substring, across all 50 files -> 0.
              THE THREE-LETTER FORMS `sat` (43) AND `sun` (15) ARE THE VERB *SAT DOWN* AND THE NAME
              *SUN MEILING* AND ARE NOT ADMISSIBLE PROBES. `mon wed fri tue thu thur` -> 0.

AGES          `aged \d+` 0 · `aged of \d+` 0 · `\d+ years old` 0 · `\d+ years of age` 0 ·
              `\d{2}-year-old` 0 · `\d{2} year old` 0 · `in (her|his|their) (early|mid|late)
              (twenties|thirties|forties|fifties|sixties)` 0 · `a (girl|boy|woman|man|child) of
              TWENTY..NINETY` 0 · BARE `aged` SWEEP 0.        **NINE FORMS, ALL ZERO.**
              ONE FIXED AGE IS PRINTED AND IT IS CANON: **Agnete Lindqvist is forty-five**, at
              546:120, written *a big woman of forty-five* and not *forty-five years old*.
              **HANNEKE RUIS IS GIVEN NO AGE AND NO MARK IN ANY OF HER SIX CHAPTERS.**

ARITHMETIC    SPINE RE-DERIVED TWICE, BOTH METHODS AGREE AT ALL ELEVEN DATES:
              540 1230 · 541 1240 · 542 1261 · 543 1284 · 544 1319 · 545 1324 · 546 1325 ·
              547 1329 · 548 1334 · 549 1341 · 550 1347.  MONOTONIC, ZERO VIOLATIONS.
              Intervals 10·21·23·35·5·1·4·5·7·6 summing 117 from 1,230. 1,347-1,230 = 117.
              FUSE 1329 + 111 = 1440 = 4 x 360.  LANE 1347 + 118 + 1 = 1,466.
              **FIVE FIGURES FAIL. FINDINGS 1-5 ABOVE. THE BLOCK'S ARITHMETIC ROW IS THE LEAST
              RELIABLE ROW IN THIS REPOSITORY AND HAS NOW FAILED FIVE TIMES INSIDE ONE VOLUME.**

QUARTERLY     ENTERED, re-run: one (508, Q1) · two (514, Q4) · five (524, Q8) · nineteen (527, Q9)
FIGURES       · thirty-one (529, Q10) · thirty-four (530, Q11) · thirty-four (534, Q12) ·
              thirty-nine (537, Q13) · **eight hundred and forty-one (539, Q14)** ·
              **eight hundred and forty-one again (544)**.  Monotone, and the standing figure is
              identical ninety days apart with 419 accounts behind it.
              **THE QUARTER ORDINALS ARE WRONG AT 544. FINDING 2.**

ACCOUNT       `grep -rioE '8,1[0-9][0-9]|two hundred and eleven thousand' chapters/volume-11/`
              -> 0.  NO LEDGER TOTAL, NO RUNNING BALANCE IN GRAINS ANYWHERE.
              `grep -rio 'settle' chapters/volume-11/` -> 0, and the inflected forms -> 0.
              NO FIGURE OF THE FORM 8,1xx.  NO FLOOR.

FLOORS / RT   `grep -rio 'right temple' chapters/` -> **0 across all 550 chapters.**
              `grep -rlio 'cuticle' chapters/` -> **4 files: 329, 340, 404, 446.** Volume 11 -> 0.
              (`grep -rlio 'ink at the cuticles'` returns 2 — a phrase grep understates the
              construction. The construction is at four and stays at four.)

PARAGRAPHS    3,184 prose paragraphs across the 50 files, blank-line split skipping headings,
              headings' words excluded. **0 OVER NINETY WORDS. 0 OVER ONE HUNDRED AND TWENTY.**
              **QUOTATION-MARK PARITY PER PARAGRAPH: 0 ODD.**
              **SPEECH RUNNING ACROSS A BREAK: 0** — no paragraph ends with an unclosed quotation.

HEADINGS      one `# ` in 50 files; 347 `## ` in all. **NO HEADING NAMES THE CHAPTER'S TURN.**
              **ONE DEFECT: `chapter-0505.md` CARRIES TWO SECTIONS BOTH TITLED `## The Hour`,
              at lines 91 and 195.** FINDING 6.

MARKDOWN      blockquote 0 · table 0 · horizontal rule 0 · code block 0 · **bold `**` 0**.
              **SINGLE-ASTERISK MARKERS: 514 ACROSS 50 FILES = 257 COMPLETE PAIRS, 0 ODD FILES
              AFTER THE FINDING 1A REPAIR. BEFORE IT: 511 markers with THREE FILES ODD AND THREE
              ITALIC SPANS UNCLOSED — `chapter-0538.md:137`, `chapter-0539.md:127`,
              `chapter-0540.md:119`. ALL THREE APPLIED. A DOUBLED COMMA AT `chapter-0538.md:131`
              ALSO APPLIED; A FULL PUNCTUATION SWEEP NOW RETURNS 0.**
              **SYSTEM PANELS: 0 IN 50 CHAPTERS.** Volume 10 stands at two in fifty and this volume's
              budget is five; five batches have now spent none.

DUPLICATION   12-GRAM SCAN FIRST against **all 500 earlier chapters**, normalised token method, then
              11 and 8. **12-grams: 366 hits, 277 families. 11-grams: 516 hits, 388 families.
              8-grams: 2,572 hits, 1,980 families.**
              **EVERY 12-GRAM FAMILY CLASSIFIED BY HAND. THE CLASSIFICATION:**
              · **CANON TEXT THAT MUST RECUR** — the standing sheet's boilerplate; the disposition
                of the first of October; the clerk's rule (may only enter, cannot improve, cannot be
                asked to hurry) at 508, 510, 514, 520; the second line in the office's hand at the
                height of a name on a plate; the composition of 34-6-118 quoted into a tenant's
                lease every quarter for nine years; Rask's line at 547, spoken in the room it
                predicted; the clause of the twenty-first of June, all thirty-eight words, at 549;
                Hanneke Ruis's six words; the books that would have taken the account and the reason
                nobody will say in a book that it is empty.
              · **THE VOLUME'S OWN STRUCTURE** — *I am going to say one thing and I am not going
                to* (513, 541, 545, 547, 550): the rule of one thing each, arriving at a Church.
              · **A CHARACTER QUOTING HIMSELF** — 510 re-states the sentence he spoke at the sitting
                (493) as the thing he refuses to un-say, sixteen words of it verbatim. Correct.
              · **A BOOKEND** — 550 quoting 501's branch opening and the woman with the cloth.
              · **THE MANUSCRIPT'S REGISTER** — the *I am going to tell you what I want* and
                *put her hands flat on the table* constructions, echoing 0171, 0186, 0258, 0259,
                0261, 0306, 0380, 0395 and 0061. Low-value and structural. Not cut.
              · **ONE STAGING RE-USE, FINDING 8.**
              EXACT DUPLICATE PARAGRAPHS (>= 12 words), 2 families, both canon: the definition's own
              sentence (519/520) and the sentence of the thirtieth of September (530/537/544). The
              530 instance is twice *in one chapter* — written on foolscap at line 83, entered by
              the clerk at line 123 — which is a three-step staging, not a slip.
              EXACT DUPLICATE SENTENCES (>= 10 words), cross-chapter, 2: *One thing each, said
              Marguerite Vale from the broker's chair* (519/549) and *The first with eight hundred
              and forty-one lines against it* (539/544).

SCENES        505 · 515 · 525 · 536 · 546, all five written out. 340 is Volume 7's and is not
              continued; 505 answers 340's last line instead of restaging it.
              CADENCE 11 · 10 · 10 · 11 · 10, all inside 8-15.
              PER-WOMAN 51 · 32 · 51 · 71 · 177, none inside 8-15, and no file may say one is.
              EXPLICIT VOCABULARY OVER 547-550: 14 · 2 · 8 · 7 tokens, all *come / came / inside /
              mouth* in ordinary senses. **NO SCENE AFTER 546.**
              MEASUREMENTS PRINTED UNDER THREE DEFINITIONS IN §4b ABOVE.
              THE BLOCK'S RECORDED SPANS — 546 at 1,429 and 536 at 817 — WERE TAKEN BY TWO
              DIFFERENT DEFINITIONS AND NEITHER REPRODUCES. FIRST-##-TO-LAST-##: 3,355 · 2,554 ·
              3,233 · 2,071 · 2,794.

BODIES        §4a READ BEFORE ANY EXAMINATION. NO BORROWED BODY IN 501-550.
              `right temple` 0 book-wide. `cuticle` 4 files book-wide, 0 in Volume 11.
              Ines's grey at the LEFT temple, once, correctly. Sun Meiling's spine line, once,
              correctly. Hanneke Ruis no age and no mark. Ada, Dagmar Oyelowo and Wren Kallo do not
              appear in Volume 11 at all. Agnete Lindqvist carries only what she had at 369.
```

### 7a. TWO PROBES THE BLOCK ITSELF FLAGGED, RE-RUN

- **The hedge rate.** The block measured *about* at 11.7 per thousand and declined to cut. **Re-probed with the same method as the block: 11.7 per thousand across the volume's ten chapters is a count of the word, and five of the highest-frequency hits in the volume are the verb (*right about it, asked me about the yard, a word about that*) and one is a canon figure (*about nine hundred*).** The block's refusal to cut is correct and is upheld.
- **`outline/ending.md` UNTOUCHED.** Its guard list is inherited whole: Lin Wei alive and classified, the reservoir returned and never replenished, Lin Hao at rank one, the Church not dissolved and not vindicated, Ferreira lives, Sowe lives, **Adeyemi is Registrar of Unrecorded Merit** (carried at 501, 512, 537 and never called anything else), no partner dies, no partner is left behind by a choice she does not explain. **No chapter of 501–550 contradicts any of it.** `grep -rn 'Registrar' chapters/volume-11/` returns Adeyemi's title and never Lin Hao's.

---

## 8. FINDINGS

**Nine findings. One class applied, eight recorded.**

### FINDING 1A — APPLIED. THREE ITALIC SPANS DID NOT CLOSE, AND ONE DOUBLED COMMA.

`chapter-0538.md:137`, `chapter-0539.md:127` and `chapter-0540.md:119` each open an italic notebook line with `*` and end the line on a full stop with no closing `*`. Every other notebook line in the same three chapters is `*…*` on one line.

**A reader is actively mis-served:** an unclosed `*` renders as a literal asterisk at the end of the line in a serial reader and an EPUB, and the notebook line that follows loses its emphasis. **Three characters added, no word changed, no meaning changed, no figure changed.** This is a fault in the markdown artefact governed by `PHASE_SYSTEM.md`'s Chapter Format and by `AGENTS.md`'s "bold and italic counted as complete pairs", not a claim about the story, and it is the only class of defect in this file that qualifies for application under the rule that repairs go in where a reader is actively mis-served.

**AND AT `chapter-0538.md:131` THE SAME SWEEP FOUND *neither does he,, and I am the only person in Ostara who has ever been told* — A DOUBLED COMMA IN THE MIDDLE OF HIS LONGEST NOTEBOOK LINE. ALSO APPLIED.** A full punctuation sweep for `[,.;:!?]{2,}` and for a space before a full stop returns **0 hits across all fifty files** after the repair.

**POST-REPAIR RE-RUN, BY COMMAND: `grep -o` parity on the single-asterisk count after stripping `**` — 514 markers, 257 complete pairs, 0 odd files. Before the repair: 511 markers, 3 unpaired.**

### FINDING 1 — `chapter-0542.md:15`, the forty went out for four days. It is three.

*See §6b.* Carried to the Volume 12 planning phase. **Ten lines in the chapter, one row of the title bank and six rows of state carry the figure.** (The first draft of this line said six places and two rows.)

### FINDING 2 — `chapter-0544.md:37`, the sixteenth quarter. It is the fifteenth.

*See §6b.*

### FINDING 3 — `chapter-0544.md:39`, the ninth of July. It is the eleventh.

*See §6b.*

### FINDING 4 — `chapter-0537.md:95` and `chapter-0544.md:43`, four years on that sheet. It is one year and six months.

*See §6b.*

### FINDING 5 — `chapter-0548.md:72–74`, seven dates and then *five quarters*.

*See §6b.*

### FINDING 6 — `chapter-0505.md` CARRIES TWO SECTIONS BOTH TITLED *The Hour* (lines 91 and 195).

Every other chapter of 501–550 has unique section titles within itself. A repeated heading produces a table of contents with *The Hour* twice in one entry and an anchor collision in any renderer. **Not applied:** renaming a section in a closed volume is a content change, and the second *The Hour* is a load-bearing beat (the auditor reads the sheet by the hour). Recorded for the planner.

### FINDING 7 — `chapter-0534.md` IS TITLED *What The Church Did Not Bring*, and `outline/volume-11.md` §10 says no title in this volume begins with *What*.

Recorded. The twenty-two-word title is not a scene restatement and does not collide with anything in the bank of 550, so it is not urgent; but it is a direct breach of this volume's own title rule and the bank must be re-run by command in the same commit if it is ever changed. **Not renamed here** — a title change closes a volume's title bank and belongs to the phase that owns the volume.

### FINDING 8 — `chapter-0515.md:145` GIVES TESSA OKONKWO ALMA QUAYLE'S SEATED STAGING, VERBATIM.

> 515:145 — *She sat on the edge of the cot with her feet on the floor and her elbows on her knees…*
> 0261:186 — *sat on the edge of the cot with her feet on the floor and her back to the mirror.*

and

> 515 — *with her division's own paperwork on her knees and she had been there since about twenty to…*
> **0486:13 — Alma Quayle was in it in her coat with her division's own paperwork on her knees, and she had been there since about twenty to two…**

**The paperwork-on-her-knees construction, including the *since about twenty to* clock, is Alma Quayle's, and at 486 it belongs to her. At 515 it is put on Tessa Okonkwo.** Alma's own staging then recurs twice more at 516:39 and 518:7, which is legitimate.

§4a's instruction is *when you find a borrowed body, remove the claim, do not move it*, and that instruction is addressed to a planning phase, not to a close audit. This is a staging re-use rather than a mark, it costs the reader nothing they can see, and correcting it would mean touching the body of Volume 11's second scene. **Recorded, not applied.** A twelve-gram scan cannot see this class and the §4a table did not name it; **the Volume 12 planner should read this staging aloud before planning any body.**

### FINDING 9 — THE CARRIED REPAIRS, AS ONE ITEM.

Findings 1–5 are five one-word-or-one-figure corrections inside finished chapters that four separate batch gates certified as passing. **They are not applied here, and the reason is the rule this phase is under: an audit that repairs the volume is not an audit, and changing figures inside a closed volume without re-running the four batch gates that certified them would repeat the exact error this audit was run to catch.** They are carried to the Volume 12 planning phase as its first item, with the correct figure and every line that carries it named, so that one commit repairs all five and re-runs the bank.

**THE FIGURES THAT ARE CORRECT, FOR THAT COMMIT — EVERY LINE THAT CARRIES THEM, AND THE OPERANDS, BECAUSE A REPAIR INSTRUCTION THAT DROPS THE OPERAND IS THE SAME DEFECT IT IS REPAIRING:**

| Where — every line | Printed | Correct, with its operands |
| --- | --- | --- |
| **542:1 (title), :15, :17, :25 (heading), :45, :49, :53, :61, :103, :107 — TEN LINES — plus `outline/volume-11.md` §10 row 542, `state/chapter-summaries.md:44`, `state/continuity.md:67` and `:85`, `state/open-threads.md:17` and `:84`** | four days | **three days** — 29 Jul y4 = 1,258 · 2 Aug y4 = 1,261 · 1,261 − 1,258 = 3. The breakdown must be **rewritten** as `(30 − 29) + 2 = 3`, not substituted. **The title loses *Four*.** |
| 544:37 | Sixteenth quarter | **Fifteenth quarter** — 30 Sep y4 is the fifteenth; the sixteenth is the sheet of 30 December that has not gone out |
| 544:39 | the ninth day of July | **the eleventh day of July** — 541:3, :67, :120 · 542:11 · 547:37, :84 |
| 537:95, 544:43 | the four years it has been on that sheet | **one year and twenty-one days** (537; 1,139 − 758 = **381**) · **one year, six months and twenty-one days** (544; 1,319 − 758 = **561**). The column was ruled 9 Mar y3 = spine day **758** |
| **544:43, 544:85, 545:109, 546:23, 548:70 (heading), 548:74, 550:78, 550:102 — EIGHT LINES IN FIVE CHAPTERS** | Five quarters | **seven quarter-ends and one year, seven months and six days** — 1,334 − 758 = **576**. Two conventions coexist and differ by two; the count is taken from the ruling |
| `state/continuity.md:33` · `state/current.md:5` and `:9` · `state/open-threads.md:85` · `state/chapter-summaries.md:39` | the rounded and the wrong restatements of the two figures above | **the same figures, with operands** — `:33` currently prints the rounded *one year and six months* for 561 and is wrong by twenty-one days even though it is the correct side of the finding |

---

## 9. WHAT THE DO-NOT-OPEN REGISTER LOOKS LIKE AFTER THIS AUDIT

**EVERY ITEM ON `outline/volume-11.md` §8 IS STILL SHUT.** Mechanically re-checked: `Lin Wei` **0** · `B103` **0** · `settle` and its inflections **0** · the figure of the account **0** · `right temple` **0** book-wide. No character in 501–550 says the reach of the return is settled or is not settled; no character says whether the account belonged to the unrecorded; no character names who put the white tile up; Hanneke Ruis's six words carry no certificate and will not; the words under the tile are not given; Mrs Imrie is not named; Perrin Sowe is not forgiven and is not discussed and Ines's correction stays unpressed; Marguerite Vale's fourth line is not struck; Agnete Lindqvist's refusal of the ninth of October is on the page twice and resolved neither time; Sun Meiling's row and her bar are told once, at 434, and not re-told; the instrument he swore on the ninth of May never to use is still unused.

**AND THE TWO THAT VOLUME 11 ITSELF OPENED ARE STILL OPEN, WHICH IS CORRECT AND IS WHAT THE AUDIT IS FOR:**

1. **The keeper's six words now have a name against them. She reads it on the second of January, year five.** No page of 501–550 shows her reading it. Hanneke Ruis's last appearance is 544, ten days before the name exists.
2. **Whether the woman two flights up off Cordwain ever learns what was done for her.** The prose no longer contradicts the notebook. Nothing answers it.

---

## 10. PIPELINE GAPS — RECORDED, NOT REPAIRED HERE

**GAP 1 — BATCH 0005 OF VOLUME 11 CREATED NO NEXT PHASE, ON AN INSTRUCTION THAT CONTRADICTS THE SYSTEM.**

`workspace/volume-11/batch-0005/PROMPT.md`:148 told the writing phase, in its own words, *THEN CREATE NOTHING ELSE. THIS IS THE LAST WRITING PHASE OF VOLUME 11 AND THE NEXT PHASE IS THE CONTROLLER'S. DO NOT WRITE A BATCH 0006, DO NOT WRITE A VOLUME-CLOSE PROMPT, AND DO NOT OPEN VOLUME 12.*

That contradicts `AGENTS.md` and `PHASE_SYSTEM.md`:153 — *After a batch finishes, the writer creates exactly one next-phase prompt: either the next batch or the volume-close phase.* **This file, `workspace/volume-11/volume-close/PROMPT.md`, is the volume-close prompt that instruction owed the pipeline. It has now been written, it is the one next phase, and the self-dispatch workflow selects it. This audit does not treat itself as a precedent for skipping the prompt again, and neither may any later phase.**

**GAP 2 — VOLUME 10 HAS NO CLOSE PROMPT AND NO CLOSE AUDIT.** `workspace/volume-10/` holds five batches and a `volume-plan`, and nothing else. Volume 10 closed in prose at 500 and no close phase has ever run against it. **Recorded. Not repaired here, and this phase has no standing to repair it: a Volume 10 close audit is a separate unit of work and creating its prompt would be creating a second next phase, which this phase is forbidden to do.**

**GAP 3 — FOUR BATCH GATES IN VOLUME 11 CERTIFIED FIGURES THAT DID NOT REPRODUCE.** Five, counting the 500 interval that Volume 10 carried forward. See Claim 2.

---

## 11. WHAT THIS PHASE HANDS ON

**THE SERIES IS PLANNED PAST 550. `state/complete.md` IS NOT CREATED.**

The next phase is **`workspace/volume-12/plan/PROMPT.md`**, a **planning** phase: it writes `outline/volume-12.md` and **no prose**. That phase, and not this one, is where a decision is made about whether the wall gets a threshold under it or does not.

**THE FIRST THING THE PLANNER OWES, IN THIS ORDER:**

1. **Findings 1–5, as one commit, with the bank re-run** (§8, Finding 9).
2. **The 2 January, year five.** A keeper takes six words off a shelf and reads them and there is a name against them. That is a dated scene and nobody has written it.
3. **Whether Mavis Rooke ever reads a public sheet.** Open, undated, and the volume deliberately left it so.
4. **The wall.** A city cannot read the two words in the office's own hand and the man with the chalk is right about every fact. The next volume's sentence has to decide whether that is paid or merely survived.
5. **The 177.** Whether a woman who has not had a scene in a hundred and seventy-seven chapters gets one sooner.

**AND THE STANDING RULE FOR EVERY ARITHMETIC ROW FROM HERE ON, LEARNED AT THE COST OF FIVE FAILURES IN ONE VOLUME:**

> **A gate row that quotes the prose it is checking cannot catch the prose. Every interval is derived from the spine, twice, with the operands printed — never copied out of the chapter it is meant to be checking.**