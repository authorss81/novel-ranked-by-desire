# VOLUME 13 · BATCH 0002 · CHAPTERS 611–620 · WRITING PHASE · MOVEMENT TWO, *ASKED*

**A WRITING PHASE. YOU WRITE TEN FINISHED CHAPTERS AND NO PROSE THAT IS NOT ONE OF THEM. YOU DO NOT PLAN A VOLUME. YOU DO NOT REOPEN CHAPTER 500 OR CHAPTER 610. YOU DO NOT TOUCH `outline/ending.md`. YOU DO NOT WRITE A BATCH 0003 AND YOU DO NOT WRITE A VOLUME-CLOSE PROMPT — VOLUME 13 IS NOT CLOSED BY THIS BATCH AND IT HAS THIRTY CHAPTERS LEFT AFTER IT. `state/complete.md` MUST NOT BE CREATED. THE SERIES IS PLANNED PAST 600 AND THE SERIES ENDING IS `outline/ending.md`, WHICH YOU DO NOT TOUCH.**

**WRITTEN AGAINST `outline/volume-13.md` §7 MOVEMENT TWO, *ASKED*, AND §2, §3, §4, §4c, §4d, §5, §6, §8, §9 AND §10. IF THE PAGE AND A CARD DISAGREE, THE PAGE WINS AND YOU REWRITE THE CARD AND THE OUTLINE IN THE SAME COMMIT.**

**BATCH 0001 IS ON DISK AND THIS BATCH STARTS SEVEN DAYS AFTER IT. READ `state/current.md`, `state/continuity.md` AND `state/open-threads.md` AT THE HEAD OF EACH BEFORE YOU PLAN A WORD. EVERY FIGURE BELOW THAT IS ABOUT THE FIRST TEN CHAPTERS IS TAKEN FROM THOSE BLOCKS AND NOT FROM ANYWHERE ELSE.**

---

## 0. THE ONE COMMIT AND WHAT IS IN IT

```
chapters/volume-13/chapter-0611.md ... chapter-0620.md   ten finished files, one scene at 613
outline/batches/volume-13-batch-0002.md                  ten cards written against the page
outline/volume-13.md                                     §7 movement two rewritten against the page
state/current.md                                         live block at the head
state/continuity.md                                      live block at the head
state/open-threads.md                                    live gate block at the head
state/chapter-summaries.md                               ten rows and a batch block
workspace/volume-13/batch-0003/PROMPT.md                 the one next phase
```

**AND NOTHING ELSE. `scripts/`, `.github/`, `.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json` AND `state/phase-ledger.json` ARE CONTROLLER FILES AND ARE NOT YOURS.**

---

## 1. WHAT YOU READ, IN THIS ORDER, AND YOU DO NOT SKIP THE FIRST FOUR

1. **`outline/volume-13.md` IN FULL.** **§4d is the table of marks and you read it before you plan a single body, not after** — 613 is Sun Meiling and §4d's row for her is *one new physical fact from 358 and no mark at all*, and her twenty-two-stitch row in a coat lining is paper and not a body. **§8 is the register you may not open and you read it before you plan, not after.**
2. **`outline/batches/volume-13-batch-0001.md`.** It has just been written against and three of its rows are marked **CORRECTED AGAINST THE PAGE**. Read the correction block at its head; those three errors are the kind this batch makes too.
3. **`AGENTS.md`.**
4. **`reviews/volume-12/volume-close.md` §4a, §4b, Finding I and §11.** **Finding I is a judgement about Volume 12's density that you inherit as a fact, not a mood:** dramatic density fell at chapter 571 and never recovered, and the volume's last thirty chapters were **compressed rather than lean**. **Batch 0001 measured itself against that and printed the measurement: 44.7 quoted spans a chapter and 63.9 paragraphs against Volume 12's 24.7 / 52.3 / 16.1 / 17.4 / 20.7 and 54.2 / 66.8 / 28.0 / 39.4 / 32.8. HOLD THAT LINE.**
5. **The live blocks at the head of `state/current.md`, `state/continuity.md`, `state/open-threads.md`.**
6. **`chapters/volume-13/chapter-0601.md` through `:0610.md` — all ten, in order.** You need the voice, the furniture, the dates and the figures. Then **`:0603.md`, `:0606.md`, `:0609.md`, `:0610.md`** a second time, and those four are enough of Volume 12 as well: **`:0600.md`, `:0595.md`, `:0587.md`, `:0588.md`, `:0559.md`, `:0549.md`, `:0525.md`, `:0474.md`, `:0478.md`, `:0481.md`.**

