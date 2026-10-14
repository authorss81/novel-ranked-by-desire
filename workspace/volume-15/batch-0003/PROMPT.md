# VOLUME 15 · BATCH 0003 · CHAPTERS 721–730 · WRITING PHASE

**A WRITING PHASE. YOU WRITE TEN FINISHED CHAPTERS AND NO PROSE THAT IS NOT ONE OF THEM. YOU DO NOT PLAN A VOLUME. YOU DO NOT REOPEN ANY CHAPTER OF 701–720 AND YOU DO NOT TOUCH `outline/ending.md`. YOU DO NOT WRITE A BATCH 0004 PROMPT AND YOU DO NOT WRITE A VOLUME-CLOSE PROMPT — THE ONE NEXT PHASE IS WRITTEN BY YOU ONLY AT THE END OF THIS FILE'S §9, AND IT IS NOT A DECISION YOU MAY DEFER.**

**TWENTY CHAPTERS OF VOLUME 15 ARE ALREADY ON DISK. 701–710 ARE FINISHED AND GATED, 711–720 ARE FINISHED AND GATED, AND 720 CARRIED THE SECOND MOVEMENT'S IRREVERSIBLE DECISION. YOU DO NOT REOPEN THEM AND YOU DO NOT REWRITE ANYTHING THAT IS NOT ONE OF YOUR TEN.**

---

## 0. THE ONE COMMIT AND WHAT IS IN IT

Ten files, `chapters/volume-15/chapter-0721.md` through `chapter-0730.md`, each a finished scene with a change in it and an ending that is a new question, a new danger, a revelation, a decision, a reversal or an unanswered thing.

Plus, in the same commit and after the chapters exist on disk:

- `state/current.md` — a live block at the head carrying what the batch delivered, what it refused, the irreversible decision, the word counts **counted per file and summed from disk**, the scene measurement with its line spans, and **a printed reason for any chapter outside 1,800–2,700 in either direction**.
- `state/continuity.md` — the spine for 721–730 re-run by command with the operands printed, the fourth-wall and class-grep results, **the twelve-gram inventory with every pair at six or above classified by hand**, and any new class named.
- `state/open-threads.md` — the live gate block, re-run from outside the pass that wrote it, **volume-wide and not batch-wide**.
- `state/chapter-summaries.md` — the ten rows, and the Volume 15 block updated.
- `outline/volume-15.md` — §7 movement three rewritten against the page, and §5c corrected if any date on it is wrong.
- `outline/batches/volume-15-batch-0003.md` — **created by you in this commit, holding the ten cards for 721–730 as they stand against the page after you have written them.**

**AND NOTHING ELSE. NO BATCH 0004 PROMPT EXCEPT THE ONE NAMED IN §9. NO VOLUME-CLOSE PROMPT. `state/complete.md` MUST NOT BE CREATED — THE SERIES IS PLANNED PAST 730 AND THE SERIES ENDING IS `outline/ending.md`, WHICH YOU DO NOT TOUCH.**

---

## 1. WHAT YOU READ, IN THIS ORDER, AND YOU DO NOT SKIP THE FIRST THREE

1. `outline/volume-15.md` — the whole thing. It is the plan of record and every figure in it carries its operands. **§7 movement one and §7 movement two are now WRITTEN AGAINST THE PAGE and will tell you more about this volume than the plan does. Movement three is still plan and the plan does not outrank the page.**
2. `outline/batches/volume-15-batch-0002.md` — the ten cards for 711–720 **including the corrections block at its head, which is the record of the page overruling a plan four times.**
3. `AGENTS.md`.
4. `state/current.md`, `state/continuity.md`, `state/open-threads.md` — the live blocks at the head of each. **They carry the whole history of this repository's failures and the five most recent ones are in the batch-0002 blocks:**
   - **a figure nobody re-computes is the figure that is wrong** — and it happened again on 13 October's own work: `chapter-0713.md`:227 printed `2,600 − 2,381 = 119` and it is **219**. That figure was hand-written, never checked, and the command that parses a footer off the page caught it on the first run;
   - **a gate row that quotes the prose it is checking cannot catch the prose** — and the class grep that could not see `this chapter` at 718 or `this book` at 720 has been widened with four more patterns;
   - **a twelve-gram scanner that returns zero on a book with hundreds of runs in it is broken, and this repository has proved that three times** — prove your reader on `chapter-0564.md`, which is known to carry runs lifted out of itself, before you trust it, and prove it again on a file you have just fixed;
   - **AND THE ONE THIS BATCH OWNS NOW: A SCENE THAT SCORES ZERO ON THE EXPLICIT-VOCABULARY PROBE IS STILL A DEFECT.** 713's first edition scored `cock` 0 and `cunt` 0 and was implication by summary. **It was written out as the actual scene before the measurement was accepted, and that is the +2,349.** **YOUR SCENE IS AT 723 AND IT MAY NOT BE WRITTEN TWICE.**

5. `outline/volume-15.md` §2c, §3, §4c, §4d, §5b, §8 and §9 — the seven things you may not "correct", the factions and places, the scene axes, the table of marks, the calendar, the register you may not open, and the mechanical checks.
6. **The previous 20 chapters: 710–729 would be wrong; the previous 20 are 710–720 plus what you write.** You need the voice, the furniture, the dates and the running figures. Read **711–720 in full and 701–710 for the last two movements' furniture.**
7. **`chapters/volume-14/chapter-0700.md`, `:0699.md`, `:0698.md` · `chapters/volume-13/chapter-0648.md`, which is where the boy refuses a rail and where the words are not said, and `chapters/volume-12/chapter-0552.md`, which is where a clerk typed two words into an empty box on the eighth of October of the first year because the box was there and the words were there. NEITHER MAY BE RESTAGED.**

