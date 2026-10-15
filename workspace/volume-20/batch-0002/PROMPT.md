# VOLUME 20 · BATCH 0002 · CHAPTERS 961–970 · WRITING PHASE

**A WRITING PHASE. YOU WRITE TEN FINISHED CHAPTERS AND NO PROSE THAT IS NOT ONE OF THEM. YOU DO NOT PLAN A VOLUME. YOU DO NOT REOPEN ANY CHAPTER OF 901–960 AND YOU DO NOT TOUCH `outline/ending.md`, `outline/series.md` OR `NOVEL_SPEC.md`. THERE IS NO CHAPTER 971 IN THIS BATCH. MOVEMENT TWO IS *THE STAIR*, 961–970, IT OPENS VOLUME 20'S SECOND MOVEMENT ON THE THIRTIETH OF MARCH OF YEAR THIRTEEN AND CLOSES ON THE THIRD OF JUNE, AND **THE CARDS OF RECORD FOR THIS BATCH ARE ALREADY ON DISK, AT `outline/batches/volume-20-batch-0002.md`, IN FULL, WRITTEN AGAINST THE REPAIRED PAGE OF 901–950 AND AGAINST THE PAGE OF 951–960 AS BATCH 0001 ACTUALLY WROTE IT, AND MOVEMENT TWO'S ONE-LINE TABLE IN `outline/volume-20.md` §7 HAS ALREADY BEEN REPLACED IN PLACE BY WHAT THOSE CARDS PUT ON THE PAGE. YOU DO NOT PLAN THIS BATCH. YOU WRITE THE CHAPTERS THE CARDS DESCRIBE, AND WHEN A CHAPTER LANDS DIFFERENTLY FROM ITS CARD YOU FIX THE CARD IN PLACE IN THE SAME COMMIT — THE RULE IS ONE WAY AND A CARD THAT LICENSES SOMETHING THE PAGE FORBIDS IS WRONG.**

## 0 · THE HOUSE RULE THIS BATCH RUNS UNDER

**EVERY MOVEMENT OF VOLUME 20 CARRIES ITS OWN TEN CARDS, WRITTEN BEFORE ANY PROSE OF IT AND WRITTEN AGAINST THE PAGE OF THE CHAPTERS BEFORE IT.** Movements one and two have theirs. **When you write 971–980 you must write `outline/batches/volume-20-batch-0003.md` first and replace movement three's one-line table in `outline/volume-20.md` §7 in the same commit as the chapters — and that table contains one row no chapter can execute, which is 992's *the office is shut on Fridays*, because §5a forbids a day of the week in any chapter of this volume. The flag is at `state/open-threads.md` §8c. The shape that works is the one 952 actually used: a true thing about the light welded onto the three lines, said by a man being kind, which nobody said and nobody can un-say.**

**AND NOTE WHAT THE PAGE 951–960 LOOKS LIKE NOW, BECAUSE YOUR OPENING STATE IS THAT PAGE AND NOT A PLAN.** A fourth true clause about the light is travelling in one sentence with the three lines and cannot be traced. A man in a street says his price before he names the door, walks the stair himself once more before he takes anybody, has never been up those four flights to that door, and has not lied to anybody. **He is a market and he is right and no chapter of this volume may write him as a villain.** Sanna Ruhl works a floor at the end of a market; Ilva Tern stands at a stop where the service has stopped calling; neither is Nadia Ferrous; neither is aged; neither is on a roll. The counterman, paid nothing, has said out loud that the ground was dug by the man who gave it away for nine years and that he would go on doing it. **The fifth `cuticle` was NOT printed at 953, `grep -rio cuticle chapters/` still returns exactly four files — 329, 340, 404 and 446 — and `outline/volume-20.md` §9's row still reads four. Do not print it and do not raise it. If you print it, you raise the row in the same commit, measured from disk, and no character may call it the last.**

## 1 · WHAT YOU READ, IN ORDER