**YOU DO NOT NEED ALL SIX HUNDRED AND TWENTY CHAPTERS.**

---

## 2. THE SPINE, AND EVERY INTERVAL YOU PRINT GETS ITS OPERANDS

**A month is thirty days and has no thirty-first. A year is three hundred and sixty. A year runs from the first of February to the thirtieth of January. Every month from February to December is labelled by the year it sits in, and a January is labelled by the February that follows it — WHICH MEANS A JANUARY IS THE TWELFTH MONTH OF THE YEAR IT CLOSES.**

```
day 0 = 1 February, year one      1 February of year y = (y - 1) x 360
day of month d = (y-1) x 360 + offset[month] + (d-1)      for every month BUT January
a January labelled y          = (y-2) x 360 + 330 + (d-1)     *** THIS EXCEPTION IS NOT
                                  OPTIONAL AND IT HAS COST THIS REPOSITORY 2,133 TWICE ***
METHOD B (contains no 360 at all)  i = (y-2)*12 + 11 for a January labelled y, else
                                    (y-1)*12 + pos(m);  day = 30*i + (d-1)

611  11 Mar y6 = 1840    1840 - 1833 =  7
612  17 Mar y6 = 1846    1846 - 1840 =  6
613  24 Mar y6 = 1853    1853 - 1846 =  7   SCENE, Sun Meiling
614  30 Mar y6 = 1859    1859 - 1853 =  6   QUARTER-END, the TWENTY-FIRST SHEET, at four
615   7 Apr y6 = 1866    1866 - 1859 =  7
616  15 Apr y6 = 1874    1874 - 1866 =  8
617  22 Apr y6 = 1881    1881 - 1874 =  7
618  29 Apr y6 = 1888    1888 - 1881 =  7
619   6 May y6 = 1895    1895 - 1888 =  7
620  13 May y6 = 1902    1902 - 1895 =  7   THE MOVEMENT'S TURN
SEAM 611-610 = 1840 - 1833 = 7
BATCH SPAN  620-611 = 1902 - 1840 = 62, and 6+7+6+7+8+7+7+7+7 = 62
(the 7 in the 611 row above is the SEAM from 610 and is not part of the batch's own span)
```

**MONOTONIC AT ZERO VIOLATIONS ACROSS ALL TEN. RE-RUN IT BEFORE YOU FINISH, AND RUN IT AGAINST THE SPINE AND NOT ONLY AGAINST THE PROSE.**

**THE ANCHORS YOU MAY NEED. EVERY ONE OF THESE WAS RE-DERIVED BY COMMAND IN THE COMMIT THAT WROTE THIS PROMPT AND NOT CARRIED OUT OF A CHAPTER, AND A FIGURE THAT WAS NOT RE-DERIVED IS NOT PRINTED HERE:** 1,902 = 13 May y6 · 1,895 = 6 May y6 · 1,888 = 29 Apr y6 · 1,881 = 22 Apr y6 · 1,874 = 15 Apr y6 · 1,866 = 7 Apr y6 · 1,859 = 30 Mar y6 · 1,853 = 24 Mar y6 · 1,846 = 17 Mar y6 · 1,840 = 11 Mar y6 · 1,833 = 4 Mar y6 · 1,780 = 11 Jan y6 · 1,773 = 4 Jan y6, the day the demand came back to the room off a third court · 1,769 = 30 Dec y5, the twentieth sheet · 1,722 = 13 Nov y5, the day the two sentences went out at four · 1,718 = 9 Nov y5, the day they were written · 1,715 = 6 Nov y5 · 1,706 = 27 Oct y5 · 1,685 = 6 Oct y5 · 1,680 = 1 Oct y5, the nineteenth sheet lying out at the public desk · 1,439 = 30 Jan y5, the yard · 1,409 = 30 Dec y4, the sixteenth sheet · 1,334 = 15 Oct y4, the four conditions entered against himself in the column headed carried by · 247 = 8 Oct y1, the second line going onto the wall.

