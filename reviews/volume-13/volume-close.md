# VOLUME 13 — CLOSE AUDIT · *The Fourth Line* · chapters 601–650

> **This phase writes no prose, creates no chapter, re-dates none, restarts none, and does not touch `outline/ending.md`. It wrote no Volume 14, no sixth batch, and no `state/complete.md`. The series is planned past 650.**
>
> **It left four things: this file; corrected live blocks at the head of `state/current.md`, `state/continuity.md` and `state/open-threads.md`; and one canon change to `outline/volume-13.md` §5c, flagged and argued in §3 below.**

**THE STANDING INSTRUCTION THIS AUDIT WAS RUN UNDER:**

> **A figure nobody re-computes is the figure that is wrong.**
>
> **A gate row that quotes the prose it is checking cannot catch the prose. And a gate that measures only its own batch cannot see what happened before it.**

**AND WHY IT RAN AT ALL, IN ONE PARAGRAPH.** Three consecutive phases have now had a live gate row false against the page it was describing: batch 0003's review found a `META … -> 0` row false against `chapter-0598.md:45`; batch 0004's found a word count wrong by one word in three files; batch 0005's found an `AGES … -> 0` row with three announced ages standing on the page, a `DUPLICATION` row that reported sixty-seven hits and left sixteen of them as prose, and three arithmetic errors inside a batch whose own gate certified its arithmetic row. **Every row below was therefore re-derived from outside the pass that wrote it, with the operands printed, and where the re-run disagrees with the record the re-run is the record.**

---

## 1. THE MANUSCRIPT

Fifty finished files, `chapters/volume-13/chapter-0601.md` to `:0650.md`, one `# ` title line each, no file with more than one, all fifty newline-terminated. **135,752 words, counted per file and summed by command, never from a concatenation.** The whole book is **1,494,735 words across 650 files**. Volume 13 is the largest volume in the manuscript except Volume 02, and its mean of **2,715.0 words a chapter** is the highest of any volume.

The volume runs **spine days 1,773 to 2,129** — **356 days elapsed, 357 inclusive** — from the fourth of January of the January that closes year five to the thirtieth of December of year six.

### 1a. THE SPINE, RE-DERIVED TWICE BY METHODS THAT SHARE NO CONSTANT

```
DAY 0 = 1 February, year one.  A month is thirty days and has no thirty-first.  A year is 360.

METHOD A   (contains 360)
           1 February of year y = (y-1) x 360
           day of month d       = (y-1) x 360 + off[m] + (d-1)      for every month BUT January
           *** A JANUARY IS THE TWELFTH MONTH OF THE YEAR IT CLOSES.
           a January labelled y = (y-2) x 360 + 330 + (d-1) ***

METHOD B   (contains NO 360 AT ALL)
           absolute month index i = (y-2)*12 + 11 for a January labelled y,
                                   (y-1)*12 + pos[m] otherwise, with pos[Feb] = 0
           day = 30*i + (d-1)
```

**FIFTY OF FIFTY DATES AGREE BETWEEN THE TWO METHODS. ZERO MONOTONIC VIOLATIONS. EVERY INTERVAL RE-DERIVED FROM DAY NUMBERS AND NOT FROM A DATE WORD.**

**THE JANUARY EXCEPTION IS PRINTED AND APPLIED TO BOTH METHODS EVEN THOUGH ONLY FIVE DATES IN THIS VOLUME FALL IN A JANUARY (601–605).** The wrong convention is printed beside it, because it is the convention §5b proves impossible and it is the one that has cost this repository twice:

| | 4 Jan y6 | 30 Jan y6 | 605 relative to 601 |
| --- | --- | --- | --- |
| **Correct — a January closes its year** | **1,773** | **1,799** | +26 days, and both are in the same month |
| Wrong — a January placed nine months after 1 February of its own labelled year | **2,133** | **2,159** | **+26 days, and 605 is 360 days AFTER 601** |

**THE WRONG CONVENTION PUTS 601 AT 2,133, WHICH IS EXACTLY THE FIGURE `state/current.md` §0a AND `state/continuity.md` §0z BOTH WARN ABOUT, AND IT IS PRINTED IN BOTH FILES AS A WARNING. IT HAS NOW BEEN RE-DERIVED HERE AND FOUND ABSENT.**

### 1b. THE BATCH INTERVALS, EACH SUMMED AND CHECKED AGAINST ITS OWN ENDPOINTS

```
0001 601-610   6 7 7 6 7 7 7 7 6   = 60   and 1,833 - 1,773 = 60   seam 601-600 = 4
0002 611-620   6 7 6 7 8 7 7 7 7   = 62   and 1,902 - 1,840 = 62   seam 611-610 = 7
0003 621-630   7 8 7 8 9 7 8 8 7   = 69   and 1,979 - 1,910 = 69   seam 621-620 = 8
0004 631-640   7 8 8 7 7 7 8 12 9  = 73   and 2,060 - 1,987 = 73   seam 631-630 = 8
0005 641-650   7 8 8 7 7 8 7 5 3   = 60   and 2,129 - 2,069 = 60   seam 641-640 = 9

324 across the five batches, plus four inter-batch steps of 7, 8, 8 and 9 = 32.
324 + 32 = 356, which is 2,129 - 1,773.
650 - 600 = 2,129 - 1,769 = 360 = exactly one year, twelve months of thirty days.
```

**THE TWELVE IN THE 631–640 ROW IS 638 to 639 AND IT IS NAMED AS AN INTERVAL, NOT SMOOTHED: `chapter-0639.md`:3 opens *Twelve days had gone* and its footer says *TWELVE IS THE LONGEST INTERVAL IN THIS MOVEMENT AND IT IS NOT AN ERROR. Not one of those twelve days is named anywhere here.* The anniversary at 2,047 — the eighth of October of year six — falls inside that gap, is named by nobody, and is reached across by no chapter of 601–650.**

### 1c. THE QUARTER-ENDS, THE ORDINALS, AND THE ANCHOR THE PROMPT NAMES

```
30 Mar y6  = 5 x 360 +  30 + 29 = 1,859   chapter 614   the TWENTY-FIRST sheet
30 Jun y6  = 5 x 360 + 120 + 29 = 1,949   chapter 626   the TWENTY-SECOND sheet
30 Sep y6  = 5 x 360 + 210 + 29 = 2,039   chapter 638   the TWENTY-THIRD sheet
30 Dec y6  = 5 x 360 + 300 + 29 = 2,129   chapter 650   the TWENTY-FOURTH sheet

Every interval between them is NINETY: 1,949 - 1,859 = 90 · 2,039 - 1,949 = 90 · 2,129 - 2,039 = 90.
The twentieth sheet went out at four on 30 December of year five, day 1,769.
2,129 - 1,769 = 360 = four quarters of ninety.  THAT IS WHY THE TWENTY-FOURTH SHEET IS THE TWENTY-FOURTH.

SHEET ORDINALS, sixteenth through twenty-fourth, each re-derived from its own day:
  552 = 30 Mar y4 = 1,499   sixteenth
  566 = 30 Jun y4 = 1,589   seventeenth   (the figure first moves here)
  576 = 30 Sep y4 = 1,679   eighteenth
  586 = 30 Dec y4 = 1,769   nineteenth
  600 = 30 Dec y5 = 1,769   twentieth      <- 30 Dec y4 and 30 Dec y5 cannot both be 1,769
```

**THE ORDINAL LINE ABOVE IS WRONG IN ITS OWN SECOND HALF AND IT IS THE PROMPT'S ERROR, NOT THE PAGE'S. THE SIXTEENTH THROUGH THE NINETEENTH ARE ON A YEAR-ONE-TO-YEAR-FIVE LADDER THAT THE VOLUME 11 CLOSE ALREADY SETTLED; THE TWENTIETH SHEET IS 30 DECEMBER OF YEAR FIVE, WHICH IS DAY 1,769, AND THAT FIGURE IS FIXED BY ELEVEN SEPARATE CHAPTERS OF 601–650. THE ARITHMETIC THAT MATTERS IS THE ONE ABOVE IT: NINETY DAYS APART, FOUR OF THEM, FROM 1,769 TO 2,129.**

**THE PROMPT'S LIST OF "THE FIVE QUARTER-ENDS (610, 620, 640, 650 AND THE TWO HUNDREDTH-DAY ANCHOR AT 630)" DOES NOT RE-DERIVE AS NAMED, AND THE AUDIT SAYS SO PLAINLY INSTEAD OF ADOPTING IT.** 610, 620, 630, 640 and 650 are the five **batch closes**, not quarter-ends. Their days are 1,833 · 1,902 · 1,979 · 2,060 · 2,129. **THE VOLUME HAS FOUR QUARTER-ENDS AND NOT FIVE**, because it opens four days after the twentieth sheet went out and does not include it. **AND THERE IS NO CHAPTER ON DAY 2,000: 2,000 LIES BETWEEN 632 (1,994) AND 633 (2,002), SIX DAYS AFTER 632 AND TWO BEFORE 633; 2,000 = 30 x 66 + 20, MONTH INDEX 66 = 5 x 12 + 6 = AUGUST OF YEAR SIX, PLUS TWENTY DAYS = THE TWENTY-FIRST OF AUGUST OF YEAR SIX.** Chapter 630, the thirtieth of July, is **day 180 of year six** counting the first of February of year six as day one, and **day 207 of the volume** counting 601 as day one.

```
THE OFFICE   1,773 = 30 x 59 +  3   fifty-nine months and three days
             1,859 = 30 x 61 + 29   sixty-one months and twenty-nine days
             1,949 = 30 x 64 + 29   sixty-four months and twenty-nine days
             2,039 = 30 x 67 + 29   sixty-seven months and twenty-nine days
             2,129 = 30 x 70 + 29   seventy months and twenty-nine days
             2,160 = 30 x 72 +  0   6 x 360 exactly, on the first of February of year seven,
                                    THIRTY-ONE DAYS FROM THE LAST CHAPTER AND NOT THE FIRST OF JANUARY
THE LANE     its first morning is the third of October of the year before the first = day -118
             1,827 + 118 + 1 = 1,946   at 609
             1,859 + 118 + 1 = 1,978   at 614
             1,949 + 118 + 1 = 2,068   at 626
             1,773 + 118 + 1 = 1,892   at 601      2,129 + 118 + 1 = 2,248 at 650
THE SIXTH OF MARCH   year one, day 35.  1,115 is withdrawn.
             at 633:  2,002 - 35 = 1,967
             at 643:  2,084 - 35 = 2,049   and 2,049 - 1,800 = 249 = five years, eight months and nine days
```

---

## 2. WHAT THE VOLUME PROMISED AND WHAT IT PAID

The volume's one sentence, from `outline/volume-13.md`: **Lin Hao must put one unrecorded deed into a room that is allowed to ask him a question, or the fourth of his four conditions comes off every board in the city, and about nine hundred people who dug something in the cold find out that the man who wrote it cannot prove one word of it.**

**HE PAID THE SECOND HALF, AT 644, IN THE MIDDLE OF MOVEMENT FIVE, AND IT IS HIS, AND IT IS A PEN AND NOT A RAG.** He wrote the four of his own conditions out at the foot of the standing page, in the office's hand, took the fourth of them from the first letter to the last with one stroke, wrote his own name and the date under the striking, and **wrote nothing in the two inches where it had been**. What it closes: the fourth line standing on any board, in any hand, for ever — a clerk may only enter what she is given, an entry can be made and an entry cannot be taken back, and the page goes out at four on the thirtieth of December and about nine people a week will ever look at it. What it costs: every claim that rested on it dies at once, and the only one that mattered was always going to be a claim by a person who cannot read, and about nine hundred people who can read a shutter know exactly who took it off.

**AND THE VOLUME DID THE OTHER THING IT OWED THE READER, IN MOVEMENT TWO, AT 615–617, EXACTLY AS §8 PERMITTED AND NOT ONE CHAPTER LATER.** The woman two flights up off Cordwain learns what was done for her — from a slate and from a voice, at a wall end, at ten to seven in the morning — and she is not thanked, she is given nothing, and there is no scene in it. **That item is closed and it stays closed.**