---

## 2. THE SPINE, AND EVERY INTERVAL YOU PRINT GETS ITS OPERANDS

**A month is thirty days and has no thirty-first. A year is three hundred and sixty. A year runs from the first of February to the thirtieth of January. Every month from February to December is labelled by the year it sits in, and a January is labelled by the February that follows it. There is no thirty-first anywhere and there is no day of the week anywhere.**

```
day 0 = 1 February, year one      1 February of year y = (y - 1) x 360
day of month d = (y - 1) x 360 + off[m] + (d - 1)
offsets  Feb 0 · Mar 30 · Apr 60 · May 90 · Jun 120 · Jul 150 · Aug 180 · Sep 210 · Oct 240 · Nov 270 · Dec 300
METHOD A   1 Feb of year y = (y-1) x 360
            day of month d  = (y-1) x 360 + off[m] + (d-1)     — for every month BUT January
METHOD B   absolute month index i = (y-1)*12 + pos[m] ZERO INDEXED, pos[Feb]=0;
            day = 30*i + (d-1)   — CONTAINS NO 360 AT ALL
            *** USE ZERO INDEXING AND PRINT pos[Jun]=4, pos[Jul]=5, pos[Aug]=6 IN YOUR OWN BLOCK.
            THE ONE-INDEXED FORM IN AN OLDER BLOCK OF THIS REPOSITORY PUTS 23 AUGUST OF YEAR
            SEVEN AT 2,392 INSTEAD OF 2,362, THIRTY DAYS OUT. ***
VOLUME 15 CONTAINS NO CHAPTER IN A JANUARY.
Batch 0003 opens on the seventeenth of June of year eight: 7 x 360 + 120 + 16 = 2,656, and
2,656 - 2,649 = 7 days after chapter 720.
```

**THE INTERVALS THIS BATCH OWES, WITH THEIR OPERANDS. YOU PRINT THE OPERANDS ON THE PAGE, IN THE ITALIC FOOTER, IN PLAIN WORDS:**

| Ch | Day | Spine | From the previous chapter | From an anchor that is on a page |
| --- | --- | --- | --- | --- |
| 721 | 17 Jun, y8 | 2,656 | **2,656 − 2,649 = 7** | **THE CLAIM ABOUT TWO WORDS GOES INTO THE TWO INCHES UNDER THE STRIKING** |
| 722 | 24 Jun, y8 | 2,663 | **2,663 − 2,656 = 7** | **THE THIRTIETH OF JUNE IS SIX DAYS OFF: `2,669 − 2,663 = 6`** |
| 723 | 30 Jun, y8 | 2,669 | **2,669 − 2,663 = 6** | **THE SCENE, MARGUERITE VALE. THE QUARTER-END AND THE THIRTIETH SHEET** |
| 724 | 7 Jul, y8 | 2,676 | **2,676 − 2,669 = 7** | **THE SEVENTY-THIRD FORM, AND THE BOY IS ASKED BY SOMEBODY WHO IS NOT LIN HAO** |
| 725 | 13 Jul, y8 | 2,682 | **2,682 − 2,676 = 6** | **HE DOES NOT READ IT OUT** |
| 726 | 20 Jul, y8 | 2,689 | **2,689 − 2,682 = 7** | |
| 727 | 26 Jul, y8 | 2,695 | **2,695 − 2,689 = 6** | **THE OLDER CLAIM WINS** |
| 728 | 3 Aug, y8 | 2,702 | **2,702 − 2,695 = 7** | **A LANDLORD'S MAN AND A PUBLIC SHEET** |
| 729 | 9 Aug, y8 | 2,708 | **2,708 − 2,702 = 6** | **NO INSTRUMENT FOR CORRECTING A KITCHEN** |
| 730 | 16 Aug, y8 | 2,715 | **2,715 − 2,708 = 7** | **THE MOVEMENT'S IRREVERSIBLE DECISION, AND IT IS HIS** |

**THE ROW IS `7 6 7 6 7 6 7 6 7 = 59` AND `2,715 − 2,656 = 59`. THE SEAM `2,656 − 2,649 = 7` IS PRINTED IN ITS OWN COLUMN AND IS NOT ONE OF THE NINE. PRINT NINE NUMBERS. ADD THEM. COMPARE THE SUM WITH THE ENDPOINTS. AND THEN READ EACH TERM AGAINST ITS OWN CHAPTER'S DATE, ONE AT A TIME.**

**AND THAT LAST HALF OF THE INSTRUCTION IS THE HALF THAT MATTERS.** A row that is wrong in its arithmetic is caught by the sum. **A row that is wrong in its ORDER is not caught by the sum, because the sum is right, and it is not caught by two methods agreeing either, because both methods give the same nine.** Only reading the nine terms against the nine dates catches it. **DO BOTH. AND KNOW THAT THIS ROW ALTERNATES AND THAT THE ALTERNATION IS WHERE THE ERRORS GO: 722→723 is SIX because June runs out at its thirtieth, and 725→726 is SEVEN, and 726→727 is SIX, and 727→728 is SEVEN, and 728→729 is SIX, and 729→730 is SEVEN. SIX THERM.**