**AND ONE ANCHOR THIS PROMPT DELIBERATELY DOES NOT GIVE YOU: the year the Vant's entry was entered in. It is not on a page anywhere in this book, two pages that keep it already disagree about it, and no chapter of 601–650 prints a year for it. Write *the sixteenth of September* and nothing else.**

**THE OTHER FIGURES THIS BATCH MAY TOUCH, AND WHERE EACH ONE IS ALLOWED TO APPEAR — BATCH 0001 ALREADY SPENT TWO OF THESE, AND THE COUNT IS NOT RESET BY A NEW BATCH BUT THE WORDS ARE:**

- **THE OFFICE'S AGE.** **PRINTED ONCE ALREADY, AT 601, WITH OPERANDS: `1,773 = 30 × 59 + 3`.** If a chapter of 611–620 needs it, the figure is `1,859 = 30 × 61 + 29` at 614 and `1,902 = 30 × 63 + 12` at 620, and **it may be printed at most once in this batch and at 614 is the natural place.** A month is thirty days and the thirtieth is the last working day of the month and of the quarter.
- **THE LANE.** The first morning was the third of October of the year before the first, which is day −118. `1,859 − (−118) + 1 = 1,977` mornings at 614, `1,902 − (−118) + 1 = 2,021` at 620. **PRINTED ONCE ALREADY, AT 609, WITH OPERANDS.** At most once more in this batch.
- **THE WALL.** **About nine thousand people go under it in a day, and the reason is that it is an ordinary morning of an ordinary month and the trams go under it.** That rate is on the page in more than one chapter — `chapter-0521.md:27`, `chapter-0526.md:109`, `chapter-0545.md:23`, `chapter-0548.md:47` — and its scene is `chapter-0489.md:21`, at about a quarter past nine on the fourth of October. **PRINTED ONCE ALREADY, AT 605, WITH ITS REASON. AT MOST ONCE MORE IN THIS BATCH.** **TWO FIGURES ARE NOT THAT RATE AND ARE NOT USED AS IT AND ARE NOW BANNED FROM THE WHOLE OF 601–650.** `chapter-0545.md:87` is Beatrix Halm's *about four hundred people go under this wall in a day*, said in the same chapter that says nine thousand at `:23`, and no page reconciles the two. `chapter-0500.md:35` is *about four hundred people have gone past him doing it* — **a total since the first of January, not a rate** — and it is reserved by `PC-117`. **NEITHER FOUR HUNDRED IS PRINTED, DERIVED OR MENTIONED IN 611–620.**
- **THE SHEET.** Eight hundred and fifty-two, unmoved since the thirtieth of March of the fifth year. About four hundred and nineteen of the lines are accounts with an hour against each and no figure on any of them. **The second column has two lines.** **841 and 419 are two numbers and may not be merged.** **The twenty-first sheet goes out at four on the thirtieth of March at 614** and the head is unmoved for the fifth quarter running and no chapter of this volume calls the figure a count of deeds.
- **THE FOUR LINES**, quoted at most once in this batch and not re-explained after it. **BATCH 0001 ALREADY QUOTED THEM, ONCE, AT 601. SO THEY MAY BE QUOTED ONCE IN 611–620 AND NOT AGAIN AFTER THAT.**
- **THE TWO SENTENCES AT THE FOOT**, in the office's own hand, printed since the ninth of November: the invented-figures sentence with a name under it, and *where the Register has nothing it has not been given anything*. **THE INVENTED-FIGURES SENTENCE IS THE PRINTED INSTRUMENT AND IS CLASSIFIED AS ONE: it stands verbatim at 595 as a hand writing a document, at 596 as a clerk reading it back, at 606 as a checker in a yard reading it off a public page, and it may stand verbatim ONCE MORE in 611–620 and not again in the volume.**
- **IF A CHAPTER PRINTS AN INTERVAL THAT IS NOT IN THE TABLE ABOVE, YOU DERIVE IT YOURSELF, TWICE, FROM DAY NUMBERS, AND YOU PRINT THE OPERANDS IN THE ITALIC FOOTER IN PLAIN WORDS.** *A figure nobody re-computes is the figure that is wrong*, and that sentence has now failed eleven times in three volumes.