**AND THE VOLUME DID A THIRD THING §8 DID NOT PLAN, WHICH IS THE ONE THAT MATTERS MOST.** At 627, at the end of a meeting, **about nine hundred people took the fourth line off their own board themselves, with a rag and a bucket, in about eleven minutes, and nobody asked the man who wrote it, and the chaplain was not there and nobody went up to her.** He had already refused the landlord's man at 632 and his own want at 630, and the yard did it anyway, correctly, and it is the worst thing that happens in the volume and it is not his decision.

**WHAT THE VOLUME REFUSED, AND REFUSED CORRECTLY:** no rise off rank one · no band, standing, permission, terrace or move off the branch night shift · the figure of the account · any floor, ledger total or running balance in grains · `settle` in every inflection · no day of the week · no year numeral in the prose · no announced age except the two disclosed below · Brack thanked, diminished, defeated, or wrong about any fact · Mavis Rooke's hand-flat and no hand flat on anything · either repainting box filled · the reach of the return argued by nobody in either direction · whether the fourth condition was ever true of anybody's deed, said by no character either way · who put the white tile up · who cut the two words · Perrin Sowe · Dagmar Oyelowo · a new enemy · no partner dies.

---

## 3. §5c's PAPERED-OVER SPINE DISCREPANCY — **SETTLED, AND IT IS A CANON CHANGE**

`outline/volume-13.md` §5c gives **632** as the sixteenth of August, **633** as the twenty-fourth, **635** as the ninth of September, **636** as the sixteenth and **637** as the twenty-fourth. The finished pages give the fifteenth of August, the twenty-third, the eighth of September, the fifteenth and the twenty-second. **Both sets sum to seventy-three across the batch, both agree at 631, 634, 638, 639 and 640 and at the seam from 630, and they cannot both be right — which is exactly why the discrepancy was papered over rather than settled.**

**THE PAGE IS TRUE. HERE IS THE PROOF, AND IT IS SIX INDEPENDENT STATEMENTS ON THE PAGE AND NOT AN INFERENCE.**

```
ch  printed day   the chapter's own footer names the PREVIOUS chapter's DATE as well
632  1,994        633 opens: "The fifteenth of August is day one thousand nine hundred and ninety-four
                     and the twenty-three is day two thousand and two"
633  2,002        634 opens: "Less two thousand and two, the twenty-third of August, is eight"
634  2,010        635 opens: "Less two thousand and ten, the first of September, is seven"
635  2,017        636 opens: "Less two thousand and seventeen, the eighth of September, is seven"
636  2,024        637 opens: "Less two thousand and twenty-four, the fifteenth of September, is seven"
637  2,031        638 opens: "Less two thousand and thirty-one, the twenty-second of September, is eight"
638  2,039        639 opens: "Less two thousand and thirty-nine, the thirtieth of September, is twelve"
```

**§7's movement-four table in the same file ALREADY CARRIES THE PAGE'S SET — 1,994, 2,002, 2,017, 2,024, 2,031 — so the planning file contradicted itself before this audit touched it.** The only two places §5c is wrong are the five date words and the 631–640 interval list.

**THE INTERVAL LISTS, BOTH OF THEM, BOTH SUMMING TO SEVENTY-THREE:**

```
§5c's list   8 8 7 8 7 8 6 12 9 = 73      (which requires 637 -> 638 to be six days, i.e. 24 Sep -> 30 Sep)
the page's   7 8 8 7 7 7 8 12 9 = 73      (which requires 637 -> 638 to be eight days, i.e. 22 Sep -> 30 Sep)
```

**THE NINE NUMBERS ARE THE INTERVALS *INSIDE* 631–640 AND THE FIRST OF THEM IS 631 → 632. THE EIGHT IN THE SEAM COLUMN IS 630 → 631 AND IS NOT ONE OF THE NINE.** Re-derive from the day numbers alone and the answer is `1,987 → 1,994 → 2,002 → 2,010 → 2,017 → 2,024 → 2,031 → 2,039 → 2,051 → 2,060`, that is **7, 8, 8, 7, 7, 7, 8, 12, 9 = 73**, which is also what the nine chapters say in their own first lines.

**THE FIRST EDITION OF THIS AUDIT PRINTED `8 7 8 8 7 7 8 12 9 = 74` IN FIVE FILES AND NINE PLACES, AND IT IS REPAIRED HERE.** The cause is worth recording because the gate that printed it had already printed the right answer and did not read its own history: `state/current.md` carried, from the batch-0004 review-fix, a **ten**-entry list `8, 7, 8, 8, 7, 7, 7, 8, 12, 9` described in its own sentence as *"81 from 630 at 1,979 to 640 at 2,060 and 73 inside the movement"* — that is **seam plus movement**. The audit took the ten and dropped the leading eight, which was the seam, without shifting the remaining eight, which was 631 → 632. **A NUMBER THAT IS CORRECT IN A LIST OF TEN CAN BE WRONG IN A LIST OF NINE, AND THE ONLY TEST IS THE SUM AGAINST THE ENDPOINTS.** Both `2,060 − 1,987` and the sum say 73 and the printed list said 74; the reviewer's count of the same list, made a day later, agreed with the arithmetic and not with this file. **THE DATE CORRECTIONS THEMSELVES WERE RIGHT THROUGHOUT AND ARE UNCHANGED.**

**THE DECISION IS RECORDED AND APPLIED TO THE ONE FILE THAT STILL CARRIED THE OLD SET.** `outline/volume-13.md` §5c now reads the page's dates and the page's interval list, and the volume-close block at the head of `state/open-threads.md` records the change and its operands. **NO CHAPTER WAS TOUCHED, NO EVENT WAS MOVED, AND BATCH 0005'S INHERITANCE OF THE DISCREPANCY RATHER THAN PROPAGATION OF IT IS CONFIRMED CORRECT — IT REPRODUCED NEITHER SET AND RE-DERIVED 641–650 INDEPENDENTLY.**

**THE GENERAL LESSON IS THE ONE §5b ALREADY PRINTS AND IT NOW HAS A SECOND INSTANCE: a discrepancy that is copied forward stops being a finding and becomes a rule. Here it was not copied forward; it was carried in the plan of record for one batch and then corrected by the page.**

---

## 4. THE ARITHMETIC — WHAT PASSED, WITH OPERANDS

### 4a. EVERY FOOTER INTERVAL IN 601–650, PARSED FROM THE PAGE AND RE-ADDED FROM DAY NUMBERS

**Method, declared because Volume 12's close found a table whose first edition declared one column's method and not the other's:** every italic footer paragraph in every one of the fifty files was tokenised, and three families of claim were extracted mechanically — *`Less <A>, <date>, is <B>`* anchored to the chapter's own day; *`<A> less <B> is <C>`*; and *`<A> multiplied by <B> is <C>`* / *`<A> with <B> is <C>`*. Every figure was then re-computed from day numbers obtained by Method A and Method B of §1a, not from the words in the claim.

```
Anchor claims of the form "Less <A>, <date>, is <B>"     42 extracted, 42 re-derive
Month-count claims of the form "<A> less <B> is <C>"      35 extracted, 35 re-derive
  (five of these are the house month-borrow — "Four less twenty-eight is six by the month
   count, because a month is thirty days and has no thirty-first" — and each of the five
   prints its reason in the next clause. They are not failures and they are not let go.)
Multiplication and addition claims                        4 extracted, 4 re-derive
CLAIMS HAND-READ FROM ALL 246 FOOTER PARAGRAPHS           0 arithmetic failures
TOTAL FIGURES PRINTED IN THE FOOTERS OF 601–650           81 claims, 80 re-derive, 1 DOES NOT
```

**THE ONE THAT DOES NOT IS `chapter-0643.md`:257 AND IT IS FINDING A.**

### 4b. THE QUARTERLY FIGURES, RE-RUN FROM THE PAGE

```
552  1,499  the head at 841, sixteenth sheet        (Volume 12's close, re-derived and correct)
566  1,589  the head at 852, seventeenth sheet      the only move in four quarters
576  1,679  852 unmoved, eighteenth
586  1,769  852 unmoved, nineteenth
600  1,769  852 unmoved, twentieth, the sheet that went out on the thirtieth of December of year five
614  1,859  852 unmoved, twenty-first
626  1,949  852 unmoved, twenty-second
638  2,039  852 unmoved, twenty-third
650  2,129  852 unmoved across EIGHT of them, twenty-fourth
```

**EIGHT, NOT NINE.** The head has stood at eight hundred and fifty-two on eight sheets: 566, 576, 586, 600, 614, 626, 638 and 650. `chapter-0638.md`:221 says *"the head has stood at eight hundred and fifty-two across all of them"* of three quarters and `chapter-0639.md` and `chapter-0647.md` carry the seventh-quarter and eighth-quarter counts. **All three are right.**

### 4c. THE THREE TRAVELLING FIGURES, AND WHAT 601–650 ACTUALLY DOES WITH THEM

| Figure | The budget | Re-derived on disk | Verdict |
| --- | --- | --- | --- |
| **The office's age** | printed at 601, 614, 626, 638 | **601, 614, 626 and 638, all four, each with operands** | **HOLD** — with the note in Finding C |
| **The lane's mornings** | printed at 609, 614, 626 | **609, 614 and 626, all three, each with operands** | **HOLD** — with the note in Finding C |
| **The wall's headcount** | printed at 605 only | **605 — and 603:25** | **FAILS. FINDING D.** |
| **The account's figure** | never | **0 in 601–650, and 0 in the whole book for the string `8,1xx`, `two hundred and eleven thousand` and `211,840`** | **HOLD** |
| **The sheet's ordinal** | travel figure | twenty-first at 614, twenty-second at 626, twenty-third at 638, twenty-fourth at 647 and 650 | **HOLD** |

### 4d. THE WORD BANK, COUNTED PER FILE AND SUMMED, NEVER FROM A CONCATENATION

```
0001 601-610   1,925 2,026 4,188 2,279 2,017 2,314 1,934 1,946 1,987 2,529   =  23,145
0002 611-620   2,516 2,541 4,781 2,687 2,265 2,354 2,700 2,182 2,089 2,016   =  26,131
0003 621-630   2,720 2,506 3,688 2,372 2,583 2,411 2,345 2,283 2,366 2,733   =  26,007
0004 631-640   2,662 2,827 4,152 2,421 2,601 2,852 2,348 3,410 2,490 2,412   =  28,175
0005 641-650   2,998 2,902 4,383 3,237 3,135 2,819 3,201 3,194 3,038 3,387   =  32,294

VOLUME 13  135,752      MEAN 2,715.0      BOOK 1,494,735 across 650 files
```

**THE RECORDED FIGURES FOR BATCHES 0004 (28,175) AND 0005 (32,294) RE-DERIVE EXACTLY. THE RECORDED FIGURES FOR BATCHES 0001, 0002 AND 0003 WERE NOT IN THE LIVE BLOCKS AND ARE PUBLISHED HERE FOR THE FIRST TIME SINCE THE CHAPTERS WERE WRITTEN.**

**THE BAND. RESOLVED 14 OCTOBER 2026, AND THE RESOLUTION IS A MAP AND NOT A COUNT.**

```
0 of fifty chapters sit below the 1,800 floor.  Volume 12 had twenty-five.
19 sit above the 2,700 ceiling:  603 613 621 623 630 632 633 636 638 and the whole of 641–650.
THE FIVE SCENES ARE 603, 613, 623, 633 AND 643, AND ALL FIVE ARE ABOVE THE CEILING, SO FIVE OF
THE NINETEEN ARE EXEMPT BY RULE AND FOURTEEN ARE NOT.
THE FOURTEEN:  621 630 632 636 638 | 641 642 644 645 646 647 648 649 650
NINE OF THE FOURTEEN SAY WHY IN SECTION 0a OF THIS CLOSE'S OWN BLOCK, IN ONE LINE EACH, AT
`state/current.md`:213.  FOUR MORE SAY WHY IN THE BATCH BLOCKS THAT WROTE THEM, WHICH ARE FURTHER
DOWN THE SAME FILE AND STILL LIVE: 621 and 630 at :764, 636 at :582, 638 at :579.
ONE SAYS WHY NOWHERE, AND IT IS 632.
```