1. `AGENTS.md`. 2. `outline/ending.md`, in full, and then do not touch it. 3. `outline/volume-20.md` **entirely** — §1 the sentence and the seven things this volume is not · §2 the beginning state · §3 the places · §4 the scene schedule, the five axes and the table of marks · §5 the calendar, the spine, the fence, the rail row and the three crossing forms · §6 the engine · §7 movement two, whose table is now the cards · §8 the register you may not open · §9 the mechanical checks · §10 the title bank. 4. `outline/batches/volume-20-batch-0002.md`, all ten cards, in full. 5. `reviews/volume-19/volume-close.md`, §6 to §9 and §14. 6. `reviews/volume-20/batch-0001.md`, which is the gate record for the page you come from. 7. `state/current.md` in full; **its live head block is the Volume 20 batch 0001 block and that block is the whole of what you inherit.** 8. `state/continuity.md` in full, **§0a in particular, which is what 951–960 added to canon.** 9. `state/open-threads.md` in full, **§7a and §8c in particular.** 10. Previous 20 chapters for voice: **941–960, with `chapter-0960.md`, `chapter-0959.md` and `chapter-0953.md` read twice, because 960 is the chapter you come from, 959 is the one that relocates the blame, and 953 is the last scene in the book.** 11. `state/chapter-summaries.md`, the ten rows for 951–960. 12. `outline/volume-19.md` §8 and §9 for the inherited must-nots and the inherited mechanical rows.

**NEITHER 960's DECISION MAY BE RESTAGED NOR 970's MAY BE PRE-EMPTED.** **960 OWNS** a man standing at the foot of his own stair from a quarter to ten to half past five on working mornings, five days in seven, out of his three days off, with the price named out loud with the door open before it was done once, and the thing he has also decided and not entered anywhere, which is that he will not be the only one. **The card is not taken down, not re-nailed, adds no name, no fourth line, no hour about a turn of a year, and is not copied or transcribed in any chapter of this batch.** **940's rule is inherited whole: no list, count, bracket, figure or total of who comes, in any chapter, in any form, and restoring one needs a second decision taken out loud in that room with the door open.** **943 owns the hall and the winter light and 953 owns the records room and the echo, and 933's platform is a different platform from 963's.**

## 2 · THE SPINE (derive twice, print operands in italic footers)

A month is thirty days, no thirty-first, no day of the week. A year runs first of February to thirtieth of January; a January is labelled by the February that follows it. **THE DAY NUMBER IS THE AUTHORITY AND THE YEAR LABEL IS NOT: `outline/volume-19.md` §5a prints its own opening as year twelve at a day number whose formula year is eleven, that slip is inherited and is deliberately not corrected, and every interval in this batch is derived from the day column below.**

```
METHOD A: 1 Feb y = (y-1) x 360; day d = (y-1) x 360 + off[m] + (d-1)
          off Oct 240 Nov 270 Dec 300, February at 0, and a January at 330
          *** AND A JANUARY IS NOT (y-1). A JANUARY IS (y-2) x 360 + 330 + (d-1). ***
METHOD B: day = 30*i + (d-1), i = (y-1)*12 + pos[m] ZERO INDEXED. NO 360.
          pos Feb 0 ... Dec 10, AND pos Jan = 11, BECAUSE A JANUARY IS THE
          TWELFTH MONTH OF THE YEAR THAT BEGAN IN FEBRUARY.
          *** AND A JANUARY'S i IS (y-2)*12 + 11. A JANUARY LABELLED y IS THE LAST
          MONTH OF THE YEAR THAT BEGAN IN FEBRUARY OF y-1, SO IT BELONGS TO THE
          YEAR BEFORE THE ONE ITS LABEL NAMES. pos[m] = 11 IS RIGHT; y-1 IS NOT. ***
THE TWO METHODS SHARE NO CONSTANT AND AGREE ON ALL TEN DATES.
CHECK THEM YOURSELF, AND CHECK THE ONE DATE THEY BOTH GOT WRONG UNTIL THIS BLOCK
WAS CORRECTED ON THE FIFTEENTH OF OCTOBER 2026 BY AN INDEPENDENT REVIEW PASS:

  AS PUBLISHED UNTIL THAT PASS, BOTH METHODS GAVE 20 Jan y13 = 4,669.
  THE PAGE HAS PRINTED 4,309 EVERYWHERE SINCE 951 AND 4,309 IS CORRECT.
  UNDER THE CORRECTED RULE: A = 11 x 360 + 330 + 19 = 4,309, B = 30 x 143 + 19
  = 4,309. THE PAGE WAS RIGHT AND THE INSTRUMENT WAS WRONG. THE SPINE ITSELF IS
  COHERENT AND WAS NEVER IN DOUBT: 4,289 + 20 = 4,309 and 4,309 + 63 = 4,372.
  *** THERE IS NO JANUARY IN ANY OF THIS BATCH'S TEN DATES, SO YOU CANNOT CATCH
  THIS BY WORKING AND YOU MUST CARRY IT. IT WILL BITE THE FIRST WRITER WHO
  DERIVES ONE. ***

Batch 0002 opens 30 Mar y13: 4,379, quarter-end crossing 4,379 - 4,372 = 7.
```