---

## 3. THE BATCH, IN TEN LINES, AND THE TITLES ARE FIXED

- **611 — THE OFFICE NAMED IN A FINDING.** A clerk with standing names the office as a party for the first time in its life and asks the one question he is entitled to ask.
- **612 — NINE DIVISIONS RETURN A LINE.** Nine divisions must return a line to a finding and one of them has to ask what the line is for.
- **613 — THE SIXTH TIME SHE IS ASKED. THE SCENE.** Sun Meiling, five hundred and fifty chapters, the folder at the far table of a counting room two floors under a sales floor, asked for the first time in this book.
- **614 — THE TWENTY-FIRST SHEET.** The quarter-end, at four, with the head unmoved and the lane's mornings and the office's months printed once each with operands.
- **615 — A DESK UNDER HER OWN STAIR.** The woman two flights up off Cordwain has been to the desk under her own stair and has not read it and cannot.
- **616 — AN ENTRY OPEN SINCE SEPTEMBER.** A real book in a building off Cordwain and an entry that has stood open since a September this volume does not name.
- **617 — WHICH OF THESE DID YOU MAKE UP.** **THE INVERSION, AND IT IS THE PAYMENT.** The man who invents figures tells her which of his own figures he made up, and she asks the question the whole volume is about, and he answers it correctly. **She is not thanked. She is given nothing. It is not a scene.**
- **618 — THE MAN ENTITLED TO READ IT.** The sentence in the office's own hand read back to him by the man entitled to read it, in order.
- **619 — A PIECE OF PAPER CAME BACK.** Night shift, three women on a rota, and the demand from the fourth of January.
- **620 — THE WEEK THE YARD DECIDES.** **THE MOVEMENT'S TURN, AND IT IS NOT HIS.** A yard of about eleven thousand people has a week to decide, and he is told about it by a woman who is not asking him for anything.

**THE TEN TITLES WERE CHECKED BY COMMAND AGAINST ALL SIX HUNDRED AND TEN WRITTEN TITLE LINES: 611 The Office Named In A Finding · 612 Nine Divisions Return A Line · 613 The Sixth Time She Is Asked · 614 The Twenty-First Sheet · 615 A Desk Under Her Own Stair · 616 An Entry Open Since September · 617 Which Of These Did You Make Up · 618 The Man Entitled To Read It · 619 A Piece Of Paper Came Back · 620 The Week The Yard Decides.**

**IF ONE COLLIDES — none of them does — CHOOSE ANOTHER AND DO NOT CHANGE A WRITTEN CHAPTER TO MAKE ROOM.** A title names a thing, is between two and twelve words, and may not restate the scene, the hour, the weather, the date or the age of anyone present.

---

## 4. THE TWO THINGS THIS BATCH OWES, AND BOTH ARE HARD

### 4a. THE SCENE AT 613, AND THE FOUR THAT ARE NOT YOURS

**THE SCENE IS SUN MEILING. READ `outline/volume-13.md` §4d AND §4c BEFORE YOU PLAN A WORD OF HER BODY. She has no mark on the page and none may be given her.** Her only physical fact is the line of work across the top of her spine, hers from 358. Her twenty-two-stitch row in a coat lining is paper and not a body and may be referenced once and never restaged.