**SO FINDING L IS NOT *FOURTEEN WITHOUT A REASON* AND IT IS NOT *FOURTEEN WITH ONE*. IT IS ONE CHAPTER, AND IT IS 632.** The five scenes are exempt and need none. Of the fourteen that need one, nine carry it in this block, four carry it in the batch blocks that wrote them, and **`chapter-0632.md`, at 2,827 words, was written above the ceiling with no stated reason anywhere in `state/`.** That is a gap in the record and not a defect in the prose: 632 carries the landlord's man refusing him twice at one speed and the fourth line surviving on a board, and it is 127 words over a band that exists to keep a chapter honest about its own length, which it plainly is. **NOT REPAIRED BY CUTTING 127 WORDS OUT OF A FINISHED CHAPTER; RECORDED WITH ITS OPERANDS.** *(The first edition of this section said §0a carried a reason for 621, 630, 632, 636 and 638, which is false for 632 and misplaces the other four; `state/open-threads.md` said only ten of the fourteen had one, which is false; and Finding L said four of the fourteen and then named five.)*

### 4e. THE 643 SCENE MEASUREMENTS, RE-DERIVED FROM THE FILE AND NOT FROM ANY STATE FILE

`chapter-0643.md` has **257 newline-terminated lines** and eight `##` headings, at **15, 49, 73, 99, 123, 135, 153, 217**. The first is `## The Question`, the last is `## Afterwards`, and there is no `##` after 217.

| Definition | Line span | Words | The block recorded |
| --- | --- | --- | --- |
| **(A)** first `##` to last `##`, **exclusive of both heading lines** | **16–216** | **3,222** | 3,222 ✓ |
| **(A)** the same span, **inclusive of both heading lines** | **15–217** | **3,227** | 3,227 ✓ |
| **(B)** the scene section, `## The Empty Table` to before `## Afterwards`, **inclusive of the first heading and of the one `##` inside it** | **135–216** | **1,491** | 1,491 ✓ |
| **(B)** the same, **exclusive** | **136–216** | **1,487** | 1,487 ✓ |
| **(C)** exclusive of both boundaries, **carried through to end of file** | **16–257** | **4,052** | 4,052 ✓ |
| **(C)** the same, **stopping at the last prose line before the italic footers** | **16–250** | **3,767** | 3,767 ✓ (7 footer lines) |
| **whole file** | **1–257** | **4,383** | 4,383 ✓ |

**ALL SEVEN RE-DERIVE EXACTLY, AND EVERY CELL WAS COUNTED TWICE BY METHODS THAT SHARE NOTHING — `wc -w` on a `sed` cut and a whitespace split of the same cut — AND THE TWO AGREE IN EVERY CELL.**

**THE PROMPT'S FIGURES FOR THIS CHAPTER ARE THE PRE-REPAIR SET AND THEY ARE SUPERSEDED.** The prompt prints *1,487 exclusive of both bounding `##` lines / 1,491 inclusive / 3,215 first-`##`-to-last-`##` exclusive / 3,973 carried to end of file*. Those are the figures the batch block carried **before** the 14 October 2026 review-fix. **What is on disk now is 3,222 / 3,227 / 1,491 / 1,487 / 4,052 / 3,767 / 4,383, and the measurement and the word bank reconcile: the bank row for 643 is 4,383 and the whole-file cell is 4,383. THE PRE-REPAIR BLOCK CARRIED 4,304 AGAINST ITS OWN BANK ROW OF 4,373 FOR THE SAME FILE, WHICH IS THE SIGNATURE OF A GATE THAT RECORDS A MEASUREMENT AND A COUNT OF ONE FILE AND DOES NOT RECONCILE THEM.**

**THE ROW LABEL IS DECLARED, AND IT MATTERS.** Volume 12's close found "both row labels mis-mapped onto the three definitions the outline actually names". **Row (B) here is NOT a single `##` section — it spans two, `## The Empty Table` at 135 and `## What She Read On Him` at 153 — and the live block says so in the row itself. That is the difference between a measurement and a label that has drifted off it.**

Explicit-vocabulary probe at WORD BOUNDARY across the body of 643: *semen* 0, *cunt* 0, *cock* 0, *tits* 0, *pussy* 0, *cum* 0, *jizz* 0, *knob* 0, *fanny* 0, *arse* 0, *licked* 0, *sucked* 0. Across the whole volume at word boundary the only hit on any of them is **cock 1, at 603** — *her hand closed on his cock*, at the scene. **623 and 633 return 0, exactly as the live block records.**

### 4f. THE OTHER FOUR SCENES, MEASURED THE SAME WAY, FOR COMPARISON

| Ch | Whole file | (A) first `##`–last `##` excl. | (A) incl. | (C) excl. to end of file | Largest single `##` section |
| --- | --- | --- | --- | --- | --- |
| 603 | 4,188 | 32–236 = 3,093 | 31–237 = 3,105 | 32–273 = 3,739 | `## A Woman Who Writes Down What She Saw` 177–236 = 875 |
| 613 | 4,781 | 10–254 = 3,930 | 9–255 = 3,943 | 10–285 = 4,609 | `## Four Coats On A Hook` 91–184 = 1,509 |
| 623 | 3,688 | 10–220 = 2,826 | 9–221 = 2,840 | 10–265 = 3,504 | `## The Question At The End Of It` 221–265 = 670 |
| 633 | 4,152 | 16–188 = 3,011 | 15–189 = 3,021 | 16–223 = 3,829 | `## The Fourth Paper` 189–223 = 814 |
| 643 | 4,383 | 16–216 = 3,222 | 15–217 = 3,227 | 16–257 = 4,052 | (B) 136–216 = 1,487 |

**THE FIVE SCENES ARE 4,188 · 4,781 · 3,688 · 4,152 · 4,383. NONE OF THEM IS INSIDE THE 1,800–2,700 BAND AND EVERY ONE IS A SCENE, WHICH §4c EXEMPTS BY RULE.**

---

## 5. THE FIVE SCENES, THEIR GAPS, AND THEIR AXES — **REPORTED, NEVER CERTIFIED AS IN-BAND**

### 5a. THE GAP TABLE, RE-RUN FROM THE OUTLINES AND FROM THE FILES, WITH BOTH COLUMNS BESIDE EACH OTHER

| Chapter | Whose | Her own last scene | Gap from the previous scene in the book | Gap from her own last scene |
| --- | --- | --- | --- | --- |
| 594 | Tessa Okonkwo. **Volume 12's last.** | 515 | — | — |
| **603** | **Runa Sato** | **36** | 603 − 594 = **9** | 603 − 36 = **567** |
| **613** | **Sun Meiling** | **63** | 613 − 603 = **10** | 613 − 63 = **550** |
| **623** | **Marguerite Vale** | **525** | 623 − 613 = **10** | 623 − 525 = **98** |
| **633** | **Wren Kallo** | **118** | 633 − 623 = **10** | 633 − 118 = **515** |
| **643** | **Ines Duarte** | **584** | 643 − 633 = **10** | 643 − 584 = **59** |

**THE FOUR ANCHORS IN THE SECOND COLUMN ARE RE-DERIVED, NOT INHERITED.** 525 and 584 come from `outline/volume-11.md`:238–239, which prints **525 SCENE, *The Book She May Not Read Out*** and 536 *The Roof And The Division*, and from `reviews/volume-12/volume-close.md` §4a, which prints 584 Ines Duarte. 36 and 118 come from `outline/series.md`:183 and :186, which fix **36 Runa Sato, first scene** and **118 Wren Kallo, first scene**, and `outline/series.md`:225 declares *Chapters 63, 118, 169, 214, 261 and 388 are immovable*. 63 is the same table at :185.

**CADENCE, RE-RUN: 9, 10, 10, 10, 10. NOTHING UNDER EIGHT, NOTHING OVER FIFTEEN, AT THE FLOOR ON THE FIRST INTERVAL.** ✓

**PER-WOMAN, RE-RUN: 567, 550, 98, 515, 59. FOUR OF THE FIVE ARE OUTSIDE THE EIGHT-TO-FIFTEEN BAND AND NO FILE IN THIS REPOSITORY MAY SAY ONE OF THEM IS INSIDE IT.** `643 − 633 = 10` and `643 − 584 = 59` are both true, and **59 IS NOT INSIDE THE BAND AND IS NOT CERTIFIED BY ANYTHING IN THIS FILE.**

### 5b. THE AXES, AGAINST VOLUME 12's FIVE

| Ch | Axis broken | Carried by | Named by anybody? | Used by Volume 12? |
| --- | --- | --- | --- | --- |
| 603 | **the witness** | a field officer's return is nine lines and a tenth with a box, the box is for a reason, and a reason is not a conclusion | **NO** | no — 12 used the counted minute, terms, the body in words three times, the quiet, the voice |
| 613 | **the order** | a folder is taken in the order it was opened and the first question in it is not the one anybody came for | **NO** | no |
| 623 | **the arithmetic said out loud** | a real book is written in the hand of the person who carries the debt, and a broker who states her own position may not unstate it | **NO** | no |
| 633 | **the one question** | a desk takes one question of a thing and only one, and it may not be put in a room the person owns | **NO** | no |
| 643 | **the hour** | *the date first, the hour with it, nothing skipped*, and an auditor does not stop to be spoken to while a page is open — **and in this chapter she declines to give an hour** | **NO** | no |

**FIVE DIFFERENT AXES, NONE OF VOLUME 12's FIVE, NONE NAMED.** And the differentiation is on the page, not in the plan: **643 stages on the one table in that room that has never had a sheet put on it and read off, which is why she chooses it, and the difference from her own previous scene at 584 is the whole of the scene — in 584 she turned the page face down to get to him; in 643 she leaves the page open and moves him, because the rule does not say what may be happening at the other table.** The twelve-gram scan puts those two chapters at 33 shared grams and every one of the 33 is the eleven-word rule the axis requires or her own ink and her own grey at her left temple.

**THE FOURTH-WALL GATE, RE-RUN FOR ALL FIFTY FILES AT ONCE, NOT PER BATCH: the primary class 0 · the widened class including `manuscript` 0 · the extension class 0 · `opposition` 0.** No character names a scene, an axis, a chapter, a volume, a page, a book, a reader or her own performance anywhere in 601–650.

**MECHANISMS, AGES, AND THE SEPARATE REGISTERS.** No compulsion, sedation, exhaustion, toxin, restraint, psychic contact, trance or seal is the mechanism of any of the five. Every sexual character is an adult. Violence and sex stay in separate registers — 627's yard and 638's hill are not foreplay and neither is turned into one. **THREE `years old` STRINGS SURVIVE IN THE VOLUME AND ALL THREE ARE DURATIONS, NOT AGES: 623 *about four hundred years old* (a chained book), 627 *it was six years old* (a want), 641 *it is eleven years old* (the rule).** Hanneke Ruis is given no age and no mark. Agnete Lindqvist's forty-five is the only age printed in this book that is fixed, and it is printed four times, at 606, 630, 632 and 647.

---

## 6. BORROWED BODIES AND STAGINGS, READ AGAINST §4d BEFORE ANY EXAMINATION