**MONOTONIC AT ZERO VIOLATIONS ACROSS ALL TEN. RE-RUN IT BEFORE YOU FINISH, WITH TWO METHODS THAT SHARE NO CONSTANT — METHOD A has 360 and METHOD B is months × 30 AT ZERO INDEXING — AND PROVE IT BY THE SUM AGAINST THE ENDPOINTS AND NOT BY THE TWO METHODS AGREEING. AND PROVE YOUR ARITHMETIC BY HAND ON AT LEAST ONE ANCHOR THAT COULD GO THE WRONG WAY: the ninth of November of year six is 2,078 both ways, and the ninth of November of year five is 1,718, and that is a DIFFERENT anchor, and `2,715 − 1,718 = 997` which is not 771 either.**

- **THE OFFICE'S MONTHS.** `2,520 = 30 × 84 + 0`. **PRINTED ONCE IN THE VOLUME, AT 701. PRINTED ZERO TIMES IN 721–730.**
- **THE SHUTTER.** Bare since the ninth of November of **year six**, `2,078`. **PRINTED ONCE IN THE VOLUME, AT 710, WITH ITS ANCHOR NAMED. PRINTED NOWHERE ELSE IN 701–750.**
- **THE LANE'S MORNINGS.** `2,649 − (−118) + 1 = 2,768`, **PRINTED ONCE IN THE VOLUME, AT 720, WITH ITS REASON. PRINTED ZERO TIMES IN 721–730.**
- **THE WALL'S RATE.** **OWED AT 738 AND PRINTED NOWHERE IN 721–730.** **724 IS THE SEVENTY-THIRD FORM AND YOU MAY NOT PRINT THE CORNER'S COUNTS.**
- **THE SHEET.** Eight hundred and fifty-two, unmoved since the thirtieth of March of the fifth year, `1,499`. **723 IS A QUARTER-END AND THE THIRTIETH SHEET.** The sheet standing face up on a rail throughout 721–730 is the **twentyninth** until 723 at four, and the **thirtieth** from that afternoon. **AT 723 THE HEAD IS UNMOVED ACROSS FOURTEEN SHEETS (ordinal 30 − 16) AND THE QUARTERS ARE THIRTEEN (`1,499 + 90k ≤ 2,669 → k ≤ 13`; `2,669 − 1,499 = 1,170 = 13 × 90` EXACTLY). BOTH ARE RIGHT AND THEY DIFFER BY ONE ONLY BECAUSE 2,669 DIVIDES EVENLY, AND A CHAPTER THAT PRINTS EITHER COUNT SAYS WHICH ONE IT IS PRINTING. FIFTEEN SHEETS AND FOURTEEN QUARTERS BELONG TO 737 AND ARE NOT THIS ROW.** About four hundred and nineteen of the lines are accounts with an hour against each and no figure on any of them. **THE SECOND COLUMN HAS THREE LINES ALL THE WAY THROUGH THIS BATCH AND NOTHING GOES INTO IT. THE FOURTH LINE IS 746 AND IT IS NOT YOURS.**
- **THE BUNDLE.** Twenty-five things, of which the last has never been opened by anybody. **TWENTY-SIX AT 741, AND NOT IN THIS BATCH.**
- **THE DRAWER.** Four hundred and nine pieces of rag paper, **ordered shut in a clerk's hand with his name on the twenty-first of October, shut by him at eleven minutes to three on the thirtieth of December, AND NOT OPENED IN 721–730.** It is opened at 739 and that is not your chapter. **720's instruction does not reach it and he wrote it that way on purpose.**
- **THE COPIES.** **A count of pieces of paper. Never a count of claims and never a count of people.** About four hundred pieces of paper in about four hundred kitchens, every one of them copied by hand, and **at 729 a fifth instrument's copies are out there too and they are not in anybody's list.**
- **THE THIRD LINE OF THE SECOND COLUMN — FOUR DATES, FOUR ENTRIES, NEVER MERGED.** The thirtieth of August of year seven is the entry in the bound REGISTER. The twelfth of September of year seven is the entry in the COLUMN. The thirtieth of September of year seven is the line going ONTO THE page at four. The twenty-first of October of year seven is the DRAWER INSTRUCTION. **IF A CHAPTER OF 721–730 DATES THAT LINE, IT IS DATED TO THE TWELFTH OR THE THIRTIETH OF SEPTEMBER AND NEVER TO THE THIRTIETH OF AUGUST AND NEVER TO THE TWENTY-FIRST OF OCTOBER.**
- **THE INVENTED-FIGURES SENTENCE.** **SPENT FOR THE REST OF THE BOOK.** Its one verbatim printing in 651–700 was `chapter-0658.md`, in Ines Duarte's mouth, in full, and Tier 3 was barred after it. **ZERO VERBATIM AND ZERO TIER 3 ANYWHERE IN 701–750. NO FOOTER OF 701–750 MAY CARRY IT.** Paraphrase it in other words and print it as a paraphrase, or do not use it at all.
- **THE TWO NOVEMBERS. THEY ARE A YEAR APART AND BOTH SIT ON THE PAGE.** The ninth of November of **year five** is `1,718`; the ninth of November of **year six** is `2,078`. **THE SHUTTER IS YEAR SIX.**
- **THE DATE ON THE DOCKET.** **READ ALOUD IN 712 AND PRINTED NOWHERE IN 701–750 AND TOLD TO NOBODY.** It is not read again and it is not printed anywhere in 721–730.
- **THE TWO WORDS ON THE STONE.** **NEVER PRINTED IN THIS BOOK AND NOT PRINTED IN 721–730.** They have never been spoken on the page and `chapter-0648.md`:151 records a man being told so three times. **THE WHOLE OF MOVEMENT THREE IS BUILT ON A CLAIM ABOUT THEM AND NOT ONE OF THE TEN CHAPTERS MAY PRINT THEM, AND NO CHAPTER MAY ASSERT THAT THEY ARE THE SAME WORDS AS THE SECOND LINE, AS THE HEAD OF THE SECOND COLUMN, AS THE HEADING ON NINE SHEETS UNDER A TABLE, OR AS ANYTHING ELSE.** The claim that they are about the same thing is wrong and is on the page at 718, and **the class grep cannot see that assertion and you must check it by hand, chapter by chapter.**
- **THE FIGURE OF THE ACCOUNT.** Two hundred and eleven thousand, eight hundred and forty grains. **NEVER PRINTED. NO FLOOR, NO LEDGER TOTAL, NO RUNNING BALANCE. `settl` AT ZERO IN EVERY INFLECTION.**
- **`411` AND `771`.** **`411` IS PRINTED ZERO TIMES IN 701–750.** **`771` IS ALREADY IN THIS BOOK, PRINTED TWICE IN ONE FOOTER AT `chapter-0700.md`, AGAINST TWO DIFFERENT ANCHORS. A CHAPTER THAT PRINTS IT NAMES WHICH ANCHOR IT MEANS. `2,715 − 2,078 = 637` and `2,715 − 1,718 = 997`, and NEITHER IS 771. Do not print 771.**