- **THE AXIS BROKEN IS THE ORDER**, carried by her room's rule and named by nobody: **a folder is taken in the order it was opened and may not be taken out of order afterwards, and the first question in it is not the one anybody came for.** **NO CLOCK IS PRINTED INSIDE THE SCENE AND NO HOUR IS COUNTED IN IT. NO KETTLE, NO CHART, NO ARM TURNED UP.**
- **No compulsion, no sedation, no exhaustion, no toxin, no restraint, no psychic contact, no trance and no seal as the mechanism. Every sexual character is an adult. He is rank one with a spent chest and no permission of any kind. Saying yes is fast and it is enjoyable to her and it is written as real and specific, not as reluctance.**
- **Violence and sex stay in separate registers. There is no violence in this chapter.**
- **The chapter's structural difference from 603, which it must not repeat:** at 603 a woman had the authority and he was the one who could not be found. **At 613 the room has the order, and the order is hers, and the thing she has wanted for four years is to be asked, and she has a folder she has not opened out of sequence since the second year, and the first question in it is not the one anybody came for.** Her brother is not in the folder and she says so in her own mouth and **the chapter is not about him.**
- **The scene may leave the 1,800–2,700 band and if it does you record why in `state/current.md` in the same commit. The default is that it is not long enough.** 584 ran at 1,648 once and was written out again at 3,022.
- **613 − 603 = 10, in band. 613 − 63 = 550.** Reported and not certified, and no file may call that inside the eight-to-fifteen band.

**AND THE NEXT FOUR SCENES OF THIS VOLUME ARE NOT IN THIS BATCH.** They are at 623 (Marguerite Vale), 633 (Wren Kallo) and 643 (Ines Duarte), and `outline/volume-13.md` §4 names the rest. **Do not write a scene at any other chapter in 611–620, and do not write a second explicit passage in a chapter that is not the scene.**

### 4b. THE PAYMENT AT 615 AND 617, AND IT IS THE ONLY REGISTER ITEM VOLUME 13 MAY CLOSE

**WHETHER THE WOMAN TWO FLIGHTS UP OFF CORDWAIN EVER LEARNS WHAT WAS DONE FOR HER.** Open and undated through Volume 12. Named as owed at `reviews/volume-12/volume-close.md` §11 item 1.

- **IT IS MADE BY EMIL BRACK AND NOT BY LIN HAO.**
- **IT IS NOT A SCENE.**
- **SHE IS NOT THANKED AND SHE IS GIVEN NOTHING AND NO CHAPTER SHOWS HER READING A SHEET.**
- **She learns it from a slate and a voice.** She cannot read. She is the Register's first creditor, big, the hands of somebody who has not stopped and then stopped. **THE NINTH LINE DOWN ON THE STANDING SHEET IS HERS: a street dug for six years in the cold, no figure against it and no name against it, entered on the eleventh of July in a clerk's hand because the division was not permitted to ask her for a name and did not ask her, and there is no column on the page that would take one if it had asked.**
- **`outline/volume-13.md` §4d DECISION 1 STANDS AND IS NOT A RESTRAINT: MAVIS ROOKE'S HAND-FLAT ON THE TABLE IS NOT USED AGAIN.** It was hers at `chapter-0547.md:86`, it was put on Ines Duarte at `chapter-0584.md:75` where it was a borrow, and a gate row once certified its absence and was false. **No chapter of 601–650 puts a hand flat on a table.**
- **The man with the broom is not in this batch and is given no name, no mark, no age and no second conversation.**
- **PAYING IT ONCE IS THE WHOLE OF THE JOB. NO CHAPTER OF 601–650 REOPENS IT AFTER 617.**

---

## 5. WHAT THIS BATCH MAY NOT DO, AND EACH ONE IS A LINE A LATER PHASE WILL CHECK BY COMMAND