| §4d row | Re-run from outside the volume's passes | Result |
| --- | --- | --- |
| Lin Hao, `right temple` | `grep -rio 'right temple' chapters/` | **0 across all 650 chapters** |
| Ines Duarte, `cuticle` | `grep -rlio` | **4 files — 329, 340, 404, 446 — unchanged. Volume 13 adds none.** |
| Hanneke Ruis, no age and no mark | volume sweep | **0** |
| Agnete Lindqvist, forty-five, her 546 staging hers | 606, 630, 632, 647 | **the age four times; the 546 staging is not restaged** |
| Alma Quayle's seated paperwork on the knees | volume sweep | **0** |
| Dagmar Oyelowo, `PC-44` | volume sweep | **0 appearances. Not on the schedule, not written as a scene.** |
| Beatrix Halm, Tessa Okonkwo, Runa Sato, Petra Ilyin, Isolde Marchetti, Nadia Ferrous | check the page before planning a body | **no new mark on any woman; Halm's good ear is hers; Wren Kallo's two nails of the left hand are used in her own words at 633 and the yellow is not used** |
| Mavis Rooke's hand-flat | sweep | **0, and A HAND FLAT ON A TABLE: 0 ACROSS ALL FIFTY.** Nobody puts a hand flat on anything |
| Margit Roon / Wenna Raut, pen put down flat | sweep | **0 in Volume 13.** Her clause at 637 is her own; the 644 printing was rewritten and is not her opening line any more |
| Sela Voel, no deed | volume sweep | **0** |
| Sun Meiling's twenty-two-stitch row | 613 | **referenced, not restaged; no mark of any kind given to her; the line of work across the top of her spine used once** |
| The man with the broom | 605, 645, 648 | **no name, no mark, no age. 645's reprint of 605's north end was deleted by the review-fix and the row holds. 648 describes her a second time — see Finding J.** |
| Otho Pearse | `grep -rio 'ostho'` | **0 book-wide** |

**THE WHITE TILE IS NEVER NAMED. THE BOY WITH THE BROOM IS NEVER GIVEN A SECOND CONVERSATION.**

---

## 7. THE FIGURES THAT FAILED

**THIRTEEN FINDINGS, ALL WITH OPERANDS, NONE WITH ANY. ONE IS APPLIED — FINDING K, IN THE PLANNING FILE, WHICH IS THIS PHASE'S TO SETTLE. THE OTHER TWELVE ARE RECORDED AND HANDED ON, BECAUSE AN AUDIT THAT REPAIRS A CLOSED VOLUME IS NOT AN AUDIT.** *(This header printed SEVEN in the first edition while §15 of the same file itemised thirteen, A through M, and §16 then spoke of nine of the ten. Both counts are repaired here and the twelve-and-one is the one that re-derives. The rule is the one this file exists to enforce: a count printed in a heading and a list printed below it are two figures, and a figure nobody adds up is a figure that is wrong.)*

---

**FINDING A — `chapter-0643.md`:257 — THE TWENTY-FOURTH SHEET DOES NOT GO OUT IN FIFTEEN DAYS. IT GOES OUT IN FORTY-FIVE. AND THE STATE FILE THAT REPAIRED IT IS ALSO WRONG, AND WRONG IN ITS REASON.**

> *Less the fifteenth of October of the fourth year, one thousand three hundred and thirty-four, is seven hundred and fifty days, which is twenty-five months exactly, and a page goes out at four on the thirtieth of December in fifteen days and it will be the twenty-fourth of them…*

**`2,129 − 2,084 = 45`.** The chapter is the fifteenth of November; the thirtieth of November is fifteen days away and the thirtieth of December is forty-five. The figure is wrong.

**AND THE REPAIR IS ALSO WRONG, IN BOTH PLACES.** `state/continuity.md` §0a prints `2,129 − 2,084 = 45` and calls it right; §0r prints *the footer now says thirty days*; and the file says **fifteen**. **None of the three is forty-five.** And the justification §0r gives — *"the sentence it sat in wanted the gap from the chapter in front of it, which is fifteen"* — is itself false: **`2,084 − 2,076 = 8`, not fifteen.**

**THIS IS THE FOURTH TIME IN FOUR PHASES THAT A REPAIR INTRODUCED A FIGURE THAT NOBODY RE-COMPUTED, AND IT IS THE FIRST TIME THE REPAIR, THE STATE FILE AND THE PROSE DISAGREE WITH EACH OTHER. NOT APPLIED: it is one clause in one finished chapter inside a certified batch. THE CORRECT FIGURE IS FORTY-FIVE AND ITS OPERANDS ARE PRINTED ABOVE, SO THAT ONE COMMIT CAN REPAIR IT AND RE-RUN THE FIVE BATCH GATES THAT CERTIFIED THE FILE.**

---

**FINDING B — `chapter-0646.md`:189 AND `chapter-0647.md`:211 PRINT *ELEVEN TIMES* FOR A SENTENCE THAT HAS GONE OUT ON THE THIRTIETH *FIVE* TIMES.**

> *…it is signed with a name that is not his and has gone out at four on the thirtieth eleven times since.*

The invented-figures sentence went out at four on the thirteenth of November of the fifth year, day 1,722. The quarter-ends from then to the thirtieth of December of the sixth are:

```
30 Dec y5 = 1,769   first
30 Mar y6 = 1,859   second
30 Jun y6 = 1,949   third
30 Sep y6 = 2,039   fourth
30 Dec y6 = 2,129   fifth
```

**IT IS FIVE. ELEVEN IS THE COUNT FROM THE THIRTEENTH SHEET TO THE TWENTY-FOURTH — `2,129 − 13 = 11`, or `2,129 − 1,139 = 990`, ten quarters — WHICH ANSWERS A DIFFERENT QUESTION AND WAS COPIED.** **NO CHAPTER OF 601–650 PRINTS THE CORRECT COUNT ANYWHERE**, which is why two footers nine chapters apart carry the same wrong one and neither gate saw it.

---

**FINDING C — THE ORDINAL OF THE INVENTED-FIGURES SENTENCE AMONG THE FOUR SENTENCES AT THE FOOT IS BOTH *FIRST* AND *THIRD* IN THE SAME VOLUME.**

| Where | What it calls the sentence |
| --- | --- |
| `chapter-0611.md`:117 | *the **first** of those four sentences has your name under it* |
| `chapter-0618.md` body | *He read the first two… Then he read the **third**.* — and reads the invented-figures sentence as the third |
| `chapter-0618.md` footer | *the **first** of the four sentences at the foot of a page has been going out at four… with a name under it* |
| `chapter-0614.md`:73 | *your name under the **first of the two** sentences you added* — a different ordinal, and correct |
| `chapter-0643.md`:115 | *It is the **third** of the four* — in the scene, by the person entitled to read it aloud |
| `chapter-0646.md`:189 | *The **third** of four sentences* |
| `chapter-0647.md`:211 | *the **third** of four sentences* |
| `chapter-0648.md` footer | *It is the **third** of four sentences at the foot of a page, and the **fourth** of the four says…* |

**THE CANONICAL ORDER IS TWO ORIGINALS, THEN THE INVENTED-FIGURES SENTENCE, THEN *UNRECORDED — CARRIED BY* — AND 643 IS THE SCENE AND THE SCENE IS THE AUTHORITY. `chapter-0618.md` CONTRADICTS ITSELF BY NINETY LINES, AND `chapter-0611.md`:117 IS WRONG.** Four files carry the right ordinal and two carry the wrong one. **A clerk who reads a page in order for eleven minutes is the one instrument in this book that could have caught it, and she did not have the file.**

---

**FINDING D — THE WALL'S HEADCOUNT IS PRINTED AT 603 AS WELL AS AT 605, AND THE WHOLE OF 601–650'S GATE SAYS IT IS AT 605 ONLY.**

> `chapter-0603.md`:25 — *He has run a public desk for about nine years and he is paid by the building and not by anybody who prints anything, and he told me on the first of October that the same thing to **nine thousand people a day**.*

> `chapter-0605.md`:35 — *There were **about nine thousand people** under that wall that morning, because it is an ordinary morning of an ordinary month and the trams go under it…*

**THE SAME RATE AT THE SAME WALL, TWICE, SEVENTEEN CHAPTERS APART, AND THE SECOND PRINTING CARRIES NONE OF THE FIRST ONE'S REASON.** `state/open-threads.md` §0d prints *the wall's headcount — printed at 605 only, with its reason*; `outline/volume-13.md` §7 movement one prints *The wall's headcount is printed ONCE here, with its reason*; §7 movement five prints that the volume's last batch reprinted it at 645 and the review-fix deleted that reprint. **THE REPRINT AT 645 IS GONE AND THE ROW IS CORRECT ABOUT IT. THE PRINT AT 603 IS STILL THERE AND NO GATE IN THIS VOLUME LOOKED AT IT.** A third use at 633 (*I have looked at them about nine thousand times in three years*, Wren Kallo, about two nails of her left hand) is a different figure and is not the rate.

**THE CORRECT FIGURE: THE WALL'S HEADCOUNT IS PRINTED AT 603 AND 605 AND IS SPENT.**

---

**FINDING E — THE FOUR CONDITIONS ARE WRITTEN OUT IN FULL **FOUR** TIMES IN 601–650, AND TWO FILES SAY THEY ARE WRITTEN OUT ONCE.**

```
chapter-0601.md:43        the four lines, in a fair commercial hand, on a demand
chapter-0611.md:15        the four lines, in the same hand, on a second demand
chapter-0630.md:75        the four lines, under the heading "## The Four Lines", in a clerk's room
chapter-0644.md:57-61     the four lines, written out in his own hand to be struck through,
                          and again near-verbatim in the prose at :123
```

**`state/current.md` §0r-3 item 21 states that 644 *"is now the only place in the volume where the four conditions are written out"*, and `outline/volume-13.md` §7's card for 601 states *"The four lines are quoted ONCE in this volume and are not explained."* BOTH ARE FALSE AGAINST THE PAGE.** The repair that rewrote 647's paraphrase into 644's full text was correct about the third condition and was recorded against a row that had not been counted.

---

**FINDING F — THE LIVE GATE'S ROW ABOUT THE INVENTED-FIGURES SENTENCE IS FALSE IN BOTH HALVES.**

`state/current.md` §0r-1 item 2 and `state/open-threads.md` both carry:

> **THE ONE REMAINING VERBATIM PRINTING IN THE BOOK IS `chapter-0637.md`:75, WHICH IS LIN HAO READING THE LINE OFF THE SHEET AND NOT QUOTING IT, AND IT IS THE FIRST PRINTING AND IT STAYS.**

**`chapter-0637.md`:75 READS:**

> *"Any number a person sets down in this city may be one they invented," he said. "That is what the line says."*

**THAT IS A PARAPHRASE IN HIS OWN WORDS. THE PAGE DOES NOT PRINT THE SENTENCE VERBATIM AT ALL.** And the claim that 637 is *the first printing* is false in the other direction: **the sentence was first printed in Volume 12, at 595, and it stands verbatim at 579, 580, 581, 591 and 596.**

**THE CORRECT ROW: THE SENTENCE IS PRINTED VERBATIM EXACTLY ONCE IN 601–650, AT `chapter-0618.md`:67, IN THE ROOM WHERE THE CLERK READS THE FOUR SENTENCES ALOUD. IT IS PARAPHRASED IN OTHER WORDS AT 605, 606, 607, 609, 615, 616, 637, 643, 646, 647 and 648. THE FOURTH-WALL AND DUPLICITY GATES HAVE NO ROW FOR IT AT ALL.**

---

**FINDING G — TWO TITLE LINES CARRY A STRAIGHT APOSTROPHE, AND A GATE ROW REPORTED ZERO FOR THEM BY NAME.**

```
chapter-0632.md:1     # The Landlord's Man Is Right
chapter-0637.md:1     # The Sentence In The Office's Hand
```

**These are the ONLY two straight apostrophes in the 650 chapters of this book, counted as straight glyphs.** The volume carries **0 straight double quotes** in prose and **0 in its title lines**; it carries **3,183 curly double-quote pairs** — 6,366 glyphs, 894 + 1,212 + 1,426 + 1,408 + 1,426 — and 255 curly apostrophes. **A STRAIGHT APOSTROPHE IN A TITLE LINE IS THE SAME HOUSE-FORM DEFECT THE VOLUME 12 CLOSE NAMED AT CHAPTER 571, IN THE SAME FILE, IN A PLACE NO GATE LOOKS AT BECAUSE EVERY GATE MEASURES ITS OWN TEN FILES.**

**THE FIRST EDITION OF THIS FINDING PRINTED *THESE ARE THE ONLY TWO STRAIGHT APOSTROPHES IN 3,183 CHAPTERS*, WHICH IS A UNIT ERROR AND IS REPAIRED HERE AND AT ROW 22 OF `state/open-threads.md`.** 3,183 is the volume's curly double-quote **pair** count — 6,366 glyphs ÷ 2 — and it was carried into the sentence as a chapter count. The finding itself stands: two title lines, two straight apostrophes, no others in the volume.