**ON THE WORD *SEAM*, WHICH THIS BATCH MUST NOT USE FOR 961.** **In 951–960 *the seam* is canon and it means one thing only: the twenty days between the renewal at 4,289 and 951 at 4,309, printed in 951's own spine clause and inherited whole by `state/continuity.md` §0a.** **961 is not a renewal and its crossing is a quarter-end, so it is called the quarter-end crossing here and it is a different thing from the seam and must never be described as one.** An independent review pass on the fifteenth of October 2026 found this prompt using *the seam* for 961's seven days and that collision is now repaired.

| Ch | Day | Spine | Interval |
| --- | --- | --- | --- |
| **961** | **30 Mar y13** | 4,379 | 4,379 − 4,372 = **7**, the quarter-end crossing, alone in its own column |
| 962 | 7 Apr y13 | 4,386 | **7** |
| **963** | 14 Apr y13 | 4,393 · **SCENE, Beatrix Halm**, 80 after 883 | **7** |
| 964 | 21 Apr y13 | 4,400 | **7** |
| 965 | 28 Apr y13 | 4,407 | **7** |
| 966 | 5 May y13 | 4,414 | **7** |
| 967 | 12 May y13 | 4,421 | **7** |
| 968 | 19 May y13 | 4,428 | **7** |
| 969 | 26 May y13 | 4,435 | **7** |
| **970** | 3 Jun y13 | 4,442 · **MOVEMENT TWO'S IRREVERSIBLE DECISION** | **7** |

**THE INTERIOR NINE OF THIS BATCH ARE ALL SEVEN AND SUM TO 63, AND `4,442 − 4,379 = 63`. THE QUARTER-END CROSSING `4,379 − 4,372 = 7` STANDS ALONE IN ITS OWN COLUMN AND IS NOT ONE OF THE NINE, AND IT IS NOT THE SEAM.**

**HOW TO NAME THE PREDECESSOR'S DAY, AND WHY IT IS WRITTEN DOWN. SIXTEEN DATE GLOSSES WERE WRONG IN 921–930 AND EVERY ONE OF THEM SAID *of last month* ON A PAIR THAT STAYS INSIDE ONE MONTH. A GATE ROW THAT SAYS A THING IS CHECKED IS NOT A CHECK. DERIVE THE PREDECESSOR'S MONTH BEFORE YOU WRITE THE GLOSS, AND WRITE THE GLOSS LAST, AFTER THE ARITHMETIC.**

```
SAME MONTH as this chapter   ->  \"the <N> of this one\"      and plain subtraction:
                                 \"and <today> less <prev> is <n> by the month count\"
CROSSING INTO A NEW MONTH    ->  \"the <N> of last month\"    and the crossing named as itself:
                                 \"and thirty less <N> is <two>, and <two> with <today> taken
                                  out of the next month is seven by the month count with the
                                  crossing named as itself\"
CROSSING AT A MONTH END      ->  **961 -> 962 ONLY IN THIS BATCH**, THE THIRD FORM, WORD FOR WORD:
                                 \"the thirtieth of this one and the seventh of the next one
                                  is day <D>, and <D> less <M> is seven, and the month ended
                                  in between and there is nothing in it to take out\"
```

**IN THIS BATCH THERE ARE THREE CROSSINGS AND SIX SAME-MONTH PAIRS. 962 crosses at a month end and takes the third form. 966 crosses, twenty-eight April to the fifth of May, thirty less twenty-eight is two, and two with five taken out of the next month is seven. 970 crosses, twenty-six May to the third of June, thirty less twenty-six is four, and four with three taken out of the next month is seven. THE OTHER SIX TAKE *the N of this one*.** **THE MONTH-END THIRD FORM IS THE FOURTH FORM AND IT IS THE ONLY PLACE IT APPLIES, AND THE VOLUME OUTLINE LISTS 975 AND 988 AS ITS OTHER TWO OCCURRENCES.**

