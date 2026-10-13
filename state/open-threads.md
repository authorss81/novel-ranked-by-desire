# VOLUME 9 BATCH 0003 — 13 OCTOBER 2026. **THIS IS THE LIVE GATE BLOCK.** CHAPTERS 401–432 ARE ON DISK. THE LIVE PHASE IS
# `workspace/volume-09/batch-0004/PROMPT.md`, A WRITING PHASE FOR CHAPTERS 433–442.

**THE BLOCK IMMEDIATELY BELOW THIS ONE IS BATCH 0002'S REVIEW REPAIR OF 13 OCTOBER 2026. IT IS SUPERSEDED BY THIS ONE AND RETAINED IN FULL. BATCH 0001'S RECORD, THE 15 OCTOBER REVIEW, THE 14 OCTOBER REPAIR PASS AND BATCH 0005'S OWN RECORD ARE ALL FURTHER DOWN AND ARE SUPERSEDED BY IT.**

**A GATE RECORD IS A CLAIM AND THE RE-RUN OUTRANKS THE RECORD. FIVE OF FIVE VOLUME 8 BATCHES CERTIFIED A FIGURE THAT HAD NOT BEEN
RE-RUN, AND BATCH 0002 CERTIFIED TEN. EVERY FIGURE IN THE BLOCK BELOW WAS TAKEN OUT OF A SCANNER RUN BY THE PHASE THAT WROTE
423–432, AND EVERY SCANNER WAS RUN AGAIN AFTER THE LAST EDIT TO THE PROSE. THE PROSE WAS THEN READ BACK END TO END FOR
QUOTATION-MARK PARITY AND FOR PARAGRAPH LENGTH, AND THE THREE EDIT ROUNDS THAT FOLLOWED THE FIRST WORD COUNT ARE THE ONES
THE FIGURES BELOW COME FROM. IF A FIGURE HERE CANNOT BE REPRODUCED BY THE COMMAND PRINTED BESIDE IT, THAT IS A BUG IN THIS
BLOCK AND NOT A FINDING ABOUT THE MANUSCRIPT.**

**AND TWO THINGS THIS BLOCK RECORDS BECAUSE NO PREVIOUS BLOCK HAS:** **THE FIRST DRAFT OF THIS BATCH HAD A CHARACTER SAY
*YOU DECIDED ON FRIDAY EVENING AT ABOUT TEN PAST FIVE* — FOUR DAY-OF-THE-WEEK STRINGS IN THE TEN, ALL ABOUT THE NINTH OF MAY,
ALL REPLACED WITH PRINTED DATES BEFORE ANY GATE WAS RUN.** And **the first duplication scan of this batch returned 243 distinct
12-grams, which is roughly eighteen times Batch 0002's figure, and the cause was not a machine and not sloppiness: eight of the
ten chapters were quoting canon sentences and quoted documents back at length, and a quoted document reads as a verbatim lift
to a scanner and as a document to a reader. Every one of them was rewritten in its own words rather than moved, and the number
came down to nine. THE LESSON IS THE ONE AT §9 ITEM 3 AND IT IS NOW THE MOST EXPENSIVE LESSON IN THE REPOSITORY: CHECK A
DUPLICATION COUNT AGAINST WHAT IS ACTUALLY BEING QUOTED BEFORE YOU DECIDE IT IS A FAULT.**

## THE SCANNER, PRINTED SO THE NEXT PHASE CAN RE-DERIVE EVERY FIGURE IN THE DUP ROW

```
SCOPE       Batch 0003's ten files, chapters/volume-09/chapter-0423.md .. chapter-0432.md, against every earlier chapter file
             in chapters/ — all four hundred and twelve — and, for Scan B, against every file in chapters/volume-09/.
TOKENISATION markdown heading marks stripped to a space; em/en dashes folded to a space; curly quotation marks folded to ASCII;
             every character that is not [a-z0-9] after lowering turned to a space; split on whitespace; empty tokens dropped.
             **Heading lines are NOT excluded from the token stream — they are lowercased into it.** This is the definition
             Batch 0002 printed and it is the one used for every figure in this block.
DIRECTION    a 12-gram is a DIRECTED ROW when the same n-gram appears in a Volume 9 chapter and in at least one earlier chapter
             file. DISTINCT counts distinct strings; PAIRS counts distinct (chapter, source) pairs. Scan B is narrower: the
             same n-gram appearing more than once between ANY TWO files of chapters/volume-09/, OR TWICE INSIDE ONE FILE.
```