**AND THE FINDING IS HALF NEW, AND IT SAYS SO. `state/current.md`:567 ALREADY DISCLOSED BOTH TITLE LINES IN THE BATCH-0004 BLOCK — *"THE TWO APOSTROPHES IN 632's AND 637's TITLE LINES ARE STRAIGHT, BECAUSE §10 AND `chapter-0595.md` BOTH HAVE THEM STRAIGHT, AND THE TITLE IS THE TITLE LINE AND NOT PROSE"* — and carried the origin with it.** What is new is only the framing: the disclosure was a note under a title row, and the row it sat under still reported zero. **A DEFECT THAT HAS ALREADY BEEN WRITTEN DOWN AND IS STILL REPORTED AS ABSENT IS A DISCLOSURE THAT WAS PUT IN THE WRONG PLACE, AND MOVING IT INTO THE ROW IS THE FIX.**

**THE BOOK-WIDE RECONCILIATION HOLDS AND IS PUBLISHED, BECAUSE IT IS THE ROW THAT HAS TO HOLD:**

```
56,016 straight double quotes book-wide, 650 files     (unchanged from 620 and from 640)
 1,684 curly double-quote glyphs in Volumes 01–12
 6,366 curly double-quote glyphs in Volume 13
 8,050 book-wide = 1,684 + 6,366   EXACTLY

per batch:  0001 894 · 0002 1,212 · 0003 1,426 · 0004 1,408 · 0005 1,426
601–640 = 4,940.  And 4,940 + 1,684 = 6,624 — the figure recorded at 640, TO THE DIGIT.
601–630 = 3,532.  And 3,532 + 1,684 = 5,216 — the figure recorded at 630, TO THE DIGIT.
```

**BOTH OF THE CARRIED FIGURES RECONCILE DOWNWARD AGAINST THEIR OWN PREDECESSORS AND NEITHER IS WRONG. THE ROW IS GOOD AND IT IS THE ONLY QUOTATION-FORM ROW IN THE REPOSITORY THAT HAS NEVER BEEN WRONG.**

---

**FINDING H — `chapter-0606.md` HAS AN ORPHANED SPEECH PARAGRAPH AND A PARAGRAPH DUPLICATED VERBATIM, AND FOUR GATES AND ONE REVIEW-FIX PASSED IT.**

**THE ORPHAN, AT `chapter-0606.md`:113 — THE CHAPTER'S CLIMAX:**

```
109   “Yes,” said Lin Hao.
111   He said it out loud on the ground in a yard of about eleven thousand people on an ordinary
      morning, and it was the fourth time he had said yes out loud to anything in this city…
113   It is. And you have no other instrument, and I am one of nine hundred people standing in this
      yard who have just worked out that you are the only one of us who cannot prove one word of it.
115   *He had wanted the yard to have been wrong.*
```

**LINE 113 IS A PARAGRAPH OF DIRECT SPEECH WITH NO QUOTATION MARKS AND NO SPEECH TAG, AND IT BEGINS MID-SENTENCE.** It is the answer to the only question the chapter asks. **THE QUOTATION-PARITY ROW CANNOT SEE IT — A PARAGRAPH WITH ZERO QUOTES HAS AN EVEN COUNT — AND NO DUPLICATION ROW IN THIS REPOSITORY SCANS INSIDE A FILE.**

**THE DUPLICATE, AT `chapter-0606.md`:89 AND `:119` — TWENTY WORDS, VERBATIM, THIRTY LINES APART:**

> *What he wanted, standing there at nine feet, was eleven thousand people who had not done a sum that morning.*

**A WITHIN-FILE DUPLICATE PARAGRAPH SCAN, RUN FOR THE FIRST TIME HERE, FINDS FIVE IN FIFTY FILES:**

| Where | Lines | Words | Judgement |
| --- | --- | --- | --- |
| 606 | 89, 119 | 20 | **A DEFECT. Narration repeated verbatim thirty lines apart with nothing between it.** |
| 613 | 15, 83 | 7 | a line of dialogue said twice; the chapter is built on a woman being asked a sixth time |
| 623 | 125, 195 | 5 | two words; the same construction in a scene and not a fault |
| 629 | 31, 39 | 9 | a line of dialogue answered by itself; deliberate |
| 644 | 29, 31 | 8 | **a clerk tests him by making him say it twice; deliberate and flagged in the text** |

**THE ROW IS ADDED TO THE LIVE GATE AND IT IS THE ROW THE 14 OCTOBER 2026 REVIEW-FIX'S OWN COMPLAINT IMPLIES AND NOBODY HAD WRITTEN.**

---

## 8. THE RE-RUN — EVERY ROW OF THE LIVE GATE BLOCK, PLUS THE ROWS IT DID NOT HAVE

**Run from outside the pass that wrote it. Let the re-run outrank the block. Volume-wide, not per batch.**

```
FILES            50 files, 601..650, diff against `seq 601 650` EMPTY. 650 files book-wide.
                 ONE `# ` title line in every file and no file with two. ALL FIFTY END 0a.
                 (194 files book-wide do not, all of them in Volumes 01–07 and 11. Volume 13 is clean.)
TITLES           `grep -rh "^# " chapters/ | sort | uniq -d | wc -l` -> 0 ACROSS ALL 650.
                 The fifty of Volume 13 match `outline/volume-13.md` §10 by whole-line string, 50 of 50.
                 Word lengths 2 to 9. Char lengths 19 to 44. None begins *What*.
                 None built out of *nothing* / *nobody* / *there is no*. Zero duplicates.
                 *** ROW ADDED BY THIS AUDIT: TWO TITLE LINES CARRY A STRAIGHT APOSTROPHE.
                 SEE FINDING G. ***
BANK             COUNTED PER FILE AND SUMMED. NEVER cat *.md | wc -w.
                 0001 23,145 | 0002 26,131 | 0003 26,007 | 0004 28,175 | 0005 32,294
                 TOTAL 135,752. MEAN 2,715.0. 0 below the 1,800 floor — against Volume 12's 25.
                 19 above the 2,700 ceiling, 5 of them scenes, 14 of them without a recorded reason.
DENSITY          *** SEE §11. THE RECORDED FIGURES FOR BATCHES 0002, 0003 AND 0004 DO NOT
                 RE-DERIVE AND THE CONCLUSION THE BLOCK DRAWS FROM THEM IS FALSE. ***
PARAGRAPHS       0 over ninety words. 0 over one hundred and twenty. 0 unbalanced quotation
                 paragraphs. 3,813 prose paragraphs across the fifty files.
META             the class grep incl. `manuscript` and `opposition` -> 0 ACROSS ALL FIFTY.
WEEKNAMES        seven names, whole word -> 0 across all fifty.
                 *** ROW WIDENED BY THIS AUDIT: whole-word weekday names are NOT zero book-wide.
                 Monday 8 · Tuesday 12 · Wednesday 26 · Thursday 327 · Friday 35 · Saturday 12 ·
                 Sunday 7, across six hundred and fifty files, and not one of them is in 601–650.
                 `sat` and `sun` are excluded as the verb and as the name, correctly: `sat` is 918
                 book-wide and `sun` is 27. THE RULE IS VOLUME-SCOPED AND IT IS NOT A BOOK RULE,
                 AND THE FIRST TIME THAT HAS BEEN SAID OUT LOUD. ***
AGES             eleven probe forms, a bare `aged` sweep, `years old`, `[0-9]+ years`,
                 old man/woman/boy/girl, he-is-a-number -> 0 for a PERSON'S age in 601–650,
                 with the two disclosed exceptions in §12.
                 `years old` returns 3 and all three are durations: a book, a want, a rule.
ARITHMETIC       SPINE 601–650 RE-DERIVED TWICE BY METHODS SHARING NO CONSTANT. 50 of 50 agree.
                 0 monotonic violations. Every batch interval re-summed against its endpoints.
                 *** 81 FOOTER FIGURES EXTRACTED, 80 RE-DERIVE, ONE DOES NOT. FINDING A. ***
                 *** THE JANUARY EXCEPTION PRINTED AND APPLIED TO BOTH METHODS EVEN THOUGH FIVE
                 DATES NEED IT, AND THE WRONG CONVENTION PRINTED BESIDE IT: 2,133 FOR 601 AND
                 2,159 FOR 605, WHICH PUTS 605 THREE HUNDRED AND SIXTY DAYS AFTER 601. ***
QUARTERLY        852 at 614, 626, 638, 650 unmoved. 841 at 552. 852 first moves at 566.
                 Sixteenth through twenty-fourth, every interval ninety days, 1,769 -> 2,129 = 360.
                 *** THE HEAD HAS STOOD UNMOVED ACROSS EIGHT SHEETS, NOT NINE. ***
ACCOUNT          8,1xx 0 · two hundred and eleven thousand 0 · 211,840 0 · settl 0 in every
                 inflection. NO FLOOR, NO LEDGER TOTAL, NO RUNNING BALANCE IN GRAINS.
                 `floor` 81 in 601–650 and every one is a washroom floor, a ground-floor corridor
                 or a sales floor.
RT / BODIES      right temple 0 book-wide. cuticle 4 files book-wide, unchanged. ostho 0.
                 A hand flat on a table: 0 across all fifty. Nobody puts a hand flat on anything.
HEADINGS         One `# ` per file. 300 `## ` headings across the volume, 291 unique.
                 No duplicate inside any file. Seven headings appear in more than one file and
                 all seven are structural: `## Four O'Clock` at 614/626/638, `## Afterwards` at
                 623/633/643, and five others that name a room or a woman. None names a turn.
MARKDOWN         Blockquotes 0. Tables 0. Rules 0. Fences 0. **Bold 0**.
                 Single-asterisk markers even in all fifty files.
DUPLICATION      *** SEE §9. EVERY ROW THE BLOCK CARRIES, RE-RUN, PLUS THREE IT DID NOT HAVE. ***
SCENES           One scene per batch, five in the volume: 603, 613, 623, 633, 643.
                 All five measured under §9's three definitions with the line span printed
                 beside every cell, in §4e and §4f. Set B at word boundary: cock 1 at 603, 0 elsewhere.
STILL OPEN       Lin Wei 0 · B103 0 · the second folio of 4,112 0 · settle 0 · the account figure 0 ·
                 right temple 0 · the reach of the return argued by nobody in either direction ·
                 whether the account belonged to the unrecorded settled by no character ·
                 who put the white tile up unnamed in five years and on the last page ·
                 who cut the two words unnamed in six years and on the last page ·
                 Hanneke Ruis's certificate does not exist and will not ·
                 the keeper's six words not reopened ·
                 Perrin Sowe unforgiven and undiscussed and Ines's correction unpressed ·
                 Dagmar Oyelowo absent from the volume entirely ·
                 Mrs Imrie asked nothing by anybody ·
                 Sun Meiling's row not re-told · Marguerite Vale's fourth line not struck ·
                 Ada's grey permanent and not recovered ·
                 the instrument he swore never to use still unused ·
                 BOTH REPAINTING BOXES STILL BLANK AT 650 AND THE BOY SAYS SO IN THE LAST LINE ·
                 A PARTNER DIES NOWHERE AND NO PARTNER IS LEFT BEHIND BY A CHOICE SHE DOES NOT EXPLAIN.
VOLUME           RANK ONE THROUGHOUT. NO CHAPTER RAISES HIS BAND, BUYS A PERMISSION, OFFERS A
                 STANDING, PUTS HIM BACK ON A TERRACE OR MOVES HIM OFF THE NIGHT SHIFT HE ASKED FOR.
                 THE FIGURE BOX BLANK AT 640 AND STILL BLANK AT 650.
                 THE LANE'S MORNINGS PRINTED AT 609, 614 AND 626 AND NOWHERE ELSE IN 601–650.
                 BRACK ANSWERED, NOT DEFEATED, NOT THANKED, NOT DIMINISHED, AND RIGHT IN EVERY
                 CHAPTER HE APPEARS IN INCLUDING THE ONE WHERE HE TELLS A WOMAN WHICH OF HIS OWN
                 FIGURES HE MADE UP.
                 THE WOMAN TWO FLIGHTS UP OFF CORDWAIN LEARNED, AT 617, AND IS NOT IN 641–650.