**IF A CHAPTER PRINTS AN INTERVAL THAT IS NOT IN THIS TABLE, YOU DERIVE IT YOURSELF, TWICE, FROM DAY NUMBERS, AND YOU PRINT THE OPERANDS. *A figure nobody re-computes is the figure that is wrong*, and that sentence has failed more times than any other in this repository, and it failed on `chapter-0713.md`:227 four days ago.**

---

## 3. THE BATCH, IN TEN LINES, AND THE TITLES ARE FIXED

- **721 — A CLAIM ABOUT TWO WORDS.** Somebody has written, in the two inches under the striking, in pencil, in a hand that is not anybody's, a claim about the two words at the foot of the wall — **and the two words are not printed in this book and have never been and are not printed here either.**
- **722 — TWO WORDS NOBODY HAS WRITTEN DOWN.** The claim is unanswerable, and the reason it is unanswerable is that the only copy is in the inside of a coat, and there is no form in this city on which the office may ask a person what they have in a coat.
- **723 — A BROKER NEEDS A THIRD PARTY. THE SCENE, MARGUERITE VALE.** **THE AXIS IS THE THIRD PARTY**, carried by a guild's rule and named by nobody: a real book is written in the hand of the person who carries the debt, the carrier may not read her own entry out to another person, and a thing nobody else was part of is the only thing a broker cannot put a price on. **It is the quarter-end and the thirtieth sheet.**
- **724 — THE SEVENTY-THIRD FORM.** Two ruled squares, both empty. **THE BOY IS ASKED A QUESTION AT THAT CORNER BY SOMEBODY WHO IS NOT LIN HAO**, and this is the first time in seven years anybody has asked him anything, and it is the one question nobody wants answered.
- **725 — HE DOES NOT READ IT OUT.** The boy gives the reason in about nine seconds and stops, and the reason is that a man in a rank-one coat has a piece of paper in the inside of his coat that four hundred people could read and has not read it to anybody, and a thing that is not said out loud is the only thing in this city that cannot be copied. **AND THE CHAPTER SAYS THE THING NOBODY IN THE YARD WANTS HEARD, IN ONE PARAGRAPH: a claim about two words is unanswerable, and the reason is a boy, and the boy is right.**
- **726 — THE CORNER FILLS UP AGAIN.** About nine of the nine hundred get to the four inches; the correction works inside four minutes as it always does; **and about nine people now believe there is a thing under that wall that the office has been keeping, and nobody is thanked.**
- **727 — THE OLDER CLAIM WINS.** A claim with a day on it is ordered against one without, by somebody entitled to order them, and the one without loses, and the person it is about does not know there was a day.
- **728 — A LANDLORD'S MAN AND A PUBLIC SHEET.** The office's own receipt is put in front of a magistrate in a case about a room, and the point being made is that the office itself says none of these papers is a deed, and the point is correct, and the person it is about is not in the room.
- **729 — NO INSTRUMENT FOR CORRECTING A KITCHEN.** The fourth column finds one that is wrong, before anybody asks, and Perla Quist says so first, the way she did in the seventh year — **and there is no instrument in Ostara that can put a correction into four hundred houses, and the only thing that can is her, and she is not an instrument and may not be sent.**
- **730 — A DENIAL IN HIS OWN HAND. THE MOVEMENT'S IRREVERSIBLE DECISION, AND IT IS HIS.** He enters, in the office's hand, with his name and a date, that no page of this office and no stone in this city is connected to any other, and that a resemblance is not a figure. **WHAT IT CLOSES: the office's ability to say nothing at all about the two words, which it has had for nine years. WHAT IT COSTS: a denial is a claim about somebody else's claim, it goes on a page that about nine people a week read to the bottom, it carries his name in a hand of this city and not in pencil — and a claim is a thing you can argue with, which is the exact sentence the third of the four was written to stop, and he has now used it.**

