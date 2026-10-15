# Volume 20 · Batch 0003 · Chapters 971–980 · Movement three, *The Cart* — gate record and review-fix record

**Measured from disk in the pass that wrote the chapters and again in the review fix pass that changed the page. The instrument is named with every row. Nothing in this file is a claim; every figure in it was produced by running a command on `chapters/volume-20/chapter-0971.md` through `chapter-0980.md` after the last edit to any of them.**

## 1 · THE WORD BANK

Basis of record `^#` stripped, counted per file from disk with `sed 's/^#.*//' <file> | wc -w`.

| 971 | 972 | 973 | 974 | 975 | 976 | 977 | 978 | 979 | 980 | total |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2,369 | 2,137 | 2,695 | 2,493 | 2,092 | 1,934 | 1,898 | 1,997 | 1,929 | 2,204 | **21,748** |

**The per-file row adds to the total and the total was produced by adding the ten, not by counting a concatenation. Ten of ten inside 1,800–2,700. Minimum 1,898 at 977, maximum 2,695 at 973. No chapter leaves the band and no chapter owes a reason for leaving it.**

**THE FIRST ROW PUBLISHED FOR THIS BATCH WAS WRONG AND WAS CORRECTED. THE SECOND PUBLISHED ROW WAS ALSO WRONG AND WAS CORRECTED AGAIN.** The writing pass measured 21,492 with a per-file row that did not add up after two later edits, and the first review pass re-measured every file from disk in a single command and published 21,754. **A second independent review of this batch then found four repairs that changed the page, and this row was re-measured from disk for the third time and now reads 21,748.** The failures are in the instruments, not in the chapters: no chapter was edited to make a figure fit. **The same failure that put five figures of people on the page of 961–970 is the failure this row is checked against, and the row is the measurement.**

## 2 · PROSE GATES

- **PARAGRAPHS.** Longest in the batch 90 words (971, 978, 980). **Zero over roughly ninety, zero over roughly one hundred and twenty.** Quotation-mark parity per paragraph: zero odd across all ten.
- **MARKUP.** Bold zero, blockquote zero, code fence zero, table zero, horizontal rule zero, square-bracket system panel zero, Arabic digit zero.
- **WEEKDAYS.** Seven names, whole-word and stem, zero across all ten files, and no day of the week appears in any file. `sat` and `sun` appear only as past tense and as weather, which is the house usage of 0965 and 0969.
- **THE CLASS GREP** of `outline/volume-20.md` §9, with `manuscript`, `opposition`, `this passage` and `the story` added: **zero across all ten.**
- **`settl` in every inflection, `right temple`, `cuticle`, `ostho`, and the word `axis`/`axes`: zero across all ten.** `grep -ril cuticle chapters/` from the repository root still returns exactly four files — 329, 340, 404, 446 — **and `outline/volume-20.md` §9's row was NOT raised.**
- **THE ANNOUNCED-AGE GATE, WITH BOTH INSTRUMENTS AND WITH THE TWO PROBES REPORTED SEPARATELY, WHICH THEY WERE NOT.** The probe is `about` followed by a number AND `about` followed by a **spelled** numeral, plus `since I was X`, `X years old` and `a man/woman/girl/boy of X`. **The spelled-numeral probe is the one that catches what the other cannot and it caught a real one in this batch: a binder was written as *about sixty years old* and the age was cut before the chapter was finished, because the digit-only probe cannot see the word `sixty`.** Every `about N` that survives is a clock, a duration, a distance, or a count of something that is not a person. **THE `since I was X` PROBE FIRES TWICE IN THIS BATCH AND IS NOW PUBLISHED AS ITS OWN ROW INSTEAD OF BEING SWALLOWED BY THE `about N` ROW: `chapter-0972.md`:71, *I have not worked in a lamp since I was a young man*, spoken by the binder, and `chapter-0978.md`:107, *That has been going since I was in this building*, spoken by the carrier with the bad back. NEITHER IS AN AGE, NEITHER FIXES A YEAR, AND NEITHER IS AN ANNOUNCED AGE. Zero announced ages.** The binder, the cart man, both carriers, the counterman, Wenna Raut, Perla Quist, Marguerite Vale and Beatrix Halm are all unaged on the page.

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