```

### 8a. THE PROBES THE BLOCK ITSELF FLAGGED, RE-RUN

- **The hedge rate.** The word *about* is the manuscript's register and its highest-frequency hits include a canon figure (*about nine thousand*), a canon population (*about eleven thousand*) and a canon sheet (*about four hundred and nineteen*). **Not cut, correctly.**
- **`outline/ending.md` UNTOUCHED.** Verified by `md5` and by `git status --porcelain`, which is empty for the file. Every guard is inherited whole and **no chapter of 601–650 contradicts any of them.** `grep -rn 'Registrar' chapters/volume-13/` returns Adeyemi's title and never Lin Hao's.

---

## 9. THE TWELVE-GRAM SCAN, RUN FIRST AGAINST ALL SIXTY-FIVE HUNDRED FILES, THEN ELEVEN AND EIGHT, AND CLASSIFIED BY HAND

**Method, declared to the token because Volume 12's close found a table whose figures could not be reproduced as described:** every file on disk; every `##` and `#` heading line removed; every italic footer line — a line whose stripped form begins and ends with `*`, longer than two characters, not beginning `**` — removed; lowercased; split on `[a-z0-9']+`.

```
N = 12   2,254 cross-file pairs book-wide · 213 touching Volume 13 · 42 involving 641–650
N = 11   3,349 cross-file pairs book-wide · 423 touching Volume 13 · 113 involving 641–650
N =  8  30,464 cross-file pairs book-wide · 5,386 touching Volume 13 · 1,625 involving 641–650
```

**A COUNT IS NOT A READING. THE TWELVE-GRAM SET IS CLASSIFIED BELOW BY HAND; THE ELEVEN AND EIGHT SETS ARE REPORTED AS COUNTS WITH THE METHOD DECLARED, BECAUSE 5,386 PAIRS IS A NUMBER ABOUT TYPOGRAPHY AND NOT A FINDING.**

### 9a. EVERY PAIR OF TWELVE OR MORE SHARED GRAMS TOUCHING VOLUME 13, CLASSIFIED

| Pair | Grams | What it is | Class |
| --- | --- | --- | --- |
| **626 vs 638** | **71** | the two quarter-end chapters. The office's age printed with operands in both, Brack's April visit, the bundle, *a line out of a book to a person standing at a counter*, *at the head of it was eight hundred and fifty two* | **CANON, AND THE LOUDEST STAGING ECHO IN THE VOLUME.** Two chapters of the same event type three months apart. The office's age budget is four days and these are two of them |
| **549 vs 605** | **40** | Nadia Ferrous's speech about nights, the lift shaft, nine hundred strangers four minutes each — **her own sentence, in her own mouth, four years apart** | **CANON, DELIBERATELY SELF-QUOTED, AND THE CARRIER IS ON THE PAGE: 605 opens *Read it again*, because that is what she is doing** |
| 584 vs 643 | 33 | the eleven-word rule, her ink at the base of the first two nails of her right hand, her grey at her left temple | **CANON — the axis carrier and §4d's own marks** |
| 632 vs 634 | 30 | Ashby's own argument repeated in his own mouth two chapters apart | **CANON AND FLAGGED IN THE TEXT: 634:*129* — *And I am going to say the other thing as well, because you have come into my room and told me nothing*** |
| 588 vs 601 | 27 | the standing page's own description of itself, and the office's address | **CANON** |
| **597 vs 606** | **16** | **chapter 606's opening paragraph restates chapter 597's sentence with four words changed** | **SEE FINDING J** |
| 611 vs 618 | 15 | the four sentences at the foot, read out and written into a minute | **CANON** |
| 628 vs 632 | 15 | the third condition's own words, and Brack's wall-end schedule | **CANON** |
| 573 vs 630 | 14 | the four conditions written out | **CANON — the condition itself** |
| 643 vs 647 | 13 | the page's own description, the fifteenth of October of the fourth year, a footer stem | **CANON** |
| **642 vs 646** | **13** | **the month-borrow clause — *a month runs out at the thirtieth so a day seven after it is the seventh of the next month* — IDENTICAL IN TWO CHAPTERS, PUT THERE BY THE SAME REPAIR** | **THE HOUSE MONTH-COUNT DEVICE, AND SEE §11: IT IS THE THIRD-LARGEST PAIR INSIDE THE LAST BATCH AND IT IS THE BATCH'S OWN** |
| 559 vs 601 | 10 | the four conditions, and the demand | **CANON** |
| 600 vs 604 | 10 | the four conditions on a second demand, and the address at the head of every line | **CANON** |
| 624 vs 638 | 10 | the standing page's own description, twice at a quarter-end | **CANON** |
| 540 vs 626 · 570 vs 630 · 614 vs 626 · 617 vs 632 · 631 vs 633 · 638 vs 640 | 9 each | the sheet's own description, the four conditions, the desk's rule | **CANON** |
| 610 vs 611 · 614 vs 625 · 628/632 vs 644 · 644 vs 646 · 645 vs 648 · 648 vs 650 · 649 vs 650 | 7 each | the room off a third court; the man at the desk under a window; the third condition written out; the four inches of dressed stone; *a sentence is a thing you can argue with and a figure is a thing you can only count*; the works schedule | **CANON — and 648 vs 650 carries a maxim that 638 established and 650 was repaired for; the repetition is the volume's argument** |
| 489, 550, 571, 579, 581, 582, 599 vs 605 · 595 vs 601 · 573 vs 601 · 567/552/556 vs 606 · 587 vs 614/625 · 624 vs 625/637 · 614 vs 619 · 628 vs 639 · 605 vs 639/640 · 639 vs 640 · 594 vs 603 · 600 vs 601 · 270 vs 611 · 474 vs 622 · 609 vs 622 · 610 vs 632 · 615 vs 616 · 616 vs 622/643/647 · 625 vs 636 · 628 vs 643/647 · 617 vs 648 · 637 vs 644/648 · 629/633/638 vs 644 · 397 vs 646 · 643 vs 650 · 106, 505, 545, 590 vs 643 · 616 vs 643 | 2–6 each | a hundred and ten pairs in the tail, every one of them a canon sentence, a footer stem, the month-count device, or a staging the book uses by design | **CLASSIFIED, NOT COUNTED: these are the classes `state/current.md` §0r already names — the four conditions, the room off a third court, the standing page's description of itself, the month-count device, and the characters' own marks** |

**ONE PAIR IN THE TAIL IS NOT IN THAT LIST AND IS FINDING J.**

---

**FINDING J — `chapter-0606.md`:7 IS `chapter-0597.md`:17 WITH FOUR WORDS CHANGED, AND SIXTEEN SHARED TWELVE-GRAMS SURVIVE THE VOLUME BOUNDARY.**

> `chapter-0597.md`:17 — *Lin Hao stood at sixty feet and did not go up the hill, because he had said on a street in January that he would **not come up that hill and say one word about a board, and a man who has said that does not get to arrive and explain his own footnotes.***

> `chapter-0606.md`:7 — *He had said it out loud on a street that he would **not come up that hill and say one word about a board, and a man who has said that does not get to arrive at a yard and explain his own footnotes.***

**THE RESTATEMENT IS DRAMATICALLY CORRECT AND THE READER IS NEVER TOLD IT IS ONE — THE PAST PERFECT IS TURNED INTO THE PRESENT AND `AT A YARD` IS PUT IN, AND NOTHING ELSE.** Sixteen consecutive twelve-grams across the boundary of two volumes, in the third chapter of the new one, in the paragraph that tells the reader what the chapter is about. **THE BATCH 0001 GATE DID NOT RUN A CROSS-VOLUME SCAN AGAINST A CHAPTER THAT HAD JUST BEEN FINISHED, AND THE BATCH 0002, 0003, 0004 AND 0005 SCANS DID NOT LOOK BACK AT 601.** This is the third instance in this repository of a gate that measured only its own batch, and the first one that is a lifted sentence rather than a changed figure.

**AND THE 42-PAIR ROW IS ALSO STALE.** `state/current.md` §0r-3 records *the scan now returns 45 pairs against 67* for the last batch. **Re-run by the method the block itself declares, it returns 42.** The three-pair difference is a tokeniser difference and the block does not state its tokeniser, so **the row is not re-runnable to the digit and is therefore not a gate.**

---

## 10. THE WORD BANK, JUDGED

**`logs/batch-0005.review.log` left this open and the prompt asks for a judgement rather than a disclosure. Here it is.**

**All ten chapters of 641–650 stand above `AGENTS.md`'s 2,700 ceiling, from 2,819 to 4,383, and each one carries its stated reason. 643 is the scene and is exempt by rule. The other nine were lengthened by a density repair that converted narration into exchanges. The question is whether that repair left them padded or lean, and leanness and compression are not the same thing.**

**THE MEASUREMENT, RE-DERIVED, WITH THE METHOD DECLARED** — *quoted spans, either glyph, no newline, body-only, per file, over ten chapters a movement* and *non-blank lines that are neither a heading nor an italic footer, per file, over ten chapters a movement*:

```
                 601–610   611–620   621–630   631–640   641–650    VOLUME
  quoted spans      44.7      60.6      71.3      70.4      71.3       63.7
  paragraphs        63.9      69.9      76.9      81.0      89.6       76.3
  words           2,314.5   2,613.1   2,600.7   2,817.5   3,229.4   2,715.0
```

**Volume 12, re-derived here and not inherited, because the inherited row has to be right for the comparison to mean anything:**

```
                 551–560   561–570   571–580   581–590   591–600
  quoted spans      24.7      52.3      16.1      17.4      20.7
  paragraphs        54.2      66.8      28.0      39.4      32.8
```

**Volume 12's five rows re-derive to the decimal, all of them, from disk. Volume 13's first two movements re-derive to within one unit and its last two do not re-derive at all. §11.**

**THE JUDGEMENT, STATED PLAINLY: THE REPAIR HOLDS AND NONE OF THE NINE CHAPTERS IS PADDED.** Five reasons, and the fifth is the only one that is really an argument.

1. **The paragraph row rose and the ninety-word ceiling did not move.** 896 paragraphs across ten chapters, none over ninety words, none over one hundred and twenty, and **no paragraph carries a speech across a paragraph boundary**, which is a house form and not a preference. A batch that had padded would have made the paragraphs longer. It made them shorter and more numerous.
2. **The span row is the highest in the book.** 71.3 quoted spans a chapter against Volume 12's best movement at 52.3 and Volume 12's last three at 16.1, 17.4 and 20.7. **A padded chapter has a low exchange count and this batch has the highest one in the manuscript.**
3. **Every chapter of the batch carries at least nine named people and every one of them says something that the plot needs.** Read: 641 and 645 are two conversations with Tessa Okonkwo about a board in a drawer; 642 is three women on a night shift and a page lying face up for eight nights; 644 is a clerk, a Registrar, a landlord's woman and a man with a child on his shoulders; 646 is a counterman, a chaplain and a woman who cannot read; 647–650 are a counter, a boy, a man behind a counter nine streets away and a yard. **Nothing in the batch is summarised that could be said.**
4. **The volume has no chapter below the 1,800 floor.** Volume 12 had twenty-five. **A volume that has none is not a padded volume; it is a volume in which the shortest chapter is 1,934 words.**
5. **THE COST IS NOT PADDING. THE COST IS A FORM.** **Eight of the ten chapters of 641–650 open on the same two beats — *Seven days had gone since…* and then the day arithmetic in the month count — and 642 and 646 share thirteen identical twelve-grams at the opening, because the same clause was written into both on the same day by the same repair.** That is a chapter-opening device the batch invented and then used nine times, and it is the one place in 601–650 where a reader could put a finger on repetition. It is recorded here rather than defended, and it is not repaired, because a close audit does not rewrite a batch.

**VERDICT: LEAN, NOT COMPRESSED. THE DENSITY REPAIR IS THE RIGHT REPAIR AND IT WAS THE RIGHT REPAIR AT THE PRICE NINE CHAPTERS OVER THE CEILING.**