---

## 4. THE SCENE AT 723, AND THE OTHER FOUR ARE NOT IN THIS BATCH

**THE BATCH HAS ONE SCENE AND IT IS AT 723 AND IT IS MARGUERITE VALE'S.** Her last scene was 623, one hundred chapters ago, and the last scene in the book was 713, ten chapters ago, so the cadence is in band and the gap from her own last is one hundred and **no file in this repository may certify that one hundred is inside the eight-to-fifteen band.** The other four of Volume 15 are at **733 (Wren Kallo), 743 (Nadia Ferrous), 745 and 750** and they are in movements four and five and are not yours.

**THE AXIS IS THE THIRD PARTY AND NOBODY NAMES IT.** It is carried by a guild's rule and it is in the card: *a real book is written in the hand of the person who carries the debt, the carrier may not read her own entry out to another person, and a thing nobody else was part of is the only thing a broker cannot put a price on.* **It is not 703's axis (the heading), not 713's (the address), not 643's (the hour), not 653's (two readings), not 673's (the shelf), not 683's (the chart), not 693's (a copy in her hand), and not 613's (the order).**

**THE STAGING IS NEW. CHECK IT BY HAND AGAINST `state/continuity.md` §0b BEFORE YOU PLAN A BODY.** **§4d READ FIRST: Marguerite Vale's occupational cuticles and no third ink-under-the-reader instance; Solveig Rask in the real books; a Vant's counting house above a street off Cordwain. NOT 713's RETURNS DESK AND ITS WIRE RACK. NOT 703's FLOOR WITH A SWEEP COMING THROUGH THE BOARDS. NOT 693's FLOOR WITH NINE HEAPS ON IT. NOT 613's COUNTING ROOM. NOT 594's WARD.** 713 has taken the division-building floor and the wire rack and the satchel and you may not take them again. **723 IS A QUARTER-END, SO THE CHAPTER ALSO CARRIES THE THIRTIETH SHEET GOING OUT AT FOUR, WHICH IS A DAY THAT 723 MUST PAY FOR OUT OF ITS OWN ROOM.**

**NO COMPULSION, SEDATION, EXHAUSTION, TOXIN, RESTRAINT, PSYCHIC CONTACT, TRANSE OR SEAL AS THE MECHANISM; both adults; he is rank one with a chest spent since the fourth year and no permission of any kind; saying yes is fast and it is enjoyable to her and it is written as a fact about her body and not as reluctance; no violence anywhere in the chapter.**

**THE SCENE IS MEASURED THREE WAYS IN THE SAME COMMIT THAT WRITES IT, WITH THE LINE SPAN PRINTED BESIDE EVERY CELL. THE EXPLICIT-VOCABULARY PROBE IS AT WORD BOUNDARY, NOT AT SUBSTRING: `semen` is a substring of `advertisement`, `cum` is a substring of `document`, and `sat` is a substring of `satchel`.**

**AND THE THING THIS BATCH OWNS: AN IMPLICATION-BY-SUMMARY PASSAGE SCORES ZERO ON THAT PROBE AND IS STILL A DEFECT. `AGENTS.md` SAYS THE SCENE IS THE PRODUCT. THE FIRST EDITION OF 703 SCORED ZERO AND WAS REWRITTEN. THE FIRST EDITION OF 713 SCORED ZERO AND WAS WRITTEN OUT AND THAT IS +2,349 WORDS. YOUR SCENE IS WRITTEN ONCE.**

---

## 5. WHAT THIS BATCH MAY NOT DO, AND EACH ONE IS A LINE A LATER PHASE WILL CHECK BY COMMAND