- **No figure of the account.** It is fixed and `outline/ending.md` fixes Chapter 500 as the only place it is printed. A chapter that needs it says *the figure*.
- **No floor, no ledger total, no running balance in grains.** `grep -rio 'settle' chapters/volume-13/` is **zero in every inflection across the whole volume.**
- **No year numeral.** Write the date. *Of year six* in an italic footer is a date and is permitted. **BATCH 0001 WENT FURTHER AND NAMED NO YEAR IN ITS PROSE AT ALL; HOLD THAT.**
- **No day of the week**, seven names, whole-word and stem, zero.
- **No announced age.** Nine probe forms plus a bare `aged` sweep. A span of years is permitted; an age is not. **Hanneke Ruis has no age fixed and none may ever be given — and she is not in this batch.** **Mavis Rooke is given no age and no mark.** **Sun Meiling has no mark and none may be given her.**
- **No mark, no temple, no eye, no ink.** `right temple` stays at zero across all six hundred and twenty chapters. `cuticle` stays at four chapters. `ostho` stays at zero — the name on the page is **Otho Pearse**.
- **Neither repainting box is filled.** Both are blank and blank for ever, and a character may say so out loud **once in the volume** — **it was said at 605, so a character does not say it again.**
- **The keeper's six words are not reopened.** Not in this batch, not in this volume.
- **Who put the white tile up is not said.** By anybody. For ever. **608 did not go near it.**
- **Emil Brack is not thanked, not diminished, not defeated and not wrong about any fact.** He may be useful. He may not be diminished.
- **No new enemy.** The opposition is a sentence, Corvin Ashby, a landlord's man, a magistrate's clerk with one question, Brack, and about eleven thousand people.
- **No partner dies and no partner is left behind by a choice she does not explain.**
- **`outline/ending.md` is untouched, and nothing in these ten chapters may contradict a word of it.** Lin Hao may write *his brother's file* and may not write the name.
- **Nothing about the reach of the return**, in either direction, by anybody.
- **A GATE THAT GOES UP THOSE TWO FLIGHTS OFF CORDWAIN.** He went up them once, at 610, and there was nobody at the top, and he did not knock. **No chapter of 611–650 does it a second time.**

---

## 6. THE FOURTH WALL, THE CLASS GREP, AND THE TWO SENTENCES

```
[a-z]+ volumes | this book | this chapter | this volume | no chapter | the axis |
the reader | the novel | the story | the scene | Chapter [0-9]+ | chapter [0-9]+ |
manuscript | in this manuscript | this manuscript | this page | opposition
```

**THE WORDS `MANUSCRIPT` AND `OPPOSITION` ARE BOTH IN THAT CLASS AND BOTH HAVE BEEN MISSED AT SOME POINT.** Volume 11's batch 0005 ran the class without *manuscript* and a fourth-wall break sat in a finished chapter through it. Volume 12 repaired a break that used the word *opposition* in a scene about a rent register, where the word has no referent. **Run it, print the hits, and read every one. A hit that is an object in the world — a page on a desk, a form in a hand, a book on a landing — is survivable and must be argued. ZERO IS BETTER, AND BATCH 0001 REACHED ZERO ON ITS FIRST CLEAN RUN AFTER REWRITING TWO HITS IN A CHAPTER ABOUT A CHAINED LEDGER, RATHER THAN ARGUING THEM.**

**AND THE TWO SENTENCES:**

> **A figure nobody re-computes is the figure that is wrong.**
>
> **A gate row that quotes the prose it is checking cannot catch the prose. And a gate that measures only its own batch cannot see what happened before it — which is how a house form changed at chapter 571 and four arithmetic gates passed it.**

---

## 7. THE GATE YOU RUN BEFORE YOU FINISH, AND WHAT YOU PRINT

**Every row below is a measurement, not a claim. Run it, print it, and if a row fails, FIX IT IN THE CHAPTERS — do not soften the row.**

```
FILES           ten files, 611-620. One `# ` title line in each. All ten end 0a.
                `find chapters -name 'chapter-*.md' | wc -l` -> 620, BY COMMAND.
TITLES          grep -rh "^# " chapters/ | sort | uniq -d | wc -l  -> 0 ACROSS ALL 620.
                ***RUN IT ACROSS ALL SIX HUNDRED AND TWENTY FILES, NOT ACROSS YOUR TEN. ***
BANK            COUNT PER FILE AND SUM. NEVER cat *.md | wc -w.
                Print all ten figures and the total.
                ***AND PRINT THE REASON FOR ANY CHAPTER OUTSIDE 1,800-2,700, IN EITHER
                DIRECTION. Volume 12 had twenty-five of fifty below the floor and the close
                audit's verdict was that its last thirty chapters were COMPRESSED rather than
                lean. A chapter here that cannot give a reason is not finished. ***
                ***AND PRINT THE DENSITY: quoted spans, either glyph, body-only, per file, and
                paragraphs, non-blank lines that are neither a heading nor an italic footer.
                Batch 0001 ran 44.7 spans and 63.9 paragraphs a chapter. Volume 12's five
                movements ran 24.7 / 52.3 / 16.1 / 17.4 / 20.7 and 54.2 / 66.8 / 28.0 / 39.4 /
                32.8. HOLD THE LINE. ***