**THE RAIL, WHICH BREAKS ONCE IN THIS BATCH: 961 **90** and the forty-eighth sheet comes down at about four that afternoon, and after it the anchor is 4,379, not 4,289. 962 **7** · 963 **14** · 964 **21** · 965 **28** · 966 **35** · 967 **42** · 968 **49** · 969 **56** · 970 **63**. EVERY FIGURE FROM 962 ON IS RE-DERIVED AGAINST `4,379`, THE THIRTIETH OF MARCH, ON WHICH THE FORTY-NINTH SHEET WENT UP. **DO NOT ANCHOR ON A CHAPTER'S OWN DAY, DO NOT CARRY THE FIGURE DOWN FROM THE FOOT ABOVE, AND EVERY FOOTER NAMES ITS OWN ANCHOR IN FULL AND NOT A RELATIVE PHRASE. THE ROW BREAKS FOUR TIMES IN VOLUME 20 AND ONLY AT 961 IS ONE OF THEM IN THIS BATCH.**

**THE DRAWER, RE-DERIVED AGAINST `2,420`, THE TWENTY-FIRST OF OCTOBER OF THE SEVENTH YEAR: 961: 1,959 = 65 × 30 + 9 · 962: 1,966 = 65 × 30 + 16 · 963: 1,973 = 65 × 30 + 23 · 964: 1,980 = 66 × 30 + 0, WHICH IS THE SIXTY-SIXTH MONTH AND IS NAMED ONCE, IN ITS OWN FOOTER, AND IS NOT AN EVENT · 965: 1,987 = 66 × 30 + 7 · 966: 1,994 = 66 × 30 + 14 · 967: 2,001 = 66 × 30 + 21 · 968: 2,008 = 66 × 30 + 28 · 969: 2,015 = 67 × 30 + 5, THE SIXTY-SEVENTH MONTH, NAMED ONCE AND NOT AN EVENT · 970: 2,022 = 67 × 30 + 12. Every breakdown re-derived as months × 30 + days, with both operands printed.**

**THE HEAD, PRINTED AT 961 AND NOWHERE ELSE IN THIS BATCH.** `4,379 − 1,499 = 2,880 = 32 × 90`, **thirty-three sheets and thirty-two quarters, differing by one**, said at a counter under a window in a passage off Cordwain by the man who is paid nothing, with about nine strangers in that passage. **The head has not moved and its figure is not spoken between 961 and 974.**

**A FORM FALLS ON 962 ONLY, the seventh of April at 4,386. THE MONTH'S FORMS GO UP ON A SEVENTH AND THIS ONE IS NOT AN EVENT. NO FORM ORDINAL IS PRINTED IN ANY CHAPTER OF THIS BATCH, INCLUDING IN A SECTION HEADING AND INCLUDING IN SPEECH.**

**HIS OWN BLANK ROW, `3,082`: 1,297 days old at 961 and one thousand three hundred and sixty at 970. Derived, never printed as a figure, never completed, and never described as a thing.**

## 3 · FIGURE ALLOWANCES

**SPENT AND NOT TO BE REPRINTED ANYWHERE IN 951–1000:** the office's exact months · **the head at any day other than 961, 974, 987 and 1000** · the figure of the account · any floor, ledger total or running balance · `settl` in every inflection.

