# Volume 6, Batch 0001 — Review and repair record (Chapters 251–260)

**Written by the batch that wrote the chapters. Not a review by a second reader.** The chapters were
checked by hand after the last edit and every figure in this file is the output of a command run against
the disk at that moment.

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
| 258, 259 | *"six women"*, *"six people"*, *"eight women"*, *"nine women at a kitchen table"* | room-counts re-derived or removed | Ines is absent; the count had drifted twice. |
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