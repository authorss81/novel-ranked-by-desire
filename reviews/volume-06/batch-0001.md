# Volume 6, Batch 0001 — Review and repair record (Chapters 251–260)

**§1–§5 were written by the batch that wrote the chapters. That pass was not a review by a second reader.**
The workflow's review gate did not run — `logs/batch-0001.review.log:1` records the reviewer agent
falling back to the writer — so nothing below §6 had been checked by anybody who had not already decided
to write it. **§6 is an independent review that ran afterwards**, read the finished prose on disk and
repaired it. Every figure in §1–§5 is the output of a command run against the disk at the moment that
batch's last edit was saved. Every figure in §6 is the output of a command run after the repair. **Where
the two disagree, §6 is the record.**

---

## 1. THE INHERITED REPAIR, DONE FIRST, AND IT WAS TWO LINES

`chapters/volume-05/chapter-0250.md` was drifting its own dateline. The chapter is dated **the tenth of
July** at `:3` and re-anchors to the tenth at `:93` (*"Sixteen days the finding had sat when she asked on
the ninth. Seventeen now."*), but two lines put the closing montage on *"the last night of July"* — the
thirty-first, twenty-one days past the chapter's own date and nineteen past the unwritten twelfth.

**Root cause, confirmed:** Batch 0005's review removed the meta string `on the last night of the volume`
by substituting `July` for `volume`. Right about the meta, wrong about the date.

**Both forms are fixed. Neither line was left alone.**

| Line | Was | Now |
| --- | --- | --- |
| `:91` | *He counted the sixty-one steps under his breath **on the last night of July**.* | *He counted the sixty-one steps under his breath **on the tenth of July**.* |
| `:95` | *He left the landing lamp burning till eleven **on the last night**.* | *He left the landing lamp burning till eleven **that night**.* |

- `:93` **untouched** — the day count there is the thing that proves the tenth is correct.
- `:97` **untouched** — `after eleven` works on any night and was never wrong.
- The chapter's dateline at `:3` **untouched**. No other sentence in the chapter was changed.
- **No paragraph of explanation was added.** Word count 2,138 → **2,135** (three words shorter: the two
  phrases were longer than their replacements). `grep -n "last night" chapter-0250.md` now returns nothing.
- Every other chapter in 241–250 is a strict single day and 250 is now one too.

**The argument for keeping the phrase, recorded because the prompt asked for it: there is none.** The
closing image is a montage of small household gestures and it works on any night, but the chapter's own
arithmetic fixes the night at the tenth, and a reader who traced the counts would have found the sweep.
Moving it was the only correct repair.

**Also corrected, because it was inherited as fact and is not:** `outline/volume-05.md` §6 movement 5
says *"Ch 246 is fixed by `outline/series.md`."* It is not. `outline/series.md` fixes that Ines leaves in
Volume 5 and that Volume 5 is *"a woman deciding whether she can be with a man she has to audit."* The
chapter number, the filed true report and the walkout of a flat she is still in are Volume 5's own
decisions. **Nothing in the chapter is wrong; the outline over-claims one level of authority.** Recorded
here, in `state/continuity.md` and in `state/current.md`. **No volume outline pins a chapter number except
the scene table in `outline/series.md`.**

---

## 2. Errors the batch found in its own draft and fixed before the last edit

All of these are the class the close pass named — **a figure correctly derived on one date and carried to
another** — and all are fixed on disk.

| Ch | Was | Now | Anchor |
| --- | --- | --- | --- |
| 254:93 | *"Thirty-eight days yesterday, thirty-nine today"* | *"Thirty-nine days yesterday, forty today"* | Petra off roll **4 June**. 14 July = 40. |
| 254:93 | *"for thirty-nine days I have been marking nothing"* | *"forty days"* | same |
| 258:75 | *"Fourty-three days I have been on no roll"* | *"Forty-four days"* (and the typo) | 18 July = 44. |
| 256:43, 111 | the clinic return dated **the seventeenth of July** | **the sixteenth** | Chapter 256 **is** the sixteenth. |
| 252:77 | *"I have kept it for nine days"* | *"three days"* | The term was agreed late on the **ninth**; 252 is the twelfth. |
| 255:81 | *"You have been not asking her for nine days"* | *"six days now"* | The ninth to the fifteenth. |
| 256:27 | Tessa *"waiting nine days to be asked"* | *"waiting a month"* | Her note is dated the **sixteenth of last month**. |
| 257:97 | *"You did that nine days ago"* | *"eight days ago"* | The ninth to the seventeenth. |
| 257:85, 259:121 | *"standing on it for nine days"* | *"since the ninth"* / *"since the ninth"* | same |
| 255 (×4) | Sun *"proud of it for four months"* / *"a coat for four months"* | *"since March"* / *"since the twenty-second of March"* | 22 March to 15 July is not four months. |
| 258, 259 | *"six women"*, *"six people"*, *"eight women"*, *"nine women at a kitchen table"* | **partly swept — the sweep did not finish and this row claimed it had.** Repaired on independent review; see §6 finding 7. | Ines is absent; the count had drifted twice. |
| 253, 260 | the Thursday pass described as *"two hours behind"* with the figures already up at ten | re-sequenced so the figures and the bare stretch do not contradict each other | `chapter-0246.md:5`. |

---

## 3. What was left standing, and why

1. **`nobody` ×1, at `chapter-0255.md:7`.** *"I owe you three years of a question nobody put to you."*
   This is **canon language, not a rhetorical tic**: `bible/terminology.md` defines Sun Meiling's three
   years as *"years of waiting on a question nobody put to her."* The chapter's debt is named in the
   book's own terms and Sun repeats it correctly two paragraphs later. Every other use of the word in the
   batch was cut; the batch total is one.
2. **One italic, at `chapter-0252.md:93`** — the four words of Marguerite's slip, set as written matter:
   *The account runs to the hundred and thirty-fourth mark on the first of August. Bring the plate.*
   Volume 5 Batch 0005 closed on one italic (245:39) under the same allowance. **Markup is 1, not 0.**
3. **Twenty-nine 12-grams shared with other chapters out of 260.** All nine groups are adjudicated canon
   beats, listed in the gate block. None is a scene duplication; this batch writes no scene.
4. **The word `nobody` aside, zero system panels and the batch contains no `[` at all**, so zero is
   structural and not a regex artefact. Nothing is spent from the reservoir in two hundred and forty
   chapters. **Do not manufacture a panel in Batch 0002.**
5. **Chapters 257 and 260 share four 12-grams** on *"the only person who can certify the schedule."* That
   is deliberate and load-bearing: Ines names the instrument on the seventeenth and the panel names it
   again on the twentieth, and the reader is meant to hear the second one as a thing that has been set in
   motion. It is the batch's single deliberate internal echo.
6. **`There is no form for this` was cut from Ch 254** in favour of the specific instrument the guild does
   not print — *"this guild prints no instrument by which a broker may hold a client's pricing."*
   `bible/terminology.md` caps the general observation at three book-wide and requires the third to
   escalate to a specific form; the batch spent none.
7. **`hearing tail` / `my hearing tail` was not used.** The rule it stood for is already canon and is
   stated in its own words at 259: *the rule is that every security standing against an account comes off
   it the same day.*

---

## 4. Hand trace of every date, against the anchor

Anchors: **Wren Kallo's finding filed 23 June** · **the true report filed 6 July** · **Petra Ilyin off
every roll since 4 June** · **the sworn page in his own hand 14 June** · **the broker's offer 3 July,
expiring 12 July** · **the term agreed on Lantern Row on the night of 9 July**.

Calendar derived from `outline/series.md` and Volume 5's own derivation: **July 1 is a Saturday, 1 Aug a
Tuesday. July Thursdays are the 6th, 13th, 20th and 27th.**

| Ch | Day | Weekday | Wren | Report | Petra | Sworn | To 1 Aug | What the chapter prints |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 251 | 11 | — | 18 | 5 | **37** | **27** | 21 | Petra 37; Runa 27 ✔ |
| 252 | 12 | — | 19 | **6** | 38 | 28 | 20 | report 6; the charge's own term = 12 + 14 = **the 26th** ✔ |
| 253 | 13 | **Thursday** | 20 | 7 | 39 | 29 | **19** | 1 Aug nineteen days off ✔ |
| 254 | 14 | — | **21** | 8 | **40** | 30 | **18** | Wren 21; Petra 39 yesterday, 40 today, 40 at six ✔ |
| 255 | 15 | — | 22 | 9 | 41 | 31 | 17 | six days of not asking ✔ |
| 256 | 16 | — | 23 | 10 | **42** | 32 | 16 | Petra 42; the return dated the **sixteenth** ✔ |
| 257 | 17 | — | 24 | **11** | 43 | 33 | 15 | **6 + 14 = the 20th**, printed as working ✔ |
| 258 | 18 | — | **25** | 12 | **44** | 34 | 14 | Wren 25; Petra 44 ✔ |
| 259 | 19 | — | **26** | 13 | **45** | 35 | 13 | Wren 26; Petra 45; sixteen days since the third ✔ |
| 260 | 20 | **Thursday** | **27** | **14** | 46 | 36 | **12** | report 14; finding 27; 1 Aug twelve days ✔ |

**What the anchor character actually does on each date, which is the question the close pass says to
answer and not the number:**

- **Wren Kallo** goes to Hadewig Mers's desk on the ninth of July and comes back with *"the division will
  reply in its own time."* She says the count aloud in 259 and it is twenty-six.
- **Ines Duarte** filed eleven minutes in her own hand on the sixth and the entry went up with it. She sits
  at a desk where she is the subject on the twentieth, which is the **fourteenth day from the sixth** and
  not the fourteenth day from the twelfth: a charge's own fourteen-day term runs to the twenty-sixth and
  is the slower clock. **Both are on the page and they are not the same clock** (252 and 257).
- **Petra Ilyin** marks nothing and is on no roll. She is forty days on it on the fourteenth and she says
  so, and she asks at the table on the nineteenth what the mark on the first of August is keeping.
- **The lead** wrote six in his own hand on the fourteenth of June and carries it twenty-seven days by the
  eleventh.

---

## 5. The batch's claim against the five required changes

1. **The twelfth of July has passed and the offer is gone.** Not threatened. Ch 252: he watches all day
   for a thing that cannot arrive, and at seven a guild boy brings four words in Marguerite's hand which
   are not the offer. **The proof of the expiry is the arrival of something else.**
2. **He has begun calling debts in**, out loud, in his own house, one at a time: Runa (251), Sun (255),
   Tessa (256), Beatrix (259), himself (258). Ines is not called — she is on a stair (257) and she is the
   one who is called in by the division (260). **Sun's is the one that cost.**
3. **The pricer is reachable and reachable is not available** (257). He reads figures to her on a stair,
   from the seventh step down, with the paper in his hand, and he does not go up.
4. **An institution has a name and a face before it has a number** (253). **Solveig Rask, 42, enters and
   prices four of five and refuses the fifth, and refuses to price the reservoir**, saying so: *I do not
   price a thing I cannot describe. When I do price it there will be a date on the page and you will not
   be able to refuse it, because a dated figure in a real book is not an offer. It is a fact.*
5. **Something in the household moves** in a way Ch 250 could not have predicted: **the kitchen table is
   bare for the first time since March** (254) and **Sun Meiling asks to be counted** (255).

**The batch's irreversible decision is Ch 256**, in his own hand, dated, on a counted return: **plate
8,138 against nine years of Tessa Okonkwo's hours.** It costs him the only thing he has — for five volumes
he has been the person a form goes past, and a plate number on a Bureau line is a plate that has been
looked at — and it cannot be got off, because a return is a return. **Ch 253 closes a second option:**
he has carried the household's pricing to the keeper of the real books, and his broker takes her papers
off the table within a day.
---

## 6. INDEPENDENT REVIEW AND REPAIR — the pass the workflow did not run

An independent reader took the finished ten chapters, read them against the disk and against the volume's
own anchors, and returned seven chapter-level defects and four minors. **All seven and all four are fixed
on disk. The plot is unchanged: no event, no beat, no decision, no figure that a chapter depends on has
moved.** What moved is dates, counts and two sentences of geography.

**The batch's own sweep was incomplete, and its review file claimed otherwise.** §2 of this file is the
batch's list of errors it found in its own draft, and the eighth row of that table — the household's
room-count — says *re-derived or removed* when the text still carried three different counts. A self-written
review file cannot catch this, which is the whole reason §1–§5 is not a review.

### 6.1 The seven findings

**1. Ch 260 contradicted itself about the ranks wall.** `:3` said *"the wall had been finished twice over"*
and `:97` said *"two ladders were standing against the ranks wall with nothing on them above the middle."*
Same afternoon, ninety lines apart. `:97` is the anchor and is untouched; `chapter-0253.md:101` establishes
the Thursday crew's pace — *"they had not reached the middle of the wall."* `:3` now reads **"the wall had
been done as far as the middle in a shade that was not the one under it, and there were figures on the
lower half of it."**

**2. Ch 260 walked past a basement.** `:5` had him *"walk past the Exchange without going in and past the
counting room without looking up"* — but `chapter-0253.md:7` puts the counting room *"two floors under the
sales floor."* You cannot walk past it at street level. `:5` now reads **"left the stair that went down to
the counting room alone."**

**3. The clinic count sheet carried a note older than the sheet.** `255:87/91/95` and `256:5/15` place the
count from **the first of July**, and that is correct: `chapter-0253.md:59` has Solveig Rask say the
clinic *"was not counted before the first of this month, so somebody put it there."* The impossibility was
the other date — `255:97` dated the note on the back to **the sixteenth of last month**, the sixteenth of
June. A note cannot be on the back of a sheet that begins on the first of July.
**The count dates were kept and the note moved to the ninth of July.** Everything that depended on the old
date moved with it:

| Line | Was | Now | Derivation |
| --- | --- | --- | --- |
| 255:97 | day book entry for *the sixteenth of last month* | *the ninth of this month* | after the count opened, before the chapter |
| 255:99 | *walking past for a month* | *for a fortnight* | 1 July → 15 July = 14 days |
| 256:27 | *I thought about it on the sixteenth of last month* / *waiting a month to be asked* | *on the ninth of this month* / *waiting a week* | 9 July → 16 July = 7 days |
| 256:29 | *I decided on the sixteenth* | *I decided on the ninth* | same |
| 256:55 | *she had asked him on the sixteenth of last month* | *on the ninth of this month* | same |
| 256:95 | *his initials on the first line of every month since the sixteenth of last month* | *his initials on the first line of the month … and the date was the ninth* | only July has a first line inside the batch |

**Volume 5 is not in conflict with any of this and was not touched.** `chapter-0248.md:15` has Tessa say she
*worked it out* *"on the sixteenth of last month."* That is a different act at a different date, and it is
the better reading: she worked the arithmetic out in June, the count opened on the first of July with the
line blank, and on the ninth she wrote on the back of it.

**4. The sheet teleported across the chapter break.** `255:99` left it on the bare kitchen table with Sun
looking at it and neither of them touching it. `256:5` opened with it folded in Tessa's coat pocket. The
handover is now on the page in one clause: **"because she had come up the market stair at six that morning
and taken it off his bare table, where it had lain all night with nobody's hand on it."** This **preserves**
the beat the two chapters are built on — on the fifteenth neither of them touches it. Provenance was also
missing, and `255:89` now says the sheet *"had come into the flat on the back of a household return, folded
in with the other papers that come in this building every month,"* which is how a washroom attendant's count
ends up in a head's drawer unread. `255:93` now says he **opened** it, so the contents are no longer known
three lines before they are read.

**5. Ch 259 measured one span two ways.** `:3` said *"for a fortnight"*; `:29` and `:63` said *"for sixteen
days."* The third of July to the nineteenth is **sixteen days**. `:3` now reads **"for sixteen days."** `:29`
and `:63` are untouched and are the anchor. `:121`'s *fortnight* is a **different** clock — the fourteen days
Ines's report sat in intake — and is correct.

**6. "Five months" was wrong three times over, and the table was bare a week before it could be.** `251:69`
had the kitchen table *"bare, which it had been for five months"*; `251:93` had the household eating
*"round a bare table"* on the eleventh; `254:75` said *"For five months that table has been where this house
could look at itself"*; `255:83` said the drawer had not been opened for a purpose *"in five months."* The
household's papers entered on **the twenty-second of March** and the drawer papers are dated the
twenty-seventh, the twenty-eighth and the first — **not five months, and not four.**

The number was the smaller half. **The table cannot be bare on the eleventh**, because `254:13` has the
broker's account sitting on it *"since the nineteenth of June"* and `254:117` has the broker carrying it out
of the kitchen on the fourteenth, and `254:81` has the table cleared at nine that morning. The bareness of
the table is this batch's loss beat. **It now happens on the fourteenth and on no earlier day.**

| Line | Now |
| --- | --- |
| 251:69 | the broker's account *"lay square in the middle of the kitchen table where it had lain since the nineteenth of June"* |
| 251:93 | *"a kitchen that ate standing up round a table with a broker's account still squared on one end of it"* |
| 254:17 | *"The table went from one sheet to four in about eleven seconds"* — it cannot go from nothing while holding the account |
| 254:75 | *"Since March that table has been where this house could look at itself"* |
| 254:107 | the closing parallel now reads: nothing has ever been laid over the rectangle, *"and the table in the room behind him had held this house on it since the twenty-second of March and was holding nothing at all"* — the old *"nothing had ever been laid on the table either"* contradicted its own chapter |
| 255:83 | *"and he had not opened that drawer for a purpose since March"* |

Untouched, and correct because all of them fall after the fourteenth: `255:3` *"The kitchen table had been
bare for a day"* · `256:77` *"the bare wood was bare"* · `258:7` · `259:119` *"the middle of nothing."*

**7. The household was counted three ways and one of the three was false.** `258:7` read *"Seven women on
the cut roll and one woman on no list with her door open behind her"* — eight in the room. But the roll of
seven **includes Ines Duarte, who has been out of the flat since the sixth, and excludes three of the women
standing in that kitchen**, who are on nothing at all. The room is eight women: **four on the cut roll
(Beatrix, Runa, Marguerite, Nadia) and four on nothing (Sun's pencil row, Petra, Wren, Agnete).** Tessa is at
the market and is not in it. `258:7` now reads **"Eight women in it, four of them on the cut roll and four
of them on nothing of any kind."** `258:101` said *"six women looking at him"* **one line after Petra went to
bed**; seven remain, and it now reads **"seven women."**

**`258:113` *"a building with eight women in it"*, `259:79` *"eight women hold between them"* and `259:111`
*"in a room of eight women"* were all correct and were left alone.** Eight is the number.

### 6.2 Two defects found in the same passages, not in the original findings

- **`256:109`** said the hatch *"had been in no return at all until a week ago and was now in three."* It went
  from no return to three **this morning**, when he signed the line. Now reads **"until this morning."**
- **`254:111`** counted *"Four papers"* in the drawer, but `255:87` finds a fifth lying flat against the back
  under the charge. `254:111` now reads **"Four papers were in there that he knew about"** — which is the
  point of 255, because he had opened that drawer twice by then and had not once seen the fifth. `255:99`
  now reads *"with four papers left in it, and a fifth was lying on the wood"*, so the arithmetic closes on
  both sides.

### 6.3 The minors

- **One commit, two names for the same range.** `outline/volume-06.md` §6 movement 2 named 261–270 **The
  Broker's Terms** — the volume's own title — while `workspace/volume-06/batch-0002/PROMPT.md` called it
  **The Head May Give Up A Room.** The outline now reads **The Head May Give Up A Room**, which is the name
  the prompt, the movement's content and the outline's own title bank all already use.
- **Panel frequency by volume is 10 / 4 / 1 / 1 / 0 / 0.** Defensible under `AGENTS.md` — *rare is better
  than constant* — but **two consecutive volumes with no panel at all is a choice that should be inherited
  on purpose rather than by drift.** Recorded here so Batch 0002 inherits the decision consciously. **No
  panel is due. Do not manufacture one.**
- **The Ch 250 repair in §1 is now independently confirmed.** The state files locked *"Volume 5's closure is
  now final"* on the authority of a file the batch wrote about itself. The independent pass re-derived
  Ch 250's arithmetic from its own dateline and its day counts at `:93` and the lock stands — **on a second
  reader's authority now, not the batch's own.**

### 6.4 Process notes — controller-side, recorded and not acted on

- **`state/phase-ledger.json` does not exist**, though `PHASE_SYSTEM.md` makes it the phase selector. The
  runner selects on `.done` markers instead, which works. Controller-owned file; this repair does not
  create it.
- **Volume 6 has no `volume-plan` phase.** Volumes 02–05 each have one. The batch prompt opened with
  *"outline/volume-06.md does not exist"* and the batch wrote the outline **after** its own ten chapters, so
  `outline/volume-06.md` §1–§5 is written fact derived from prose that already existed and §6 onward is a
  plan. **`PHASE_SYSTEM.md` says a writing phase never plans a volume. Movements 3–5 (271–300) are therefore
  unvalidated plan, and a later batch must treat them as a hypothesis, not as instruction.**
- **`scripts/novel_runner.sh:127` skips a volume-outline phase whose `outline/volume-NN.md` already exists.**
  A Volume 6 planning phase created now would cancel itself. Recorded; not created.

### 6.5 Gates re-run after the repair

```
files            10 (0251..0260). No chapter before 0251, none after 0260. 260 chapter files total.
titles           unique across ALL 260 -> NONE duplicated. Longest new title 34 chars, cap is 90.
wc 251-260       1888 / 2082 / 2013 / 2032 / 1845 / 1924 / 1970 / 1877 / 1885 / 2161
                 -> all ten inside 1,800-2,700.
system panels    0 in all ten. The batch still contains NO "[" character at all, so zero is STRUCTURAL
                 and not a regex artefact.
markup           bold 0 | ITALIC 1 (252:93) | blockquote 0 | table 0 | rule 0 | code 0. Unchanged.
nobody           1 in the batch -- chapter-0255.md:7, "a question nobody put to you", the canon phrase
                 from bible/terminology.md:185. The repair drafted a second occurrence at 256:5 and it was
                 cut on re-read, because the recorded ration is 1 and the second one was decoration.
                 Re-derive this gate after ANY edit, not only after a chapter is written.
8-word sentence scan   duplicated 8-word sentence openings inside the batch -> 0. Unchanged.
intra-batch      12-grams occurring in 3+ chapters -> 0. Unchanged.
vs all 260       12-grams shared with any other written chapter: 29 — 1/3/3/3/0/5/7/0/1/6, the SAME
                 figure the batch recorded in §3. The repair introduced no new shared phrasing.
exact-dup paras  6-word floor, batch and neighbours -> 0 inside Volume 6. The five hits the scan returns
                 are all inside Volume 5 and pre-date this batch.
```

### 6.6 What an independent reader says holds up

Ten titles, unique across 260, none restating scene, weather, hour, date or ages. Zero duplicated 8-word
sentences. Zero panels, structurally. `"There is no form for this"` remains 0 book-wide. Ages check out —
Sun 33 at `255:65`, Solveig Rask 42 at `253:9`, Isolde 39 against her character file. The decision to
write no scene is correct: 261 is immovable and a scene at 256 would give gaps of 7 and 5. **The
irreversible decision in Ch 256 holds and is untouched** — a plate number on a counted return, in his own
hand, cannot be got off, and Lode's line is still the best sentence in the batch: *you have bought a hatch
with the price of being findable.* Day arithmetic outside the count sheet is disciplined: Wren 25/26/27 at
258/259/260 from the 23rd of June, Petra 44/45 at 258/259 from the 4th of June, report 14 at 260 from the
6th of July.

**The failure mode this batch has, stated so Batch 0002 inherits it: dates were derived in one place and
carried to another.** Seven of the seven findings are that. Derive every date from the chapter's own
dateline at the moment you write the sentence, not from the chapter before.