**All ten closings are different and none ends on a neutral action, a window, a nail, a figure or a light.** They are: a debt called in and a sentence he cannot write down · a second quote carried up a road and a man who does not go and get the answer the same afternoon · a valuation received and a second price that cannot be lowered · **a nail in a room with no window taking the fifty-first of nothing, and a binder in a city with no page that says what his fact is** · a shut door and three days · a date given back · an argument lost and *then I will be it* · a tick with nobody in the city able to hear it · a rehearsal that cost nothing · **and a woman at a bare table under a lamp lit at an hour it has not been lit at in nine years, telling him he gave her the date and not the day.**

**THE FOURTH AND THE TENTH ENTRIES OF THIS ROW WERE WRONG AND WERE CORRECTED IN THE FIX PASS, AND THE REVIEW THAT FOUND THEM WAS ALSO WRONG IN ITS OWN PLACE.** The first published row described 974 as *a stranger's fact in a head with no page anywhere* and 980 as *a cart on a street with a sister's month behind it*. **Neither description was the chapter's last beat, and the reviewer's replacement for 974 was also not it**: it named Wenna Raut's *no practice in this building or this city covers a stranger hearing a thing and promising* (`chapter-0974.md`:121), which is eighteen lines above the file's last narrative line and is not a close. **The real closes are `chapter-0974.md`:139 and `chapter-0980.md`:113, and the row is now built from the last narrative line of each file and from nothing else.** 980's cart and the sister's month sit fourteen lines above its close and are a middle beat. **No chapter was moved to make an entry fit.**

**STANDING FIGURES, every one counted per chapter with object and scope, AND AFTER THE FIX PASS THAT REMOVED THE PRINTED ABSENCES: the head stands at eight hundred and fifty-two and is printed at 974 and at no other chapter in this batch, where it is now printed in the same sentence as the arithmetic, which is the two-figure house pattern of `chapters/volume-18/chapter-0900.md`:103 and `chapters/volume-18/chapter-0886.md`:105** · the practice sheet carries a line dated the twenty-third of May, in her hand and in his words, named at 980 · the bundle is on the side table at 980 · **and every other standing figure — the six office-hand lines, the second column's four lines, the shut drawer, the untouched card, the empty left side of the coat, the blank row — is now printed nowhere in the body of any of the ten chapters, because a chapter of this volume does not print a banned absence.** The thirteenth practice is **not quoted back as an authority anywhere in 971–980, which 979 says on the page.**

## 8 · WHAT THE REVIEW PASS FOUND, AND WHERE IT IS REPAIRED

The full list, with its reasoning, is at `outline/batches/volume-20-batch-0003.md` under the heading **REVIEW FIX PASS**, thirteen items. **Three were fatal and are the reason this file exists:**

1. **The climax at 980 did not happen on the page.** The book was never shown coming off the cart and the last image said it was still on it. It is now taken off at the tailboard, carried in over the threshold, and the empty cart with a rectangle of dust on its boards closes the movement's argument.
2. **The scene at 973 was 963's scene with the furniture swapped**, which is what adjudication 6 forbids. It is rewritten and now shares zero twelve-grams with 963 or 953.
3. **Six arithmetic errors in the spine**, each a phrase, each the kind that stops a reader trusting an apparatus they are reading carefully. The worst was 971 saying *nine months* six lines above its own *seven months*.

**Nothing was restarted. No beat, date, figure, title, scene, decision or ending moved. The planned movement is intact.**

## 8b · THE SECOND REVIEW, ITS SEVEN FINDINGS, AND WHERE EACH IS REPAIRED

**A second independent review of this batch ran against the ten chapters on disk and against the first fix pass. Its full transcript is `logs/batch-0003.review.log`. Seven findings, all repaired in place, none of them a change of plan, no chapter restarted, no title moved, no scene rewritten, no date, no spine figure and no ending altered.**