**NOT PRINTED, IN ANY FORM, ANYWHERE IN 951–1000:** the figure of the account · any floor, ledger total or running balance in grains · the docket's date · **the two words on the stone** · **what was in the space in the middle of his own row** · any age of any person · any year numeral in prose · **any day of the week, including the bare verb `sat` and the bare noun `sun` apart from the proper name Sun Meiling, who is not in this batch** · **any seventh line in the office's hand** · **any fifth line in the second column** · **any further hand in the stone — THE FIGURE IS BANNED AND THE ABSENCE IS NEVER NAMED OR COUNTED TO** · the reach of the return, argued in either direction by anybody · **the fourth condition reproved or disproved by anybody** · **HOW MANY WRONG VERSIONS OF THE THREE LINES EXIST — 950 ALREADY REFUSED A NUMBER FOR THIS AND 998 REFUSES IT AGAIN, AND NOBODY IN 961–970 MAY GIVE ONE, INCLUDING THE CLERK, INCLUDING BRACK, INCLUDING THE COUNTERMAN, INCLUDING HIM** · **HOW MANY PEOPLE HAVE BEEN TOLD THE THREE LINES, OR HAVE SAID THEM, IN ANY CHAPTER AND IN ANY FORM** · **HOW MANY PEOPLE PAID THE MAN WITH THE COIN** · **a second card, a copy of the card, or a transcript of its three lines** · **any written address for this office** · the row count with no anchor beside it · **any form ordinal** · **anything at the foot of the standing sheet in the office's hand** · **a third written refusal on paper, or the restoration of one** · who took the sheet off the rail at the foot of the hill in December, and what was on it · the two strangers who came up four flights and went down again.

**THE COUNTS THAT ARE NEVER MERGED:** rows in the book · questions · answers · people · lines on the standing sheet · sheets under a third table · **a count and a row** · **a page and a copy** · **a question about a paper and a question about a person** · **a thing a person heard and a thing that was said** · **a refusal and an answer** · **an address and a list** · **a figure and a hand** · **a price and a service** · **a thing said out loud and a thing written down** — **that last one is this volume's whole subject and merging it is the failure this batch exists to avoid.**

## 4 · THE BATCH IN TEN LINES, AND THE TITLE RULE YOU MUST APPLY YOURSELF