PARAGRAPHS      0 over roughly ninety words. 0 over one hundred and twenty. 0 odd
                quotation-mark paragraphs. ***THE HOUSE FORM IS CURLY.*** Count the curly and the
                straight glyphs and print both, across ALL SIX HUNDRED AND TWENTY files.
META            the class grep in §6 -> 0 primary, 0 widened, 0 extension.
WEEKNAMES       seven names, whole-word and stem, across your ten -> 0. `sat` and `sun`
                excluded as the verb and the name.
AGES            eleven probe forms plus a bare `aged` sweep -> 0.
ARITHMETIC      the spine 1,840-1,902 monotonic, 0 violations, by two methods THAT SHARE NO
                CONSTANT. ***Print the January exception. Two methods that share a convention
                agree with each other and are both wrong, and that has put 601 at 2,133 twice. ***
                Every interval your footers print, parsed from the page and summed with its
                operands. Both must agree with the page.
ACCOUNT         8,1xx 0. two hundred and eleven thousand 0. settl 0.
RT              right temple 0 book-wide. cuticle 4 files book-wide, unchanged.
                ostho 0. Mavis Rooke's hand-flat 0 across your ten.
                NEITHER FOUR HUNDRED anywhere in chapters/volume-13/.
DUPLICATION     12-gram FIRST against every chapter in the book including your own,
                body-only, headings and italic footers stripped, token-normalised.
                THEN 11 AND 8. EVERY HIT CLASSIFIED BY HAND, NOT COUNTED.
                ***THEN THE §4d BORROWED-BODY AND BORROWED-STAGING TABLE, READ BEFORE YOU
                PLAN A BODY AND NOT AFTER. A twelve-gram scan cannot see a borrowed body. ***
                ***AND THE THREE CLASSES THAT SURVIVED IN 601-610, CLASSIFIED AGAIN: a
                character restating his own sentence in the place he made it; the printed
                instrument, which may stand verbatim at most once more in this volume; and the
                calendar rule. ***
SCENE           613 measured three ways — first-## to last-##, single scene section
                inclusive, and exclusive — WITH THE LINE SPAN PRINTED BESIDE EVERY CELL AND THE
                CLOSING BOUNDARY NAMED. Volume 12's close audit found sixteen cells in its own
                table that did not re-derive, and one row that was another chapter's figure.
                Explicit-vocabulary probe at WORD BOUNDARY: semen is a substring of
                advertisement and a substring probe scores two false hits.
MARKDOWN        blockquotes 0. tables 0. rules 0. fences 0. bold 0. single-asterisk
                markers even in all ten. System panels at most one per chapter, in square
                brackets on their own line, not bold, not italic. Budget five for the volume
                and **BATCH 0001 SPENT NONE, so five are unspent and one spent is one too
                many.**
```

---

## 8. THE ONE NEXT PHASE, AND YOU LEAVE EXACTLY ONE

**`workspace/volume-13/batch-0003/PROMPT.md`, CHAPTERS 621–630, MOVEMENT THREE, *OWED*.** It is a writing phase. It carries the twenty-second sheet at 626, the scene at 623 (Marguerite Vale, a real book and a carrier), the yard's week at 625, and **the movement's turn at 627, which is not his: at the end of a meeting, about eleven thousand people take one line off their own shutter themselves, nobody asks the man who wrote it, and the chaplain is not there and is not asked.**

**AND NOTHING BEYOND IT. DO NOT WRITE A VOLUME-CLOSE PROMPT — VOLUME 13 IS NOT CLOSED AND HAS TWENTY CHAPTERS LEFT AFTER THAT BATCH. DO NOT CREATE `state/complete.md` — THE SERIES IS PLANNED PAST 600 AND THE SERIES ENDING IS `outline/ending.md`, WHICH YOU DO NOT TOUCH.**

---

## 9. IF YOU RUN OUT OF ROOM

**Stop at a chapter boundary. Save the completed chapters and the state. Mark the remaining batch as resumable in `state/current.md`. Do not restart a completed chapter. Do not leave a half-written file on disk. A batch that returns without writing anything has asked for more than one call can deliver.**