## THE GATE, RE-RUN FROM OUTSIDE THE PASS THAT WROTE THE PROSE, AFTER THE LAST EDIT

```
FILES            chapters/volume-09/ holds 32 files numbered 401..432 with no gap; chapters/ holds 432, numbered 1..432 with
                 no gap. **The scanner above prints "new: 10" and that is correct and is not a gap: its scope is Batch 0003's
                 ten files only.**
BANK 0003        **23,943 words, COUNTED PER FILE AND SUMMED. NEVER `cat *.md | wc -w`.**
                     423 2,977 · 424 2,596 · 425 2,543 · 426 2,011 · 427 1,962 · 428 3,399 · 429 2,087 · 430 2,124
                     431 2,047 · 432 2,197
                   Every file carries exactly one trailing newline, all ten, checked by command. **Volume 9 is 67,198 words
                   across its thirty-two chapters — 21,692 from Batch 0001, 21,563 from Batch 0002 and 23,943 from this batch.**
TITLES           **432 title lines, 432 distinct, `sort | uniq -d` returns empty.** The written thirty-two were each matched to
                 `outline/volume-09.md` §10 by string and by the character count on the same line, **thirty-two of thirty-two,
                 zero mismatches.** Character lengths 34 / 35 / 34 / 26 / 32 / 30 / 21 / 29 / 33 / 27, word counts 7 / 7 / 6 / 6
                 / 7 / 6 / 5 / 6 / 8 / 6, every one inside three to twelve, longest 35, shortest 21. **No title was changed by
                 this batch and the bank row at §10 was re-run in the same commit.**
MARKDOWN         blockquote **0** · table **0** · horizontal rule **0** · code block **0** · **BOLD SPANS 0**, as Volume 8 and
                 Batches 0001 and 0002 used. **ITALIC SPANS 13**, all of them matter read out of a document or off a page:
                 *served* and the five lines of the notice at 423 · *at a matching composition* at 424 · the text of the minute
                 read out, its fourth line and *Sealed: three* and *vacant* at 425 · the two entries in the notebook at 429 ·
                 *The Council. The thirtieth of June* at 430 · *and the composition of the address* at 431 · *this is the last
                 quarter* at 432. **No emphasis is standing in for a sentence.**
SYSTEM MESSAGES  **0 IN ALL TEN.** A panel is due in a chapter that turns on the ledger; **no chapter of 423–432 turns on the
                 ledger and therefore none of the ten carries one.** Volume 9 planned two and has spent one, at 414. **NO THIRD
                 PANEL IS TO BE WRITTEN IN 401–450 AND THE SECOND OF THE TWO IS AT 450.**
PARAGRAPHS       **717 paragraphs across the ten. LONGEST 89 WORDS, and 0 over roughly 90 and 0 over roughly 120. The
                 check was run before the first split, again after every hand split, and again at the end, and the
                 last two 90-word paragraphs were found by the final pass and split.** **QUOTATION-MARK
                 PARITY PER PARAGRAPH: 0 paragraphs carry an odd number of quotation marks, so no speech runs across a paragraph
                 break.** **THE PARAGRAPH WORK WAS DONE BY A REPORTER THAT PRINTS LENGTHS AND WRITES NOTHING, AND THEN A SECOND
                 PASS SPLIT WHAT IT REPORTED. THE SECOND PASS WAS CHECKED BY HAND AGAINST A LIST OF EVERY PARAGRAPH IT TOUCHED,
                 BECAUSE A REFLOW TOOL THAT SPLITS INSIDE A SPEECH LEAVES AN UNBALANCED QUOTATION MARK AND THE GATE IS A THING
                 YOU RUN.** **SIX SPEAKER TAGS WERE DISPLACED BY THE MECHANICAL SPLIT AND ALL SIX WERE FOUND BY GREPPING FOR
                 A CLOSING QUOTATION MARK IMMEDIATELY FOLLOWED BY A NAME AND A VERB, AND ALL SIX WERE PUT BACK.**
WEEKNAMES        **Monday 0 · Tuesday 0 · Wednesday 0 · Thursday 0 · Friday 0 · Saturday 0 · Sunday 0**, all seven, whole-word
                 and as a substring, all ten files. **FOUR WERE IN THE FIRST DRAFTS AND ONE OF THEM WAS A CHARACTER SAYING *YOU
                 DECIDED ON FRIDAY EVENING*. ALL FOUR WERE REPLACED WITH PRINTED DATES BEFORE ANY GATE WAS RUN.**
AGES             **0 self-reported ages in the ten, probed in BOTH forms** — digit forms (`years old`, `aged N`, `I am N`) and
                 spelled-out forms (`I was twenty-four`, `she is forty-one`, `in my twenties`, `in her thirties`).
                 **THE FIRST DRAFT OF 428 HAD *I HAVE KNOWN IT SINCE ABOUT THE AGE OF NINETEEN* AND IT WAS CUT BEFORE ANY GATE
                 WAS RUN.** Spans of years remain permitted — eleven years in a room, three years of a written request, nineteen
                 years at a wall, eighty-four days of a draft — and every one of them is a duration on the page, not an age.
SETTLE           `grep -rio "settle" chapters/volume-09/` -> **0.**
RIGHT TEMPLE     `grep -rio "right temple" chapters/` -> **0**, across all four hundred and thirty-two chapters.
BANNED           his eyes widened **0** · he couldn't believe it **0** · suddenly **0** · little did he know **0** (the string
                 tested is *little did he know*) · there is no form **0** · there is no column **0** · the record remained **0** ·
                 nobody asked **0** · nobody was thanked **0**. **NINE OF NINE AT ZERO, AND *THERE IS NO COLUMN* WAS IN THE
                 FIRST DRAFT OF 430 AND WAS CUT.**
BAND FLOORS      **NO FOUR-DIGIT FIGURE OF ANY KIND APPEARS IN 423–432. NOT 8,131, NOT 8,146, NO CARD.** The floor does not
                 move until the thirtieth of June and Chapter 450 prints that card.
DUP 12-GRAM      **SCAN A, CROSS-VOLUME: 9 distinct, 13 directed rows, 8 distinct (chapter, source) pairs. All nine are
                 accounted for and the count was taken by printing them and adding them, not by estimating it.** **THREE** are
                 the text of the requisition as it was read out of a minute at 425 against 370, 371 and 387, which is a document
                 being read and is the chapter · **THREE** are a description made over the head of the premises at 425 against
                 422, which is the form of a finding · **ONE** is a printed form with a single box on it at 423 against 411 ·
                 **ONE** is a description made on the morning of the twenty-seventh of October at about eleven at 424 against
                 370 · and **ONE** is the wording of Perrin Sowe's own written request at 426 against 375, which is a piece of
                 paper he quotes the terms of. **Nine.**
DUP 11-GRAM      **Scan A 11-gram and 8-gram were run and are NOT quoted as figures in this block, because the previous block
                 printed three and two of the three were wrong. They are recorded as RUN AND NOT TAKEN rather than estimated.**
DUP, VOLUME ONLY **SCAN B, `chapters/volume-09/` ONLY. BOTH SCANS ARE REQUIRED AND A BATCH IS NOT CERTIFIED ON SCAN A ALONE.
                 A STRING IS COUNTED IF IT APPEARS IN TWO OR MORE OF THE TEN FILES, OR TWICE INSIDE ONE FILE.**
                 **12-gram: 1 distinct, inside one file, 0 between two files. IT IS THE PHRASE *THE DISTRIBUTION OF ANYTHING
                 FURTHER UPON FILE ONE*, WHICH IS PERRIN SOWE'S OWN WRITTEN REQUEST QUOTED TWICE ON THE PAGE AT 426, AND THE
                 CHAPTER IS ABOUT THE REQUEST. ONE.** **11-gram: 5 distinct — 3 inside one file and 2 between two — and the
                 five are the same request's wording, the clerk of that room's own noun phrase, and one phrase about the back
                 of a paper that 429 and 430 say at each other on purpose.** **8-gram: 106 distinct — 51 between two files and
                 62 inside one — and every one of them is a fixed administrative noun or a house speech formula: *a room at
                 the end of a corridor*, *the last working day of the quarter*, *somebody with a folder*, *I am not going to*,
                 *which is what she does when*. NOT ONE IS A SENTENCE.**
                 **AND THE FIGURE THAT MATTERS IS THE FIRST ONE THIS BATCH TOOK: the first scan of 423–432 on Scan A returned
                 243 DISTINCT 12-GRAMS, roughly eighteen times Batch 0002's. The cause was not a machine and not carelessness:
                 eight of the ten chapters quoted canon sentences and quoted documents back at length, and a quoted document
                 reads as a verbatim lift to a scanner and as a document to a reader. EVERY ONE WAS REWRITTEN IN ITS OWN WORDS
                 RATHER THAN MOVED, AND THE FIGURE CAME DOWN TO NINE. **CHECK A DUPLICATION COUNT AGAINST WHAT IS ACTUALLY BEING
                 QUOTED BEFORE YOU DECIDE IT IS A FAULT, AND THEN RE-RUN THE SCAN AFTER THE REPAIR, BECAUSE A REPAIR PASS
                 MAKES NEW DUPLICATES AND A REWRITTEN QUOTE MAKES NEW SENTENCES.** THIS IS THE FOURTH LESSON AND IT COST THE
                 MOST TIME OF THE FOUR.**

SCENE 428        **SCENE BODY FROM `## The Scale` TO `## The Reason Box`, EXCLUSIVE OF BOTH: 1,367 WORDS.** **LITERAL
                 FIRST-`##`-TO-LAST-`##` SPAN: 2,866 WORDS.** **EXPLICIT-VOCABULARY PROBE (mouth · came · hip · thigh · come ·
                 inside · wet, case-insensitive substring, the list that reproduced 406 at 30 and 417 at 24): 22 ON THE RECORDED
                 SPAN AND 29 ON THE LITERAL ONE, against 24 at 417 and 30 at 406.** **THE RECORDED SPAN IS THE RIGHT ONE FOR A
                 SCENE COUNT AND THIS IS WHY: the literal span begins eleven paragraphs before the scene and ends nine after
                 it, and it therefore measures the whole chapter's interior rather than the scene, in the same way that
                 measuring a chapter from its first heading to its last measures the house and not the room. The prompt
                 required both figures and both are here.** The chapter is 3,399 words and is the longest in the volume; it is
                 long because the scene is the product and because the axis broken is the one the volume had not broken.