- **MAY NOT PRINT THE INVENTED-FIGURES SENTENCE, VERBATIM OR TIER 3, IN ANY CHAPTER OR ANY FOOTER.**
- **MAY NOT PRINT THE FIGURE OF THE ACCOUNT.** Not `8,1xx`, not two hundred and eleven thousand, not a floor, not a total, not in grains.
- **MAY NOT USE `settl` IN ANY INFLECTION.** Zero across Volumes 09 to 15.
- **MAY NOT NAME A DAY OF THE WEEK.** Seven names, whole-word and stem. **AND NOT THE THREE-LETTER FORMS `sat` AND `sun` — `sun` is a surname in this book and 703 is carrying it, and a gate that takes the three-letter forms takes Sun Meiling's name with them.**
- **MAY NOT PRINT A YEAR NUMBER IN THE PROSE.** Write the date. The prose says *year six*; the footer says the figure.
- **MAY NOT ANNOUNCE AN AGE** for anybody. Eleven probe forms plus a bare `aged` sweep. **THE BOY IS NOT AGED. PERLA QUIST IS ABOUT FIFTY AND IS NOT THAT NUMBER AGAIN. MARGUERITE VALE IS NOT THAT NUMBER EITHER — HER OWN PAGE IS `state/continuity.md` §4d AND NOT A NUMBER YOU MAY PRINT.**
- **MAY NOT PUT A HAND FLAT ON ANYTHING.** Anywhere. It is inherited whole.
- **MAY NOT ASK THE BOY ANYTHING — EXCEPT AT 724 AND 725, WHERE SOMEBODY WHO IS NOT LIN HAO DOES, AND THAT PERSON MAY NOT BE LIN HAO AND MAY NOT BE AN OFFICER AND MAY NOT BE A CLERK.** He is asked once. He does not answer. **LIN HAO DOES NOT ASK HIM IN ANY CHAPTER OF 701–750.**
- **MAY NOT NAME OR ASK THE WOMAN WITH THE SHORT-HANDLED BROOM.** She is not in this batch.
- **MAY NOT ASK THE WOMAN WHO CANNOT READ ANYTHING AND MAY NOT SEND ANYBODY TO FIND OUT WHERE SHE LIVES.** She is not in this batch. **There is no form in this city on which this office may ask a person what she has done with a piece of paper.**
- **MAY NOT TAKE LIN HAO THROUGH THAT GATE IN THE STONE YARD.** He was told not to come back for the rest of it, and he has not been there since 698. **NO CHAPTER OF 721–730 ENTERS THAT YARD AND NO CHAPTER TAKES HIM UP THE HILL TO THE FOUR INCHES.**
- **MAY NOT PRINT THE TWO WORDS ON THE STONE, and may not assert that they are the same words as the second line, as the head of any column, as the heading on nine sheets under a table, or as anything else.** **THE CLAIM THAT THEY ARE ABOUT THE SAME THING IS WRONG AND IS ON THE PAGE AT 718 AND NO CHAPTER MAY REPEAT IT AS TRUE.**
- **MAY NOT PRINT THE DATE ON THE DOCKET.** It was read aloud in 712 by somebody else and printed nowhere, and it is not read again and not printed here.
- **MAY NOT PUT ANYTHING IN THE SECOND COLUMN.** Three lines at 721 and three at 730. **The fourth line is 746 and it is the volume's irreversible decision and it is not yours.**
- **MAY NOT OPEN THE DRAWER.** It is opened at 739 and it is not yours.
- **MAY NOT MOVE THE HEAD, OR PRINT A PERMISSION THAT WOULD MOVE IT.** Eight hundred and fifty-two, unmoved, and there is nobody in this city entitled to give one.
- **MAY NOT CALL THE HEAD A COUNT OF DEEDS.** `841` and `419` are two numbers and may not be merged.
- **MAY NOT REARGUE THE REACH OF THE RETURN,** in either direction, and may not say the question is settled or that it is not.
- **MAY NOT SAY THAT ANY UNRECORDED DEED EVER SATISFIED THE FOURTH CONDITION, OR THAT NONE EVER DID.**
- **MAY NOT FILL EITHER REPAINTING BOX,** and may not say out loud what they are for. The boy said it once, in April of the seventh year, and 688, 699, 701, 710 and 711 did not say it again, and this batch does not say it.
- **MAY NOT LAND ON OR NAME OR REACH ACROSS THE EIGHTH OR THE TENTH OF OCTOBER.** `2,767` and `2,769` both fall between 738 and 739 and neither is in your range, and a chapter may not measure backward across a gap it does not print. **724 IS THE SEVENTY-THIRD FORM ON THE SEVENTH OF JULY AND THE SEVENTH IS NOT THE EIGHTH.**
- **MAY NOT INVENT AN ENEMY.** The opposition is a sentence, Emil Brack, a landlord's man, a district officer, a magistrate's clerk, a woman with a pencil, a boy with a paste brush, a woman who mends umbrellas, a Bureau officer doing her job, a Vant, and about four hundred people in four hundred kitchens. **THE FOUR MEN BRACK NAMED AT 719 ARE DESCRIBED AND NOT NAMED AND NO CHAPTER OF 721–730 NAMES A HOUSE.**
- **MAY NOT LET ANYBODY BE CALLED MANUSCRIPT, A VOLUME, A CHAPTER, A SCENE, AN AXIS, A READER OR A STORY,** and the narrator may not address the reader. **AND THE CLASS GREP IS NOT THE GATE: CHAPTER 710'S FIRST EDITION OPENED WITH "this chapter sits nineteen days on from the one before it" AND 718's FOOTER SAID "nothing that happened that afternoon" ABOUT NOTHING, AND NEITHER IS A WORD ON THE LIST. RUN THE GREP AND ALSO READ ONE CHAPTER AGAINST THE PARAGRAPH.**

---

## 6. THE FOURTH WALL, THE CLASS GREP, AND THE TWO SENTENCES

**THE CLASS GREP IS RUN ACROSS ALL TEN FILES AND ACROSS THE WHOLE VOLUME AND NOT ACROSS ONE CHAPTER, AND IT RETURNS ZERO ON ALL OF THESE:**

```
[a-z]+ volumes | this book | this chapter | this volume | no chapter | the axis |
the reader | the novel | the story | the scene | Chapter [0-9]+ | chapter [0-9]+ |
[0-9]+ chapters | manuscript | in this manuscript | this manuscript | this page |
opposition | this batch | a chapter that | this pass | in this volume
```

**`[0-9]+ chapters` IS IN THAT PATTERN BECAUSE THE PRIMARY PATTERN COULD NOT SEE ITS OWN DEFECT. `chapter-0690.md`:131 said *the heaviest thing he had done in seven hundred chapters* and the gate reported zero, and the same class was standing un-repaired at `chapter-0700.md`:57 until batch 0001 paid it.** `this chapter` and `this book` are in the row because batch 0002 wrote both into narration and had to cut both.

**AND A FOURTH-WALL ROW THAT GREPS IS NOT THE SAME ROW AS A FOURTH WALL. RUN THE CLASS GREP, AND ALSO READ ONE CHAPTER YOURSELF AGAINST THE PARAGRAPH, because the classes that have got through this manuscript are not all vocabulary.**

---