1. **HIGH — `chapter-0980.md`:105 CONTRADICTED THE CHAPTER'S OWN CLIMAX IMAGE THREE PARAGRAPHS AFTER IT LANDED.** The first fix pass took the book off the boards at the tailboard (`:73`) and left the empty cart and the grey rectangle as the image the movement closes on (`:77`), but this paragraph was an orphan of the pre-fix draft: it said *there was no strap on that cart to see and no daylight and no back board*, against the cart man's own *it had a strap on it like the ones the offices use* (`:97`) and against the strap coiled on the tailboard. **It is rewritten. What stands in its place is the consequence and not the scenery: she is going to go and look for that door in the morning on the strength of a thing a man said for money and had not known what was in it, he wanted to say something and said nothing, the rest of it is nine days away with a binder, and by morning it will be loose about this city without him.**
2. **HIGH — `chapter-0980.md`:83 CONTRADICTED ITSELF AND CANON.** It read *with nothing in his hands, which is not the way he comes down that stair and is the only way he came down it for nine years*, which asserts the opposite of itself, and which also contradicts `:51` of 972, where the book is carried down by one man every working evening. **It now reads *and is the only way he has ever come down it with nothing in his hands*.**
3. **HIGH — EIGHT PRINTED ABSENCES LANDED IN THE BODIES OF FIVE CHAPTERS, AGAINST THE INHERITED MAY-NOT ROW AT `state/continuity.md` §0b.** The row — *no chapter prints a banned absence: the drawer staying shut, the card not being touched, the second column keeping its lines, nothing entered at the foot of the standing sheet — write the bare face and leave it bare* — was carried into this batch, and this batch's own first fix pass had already applied it once at 980. **Eight instances at 971, 974, 977, 979 and 980 are cut and replaced with the bare face:** the pen held an inch above a practice sheet at 971; two people still over a document at 974; a drawer with a man's name under the instruction on it at 977, said by Wenna Raut and no longer *ordered shut*; the sheets simply present on the desk at 979; a practice sheet brought out and left where both of them could see it from the door at 980; the cart slip's own name, day and number of days at 980, with the standing sheet and the second column removed from the sentence entirely. **The decision this row forces is a decision, and it is this one: the may-not row governs, and a standing figure of this office is named by being on the page and is not announced by being counted.**
4. **MEDIUM — THE HEAD WAS PRINTED AT 974 WITH HALF THE TWO-FIGURE HOUSE PATTERN, WHILE THIS FILE AND `state/current.md` BOTH SAID THE STANDING FIGURE WAS ON THE PAGE.** `grep -rn 'eight hundred and fifty' chapters/volume-20/` returned **zero** while §7 here and `state/current.md` both claimed eight hundred and fifty-two was printed at 974. **The page is fixed, because the page is what the books inherit: 974 now prints the standing figure in the same breath as the subtraction, which is the pattern of `chapters/volume-18/chapter-0900.md`:103 and `chapter-0886.md`:105, and it is the same breath the prose had already set up by turning the sheet so that the figure at the head of it faced the room.** The arithmetic is untouched and still correct at `4,469 − 1,499 = 2,970 = 33 × 90`. **The same half-pattern is on the page at 961 and is a carried defect of batch 0002, which is not this batch's to reopen; it is flagged in `state/continuity.md` §0c and no figure was changed at either chapter.**
5. **MEDIUM — THIS ROW MISDESCRIBED 974 AND 980, AND THE REVIEW THAT FOUND IT WAS WRONG IN ITS OWN PLACE.** The fourth and tenth entries described a chapter that does not read that way. **Both are rebuilt from the last narrative line of each file, `chapter-0974.md`:139 and `chapter-0980.md`:113, and the review's replacement for 974 — a line eighteen lines above the close — is recorded here as also wrong, because a fix pass that swaps one false description for another has not fixed anything.**
6. **LOW — *TWO MARKS*, THE ONLY MONEY FIGURE IN THE BATCH OUTSIDE THE BINDER'S OWN QUOTES AT 972, AND ADJACENT TO ADJUDICATION 4.** **It is out with finding 1 and the sentence that carried it is gone. No figure of what the man in the street charges is printed anywhere in 951–980, which is what adjudication 4 says.**
7. **LOW — THE `since I was X` PROBE FIRES TWICE AND WAS BEING PUBLISHED INSIDE THE `about N` ROW.** `chapter-0972.md`:71 and `chapter-0978.md`:107. **Neither announces an age and the conclusion of zero announced ages stands. The two hits are now reported as their own row in §2 instead of being absorbed into a different probe's count, because a gate that folds two instruments into one number cannot be checked by the next pass.**

**Nothing was restarted. No beat, date, spine figure, title, scene, decision or ending moved. The planned movement is intact and 981–990 opens against exactly the page the first fix pass left.**

## 9 · THE FLAG

**The overrun flag at the head of `state/open-threads.md` is NOT closed by this batch.** The manuscript is now nine hundred and eighty chapters and the plan says five hundred, and writing thirty of them did not decide that. **`outline/ending.md` was not touched and nothing in it moved.**