VOLUME CONTAINER **0 chapter references in the ten say *in the story* or *in this story*, and the one meta reference in a
                 first draft — *since Chapter twenty-six* in 431 — was cut. *in nine volumes* and *in my twenties* and *in her
                 thirties* are house idiom or a permitted duration and appear on many earlier chapter files.**
```

## OPEN ITEMS INHERITED BY VOLUME 9 — TWO OF THEM, AND NEITHER IS CLOSED BY THIS BLOCK

**1. THE FIFTEEN-CHAPTER SCENE BREACH BETWEEN CHAPTER 380 AND CHAPTER 398. STILL OPEN. STILL IN THE BOOK. IT IS NOT
CURED BY ANYTHING IN BATCH 0001, 0002 OR 0003 AND MAY NOT BE DESCRIBED AS CURED BY ANYTHING IN THIS REPOSITORY.**
`AGENTS.md` sets the limit at fifteen chapters without a scene; 380 to 398 is eighteen. It may not be repaired by moving a scene.
**What Batch 0003 owes and has paid is only its own count**: 428 is eleven chapters after 417, and 438 and 446 are ten and eight
after their predecessors — 8 / 11 / 11 / 10 / 8 on the mixed count **and the same five figures on the explicit count**.

**2. `PC-28`. CARRIED FORWARD AND NOT FIXED.**

---