961 The Forty-Ninth Sheet · 962 Two Hands At A Rail · **963 A Second Late (SCENE, Beatrix Halm)** · 964 The Last Link · 965 Four Flights Alone · 966 Standing At The Bottom · 967 The Coin He Will Not Take · 968 The Cheapest Man In Cordwain · 969 A Debt Refused Aloud · **970 The Standing Given Away (THE MOVEMENT'S IRREVERSIBLE DECISION)**.

**963 IS THE SCENE AND 970 IS THE MOVEMENT'S IRREVERSIBLE DECISION AND NEITHER MAY BE SWAPPED FOR A QUIETER CHAPTER.** Note that 964 and 965 are a pair and must not be the same chapter with the word changed; if you find yourself writing one, write the other instead.

**A TITLE IS A NAME AND NOT A LABEL. `AGENTS.md` requires a title to name the chapter the way a chapter title reads in a table of contents: no weather, no clock time, no date, no ages, no dialogue, no `and then`, three to twelve words, none over ninety characters, unique across every written title line. THE LAST TWO REVIEW-FIX PASSES TOOK THREE AND SIX TITLES OUT OF TEN FOR IT: A FIGURE, A DATE, A DURATION, A SEASON, A PERIOD AND A CHAPTER'S OWN DECISION RESTATED BACK TO ITSELF ARE ALL THE SAME FAILURE, AND A QUARTER-END IS NOT EXEMPT — `The Forty-Ninth Sheet` IS HOUSE USAGE ONLY BECAUSE 911 AND 924 GOT AWAY WITH IT AND THE AUDIT DID NOT ARGUE.** **THE TEN LINES ABOVE WERE CHECKED AGAINST ALL NINE HUNDRED AND SIXTY WRITTEN TITLE LINES AND AGAINST EACH OTHER AND `uniq -d` RETURNED EMPTY ON BOTH COLUMNS. RE-RUN IT BEFORE YOU WRITE AND NOT AFTER, AND IF ONE OF THEM FAILS, REPLACE THAT ONE AND LEAVE THE OTHER NINE ALONE.**

## 5 · WHAT THIS BATCH OWES ITS WRITER, AND WHAT IT REFUSES

**THE SECOND MOVEMENT OF A VOLUME IS ABOUT WHAT A BODY CAN DO TO A PRICE, AND ABOUT A MAN WHO HAS ALREADY SPENT HIS THREE DAYS OFF LEARNING THAT THE PART HE CHOSE WAS NEVER THE PART THAT WORKED.** 961 is a quarter-end and the seventh morning at the bottom of a stair on the same day. 962 is a body that cannot be in two courts. 963 is the only signal operator on the Ferrier line and two years of a sentence going wrong at the far end of a carriage while she heard it. 964 is a woman who has paid and has been given the address true. 965 is the finding that **nothing happens** when he is not there. 966 is four feet of pavement that nobody built. 967 is the man who is paid nothing going to look at three floors of washrooms at eleven at night. 968 is a lane discovering that there is nothing to price. 969 is a woman offering the only thing anybody has offered him all year. **970 is his, on the practice sheet and not on the standing sheet, dated the twenty-third of May, and it is the only line in this book that is about somebody else's mouth.**

**What it refuses:** the head anywhere but at 961; the rail breaking anywhere but at 961; **no list, count, bracket, figure or total of who comes, who has been told, who has said it, who has paid, or how many wrong versions exist, in any chapter, in any form**; no second card and no copy of the card and no transcript; the card is not taken down and not re-nailed and gets no name and no fourth line and no hour about a turn of a year; the sooner figure is not rubbed out and the third figure is still unchalked and still owed; **no third written refusal on paper, and 969's no is spoken and entered nowhere**; no rank, band, permission, standing or shift change, **he is rank one and stays there, the branch night shift is not moved, and the mornings are not bought and not asked for**; no new enemy, **and the man with the coin is not one — he is a market, he is right, and nobody may be written as a villain in this batch**; nothing into the inside of that coat on the left; no hand put flat on anything; no burning and no stove; **no stone yard and no docket date, and NO CHAPTER GOES DOWN THAT HILL**; no announced age of any person — **SEE THE HAZARD BELOW, THIS GATE HAS BEEN PUBLISHED CLEAN WHILE BROKEN FOUR PASSES RUNNING**; no year numeral; no weekday; no restaging of 960's decision, 940's rule, 933's or 963's or 953's staging, 923's landing or 913's knock; **the woman with the short-handled broom is not named and not asked for anything, for the eleventh running volume; and the boy with the paste brush is not on the page at all.**

**THE AXIS OF 963 IS THE FAR END AND IT IS CARRIED BY AN IN-WORLD RULE, NOT BY THE WORD, AND THE WORD `AXIS` IS ZERO IN ALL TEN FILES.** **NONE OF 853's, 903's, 913's, 923's, 933's, 943's OR 953's STAGING RETURNS, AND 933'S PLATFORM AND ITS FAR-END BRICK SHELTER, ITS BENCH, ITS BOTTLE OF WATER AND ITS NINE-MINUTES-SLOW STATION CLOCK ARE 933'S AND NOT 963's.** 963 is the back platform at the end of the Ferrier line and it is a different platform from the stop where a service stopped calling.

## 6 · HOW YOU CLOSE

Every chapter 1,800–2,700 words on the basis of record (`^#` stripped), paragraphs of two to four sentences, none over roughly 90 words and none over roughly 120, quotation-mark parity per paragraph, at most one system message per chapter in square brackets on its own line and only if the scene turns on it (this batch should need none). Every chapter ends on a new question, danger, revelation, decision, reversal, emotional consequence or unanswered mystery — never on a neutral action. **963 IS THE NEXT SCENE AND IT IS TEN CHAPTERS AFTER 953, WHICH IS INSIDE THE EIGHT-TO-FIFTEEN BUDGET.**

Run the class grep with `manuscript` and `opposition` **and `this passage` and `the story`**, the weekday and age sweeps, the `settl`/`right temple`/`cuticle`/`ostho` gates, the within-file duplicate-paragraph scan, the 12/11/8-gram scans **proved on `chapters/volume-12/chapter-0564.md` before they are trusted**, the footer-to-footer row across the batch and the quarter-end crossing at 960/961, **the three-definition scene measurement for 963 with spans printed**, the explicit-vocabulary probe whole-file and scene-alone, the watch-construction row (cap six in narration and twelve in speech across ten chapters, and one of either in any single chapter), the closing-beat row against this batch's own nine and against 901–960, and the standing-figure row. **Record word counts from disk per file, never from concatenation, and make the per-file row add to the total — the last batch's row did not and that is how five figures went wrong unnoticed.**

**AND THE HAZARDS THAT ARE LIVE ON THIS PAGE RIGHT NOW.**

**FIRST: A GATE THAT GREPS FOR A WORD CANNOT CATCH A NUMBER, AND THE ANNOUNCED-AGE GATE HAS BEEN PUBLISHED CLEAN WHILE BROKEN FOUR PASSES RUNNING.** **THE INSTRUMENT IS A GREP FOR `about` FOLLOWED BY A NUMBER PLUS A HUMAN EYE ON EVERY RESULT: EVERY `about N` IN THE BATCH MUST BE A CLOCK, A DURATION, A DISTANCE OR A COUNT OF SOMETHING THAT IS NOT A PERSON.** Do not print an age. Do not print `a man of about forty` and then delete only the figure. **Check it while you write, because a gate run at the end of a pass will report what the pass chose to measure.** **Dagmar Oyelowo, Wenna Raut, Perla Quist, Isolde Marchetti, the counterman, Sanna Ruhl and Ilva Tern are not aged and may never be aged on the page, and the boy with the paste brush is not on the page at all.**

**SECOND: A STATE FILE THAT CONTRADICTS THE PAGE IS WORSE THAN A STATE FILE THAT IS SILENT.** When you publish a measurement, measure it from disk in the same pass that writes the chapter, publish the instrument, and make the per-file row add up to the total.

**THIRD: A TITLE IS A NAME.** See §4.

**FOURTH: THE THIRTEENTH PRACTICE IS A LINE ON THE PRACTICE SHEET AND NOT ON THE STANDING SHEET, DATED THE TWENTY-THIRD OF MAY, IN HIS OWN WORDS, AND THE STANDING SHEET KEEPS SIX LINES.** **The sixth line of the second of December of the ninth year is still the last, and no seventh goes in anywhere in this volume.**

**AND THE ONES THAT WERE ALREADY LIVE.** A refusal on the page must say what the office does and who does it, and not that nobody can. **A DATE SPOKEN INSIDE A CHAPTER IS ARITHMETIC AND NOT DECORATION.** **THE HOUSE CLAUSE `with the door open and both carriers in that passage` IS DOWN TO ZERO AND WAS NOT BROUGHT BACK IN VOLUME 19; DO NOT BRING IT BACK.** **A FIGURE BANNED BY THE ALLOWANCES IS NOT MERELY A WORD: PRINTING THE ABSENCE CONVERTS A SILENCE INTO A FACT THE READER CARRIES FOR THE REST OF THE BOOK, SO WRITE THE BARE FACE AND LEAVE IT BARE.**

After the batch, update the batch summary, chapter summaries, continuity, open threads and character state. Keep summaries compact. **Preserve the planned ending. `outline/ending.md` is not yours and nothing in it moves.**

**AND THEN YOU CREATE EXACTLY ONE NEXT PHASE: `workspace/volume-20/batch-0003/PROMPT.md`, CHAPTERS 971–980, MOVEMENT THREE *THE CART*. IT IS A WRITING PHASE AND NOT A CARD PHASE, BUT **BEFORE IT WRITES A LINE OF PROSE IT MUST WRITE ITS OWN CARDS** at `outline/batches/volume-20-batch-0003.md`, ten cards against the repaired page of 951–970, and replace movement three's one-line table in `outline/volume-20.md` §7 with what those cards put on the page, in the same commit as the chapters, **and that table contains the row for 992, which no chapter can execute as it stands because it names a day of the week and §5a forbids one; the flag is at `state/open-threads.md` §8c.** **973 IS THE SCENE AND IT IS MARGUERITE VALE. 974 IS THE FIRST OF THE TWO QUARTER-ENDS LEFT IN THIS HALF OF THE VOLUME AND THE HEAD IS PRINTED AT IT. 980 IS MOVEMENT THREE'S IRREVERSIBLE DECISION: THE REGISTER GOES OUT OF THE BUILDING IN A CART IN SOMEBODY ELSE'S HANDS FOR NINE DAYS, IN INK FOR THE FIRST TIME IN NINE YEARS, AND IT CANNOT BE UN-BEEN.** **YOU DO NOT WRITE THOSE CHAPTERS, YOU DO NOT PLAN MOVEMENT FOUR, AND YOU DO NOT TOUCH `outline/series.md`, `outline/ending.md` OR `NOVEL_SPEC.md`. Create that one phase, mark this one done, and stop.**