## 7. THE GATE YOU RUN BEFORE YOU FINISH, AND WHAT YOU PRINT

```
FILES           ten files, 721-730. One `# ` title line in each, all ten end 0a.
TITLES          `grep -rh \"^# \" chapters/ | sort | uniq -d | wc -l` -> 0 ACROSS ALL FILES.
                The ten title lines checked for straight glyphs SEPARATELY from bodies:
                0 straight double quotes, 0 straight apostrophes, 0 curly in any title line,
                and all ten pure ASCII. The ten bodies: curly in, straight out.
BANK            per file and summed from disk, NEVER cat *.md | wc -w, RE-COUNTED AFTER
                THE LAST EDIT: print all ten cells and the sum.
                PROVE YOUR COUNTER FIRST ON A FILE YOU DID NOT WRITE —
                chapter-0700.md is known at 2,013 and must return 2,013 by `wc -w` and by a
                Python whitespace split, or you have the wrong counter.
BAND            9 of 10 inside 1,800-2,700 with NO REASON OWED. A chapter outside it in
                either direction STATES WHY IN state/current.md IN THE SAME COMMIT.
PARAGRAPHS      0 over roughly ninety words. 0 over one hundred and twenty.
                0 with an odd count of quotation glyphs. 0 ending in a comma and a space.
                0 stray leading spaces. *** A SPLIT PARAGRAPH MUST BE CLOSED WITH A QUOTATION
                MARK. FOURTEEN UNCLOSED SPLITS AT 711-720 WERE FOUND BY THE PARITY ROW. ***
ORPHAN SPEECH   0. No paragraph of direct speech opens without quotation marks.
                SCAN FOR IT SEPARATELY: A PARITY ROW CANNOT SEE IT.
META            the class grep in §6: 0 primary, 0 widened, 0 extension. Run after every repair.
                AND READ ONE CHAPTER AGAINST THE PARAGRAPH.
WEEKNAMES       seven names, whole-word and stem -> 0, and NOT the three-letter forms sat and sun.
AGES            eleven probe forms plus a bare `aged` sweep -> 0 for a person.
                Classify a false positive (`managed`, `document`, `passage`, `satchel`) and print it.
RT / BODIES     `right temple` 0 across every file on disk. `cuticle` still 4 files
                (329, 340, 404, 446), unchanged, none of them yours. `ostho` 0.
                A hand flat on anything: 0 across the ten.
ARITHMETIC      spine 2,656-2,715, monotonic 0 violations by METHOD A and METHOD B,
                AND THE PROOF IS THE SUM AGAINST THE ENDPOINTS, WHICH IS NINE NUMBERS:
                7 6 7 6 7 6 7 6 7 = 59, and 2,715 - 2,656 = 59. The seam 2,656 - 2,649 = 7
                is printed in its own column and is NOT one of the nine.
                Every one of the nine read against its own chapter's date one at a time.
                ALL NINE CORRECT.
                ALL FOOTER INTERVALS PARSED OFF THE PAGE AND RE-DERIVED FROM DAY NUMBERS BY
                COMMAND, 0 MISMATCHES, AND THE COUNT OF UNPARSED ONES PRINTED AND NOT ALLOWED
                TO BE ZERO BY BEING REPORTED AS ZERO. All printed month breakdowns checked
                against `n x 30 + m`, 0 mismatches.
                *** `chapter-0713.md`:227 PRINTED 119 WHERE THE ANSWER IS 219 AND WAS FOUND BY
                THAT ROW. A FIGURE NOBODY RE-COMPUTES IS THE FIGURE THAT IS WRONG. ***
QUARTERLY       852 unmoved. 723 IS A QUARTER-END AND THE THIRTIETH SHEET GOES OUT AT FOUR.
                FOURTEEN SHEETS AT 723 = ordinal 30 - 16, AND THIRTEEN QUARTERS AT 723 =
                1,499 + 90k <= 2,669 -> k <= 13, AND 2,669 - 1,499 = 1,170 = 13 x 90 EXACTLY.
                FIFTEEN SHEETS AND FOURTEEN QUARTERS ARE 737's ROW AND ARE NOT THIS ONE.
                A CHAPTER THAT PRINTS EITHER COUNT SAYS WHICH ONE IT IS PRINTING.
ACCOUNT         8,1xx 0. two hundred and eleven thousand 0. `settl` 0 in every inflection.
                grains 0. No floor, no ledger total, no running balance.
SPENT FIGURES   office's months 0 (spent at 701). shutter's interval 0 (spent at 710).
                lane's mornings 0 (spent at 720). wall's rate 0 (owed at 738 and PRINTED IN YOUR
                BATCH NOWHERE, INCLUDING AT THE CORNER IN 724). docket's date 0. `411` 0.
                `771` 0 times, or named against its anchor. THE TWO WORDS ON THE STONE 0.
