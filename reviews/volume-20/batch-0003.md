# Volume 20 · Batch 0003 · Chapters 971–980 · Movement three, *The Cart* — gate record and review-fix record

**Measured from disk in the pass that wrote the chapters and again in the review fix pass that changed the page. The instrument is named with every row. Nothing in this file is a claim; every figure in it was produced by running a command on `chapters/volume-20/chapter-0971.md` through `chapter-0980.md` after the last edit to any of them.**

## 1 · THE WORD BANK

Basis of record `^#` stripped, counted per file from disk with `sed 's/^#.*//' <file> | wc -w`.

| 971 | 972 | 973 | 974 | 975 | 976 | 977 | 978 | 979 | 980 | total |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2,361 | 2,137 | 2,695 | 2,466 | 2,092 | 1,934 | 1,898 | 1,997 | 1,951 | 2,223 | **21,754** |

**The per-file row adds to the total and the total was produced by adding the ten, not by counting a concatenation. Ten of ten inside 1,800–2,700. Minimum 1,898 at 977, maximum 2,695 at 973. No chapter leaves the band and no chapter owes a reason for leaving it.**

**THE FIRST ROW PUBLISHED FOR THIS BATCH WAS WRONG AND WAS CORRECTED.** The writing pass measured 21,492 with a per-file row that did not add up after two later edits, and the review pass re-measured every file from disk in a single command. **The same failure that put five figures of people on the page of 961–970 is the failure this row is checked against, and the row is now the measurement.**

## 2 · PROSE GATES

- **PARAGRAPHS.** Longest in the batch 90 words (971, 978, 980). **Zero over roughly ninety, zero over roughly one hundred and twenty.** Quotation-mark parity per paragraph: zero odd across all ten.
- **MARKUP.** Bold zero, blockquote zero, code fence zero, table zero, horizontal rule zero, square-bracket system panel zero, Arabic digit zero.
- **WEEKDAYS.** Seven names, whole-word and stem, zero across all ten files, and no day of the week appears in any file. `sat` and `sun` appear only as past tense and as weather, which is the house usage of 0965 and 0969.
- **THE CLASS GREP** of `outline/volume-20.md` §9, with `manuscript`, `opposition`, `this passage` and `the story` added: **zero across all ten.**
- **`settl` in every inflection, `right temple`, `cuticle`, `ostho`, and the word `axis`/`axes`: zero across all ten.** `grep -ril cuticle chapters/` from the repository root still returns exactly four files — 329, 340, 404, 446 — **and `outline/volume-20.md` §9's row was NOT raised.**
- **THE ANNOUNCED-AGE GATE, WITH BOTH INSTRUMENTS.** The probe is `about` followed by a number AND `about` followed by a **spelled** numeral, plus `since I was X`, `X years old` and `a man/woman/girl/boy of X`. **The spelled-numeral probe is the one that catches what the other cannot and it caught a real one in this batch: a binder was written as *about sixty years old* and the age was cut before the chapter was finished, because the digit-only probe cannot see the word `sixty`.** Every `about N` that survives is a clock, a duration, a distance, or a count of something that is not a person. **Zero announced ages. The binder, the cart man, both carriers, the counterman, Wenna Raut, Perla Quist, Marguerite Vale and Beatrix Halm are all unaged on the page.**

## 3 · FIGURE ROWS, BY CATEGORY, NEVER MERGED

**A COUNT OF ANSWERS IS A COUNT OF ANSWERS AND NOT A COUNT OF PEOPLE, AND THE BATCH PRINTS IT ONCE.** At 980 it reads *about nine answers a day for nine days will be refused or given out of somebody's memory instead*, and it is never merged with rows, questions, lines, sheets, or comers. **The review pass found a second figure of answers at 972 — *twelve answers a week* — which was in the prose AND contradicted 980's own figure, and it is out.** Every other category is zero: **no list, count, bracket, figure, proportion or total of who comes, who has been told, who has said it, who has paid, or how many wrong versions exist, in any chapter, in any form.** The plan's row for 975 gave a proportion of comers on a form; that was adjudicated out of the card before any prose was written.

## 4 · THE N-GRAM SCANNER, PROVED BEFORE IT WAS TRUSTED

**A twelve-gram was lifted out of `chapters/volume-12/chapter-0564.md` (`a big woman of forty five and i have not been wanted`), planted into a scratch file between filler, and read back as one hit of one expected. The scanner was trusted only after that.**