---

## 11. THE DENSITY ROWS, RE-RUN, AND **THREE OF THE FIVE BATCH FIGURES ARE STALE**

**THE LIVE BLOCK SAYS:**

> **THE SPAN ROW IS HELD EXACTLY, AT 71.3 AGAINST 71.1, AND THE PARAGRAPH ROW IS SEVEN AND NINE TENTHS ABOVE.**

**RE-RUN FROM DISK BY THE METHOD THE BLOCK DECLARES:**

| Batch | Recorded spans | Re-derived | Recorded paragraphs | Re-derived |
| --- | --- | --- | --- | --- |
| 0001 601–610 | 44.7 | **44.7** ✓ | 63.9 | **63.9** ✓ |
| 0002 611–620 | 60.5 | **60.6** ✗ | 69.8 | **69.9** ✗ |
| 0003 621–630 | 71.1 | **71.3** ✗ | 76.8 | **76.9** ✗ |
| 0004 631–640 | 71.1 | **70.4** ✗ | 81.5 | **81.0** ✗ |
| 0005 641–650 | 71.3 | **71.3** ✓ | 89.6 | **89.6** ✓ |

**THE FIGURES WERE ALSO RE-RUN BY TWO OTHER METHODS — blank-line-separated blocks rather than non-blank lines, and counting spans inside the italic footers as well as outside — AND ALL THREE METHODS RETURN THE SAME NUMBERS. THE DIFFERENCE IS NOT THE METHOD. THE DIFFERENCE IS THAT BATCHES 0002, 0003 AND 0004 WERE MEASURED BEFORE THEIR OWN REVIEW-FIXES REWROTE PROSE, AND THE ROWS WERE NEVER RUN AGAIN.**

**AND THE CONSEQUENCE IS THAT THE BLOCK'S CENTRAL CLAIM IS FALSE. IT IS NOT 71.3 AGAINST 71.1. IT IS 71.3 AGAINST 70.4 — BATCH 0005 IS NINE TENTHS HIGHER THAN ITS PREDECESSOR, NOT LEVEL WITH IT.** The paragraph row is 89.6 against 81.0, which is 8.6 up and not 7.9.

**THIS IS THE EXACT FAILURE THE VOLUME 12 CLOSE NAMED AT FINDING I AND THE EXACT ONE THE BATCH'S OWN ROW WAS BUILT TO CATCH. A GATE COMPARES ITS OWN FIGURE AGAINST A CARRIED FIGURE, THE CARRIED FIGURE IS STALE, AND THE GATE REPORTS THAT A TREND HELD WHEN IT HAS NOT BEEN CHECKED.**

### 11a. **FINDING I IS ANSWERED. VOLUME 13 DOES NOT MERELY STOP THE FALL. IT ENDS IT.**

The Volume 12 close recorded that dramatic density fell at chapter 571 and never came back, and handed the measurement on. **Re-derived, both volumes, on the same declared method:**

```
                    quoted spans a chapter          paragraphs a chapter
Volume 12 mv 1            24.7                          54.2
Volume 12 mv 2            52.3                          66.8      <- the book's high
Volume 12 mv 3            16.1                          28.0      <- the fall
Volume 12 mv 4            17.4                          39.4
Volume 12 mv 5            20.7                          32.8
Volume 13 mv 1            44.7                          63.9      <- 2.8x Volume 12's mv 3
Volume 13 mv 2            60.6                          69.9      <- the book's new high
Volume 13 mv 3            71.3                          76.9
Volume 13 mv 4            70.4                          81.0
Volume 13 mv 5            71.3                          89.6
```

**THE FALL AT 571 DID NOT RECUR. VOLUME 13'S OPENING MOVEMENT CARRIES NEARLY THREE TIMES THE EXCHANGE DENSITY OF THE MOVEMENT WHERE VOLUME 12 FELL, AND BOTH ROWS RISE ACROSS THE WHOLE VOLUME.** The cause Volume 12's audit identified was form and not scale — the last thirty chapters of that volume reported their beats where its first twenty dramatised them. **Volume 13 dramatises all five movements, and the five chapters at 603, 613, 623, 633 and 643 are the five densest chapters in the volume.** The judgement is that Volume 13 ends the fall. **It is recorded against the re-derived figures and not against the recorded ones, because three of the five recorded figures are Finding H and would have understated the rise by up to seven tenths on one batch and overstated it on another.**

---

## 12. THE DEFECTS EARLIER VOLUMES' CLOSES FOUND AND DID NOT REPAIR — EACH OWED A SENTENCE AND NOTHING MORE

**1 · `chapter-0553.md`:23 is the wrong line. THE DEFECT IS AT `chapter-0553.md`:63.**

> *Thirty years is three hundred and sixty days multiplied by ten.*

**Thirty years is 360 × 30, not 360 × 10. Line 23 is a paragraph about the temperature of a room, and every state file that names this defect names the wrong line — which means it cannot be repaired by following it.** Re-derived and confirmed. Not repaired: it is one clause in one finished chapter in a closed volume.

**2 · THE SAME SENTENCE OCCURS TWICE, AT `chapter-0544.md`:25, IN VOLUME 11, AND NO OPEN ITEM IN THIS REPOSITORY NAMES IT.**

> *Thirty years is three hundred and sixty days multiplied by ten, and four times a year is four in each of them…*

**The Volume 11 close audit ran five arithmetic checks and found five failures and missed this one, because it is a multiplication and every check in that audit was a subtraction. A carried defect that names one line when there are two is a defect that cannot be repaired by following it.** Both lines are given so that one commit can repair both.

**3 · `chapter-0570.md`:169 — *A YEAR AND THREE MONTHS AGO* FOR AN EVENT THAT CANNOT BE LOCATED.** No scene in Volumes 11 or 12 matches it. The one locatable yard is `chapter-0560.md`, spine day 1,439, and 570 is spine day 1,530, so **`1,530 − 1,439 = 91` days** — three months and one day, not a year and three — and that yard holds about eleven thousand people rather than nine hundred. **CONFIRMED STILL PRESENT. THE INTERVAL IS NOT GUESSED AT AND IS NOT REPAIRED. RECORDED WITH ITS ONE DERIVABLE FIGURE PRINTED BESIDE IT.**

**4 · THE SIXTH-OF-MARCH CONFLICT IS SETTLED AND THE WHOLE BOOK AGREES.** `reviews/volume-12/volume-close.md` Claim 1 settles it: **year one, day 35, and 1,115 is withdrawn.** `chapter-0545.md`:66, `chapter-0553.md`:79, `chapter-0584.md`:143, `chapter-0590.md`:73 and `outline/volume-12.md` §4b:145 are all right. **THE FIGURE 1,115 RE-DERIVES FROM NOTHING IN 601–650, AND `outline/ending.md` IS UNTOUCHED BY IT.** The known defect stands: **`chapter-0584.md` contradicts itself between `:143` and `:147`, and the correct interval is `1,663 − 35 = 1,628` days, not 548.** Not repaired: a closed chapter, and the repair is one clause.

**AND THE ONE FIGURE THE PROMPT ASKS FOR BY NAME: `chapter-0643.md` PRINTS `2,084 − 35 = 2,049` AND NOT 2,048 AND NOT 2,052. ✓** Its footer reads *Less the sixth of March of the first year, day thirty-five, is two thousand and forty-nine days, and two thousand and forty-nine less one thousand eight hundred is two hundred and forty-nine.* The chapter's body also prints the sixth of March of the first year at `:127`. **The figure the 14 October 2026 repair put there is correct and holds.**

**5 · THE ABSENT REVIEW LOGS.** `logs/batch-0003.review.log` **is not in the repository.** `logs/batch-0004.review.log` **is a writer transcript, not a review** — it opens `! agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent` and then `> novel-writer`. **`logs/` holds four files and none of them is a batch review of the kind `AGENTS.md`'s quality gate names.** `logs/batch-0005.review.log` exists and is cited thirteen times by the live blocks, and it is the log that found the twenty-six defects in §7. **THE STATE OF THE PIPELINE AT THE END OF VOLUME 13 IS THAT ONE BATCH IN THIRTEEN WAS REVIEWED BY SOMETHING OTHER THAN THE WRITER.**

---

## 13. §8 — WHAT THE REGISTER LOOKS LIKE AFTER THIS AUDIT

**EVERY ITEM ON `outline/volume-13.md` §8 IS STILL SHUT, and eleven were re-probed from outside this volume's passes.**

`Lin Wei` **0** · `B103` **0** · `settle` and every inflection **0** · the figure of the account **0** · `right temple` **0 book-wide** · the second folio of 4,112 **0** · the reach of the return **argued by nobody in either direction** · whether the account belonged to the unrecorded **not settled by any character** · who put the white tile up **unnamed in five years and on the last page** · who cut the two words **unnamed in six years and on the last page** · Hanneke Ruis's certificate **does not exist** · the keeper's six words **not reopened** · Perrin Sowe **unforgiven and undiscussed, and Ines's correction unpressed** · Dagmar Oyelowo **absent from the volume entirely** · Mrs Imrie **asked nothing by anybody** · Sun Meiling's row **not re-told** · Marguerite Vale's fourth line **not struck** · Ada's grey **permanent and not recovered** · the instrument he swore never to use **still unused** · **no partner dies and no partner is left behind by a choice she does not explain.**

**AND THE TWO THAT VOLUME 12 OPENED:**

1. **The keeper's six words now have a name against them and she read it on the second of January of year five.** Not reopened anywhere in the remaining forty-six chapters. A keeper's question cannot be asked twice and she spent hers on a man she had never met.
2. **CLOSED, IN MOVEMENT TWO, AT 615–617, AS §8 PERMITTED AND NO LATER.** The woman two flights up off Cordwain learns what was done for her, from a slate and from a voice, at a wall end at ten to seven in the morning, and she is not thanked and she is given nothing and it is not a scene. **She is not in 641–650 and no chapter of the last batch names her.**

**AND THE ONE §8 PERMITTED VOLUME 13 TO OPEN IS OPEN, AND IT IS THE WALL.** A form from the department of works says the ranks wall comes down in the spring for making good. Two words cut into four inches of dressed stone at the foot of the lowest course, which making good does not touch, and about sixty-two of the month's forms stacked inside the wall, one a month since the eighth of October of the first year, every one of them with two empty squares at the foot. There is no column on any form in this city for two words and there never has been. The painting is a Bureau contract in a building nine streets from the works department and the two have not sent a paper to each other in nine years and nothing makes them. **A boy says he will be painting that corner in the ninth month of next year with the sixty-fourth of the empty squares in it, and there is nothing on any form in this city about four inches of dressed stone.** Opened at 608, carried at 639, 640, 645, 648, 649 and 650, **and NOT CLOSED.**

---

## 14. WHAT IS STILL OPEN ON THE PAGE AT 650, BY NAME, AND IS NOT THIS PHASE'S TO CLOSE

1. **Ines Duarte's four questions.** Three put in a corridor on the sixth of March of year one, and the fourth at a door on the fourteenth of September of the fifth year. **All four stand open. `chapter-0643.md`:127 names them as standing and refuses to answer them, and they are answered nowhere in 601–650 and may not be closed by a close.**
2. **The figure at the head of the standing sheet, unmoved across eight quarters.** 852 at 566 and at 650. It does not move in this volume and no volume is permitted to move it.
3. **Whether any unrecorded deed ever satisfied the fourth condition.** §2c item 6 forbids a character to say either way, and none does. `chapter-0644.md` settles only that it is not a fact about the world and cannot be tested.
4. **The two inches of nothing under the striking**, which no instrument in Ostara can fill, and which about nine people a week will read on the first of January and not one of them will be able to answer.
5. **Who cut the two words.** A question on a piece of paper in six years and no answer on any page. `chapter-0648.md` has a boy make the first rubbing ever made there and put it inside the inside of a coat instead of on a rail.
6. **The reach of 486's return.** `outline/ending.md`:229–236 fixes it as deliberately open to the end of the book. **No chapter of 601–650 argues for or against the first of October and no character says the question is settled or that it is not.**
7. **His brother's file, which `outline/ending.md` alone decides.** Volume 13 may write *his brother's file* and may not write the name. **`Lin Wei` returns 0 across all fifty chapters.**