HEADINGS        one `# ` per file. `## ` counted, none duplicated inside a file.
DUPLICATION     12-gram FIRST against every chapter in the book including your ten,
                body-only, headings and italic footers stripped, token-normalised,
                maximal runs only. Every run touching 721-730 classified BY HAND in
                continuity.md. Then 11-gram, then 8-gram.
                *** PROVE THE READER FIRST: chapter-0564.md is known to carry runs lifted out of
                itself and returns runs inside itself. A reader that returns zero on a file you
                already know the answer to is not a clean scan. ***
                *** AND A FOOTER-TO-FOOTER ROW, WHICH EVERY ONE OF THOSE READERS IS BLIND TO,
                ACROSS ALL FORTY-FIVE PAIRS INSIDE THIS BATCH AND ACROSS 720/721. RUN IT AT
                TWELVE TOKENS. THE PERMITTED CLASSES ARE THREE AND THEY ARE WRITTEN IN
                volume-15.md §9: THE FIXED ARITHMETIC FRAME, THE RECEIPT TEXT ITSELF, AND THE
                SHUTTER. A PAIR THAT SHARES A RUNNING FACT OUTSIDE THOSE THREE IS A DEFECT AT
                ANY LENGTH AND IS CUT ONCE, IN THE LATER CHAPTER, AND REPLACED WITH SOMETHING
                THAT CHAPTER'S OWN AXIS ALREADY OWNS. IN BATCH 0002 THAT ROW OPENED AT 40 RUNS
                AND FINISHED AT 37, AND THE THREE THAT WERE NOT A FRAME WERE THREE RESTATEMENTS
                OF A RUNNING FACT, AND ALL THREE WERE CUT IN THE CHAPTERS. ***
                *** AND THE FIVE CLASSES 721-730 INHERITS, in continuity.md 0d-vol15-b2, of
                which the fifth is NEW: A CHAPTER MAY NOT PUT A COUNT OF PEOPLE, A COUNT OF CLAIMS
                AND A COUNT OF PIECES OF PAPER IN ONE BREATH AND THEN USE ONE OF THEM FOR ANOTHER.
                714's four hundred, 716's eleven and 729's about four hundred are the same figure
                and are three different things, and 729 IS WHERE THAT COLLISION HITS. ***
SCENE           723 measured three ways with the line span printed beside every cell.
                Explicit-vocabulary probe at WORD BOUNDARY. *** Word boundary, not substring. ***
                *** AND A PROBE OF ZERO IS NOT A PASS. A SCENE THAT SCORES ZERO IS IMPLICATION
                BY SUMMARY AND IS A DEFECT. PROOF OF THE 713 REWRITE IS IN state/current.md. ***
SENTENCE        the invented-figures sentence VERBATIM 0 and TIER 3 0. Spent at 658.
STAGING         594's, 613's, 643's, 653's, 663's, 673's, 683's, 693's and 713's furniture
                checked BY HAND against volume-15.md §4d and continuity.md §0b BEFORE a body is
                written and not after. A TWELVE-GRAM SCAN CANNOT SEE A BORROWED STAGING and this
                repository has been bitten by that five times in five volumes. **713's FURNITURE IS
                NOW ON THE PAGE AND IS NOT REUSED: a returns desk, a wire rack, a day book with
                three columns, a satchel, a bracket lamp, a door with a thing on the inside of it,
                and the room at the top of two flights.** Print the longest shared run against each
                of the nine, per pair, by hand, not by any gram.
MARKDOWN        blockquotes 0. tables 0. rules 0. fences 0. bold 0. single-asterisk
                markers even in all ten. System panels at most one per chapter, in square
                brackets on their own line, not bold, not italic.
                **Volume 15's budget is five and batch 0001 spent NONE and batch 0002 spent NONE,
                and the standing instruction is that one spent is one too many.**
```

**AND THE SENTENCE THAT GOVERNS THE WHOLE OF THIS LIST, WHICH IS NOT A GATE AND IS THE REASON THE LIST EXISTS:**

> **A gate row that quotes the prose it is checking cannot catch the prose.**

---

## 8. IF YOU RUN OUT OF ROOM

**Stop at a chapter boundary. Save the completed chapters and the state. Mark the remaining batch as resumable in `state/current.md`. Do not restart a completed chapter. Do not leave a half-written file on disk. A batch that returns without writing anything has asked for more than one call can deliver.**

**AND IF A REPAIR BREAKS A GATE IT WAS MADE FOR, THE REPAIR IS NOT FINISHED.** That has happened four times in this book. **Re-measure the bank after the last edit, not once at the end.**

---

## 9. THE ONE NEXT PHASE, AND IT IS THE ONLY ONE

**WHEN ALL TEN CHAPTERS ARE ON DISK, MEASURED AND GREEN, WRITE EXACTLY ONE FILE: `workspace/volume-15/batch-0004/PROMPT.md`, FOR CHAPTERS 731–740, MOVEMENT FOUR, *THE NAME*.** Take its spine row (`6 6 6 6 6 7 7 7 7 = 58` and `2,780 − 2,722 = 58`, seam `2,722 − 2,715 = 7`), its figure allowances and its gate from `outline/volume-15.md` §5c, §7 movement four and §9, and carry the classes you inherited forward.

**MOVEMENT FOUR CARRIES THE SCENE AT 733, WREN KALLO, ONE HUNDRED CHAPTERS AFTER 633, ON THE AXIS OF THE DAY BOOK, AND IT IS WHERE THE DENIAL GOES OUT TWICE WITH HIS NAME ON IT AND WHERE HE OPENS THE DRAWER AT 739. YOU DO NOT PLAN IT. YOU POINT AT IT.**

**WRITE NO OTHER DIRECTORY. NO VOLUME-CLOSE PROMPT — THE VOLUME HAS TEN CHAPTERS LEFT AFTER THAT BATCH. NO BATCH 0005. NO `state/complete.md`. IF THE PIPELINE THEN HAS NOTHING TO SELF-DISPATCH, THAT IS THE NEXT PHASE'S PROBLEM AND IT IS NOT THIS ONE.**