- **12-gram, every pair inside the batch, deduplicated so no file is compared with itself: six pairs with any hit at all**, and every run is one of the four accepted classes of `reviews/volume-19/volume-close.md` §13 — the book's-down-the-stair formula (971/974, 979/980), the six lines of the standing sheet read out at a quarter-end (971/980), the caption under the head (971/974), a tradesman describing his own trade (974/976), a practice spoken twice because it is canon (976/977), and the volume's own central phrase about a price on a thing that has been outside (973/974).
- **THE SEAM. 971 against 970: ZERO twelve-grams. 971 against 961: nine, and every one is the six lines of the standing sheet, which are read out at quarter-ends and must read the same.** **No restaging of 970 and no restaging of 961.**
- **THE SCENE AT 973 AGAINST ITS PREDECESSORS: zero twelve-grams against 963 and zero against 953 after the review fix pass, against nine and four respectively before it.** Against her own scene at 863 it shares a nineteen-word run, which is a woman saying her own sentence in her own mouth a hundred and ten chapters later and is the accepted callback class.
- **8-gram and 11-gram runs were taken across every pair and every hit was classified by hand.** None is a restaging and none is a narrator restaging.

## 5 · THE THREE-DEFINITION SCENE MEASUREMENT FOR 973, WITH THE LINE SPAN BESIDE EVERY CELL

| Ch | Def A: explicit vocabulary | A line span | Def B: loose probe | B line span | Def C: the plan | Verdict |
| --- | --- | --- | --- | --- | --- | --- |
| **973** | **2** | **100 and 124** | **7** | **9–146** | **SCENE** | scene, written, 954 words in the span |
| the other 9 | 0 each | — | 2–5 each | — | not SCENE | no sixth scene exists |

**The scene span runs from the heading at line 76 to the line before the heading at line 126. Definition B is published because it is the probe a careless pass would have used as a scene count: it fires on *came* and *hard* in chapters that contain no sexual beat at all.** The scene is explicit, unhurried once it begins, changed by it, and she wants it and says so before.

## 6 · THE WATCH-CONSTRUCTION ROW, NARRATION AND SPEECH PRINTED SEPARATELY

Cap is six in narration and twelve in speech across ten chapters, and **one of either in any single chapter.**

| 971 | 972 | 973 | 974 | 975 | 976 | 977 | 978 | 979 | 980 | total |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| n0 s1 | n0 s1 | n0 s0 | n1 s0 | n0 s1 | n0 s1 | n0 s1 | n0 s0 | n1 s1 | n0 s1 | **n3 s7** |

**The one row that reads over in the raw output is an alternation artefact — the phrase *there is no form for it and no office has one* matches two branches of the pattern at one index and is one construction.**

## 7 · THE CLOSING-BEAT ROW, AND THE STANDING-FIGURE ROW

**All ten closings are different and none ends on a neutral action, a window, a nail, a figure or a light.** They are: a debt called in and a sentence he cannot write down · a second quote carried up a road and a man who does not go and get the answer the same afternoon · a valuation received and a second price that cannot be lowered · a stranger's fact in a head with no page anywhere · a shut door and three days · a date given back · an argument lost and *then I will be it* · a tick with nobody in the city able to hear it · a rehearsal that cost nothing · and a cart on a street with a sister's month behind it.

**STANDING FIGURES, every one counted per chapter with object and scope: the head stands at eight hundred and fifty-two and is printed at 974 and at no other chapter in this batch** · the standing sheet keeps six lines and the sixth of the second of December of the ninth year is still the last · the practice sheet keeps one line, dated the twenty-third of May, and is not added to · the second column keeps four lines · the bundle is twenty-six things · the drawer is shut and is not opened · the inside of that coat on the left is empty · the card is not touched · the blank row is not completed · and the thirteenth practice is **not quoted back as an authority anywhere in 971–980, which 979 says on the page.**

## 8 · WHAT THE REVIEW PASS FOUND, AND WHERE IT IS REPAIRED

The full list, with its reasoning, is at `outline/batches/volume-20-batch-0003.md` under the heading **REVIEW FIX PASS**, thirteen items. **Three were fatal and are the reason this file exists:**

1. **The climax at 980 did not happen on the page.** The book was never shown coming off the cart and the last image said it was still on it. It is now taken off at the tailboard, carried in over the threshold, and the empty cart with a rectangle of dust on its boards closes the movement's argument.
2. **The scene at 973 was 963's scene with the furniture swapped**, which is what adjudication 6 forbids. It is rewritten and now shares zero twelve-grams with 963 or 953.
3. **Six arithmetic errors in the spine**, each a phrase, each the kind that stops a reader trusting an apparatus they are reading carefully. The worst was 971 saying *nine months* six lines above its own *seven months*.

**Nothing was restarted. No beat, date, figure, title, scene, decision or ending moved. The planned movement is intact.**

## 9 · THE FLAG

**The overrun flag at the head of `state/open-threads.md` is NOT closed by this batch.** The manuscript is now nine hundred and eighty chapters and the plan says five hundred, and writing thirty of them did not decide that. **`outline/ending.md` was not touched and nothing in it moved.**