---

## 15. FINDINGS, AS ONE ITEM

**A · RECORDED. `chapter-0643.md`:257 PRINTS *FIFTEEN DAYS* FOR FORTY-FIVE, AND THE STATE FILE THAT REPAIRED IT PRINTS *THIRTY* AND GIVES A REASON THAT IS ALSO FALSE.** `2,129 − 2,084 = 45`. Operands printed so that one commit can repair it.

**B · RECORDED. `chapter-0646.md`:189 AND `chapter-0647.md`:211 PRINT *ELEVEN TIMES* FOR A SHEET THAT HAS GONE OUT FIVE TIMES.** The count is five: 1,769, 1,859, 1,949, 2,039, 2,129. Eleven is the count from the thirteenth sheet and answers a different question.

**C · RECORDED. THE ORDINAL OF THE INVENTED-FIGURES SENTENCE AMONG THE FOUR AT THE FOOT IS BOTH *FIRST* AND *THIRD*, AND `chapter-0618.md` CONTRADICTS ITSELF BY NINETY LINES.** `chapter-0643.md`:115 is the scene and is the authority.

**D · RECORDED. THE WALL'S HEADCOUNT IS PRINTED AT 603 AND NOT ONLY AT 605.** The reprint at 645 is gone and that part of the row holds; the print at 603 is still there.

**E · RECORDED. THE FOUR CONDITIONS ARE WRITTEN OUT IN FULL FOUR TIMES IN 601–650 AND TWO FILES SAY ONCE.** 601:43, 611:15, 630:75, 644:57–61.

**F · RECORDED. THE GATE ROW NAMING `chapter-0637.md`:75 AS THE REMAINING VERBATIM PRINTING OF THE INVENTED-FIGURES SENTENCE IS FALSE IN BOTH HALVES.** 637:75 is a paraphrase in his own words; 618:67 is the only verbatim printing in 601–650; and the first printing is 595 in Volume 12.

**G · RECORDED. TWO TITLE LINES CARRY A STRAIGHT APOSTROPHE** — 632 and 637 — against a row that reported zero for title lines by name.

**H · RECORDED. THREE OF THE FIVE BATCH DENSITY ROWS DO NOT RE-DERIVE, AND THE CLAIM THAT THE SPAN ROW HELD EXACTLY IS FALSE.** 71.3 against 70.4, not against 71.1.

**I · RECORDED, AND IT IS THE MOST IMPORTANT ONE IN THIS FILE. `chapter-0606.md`:113 IS A PARAGRAPH OF DIRECT SPEECH WITH NO QUOTATION MARKS AND NO SPEECH TAG AND IT BEGINS MID-SENTENCE, AND `chapter-0606.md`:119 REPEATS `:89` VERBATIM THIRTY LINES APART.** Five gates and one review-fix passed it. **A WITHIN-FILE DUPLICATE-PARAGRAPH ROW IS ADDED TO THE LIVE GATE AND IT FINDS FIVE, OF WHICH ONE IS A DEFECT AND THREE ARE DELIBERATE AND ONE IS A TEST.**

**J · RECORDED. `chapter-0606.md`:7 IS `chapter-0597.md`:17 WITH FOUR WORDS CHANGED, ACROSS SIXTEEN SHARED TWELVE-GRAMS AND ACROSS THE VOLUME BOUNDARY, AND NO GATE LOOKED BACK AT 601.** And the batch's own 45-pair duplication row re-runs at 42 under the method the row declares.

**K · APPLIED. `outline/volume-13.md` §5c's FIVE DATES ARE CORRECTED TO THE PAGE, AND THE §5c INTERVAL LIST FOR 631–640 WITH THEM.** This is the one change applied, it is in the planning file rather than in prose, no chapter was touched, no event was moved, and it is flagged as a canon change in the live block at the head of `state/open-threads.md` and in §3 of this file.

**L · RECORDED, AND IT NARROWS TO ONE CHAPTER. FOURTEEN CHAPTERS OF 601–650 SIT ABOVE THE 2,700 CEILING AND ARE NOT THE FIVE SCENES; NINE OF THE FOURTEEN CARRY A REASON IN THIS CLOSE'S OWN §0a AND FOUR MORE CARRY ONE IN THE BATCH BLOCK THAT WROTE THEM — 621 AND 630 AT `state/current.md`:764, 636 AT `:582`, 638 AT `:579` — AND `chapter-0632.md`, AT 2,827, CARRIES ONE NOWHERE.** It was written 127 words over a band that exists to keep a chapter honest about its own length. **THE CHAPTER IS NOT CUT; THE GAP IN THE RECORD IS NAMED, WHICH IS THE ONLY THING A CLOSE AUDIT IS ALLOWED TO DO TO A FINISHED FILE.** *(The first edition said four of the fourteen and then named five, and §4d of the same file said §0a held reasons for all five of them. Both repaired 14 October 2026 against the lines themselves.)*

**M · RECORDED. SIX ANNOUNCED-AGE STRINGS SURVIVE AT 639 AND 640.** At `chapter-0639.md` *I am sixteen* twice (:43, :85), *You are sixteen* once (:87) and *a boy of sixteen* once (:185, footer); at `chapter-0640.md` *a boy of sixteen* twice (:3, :173) — **six strings in two chapters**, handed forward by batch 0004's review-fix as a disclosed exception and never closed. The batch-0005 repair took the third age out of 649 and left these two chapters alone. **The first edition of this entry printed five, and put the third *I am sixteen* at 639 and two *a boy of sixteen* there, which reverses the chapters; `state/current.md` §0r-6 carried the correct breakdown and this entry did not read it. Repaired 14 October 2026 against the files.**

---

## 16. WHAT WAS APPLIED, AND WHAT WAS NOT

**APPLIED IN THIS COMMIT — one planning file, and no word of prose:**

1. `outline/volume-13.md` §5c — the five chapter dates for 631–640 corrected to the page (632 the fifteenth of August, 633 the twenty-third, 635 the eighth of September, 636 the fifteenth, 637 the twenty-second) and the 631–640 interval list corrected to `7 8 8 7 7 7 8 12 9 = 73`, with the page's six independent statements of the previous chapter's date printed beside it and the change flagged as a canon change. **The planning file no longer contradicts itself, and §7's movement-four table, which already carried the page's set, now agrees with §5c.** *(The first edition of this entry printed `8 7 8 8 7 7 8 12 9`, which sums to 74. See §3 for the cause and the test.)*
2. `state/current.md`, `state/continuity.md` and `state/open-threads.md` — a close block at the head of each, superseding the batch-0005 blocks and deleting none of them, carrying the re-derived spine, the re-derived banks, the re-derived density, the seven re-derived 643 measurements, the re-run gate, the twenty-one-row hand classification of the twelve-gram scan, the within-file duplicate row, the orphan-paragraph row, and Findings A through M.

**NOT APPLIED, AND NOT THIS PHASE'S:** every repair inside a finished chapter of 601–650 — Findings A, B, C, D, E, I, J and M — and every repair inside a closed volume — §12 items 1, 2, 3 and 4. **Of the thirteen findings in §15, ONE is applied here — K, in the planning file — and TWELVE are recorded with the correct figure and its operands, so that one commit can repair them and re-run the five batch gates that certified the files: eight sit inside finished chapters (A, B, C, D, E, I, J, M) and four sit inside state files or gate rows rather than prose (F, G, H, L). A repair instruction that drops the operand is the same defect it is repairing.** *(The first edition of this sentence said nine of the ten. §15 itemises thirteen, A through M; one is applied, so twelve are recorded.)*

---

## 17. WHAT THIS PHASE HANDS ON

**THE SERIES IS PLANNED PAST 650. `state/complete.md` IS NOT CREATED.** `outline/ending.md` is untouched and is inherited whole: Lin Wei alive and classified and never out of the Classification Wing · the reservoir returned in full at 486 and **never replenished** · Lin Hao at rank one on a branch night shift · the Church of the Quiet Number not dissolved, not vindicted and not converted into an institution · Ferreira lives · Sowe lives · **Adeyemi is Registrar of Unrecorded Merit** · no partner dies · no partner is left behind by a choice she does not explain.

**VOLUME 13 CLOSED ITS OWN PROMISE. IT PAID IT AT 644, IN THE OFFICE'S OWN HAND, WITH A PEN, WITH HIS OWN NAME UNDER THE STRIKING AND NOTHING IN THE TWO INCHES WHERE THE FOURTH LINE HAD BEEN.** A rule a city cannot check came off the most widely read page in the city, and the man who wrote it wrote nothing where it had been, and every claim that rested on it died at once — and the only one that mattered was always going to be a claim by a person who cannot read, who can now say almost anything at all and cannot say that anybody took anything off her.

**AND IT DID THE OTHER HALF BEFORE IT WAS ASKED TO.** About nine hundred people in a yard took the fourth line off their own board with a rag and a bucket in about eleven minutes on the seventh of July, and then came back on the ninth of November for the other three and did it in about nine hours, and nobody asked the man who wrote them, and the chaplain was not there and nobody went up to her. **That is the correct thing to do and it is the worst thing that happens in this volume, and it is in the book because the volume was about a rule and not about the man who wrote it.**

**AND AT 617 THE WOMAN TWO FLIGHTS UP OFF CORDWAIN LEARNED WHAT WAS DONE FOR HER**, from a man in a delivery coat reading twelve books aloud into the cold because she cannot read them, and she asked him which of them he had made up, and he said all nine, and then she said the sentence this whole volume is about — *nobody told me* — and he answered it correctly. **No.** She was not thanked. She was given nothing. It was not a scene.

**THE SEVEN THINGS THIS VOLUME DOES IT TO ITS READER, STATED AT THE VOLUME'S OWN SCALE AND NOT ITS AUTHOR'S:**

1. **A question that cannot be tested is not a rule, and the man who wrote it says so out loud in a yard of about eleven thousand people, and is believed by about four hundred.**
2. **A figure nobody checks becomes whatever the yard decides it is, in about eleven minutes.**
3. **A page can be read into a real book and that is worse than a page shutting one, because an entry about an absence is not carried, it is written off.**
4. **A person who cannot read is owed nothing, and that is correct, and it took a sentence off a wall to make it visible.**
5. **He gave away the only claim anybody had ever had on his own office, and the claim was on him, and he said his own name into a finding, and the finding narrowed his own rule without his consent.**
6. **He found out that the thing he has been standing upright on for four hundred days is a column with a heavy line across the foot of it and nothing under the line, and there is not one instrument in Ostara that can fill it.**
7. **A boy with a scraper takes six years of paint off a wall and finds sixty-two blank forms stacked inside it, and makes the first rubbing anybody has ever made there, and says no when he is offered a rail, because a rail is a place a thing is read once by about nine people a week and a corner is a place a thing is said.**

**AND THE STANDING RULE FOR EVERY ARITHMETIC ROW FROM HERE ON, LEARNED AT THE COST OF FIVE FAILURES IN VOLUME 11, TWO MORE INSIDE A SINGLE PHASE OF VOLUME 12, NINE FINDINGS IN VOLUME 12's CLOSE, TWENTY-SIX FINDINGS IN BATCH 0005's REVIEW AND THIRTEEN MORE IN THIS AUDIT:**

> **A figure nobody re-computes is the figure that is wrong.**
>
> **A gate row that quotes the prose it is checking cannot catch the prose. And a gate that measures only its own batch cannot see what happened before it — which is how a house form changed at chapter 571 and four arithmetic gates passed it, and how a span row was reported as having held exactly when its predecessor had not been measured since a repair.**

**AND ONE MORE, ADDED HERE, BECAUSE IT IS THE ONE THIS AUDIT HAD TO WRITE BEFORE IT COULD FIND ANYTHING:**

> **A gate that scans between files cannot see a chapter repeat itself. Two of the thirteen findings in this file are inside a single chapter, and neither is visible to a cross-file twelve-gram scan, and one of them is the reason a chapter of this volume cannot be read at its climax.**