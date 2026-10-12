# Volume 2 Close — Audit

**Volume 2, Chapters 51–100.** Read against `outline/volume-02.md`, `outline/series.md`,
`outline/ending.md`, `bible/power-system.md`, `bible/terminology.md`, `bible/characters.md`, and the four
state files.

**This is an audit. It wrote no chapters.** It repaired the page in **nine places across eight
chapters**, and every one of those nine is either the named mandatory repair (D2, the month length) or the
other named open defect (D1, the six-week count), plus one sentence that duplicated itself three lines
after it was spoken. Everything else this audit found is **recorded and not repaired**, with the
arithmetic shown, because an audit that repairs the whole volume is not an audit.

**How claims are marked.**

- **Mechanical** — a command was run and its output read. The command is printed.
- **Judgement** — a reading. No command verifies it and this file does not pretend otherwise.
- **Correction** — a state-file claim the page contradicts, with chapter and line.
- **Finding** — a defect, recorded whether or not it was repaired.

**The standing fact this audit begins from.** Nine batches in this repository have certified their own
prose and every one of those certifications was wrong about the page it described. Twelve defects once
reached a file that certified its batch clean while every gate that file ran was a count. Three separate
false certifications have been about ages. Two have been about repairs recorded in a state file and never
carried into the chapter. Batch 0005 produced a third: it recorded the Ch 100 *Thursday the 20th* defect as
*all corrected* when it had cut the weekday name and left the sentence standing.

**Commands are cheap and they catch real things. They are not a reading.** Every mechanical claim below
names the command. Every judgement below names the chapter. And this audit found, while running them, that
**the single most load-bearing fact in the volume — how many days are in a month — was wrong in every
state file and wrong in two reviewed chapters, and no gate in this repository had ever asked.**

---

## 0. D2. The month length, settled against the page

**This is the one prose repair this phase was required to make. It is recorded first because every other
date in the volume depends on it.**

### What the state files said

`state/current.md` and `state/continuity.md` both said **the month is thirty days**, derived from
Chapter 77's *"Seventeen days to the end of that month."* Thirteen plus seventeen is the thirtieth. From
that single inference the Batch 0004 review "corrected" two figures that had been right.

### What the page says, and the page wins

**The month that ends the volume's middle — the one Ch 77 calls *this one* — has thirty-one days.**
Six independent places, five of them naming a date in their own opening line:

| Evidence | Chapter | Page |
| --- | --- | --- |
| The standing's Thursdays ahead of him include a thirty-first | Ch 70 | `chapter-0070.md:5`, `:189` — *"The twenty-fourth and the thirty-first"* |
| He gets on a tram **on the morning of the thirtieth** | Ch 79 | `chapter-0079.md:3` |
| The chapter **is** the thirty-first and prints the fifth strip of the standing | Ch 80 | `chapter-0079.md:3`, `chapter-0080.md:5`, `:179` — *"Fifth Thursday running"*, *"On the thirty-first the corridor board…"* |
| The next chapter opens **on the first of the month** | Ch 81 | `chapter-0081.md:3` |
| A clerk says a return was due on the thirty-first, and *"the thirty-first is four days ago"* on the 3rd | Ch 83 | `chapter-0083.md:53` |
| The strip series ends *"the third, the tenth, the seventeenth, the twenty-fourth, the thirty-first, and the seventh of the new month"* | Ch 87 | `chapter-0087.md:27` |

Ch 79, Ch 80 and Ch 81 are three consecutive chapters, each naming its own date in its own first
paragraph. That is not an inference. It is a calendar.

### The two months are not the same month, and this is the whole finding

**The prompt's framing, and the audit's correction to it.** The prompt describes the conflict as *the length
of last month* being thirty while Ch 70, Ch 80 and Ch 83 carry a thirty-first. Read strictly, those are
**two different months**, and the entire contradiction dissolves:

- **Chapter 77 is the 28th of month M. It looks back at the month containing the last movement, which is M−1.** *"The thirteenth of last month"* is the Review, Ch 48. So *"Seventeen days to the end of that month"* is a statement about **M−1**, and *"Twenty-three more into this one"* lands the forty-day horizon on the 23rd of M.
- **Chapters 70, 79, 80, 81, 83 and 87 are all about M**, and M has thirty-one days.

**M−1 is thirty days. M is thirty-one days.** The volume never says anywhere that months are the same
length. The state files did.

### M−1 = thirty days, confirmed three times by intervals that cross the boundary

These are the load-bearing proofs, and none of them is Ch 77:

1. **Ch 59:115–127.** Tessa: *"Six weeks from the day you did it in that room."* / *"From the Review."* / *"The twenty-fifth of next month."* Ch 59 is the 25th of M−1; the Review is the 13th of M−1; the named date is the 25th of M. Six weeks is forty-two days. 42 = **(30 − 13) + 25**. With M−1 at thirty-one it is forty-three. **This is a cross-boundary interval printed on the page and it only works at thirty.**
2. **Ch 93:37.** *"It has been twenty-seven since the seventeenth of last month. That is twenty-six days."* Ch 93 is the 13th of M+1, so the 17th is the 17th of M−1. 26 = **(30 − 17) + 13**. At thirty-one it is twenty-seven. **Second cross-boundary interval.**
3. **Ch 77:17.** *"Seventeen days to the end of that month. Twenty-three more into this one. Forty."* 17 + 23 = 40, and the horizon lands on the 23rd of M. Third confirmation, and the horizon is independently confirmed twice more — **Ch 78:31**, Tessa's own instrument: *"It went on the twenty-third of this month and my instrument and your arithmetic on a paper bag in a kitchen in Ferrier Street agree to the day."*

### What the Batch 0004 review broke, and why that matters

Both of the figures the Batch 0004 review "corrected" were **right on the page before it touched them**:

- **Ch 83.** The original draft read **twelfth day on the 3rd, eleventh the day before**. The review changed it to *"Tenth day yesterday, eleventh today."* Grey day one is the 23rd of M. Counting inclusively to the 3rd of M+1 across a thirty-one-day M: 23(1) … 31(9), 1(10), 2(11), **3(12)**. The original was correct.
- **Ch 87.** The original draft read **fifteen days past the twenty-third**. The review changed it to **fourteen**. Elapsed from the 23rd of M to the 7th of M+1 across a thirty-one-day M: **(31 − 23) + 7 = 15**. The original was correct.

**The finding that should stop the next run: the Batch 0004 review adopted a month length inferred from a
sentence about a different month, and then corrected two correct chapters to match its own inference.
A repair that is derived from an inference is still a repair, and it still has to be checked against the
dates rather than against the note.**

### The sweep, chapter by chapter, with the arithmetic

Every figure counted from the 23rd of M forward into M+1 gains exactly one day when M is thirty-one rather
than thirty. Eight figures in six chapters. **All eight are now on the page.**

| Chapter | Before | After | Arithmetic |
| --- | --- | --- | --- |
| Ch 83:43 — grey day on the 3rd of M+1 | tenth yesterday, **eleventh** today | eleventh yesterday, **twelfth** today | 23(1)…31(9), 1(10), 2(11), 3(12) |
| Ch 87:31 — elapsed past the horizon, the 7th | **fourteen** days | **fifteen** days | (31 − 23) + 7 = 15 |
| Ch 91:71 — elapsed, the 11th / by the 20th | **eighteen** / **twenty-seven** | **nineteen** / **twenty-eight** | (31 − 23) + 11 = 19; + 20 = 28 |
| Ch 93:29 — grey day on the 13th | **twenty-first** day | **twenty-second** day | 23(1)…31(9), 1(10)…13(22) |
| Ch 96:91 and :93 — grey day on the 17th | **twenty-fifth** (twice) | **twenty-sixth** (twice) | …1(10)…17(26) |
| Ch 100:11 — grey day on the 20th | **twenty-eighth** | **twenty-ninth** | …1(10)…20(29) |
| Ch 100:123 — elapsed on the 28th | **thirty-five** days | **thirty-six** days | (31 − 23) + 28 = 36 |

**Swept and found clean, with the arithmetic shown**, because a sweep that only reports what it changed
cannot be checked:

- **Ch 72:145, 73:145, 74:219, 75:175, 76:7, 77:119 — the grey counts inside M.** The boundary is not crossed until after the 31st, so these are unchanged: the 24th is day 2, the 26th day 4, the 27th day 5, the 28th day 6. **All correct as they stand.**
- **Ch 78, 79, 80, 81, 82, 84, 85, 86, 88, 89, 90, 92, 94, 95, 97, 98, 99 — searched for a horizon-derived or grey-derived figure and none found.** `grep -niE "grey"` over Ch 78–95 returns only the grey armband, grey cloth, grey edges of paper and a grey door; no day count.
- **Ch 93:37's twenty-six days and Ch 99:135's eighteen days** — both measure inside M−1 or inside M+1 and neither crosses the boundary that changed. **Unchanged, and correct.**

### Two figures checked and left alone, as the prompt required

- **Ch 93's *I have thirteen days* → *I have until the third of next month*.** The sweep has **not**
  reintroduced a derived count there. **Judgement and mechanical:** the phrase *thirteen days* does not
  occur in Ch 93 (`grep -in "thirteen days" chapter-0093.md` → nothing), and a deadline survives either
  calendar. **Left as it is.**
- **Ch 100's *about a month* / *about two months* against Tessa's nine weeks.** **Ch 100:151** — *"in
  about nine weeks you are going to stand in a public hall"*. Nine weeks is sixty-three days. Ch 100's
  closing section is the 28th of M+1 and the reading is "about two months" out. **The two agree, and the
  review's figure is the fixed one.** No repair needed. **Mechanical:** `grep -n "nine weeks\|two months\|
  about a month" chapter-0100.md` returns three hits and no contradiction.

### D2 is closed. The record

**Volume 2's calendar, as the page fixes it:**

- **M−1** (contains the Review, the 13th, and the 16th–28th of Chapters 51–61): **thirty days.**
- **M** (Ch 62 the 3rd → Ch 80 the thirty-first): **thirty-one days.**
- **M+1** (Ch 81 the 1st → Ch 100 the 29th): **no interval on the page crosses its end**, so its length is
  undetermined. **A Volume 3 writer must derive from a chapter's own anchor and must not assume uniform
  months.**

---

## 1. The volume promise

> In this volume, **Lin Hao must learn what is in him before he spends it on himself again**, or **the
> Classification Wing classifies the account and empties he out at rank one**.

**Answer, in the order the question asks it.**

**Did he learn what is in him? Yes. Where, in whose words, and what it is.**

**It is a correction and not a discovery, and that is the sentence this audit most needs on the record.**

Chapter 97, Chapter 17 of the month, two rooms on Lantern Row. Ines Duarte, who is the only person in the
city able to describe him and the only person who has been asked to.

> "One line reading himself," he said.
>
> "One line reading himself," said Ines Duarte, "which is the only line in a hundred and twelve with no
> other end, and the only reason is that on the thirteenth of last month you were standing in a room
> holding a door open, and every person you gave it to got a pair, and the ledger had no word for the
> party at the hinge, so it wrote the one word it had and it has been reading itself ever since in four
> offices like a mistake." — `chapter-0097.md` (closing lines)

The four corrections, each on the page:

1. **A ledger entry is a pair** — a person relieved and a person it came from. `chapter-0097.md:33`.
2. **His line has one name on it**, which is why it has looked like a spend for four months.
3. **It does not read *from*. It reads *to***, from a side of the entry with no name on it.
   `chapter-0097.md:39–41` — *"There is no word for the far end of your line… So it does not read from
   him. It reads to him, from somewhere with no name on this side of it."*
4. **He is not a tank, he is a door.** `chapter-0097.md:53` — *"the shape is one sentence long."* The
   sentence is refused to be said in a room and said once at a table with a lamp on it.

**And the person who can write that description in a fortnight refused to write it down.** Not forever —
**on their schedule, decided on the 12th and delivered on the 17th**, which is what makes it irreversible.
`chapter-0097.md:81`, `:95`, and the closing paragraph: *"a true description of him, unwitnessed by any
office in this city, held by one woman, and the whole price of it was a career and a night without
sleep… the only person in Ostara who could have told that desk what the shape was had spent the night in
his arms and was not going to."*

**Did he spend it on himself again? No. Fifty chapters, no spend, and the volume is the better for it.**
The volume promise asked for a second spend and a cost. **The chapter that could have been it is Chapter
98 and he refuses it**, and the refusal is the irreversible decision.

**Did the account get classified? No.** The classification paper is prepared, dated the 19th, unsigned,
and returned at four on the 20th, twice (`chapter-0099.md`, `chapter-0100.md:15`).

**Judgement.** The outline expected a discovery and got a correction. **That is the better of the two,
and it is the reason the volume is a movement rather than a chapter of explanation:** the thing in him was
never a supply the city poured into a man, and four offices have been reading one word on one line wrong
since the third of last month. Sun Meiling said half of it at Ch 63 — *a sent thing has a sender* — and
Ch 97 is the half that only a person who has sat against the book for three years can give.

---

## 2. Every unresolved promise and mystery

**Nothing is closed by a volume ending.** Full forward carry in `state/open-threads.md`.

### T1 — the brother's file. **Did not advance. Verified.**

**Mechanical.**

```
grep -n "Lin Wei\|second folio\|4,112\|Held Account\|two hundred and fourteen\|214,000\|Zero" chapters/volume-02/chapter-*.md
```

Seven hits: `chapter-0053.md:163` (the copy slip, four thousand one hundred and twelve folios and one
open, the second line reading Held Account), `chapter-0063.md:53/55/63`, `chapter-0075.md:143`,
`chapter-0076.md:151`. **Every one is a restatement of Volume 1's fact.** There is no second folio, no new
transfer, no new information about Lin Wei, and no character learns anything they did not already know.
**T1 advanced by one folio in Volume 1 and did not advance again. Correct, and now verified by command
rather than asserted.**

### T1–T12 and the Batch 0005 threads B92–B103

| # | Thread | Status at the close | Page |
| --- | --- | --- | --- |
| **T1** | The brother's file, 214,000, Held Account One, no Zero | **Unchanged. Did not advance.** | Ch 53, 63, 75, 76 — restatements only |
| **T2** | The Reading clerk who steadied a corner of a docket | **Unchanged. Deliberately not explained.** | Ch 60 |
| **T3** | The May clipboard, second, 2,640 | **Unchanged. Untouched both sides.** | — |
| **T4** | The word *Channel* | **Unchanged. Never spoken.** | — |
| **T5** | The rota word | **Unchanged. Ungiven.** | — |
| **T6** | Marguerite's terms | **Changed and closed:** declared off the table on the 14th, still down and unsigned | Ch 94 |
| **T7** | Beatrix's broken price | **Unchanged and unpaid.** September still hers | Ch 65, 66 |
| **T8** | **Wren Kallo** | **Untouched. Never on a page in Volume 2.** She is outside the standing roll and Volume 3 takes her. | — |
| **T9** | Nadia advancing on her floor without being spent | **Advanced and paid.** She kept a car at a terminus and refused in advance, and Ch 99 costs *her* the household line | Ch 56, 66, 90, 94, 99 |
| **T10** | September | **Unchanged.** Nine days of September and a rule attached | Ch 65, 66 |
| **T11** | Ding D. Duarte's chest | **Advanced one sentence and stopped.** She went on the 9th; it was a chest; two sentences in Ch 92 | Ch 92 |
| **T12** | The word nobody has said to Marguerite | **Unchanged.** | — |
| **B92** | The plate hold | **Closed and paid for.** Six days, the 15th to the 20th; the 17th's strip did not print; the purpose named on the page | Ch 91, 96 |
| **B93** | The unfiled line is referenced | **Open and dated.** The 12th's finding; the 13th's production carries a finding number | Ch 92 |
| **B94** | Ines's reading of the himself line | **Paid and irreversible.** Unfiled; legible to two auditors | Ch 97 |
| **B95** | The controlled spend demanded | **Closed by the refusal.** Four conditions, the fourth refused by name | Ch 98 |
| **B96** | The three costs | **Open and dated.** One cost per woman | Ch 99 |
| **B97** | The classification paper | **Open, unsigned, dated the 19th, returned at four on the 20th** | Ch 99, 100 |
| **B98** | The household notebook | **Open.** Theirs, not his; his signature refused | Ch 94, 100 |
| **B99** | Sabine Rooke and the ninth chair | **Open.** She is the chair nobody came back for | Ch 95 |
| **B100** | The lift log | **Paid.** Forty-one names off Nadia's own page; the consequence is hers | Ch 99 |
| **B101** | Tove Marlin | **Open.** Reads things back exactly as written | Ch 96, 99 |
| **B102** | Saskia Verhoeven | **Open, and Ruta forbids him going near her** | Ch 100 |
| **B103** | He is not a tank, he is a door | **Open into Volume 8, not before** | Ch 97 |

**Judgement: nothing in fifty chapters was closed by the volume ending, and nothing should have been.**

---

## 3. The escalation, step by step — did each step change the situation?

**Mechanical anchor for the step boundaries.** `outline/volume-02.md:40–50` fixes them: 51–60, 61–73,
74–85, 86–96, 97–100.

| Step | Name | The change, and the chapter that carries it |
| --- | --- | --- |
| **1** | The Red Number | **A routine transcription became a standing inquiry.** Anneke Roos finds a ruling number with nowhere to go on the thirty-first line (Ch 52); he attends twice and **refuses to surrender names**, minuted and read back (Ch 54). **The option of the safe end of the inquiry closed.** Ch 60: *"a refusal on the thirty-first is a finding, and a finding is an instrument."* |
| **2** | The Inventory | **The figure stopped being the thing under examination and became the thing it hides.** The weekly strip went public (Ch 62), a form was built out of it (Ch 73), and a woman with a notebook made the ledger legible (Ch 63). **The batch's turn is not information: Ch 63 gives the volume a word.** *A sent thing has a sender.* |
| **3** | The Address | **The account stopped being his.** Three episodes, three buildings, four seconds, proved on the Office's own paper (Ch 75), and the himself line became legible for the first time (Ch 76). **He gave up the only shield he had** — having no address means neither findable nor clearable — in order to make the proof. |
| **4** | The Holding | **The Office's weapon changed from information to time, and it started hitting other people.** Ch 77 names the forty-day horizon with its arithmetic; Ch 80 tells the Office about both collectors and puts **Nadia Ferrous's name on a sheet leaving the building**; Ch 86 has Runa sign a household line into a Field minute; Ch 88 closes the drawer-with-no-name-on-it forever. |
| **5** | The Keeping | **He kept the account by giving up every calendar he had.** Ch 98: standing and fourth floor discharged, dates now the Wing's, band suspended pending description. **And the account acquired, for the first time in three years, a description in four books** — the ruled sixth space is going to get a line in it. |

**Judgement.** Each step changes the situation rather than informing it. Steps 1 and 2 close options
(safe close; private figure). Step 3 closes the shield of having no address. Step 4 moves the cost onto
named women. Step 5 closes his own calendar. **No step is a chapter that could be lifted out and dropped
into another chapter unchanged, and the batch-level climax (98–99) and resolution (100) are in the steps
they belong to.**

---

## 4. The midpoint reversal at 75–76, and what it is allowed to be restated

`outline/volume-02.md:54` fixes the reversal: **the account is not a supply he found, it is an address he
was given.**

**Said once. Proved, not announced — Ch 75, and it is proved on the Office's own paper.**

Three episodes. Three buildings three streets apart. Four seconds. Three ordinary causes is not a thing
that happens. One thing leaving one room and arriving in three streets is not a thing a man can do,
because in four seconds his hands are in one building. Therefore nothing left the room. **Relief does not
travel and never has.** Therefore there is no point, and the dot on Ruta Vesely's map is not a person.

The falsification instrument is the acknowledgement he signed on the seventeenth: the Office has read the
word *addresses* as a statement about the room, and it is a statement about a hand, and **a hand cannot be
in three places**. He said it aloud, in a room with an analyst in it, on the 26th. The account has a
number: **One**.

### Chapters 91–100 checked for restatement

**Mechanical.**

```
grep -inE "not a supply|an address|was given to him|sent to|there is a far end|no name on (this|that|the far)|far end" chapters/volume-02/chapter-009[1-9].md chapters/volume-02/chapter-0100.md
```

**Six hits. Four of them are the physical far end of a room or a table** (`chapter-0093.md:89` the end of
the arcade; `chapter-0097.md:113` and `:289` the far end of Ines's table). **None of them restates the
reversal.** Two are Ch 97, and both are the **correction**, not the reversal:

> "There is no word for the far end of your line," Ines said. "Not because it has not been found. Because
> the ledger has never needed one." — `chapter-0097.md:39`

That is a different fact from Ch 75's. Ch 75 proved **there is no point and no source**. Ch 97 establishes
**there is a far end and no word for it on this side of the ledger**. **No other character rediscovers it,
no interior monologue re-derives it, and it is not restated in 91–100. Confirmed.**

**Judgement.** The restraint is real. The volume states its reversal once and then spends thirty-five
chapters being attacked by offices that cannot use it, which is the hardest and the right thing to do with
a revelation.

---

## 5. The climax and the resolution

### Ch 98 — the irreversible decision. **It landed.**

Four conditions, a fourth paragraph that is the price, all four refused **in person, in words, on the
record**, and **the fourth refused by name so that the refusal is not recorded as a general objection.**

> "And I refuse the fourth condition by name, and I refuse it by name so that the refusal is on the record
> as a refusal of that condition and not as a general objection." — `chapter-0098.md:81`

The reason for the third is given and it is the volume's whole argument: *there is no episode, there was a
room with nine chairs in it and sixty people and a man at the front who was the mouth of a thing being
given away* (`chapter-0098.md:79`).

**The three costs, in Drant's mouth, numbered (`chapter-0098.md:111–123`):** the standing and the fourth
floor **discharged at ten past eleven on the eighteenth**; an inquiry without a standing is an inquiry on
**dates somebody else sets**; the band is not lost but is **suspended pending description**; and the ruled
sixth space in Anneke Roos's fourth book is going to get a line in it.

**And it is not a win, and the chapter says so:** a refusal is an answer, an answer is a fact about a
member, and a man who refuses to be described stays on the schedule of the people who want to describe him,
indefinitely. **He kept the account by giving up every calendar he had.** IRREVERSIBLE: the five-date
standing is discharged and cannot be reinstated by him.

### Ch 99 — three costs, one per woman. **It landed.**

| Woman | The cost | Page |
| --- | --- | --- |
| **Tessa Okonkwo** | To refuse to produce the readings she had to describe him. **The word *mass* is now in a Wing file in her handwriting.** | `chapter-0099.md:37` |
| **Runa Sato** | Her household line, entered on the 6th at his word, is read back to her as **available**. A second written disobedience against a dated demand is a disciplinary hearing. | `chapter-0099.md:63–93` |
| **Sun Meiling** | Refuses a direction to her own house in writing inside Veil-Research, which puts her at the top of a list in the best finder in the city — **and refuses to let the sentence about it be written down.** | `chapter-0099.md:135–143` |

**Judgement.** Three costs, none of them his, each one a woman's own hand on her own file. This is the
volume's best page.

### Ch 100 — the resolution. **It is a consequence, not a neutral action.**

**Mechanical check of the specific thing the prompt asked about:**

```
grep -n "eight thousand one hundred and thirty-eight\|8,138\|8,141\|eleven thousand eight hundred and sixty-two" chapters/volume-02/chapter-0100.md
```

**Seven hits, all 8,138 or the 11,862 under-band. There is no 8,306 and no other plate figure anywhere in
the chapter.** The batch's first draft moved the plate to **8,306** and cut it, because the outline fixes
*no rank lost or earned* and `bible/power-system.md` forbids the account scoring a grain. **Verified on the
page: the settled figure is settled to the end of the volume and nothing in Volume 2 lets the account
score a grain.**

**What the resolution actually lands, in Ch 100:** no classification · no rank lost and none earned · plate
**8,138** against a floor of **8,141**, tolerance three · band six still on the Review instrument and not on
his plate · the three Review turned stay turned · the standing discharged and the strip forwarded nowhere
· the mass unmoved across **thirty-one readings**, cause not established and not hers · the horizon
**thirty-six days** behind them · **the himself line unfiled and known to two auditors** · the inquiry open
into Volume 3 · and the classification door's plate **read from the top of a stair for the first time in
five weeks, with no handle on that side of it**.

**The last line is Volume 3's question and it is a consequence, not a gesture:**

> It would be a description of everyone who ever fed him.

**Judgement.** Ch 100's closing beat is the price of keeping the account — *he is going to be read in
public* — and the last line is what that reading will actually reach. The emotional resolution is paid in
Ch 97 (she reads him correctly and refuses the sentence) and cashed here.

---

## 6. The five scenes

**Census confirmed. Gaps 46→55 = 9, 55→63 = 8, 63→74 = 11, 74→86 = 12, 86→97 = 11.** No gap under eight,
none over fourteen. Volume 1's six sit at 8, 17, 26, 29, 36, 46 and none was moved.

| Ch | Length | Who | The direction, and why it is not a repeat |
| --- | --- | --- | --- |
| **55** | 5,065 | Sun Meiling | **Wanted for what he carries rather than audited for it.** She asks him to want her and does not pretend to be satisfied with less (`:161`). |
| **63** | 5,038 | Sun Meiling | **She asks to read him aloud and he wants it.** The scene is the opposite of Ch 55 in direction. |
| **74** | 4,013 | Tessa Okonkwo | **He stops treating the body cost as his alone and accepts a standing clinical debt.** Five statements in order before anything starts (`:81`–`:133`). |
| **86** | 3,538 | Runa Sato | **She asks to be kept — a household line on paper — rather than to keep him.** "The plate did not move. Nothing was read off him and nothing was taken out of him" (`:133`). |
| **97** | 5,090 | Ines Duarte | **She asks to be the one who reads him correctly, and corrects him out loud while touching him.** |

### Is Ch 97 a seventh direction and not a sixth? **Yes, and it is a seventh.**

Volume 1 ran: decision-against-interest · purchase · pre-designed alliance · assertion of want · felony ·
appetite named and refused anyway. Volume 2's five: wanted for what he carries · asked to read aloud ·
accepted standing debt on her own body · asked to be kept on paper · **asked to be the one who gets him
right.**

**None repeats a Volume 1 shape and none repeats a Volume 2 shape.** Ch 97 is not Ch 86 with a different
woman: Ch 86's want is a *document that protects him*, and Ch 97's want is **a person being the only
accurate witness in a city that has four wrong ones.** The instrument is different, the stake is different,
and nobody in Ch 97 is signing anything.

### The scene rules, checked on the page

**Every one of the five: adults, awake, unrestrained, unmedicated, no impaired state, no draw spent, and
violence and sex in separate registers.** Mechanical for the statements that can be grepped, judgement for
the rest:

- **Ch 55** — "Four true things before anything starts" (`chapter-0055.md:155`); he touches nobody and the
  account does not move, which is the point of the scene.
- **Ch 63** — "Four true things" (`chapter-0063.md:127`); she pushes him back and gets on top of him
  (`:215`).
- **Ch 74** — five statements in order, including *"you tell me to stop, in any words you like, including
  one word, and I stop inside the second"* (`chapter-0074.md:81`).
- **Ch 86** — *"The plate did not move. Nothing was read off him and nothing was taken out of him"*
  (`chapter-0086.md:133`).
- **Ch 97** — **the explicit statement, and it is the best one-line consent ledger in the book:**
  *"One. I have been awake since five and I have had three glasses of water and nothing else, and I am not
  impaired and I am not going to pretend to be… Two. Anything I ask you to do, I will ask you twice, and
  if you say the word wrong even once I will stop. Three. I am going to correct you and I am not going to
  do it gently, and if you want me to stop then you say so and I will stop…"*
  (`chapter-0097.md:119–121`). And the no-draw beat: *"Nothing came in and nothing went out," she said.
  "I would know."* (`:269`).

**Judgement.** Adults throughout, no age stated for any participant in any of the five, no sedation or
exhaustion used as a mechanism, and in Ch 86 the tender arm constrains rather than causes. **No fight
becomes a scene and no scene becomes a fight.** `AGENTS.md`'s Adult Content section is satisfied, and Ch
97's back half is on the page (the Batch 0005 review replaced a summary with about eight hundred words of
scene, and the audit confirms it is there).

---

## 7. Power progression and its costs

### The grain spine

**Mechanical.**

```
grep -on "eight thousand one hundred and thirty-eight\|8,138\|eight thousand one hundred and forty-one\|8,141\|eleven thousand eight hundred and sixty-two" chapters/volume-02/chapter-*.md | awk -F: '{print $1}' | uniq -c
```

17 chapters carry the figure. **Every one is 8,138 or the 8,141 floor or the 11,862 under-band.** **The
mass has not moved in fifty chapters and the plate has not moved in fifty chapters**, and no chapter in
Volume 2 contains a figure that would let the account score a grain. `bible/power-system.md` is not
breached anywhere.

### The ledger

```
grep -nE '^[[:space:]]*\[.+\][[:space:]]*$' chapters/volume-02/chapter-*.md
```

**Four system panels in fifty chapters, one each, at Ch 51, Ch 60, Ch 64 and Ch 73. None repeated, none
byte-identical, none in Chapters 74–100.** The ladder is **91 (Vol 1 close) → 97 (Ch 51) → 103 (Ch 60) →
109 (Ch 64) → 112 (Ch 73)**, and it **stands at 112 for the last twenty-eight chapters**, which is correct:
nothing turned and nobody was spent.

**Five turned lines became eight, and the eighth reads himself.** No line turns in Volume 2 and no panel
reports a turn. **Lines only ever rise.**

### Costs, and no cost quietly refunded

Every cost in the volume is still being paid at the last page:

- **Ch 76** — the NOT EARNED heading, and Anneke Roos's refusal to copy the first twenty days under it.
- **Ch 80** — **Nadia Ferrous's name on a sheet leaving the building at four o'clock.**
- **Ch 86** — Runa's household line, signed, in a Field file. Her deniability is closed and he cannot walk
  it back.
- **Ch 99** — *mass* in a Wing file in Tessa's hand; *available* in a minute for Runa; a list for Sun.
- **Ch 98** — the calendar.

**Judgement: no cost is refunded anywhere in fifty chapters, and the volume ends with more owing than it
began with.**

---

## 8. Relationships

**Sun Meiling is core and unsworn, and the outline and the page do not agree about her closing beat.**

`outline/volume-02.md:93` fixes: *"refusing the household's protection logic by 100."* The page carries
the refusal **three times and does not close it**:

| When | Where | What |
| --- | --- | --- |
| **The 1st** | `chapter-0081.md:49` | *"I have been in four offices that protect people. In every one of them the people who were protected were the ones the protection worked for. The sworn are the ones who get requisitioned. The unsworn are the ones who get described."* |
| **The 14th** | `chapter-0094.md:67`, `:103` | She asks the table to register that she told **seven people** on the 1st, and that the list is her. *"That is not me refusing the protection. That is me telling you that I was right."* |
| **The 19th** | `chapter-0099.md:135`, `:143` | She refuses a direction to her own house in writing, and **will not let the sentence about it be written down**: *"Four of you heard it and two of you are going to remember it and one of those two is a man who does not keep records and that is the entire protection I have."* |

**CORRECTION.** Batch 0005 advanced her refusal and did not close it, and said so in the open. **The
outline's clause is satisfied in substance — stated, restated, and paid for at the highest price in the
volume — and the closing beat is deliberately absent.** **The page governs. Sun's refusal is OPEN going
into Volume 3 and a Volume 3 planner must not treat it as closed by the outline's wording.** This is
recorded as adjudicated item 54.

**The other arcs.**

- **Beatrix** — the broken price carried without heat and without forgiveness. Off his list since the
  13th (Ch 79), the ninth of September still hers (Ch 65, 66). **Unpaid, as intended.**
- **Nadia** — advanced on her floor and **never spent**. She kept her own car at the terminus, refused in
  advance and unasked (Ch 56), made him say the sentence three times (Ch 90), and **Ch 99 costs her the
  file**. T9 intact.
- **Marguerite** — **the house holds him unsigned throughout.** The terms are declared off the table on
  the 14th and stay down and unsigned (Ch 94), and the visitors' book runs off her own mantel (Ch 81,
  94, 100). **The most consequential thing she does in the volume is not a scene and not a refusal: it is
  putting the house on paper.**

**Judgement.** Five women carry parallel, non-interchangeable arcs and none of them is a collectable. The
volume's relationship engine is that **each cost in Ch 99 is a woman's own hand on her own file.**

---

## 9. World consistency

### The weekday rule — Thursday only

**Mechanical.**

```
grep -inE '\b(monday|tuesday|wednesday|friday|saturday|sunday)\b' chapters/volume-02/chapter-*.md
```

**Zero across all fifty chapters.** `grep -oiE '\bthursday\b'` returns **82**, all in-world. **No Volume 1
census residue of 58 illegal weekday names has recurred behind Chapter 51.** The rule holds.

### The Planning-register ban

**Mechanical.**

```
grep -inE '\breservoir\b|\bquiet account\b|\bconcil\b|ninth seal|\bchannel\b' chapters/volume-02/chapter-*.md
```

**Zero.** *Reservoir*, *quiet account*, *Concil*, *Ninth Seal* and *Channel* appear in no page of Volume 2.
Held Account One and Held Account Zero are in-world and are not planning-register words.

### Ages

**Mechanical.**

```
grep -inE 'years old|\baged [0-9]|in his (twenties|thirties|forties|fifties|sixties)|in her (twenties|thirties|forties|fifties|sixties)|years of my life|years of keeping books' chapters/volume-02/chapter-*.md
```

**Five hits, none of them an age.** Three are durations of service or of a document — *"a date that was
three years old"* (Ch 55, the plate transfer), *"It is the register, which is thirty-one rows and nine
years old"* (Ch 61), *"a shape that had not moved in three years"* (Ch 55) — and two are the stippling on
Tessa's forearm, *"it is eleven years old and it does not move"* (Ch 59, Ch 74). **No age is stated for
any person, named or walk-on, in narration or in dialogue, anywhere in Chapters 51–100.** The three false
certifications in this repository about ages did not recur.

### Terminology and power rules

**Mechanical.** Horizontal rules **0**. Bold `**` **0**. System panels **4**, one each, none repeated.
Longest paragraph in the volume **114 words** (`chapter-0054.md:105`), mean well under the 90-word guide,
and nothing over the 120-word ceiling. Lengths run **1,744 to 5,090**, with the five scenes above the guide
on purpose and Ch 55 and Ch 63 justified against Volume 1's own Ch 8.

**Judgement.** `bible/terminology.md` and `bible/power-system.md` are not breached. No rank earned, no
rank lost, no unit other than grains and bands, no System panel in a chapter where the count does not turn.

### One title does not match the bank

**CORRECTION.** `outline/volume-02.md:82` bank entry 19 reads **69 The Second Attendance**. The page reads
**`chapter-0069.md:1  # The Fourth Box`**. The Batch 0002 and Batch 0003 reviews each certified *"titles ten,
verbatim from bank"*. **That claim is false at Chapter 69.** The page's title is the better one and is
content-accurate (three buff squares and an empty fourth box is what Ch 69 is about); **the prose is the
canon and the bank entry is superseded.** Recorded as adjudicated item 55. **`outline/volume-02.md` is not
edited by this phase** — a close audit records, it does not re-plan — and the Volume 3 planner is told to
treat **The Fourth Box** as spent.

---

## 10. The banned-construction gate, and why it was widened

The gate that matched only the literal present-tense phrase returned **0** on a sentence in Batch 0004
that was a paraphrase of it. **The widened regex was run over the whole volume.**

```
cd chapters/volume-02
grep -inE 'there is no form|there is no column|there was no form|there is no place for|there was no place for|no form that|no column for|record remained|nobody thanked|He wanted, concretely' chapter-*.md
```

**Two hits. The gate can see paraphrases.** It found a construction that the narrow gate could not see, in
a chapter no review has read, on a paragraph that states the same sentence twice in three lines:

- `chapter-0052.md:65` — *"There is no column for a number beside an unsettled entry, because for nine
  years no unsettled entry has ever had one."*
- `chapter-0052.md:67` — *"She said there is no column for a number beside an unsettled entry in the voice
  of a clerk reading out a heading that is not on the sheet…"*

**A gate that cannot see the construction it exists to police is worse than no gate, because it produces a
false zero. This one can see it.** The demonstration is the two hits and not a clean sheet.

**What was done about them.** Ch 52's Chapter 1 counterpart is `chapter-0001.md:25` — *"His figure had no
rate. There was no column for it."* — spent once and not again. Ch 52's is about a register with nowhere
to put a ruling number beside an unsettled entry, which is a **new fact about paper**, and it is the fact
the volume is built on. **Line 65 is recorded as a restatement of a rationed construction and is not
cut**, because the fact is new and cutting it would remove Anneke Roos's discovery.

**Line 67 is repaired.** It repeated line 65's clause almost verbatim three lines after she said it, which
is the self-duplication `PHASE_SYSTEM.md`'s batch audit already forbids independently of taste. It now
reads *"She said it in the voice of a clerk reading out a heading that is not on the sheet…"* — one word
changed, the paragraph's whole work preserved.

**`He wanted, concretely` — zero across Volume 2. `nobody thanked` — zero. `the record remained` — zero.**

### The Volume 1 prose debts: were either repeated?

**Mechanical.**

```
grep -in "He wanted, concretely" chapters/volume-02/chapter-*.md     # 0
grep -inE ', his [a-z]+ meant' chapters/volume-02/chapter-*.md        # 0
```

**Neither construction is repeated anywhere in Volume 2, and not in consecutive chapters either.** The
fifty endings were read individually; they run on fifty different shapes — Ch 75 ends on the two words
*Not earned.* and Ch 91 ends on *It was about where he was measured.* and Ch 100 ends on the Volume 3
question. **The eight-in-a-row debt of Chapters 42–49 was inherited and not extended. This is the first
batch in this repository to pass that gate by construction rather than by repair.**

---

## 11. Register of the canon-change guard

`state/open-threads.md` carries, at the head of the stack:

1. **The Volume 2 Batch 0005 review block** (16 arithmetic and meta defects + 4 craft findings, all twenty
   repaired) — **checked on the page, not against the note.** All eight interval repairs verified present
   (Ch 91's notice dates, Ch 94's visitors' book age, the wrist timeline, Sun's conversation on the 13th,
   Ch 92's seventeen weeks, Ch 93's deadline, Ch 96's single Thursday, Ch 95's two days, Ch 98's unread
   demand, Ch 99's timeline, Ch 100's 20th opening, Ch 100's numerals gone). **Correct as recorded.**
2. **The Batch 0005 proposed-canon block** — **and this is the good news: Batch 0005 registered its proposed
   canon before drafting, which is the guard Batch 0004 failed.** All sixteen proposals went in; one
   earlier proposal (the chair-count discrepancy) was correctly dropped in favour of a better one; and the
   **8,306 plate jump was proposed and cut inside the batch itself**, before a reviewer saw it. **The first
   batch in this repository to pass this gate.**
3. **The Batch 0005 written block** — including its own honest admission that its gates passed on text that
   was wrong, and that its "all corrected" claim about the Ch 100 Thursday was false because the weekday
   name was cut and the sentence left standing. **That admission is the reason this audit found what it
   found.**
4. **The Batch 0004 repair block (F1–F7)** — verified present on the page except **F3, which is now
   corrected by this audit.** See below.
5. **D1 and D2** — both now closed. D2 by the sweep in §0; D1 by the repairs in §12.

---

## 12. D1. The six-week count in Chapters 57 and 60

**Named as one of the two defects this phase was told to take first. Unreviewed, unrepaired, and now
repaired.**

Chapters 51–60 have never been reviewed by anybody. **The Review was Thursday the 13th of M−1; Ch 57 is the
23rd and Ch 60 is the 27th.** The interval is **ten days** and **fourteen days**. Every "six weeks" is a
figure of roughly six weeks' error, and **no gate in this repository can see it** because a week count is
not a date.

| Chapter | Before | After | Anchor |
| --- | --- | --- | --- |
| `chapter-0057.md:53` | *a figure that has not gone up by one grain in **six weeks*** | **in ten days** | The plate read 8,138 from the Review day, the 13th. The 23rd is ten days later. |
| `chapter-0060.md:59` | *every Thursday for the last **six weeks** he had walked past it* | **for the last three weeks** | Thursdays: the 13th, the 20th, the 27th. Three Thursdays. |
| `chapter-0060.md:61` | *which was the **first time in six weeks*** | **the first time since the Review** | Same anchor. |
| `chapter-0060.md:109` | *further than she had stood in **six weeks*** | **further than she had stood since the Review** | Same anchor. |
| `chapter-0060.md:161` | *a woman who had been counting a mass for **six weeks** would have already been counting it for **four days*** | **a woman who had been counting a mass would have…** | The sentence contradicted itself: if she had been counting six weeks she could not have been counting four days. **The false figure is removed and the operative one is left.** |

**Five instances, two chapters, eleven words.** And the reader-facing consequence: **before this repair a
reader who counted from the Review would have found Ch 57 and Ch 60 impossible.** After it, Ch 59's *six
weeks* — the one week count in the batch that is **correct**, because it is a cross-boundary interval and
M−1 really is thirty days — stands alone and does its work.

---

## 13. The four gates the Batch 0005 review had to invent

Because **every gate the batch ran passed on text that was wrong.** These are the highest-value item in
Part one and the one that cannot be done by a count. **All four were run over all fifty chapters, not only
91–100.**

### A. Meta-language

```
grep -inE 'this volume|this book|the reader|\bchapters?\b|fifty chapters|\bvolume\b' chapters/volume-02/chapter-*.md
```

**Seven hits across fifty chapters. All seven are in-world and none is a fourth wall.**

- `chapter-0051.md:107` — *a plate settled into the reader*, a plate-reading machine.
- `chapter-0070.md:17`, `chapter-0074.md:183`, `chapter-0076.md:39`, `:59`, `:75`, `chapter-0100.md:29` —
  **this book**, six times, and every one is a physical book: Drant's thin book, Tessa's day book, Anneke
  Roos's fourth register.

**Zero real violations. Do not "fix" these.** A gate that fires on a physical book is the same failure as
a gate that misses a real one, in the other direction.

### B. Week counts — the D1 class

```
grep -inE '(four|five|six|seven|eight|nine|ten|eleven|twelve)teen? weeks' chapters/volume-02/chapter-*.md
```

**Nine survivors across fifty chapters, and each was traced to its anchor:**

| Instance | Anchor | Verdict |
| --- | --- | --- |
| `chapter-0055.md:73` *four years and then six weeks* | The mass's growth from the Review | **Fine** |
| `chapter-0059.md:99` *they come back in six weeks* | A general clinical interval, not anchored to a date | **Fine** |
| `chapter-0059.md:115/123/129/133` *six weeks* ×4 | The Review, 13th of M−1 → the 25th of M = 42 days | **Correct, and it is the load-bearing proof that M−1 is thirty days** |
| `chapter-0072.md:37` *a man who has paid a price for six weeks at least* | The Review, 13th of M−1 → the 23rd of M = 40 days | **Fine** |
| `chapter-0074.md:133` *in a corridor in six weeks* | A forecast | **Fine** |
| `chapter-0076.md:79` *In six weeks they are a body of evidence* | A forecast about the first twenty days | **Fine** |
| `chapter-0079.md:11` *driving past this stop for six weeks* | Beatrix's shift pattern | **Not date-anchored** — see D3 |

**D1 is closed.** The five instances in Ch 57 and Ch 60 are repaired and listed in §12.

### C. Ordinal counts against a named collection

```
grep -inE '(six|seven|eight|nine|ten|eleven|twelve) (women|people|chairs|men|girls|boards|charts|lines)' chapters/volume-02/chapter-*.md
```

**The household is seven women, and six of them keep the notebook. Both are on the page and they are not
the same count, and the state file got this wrong.**

- `chapter-0081.md:59` — *"**Seven women** with one man who has no address"* (Marguerite).
- `chapter-0081.md:111` — *"**Seven women**, none of them leaving."*
- `chapter-0081.md:125` — Ola's pad carries *"the date and **seven names**."*
- `chapter-0081.md:127` — *"Under the **seven names** she had written Sun Meiling's sentence and the date
  against it."*
- `chapter-0094.md:67` — *"I told **seven people** on the first of this month."*
- `chapter-0094.md:85` — *"And so **six of us** are going to write it down."*
- `chapter-0100.md:65`, `:71`, `:75` — **six women**, three times, keeping the notebook.

**CORRECTION.** The Batch 0005 review's own note reads: *"THE HOUSEHOLD IS SIX WOMEN… Six, from Ch 81's
seven people in the room on the 1st: six women and him."* **That reasoning is a miscount.** Ch 81's room
holds **seven women** — Nadia, Beatrix, Tessa, Ines, Marguerite, Ola, and Sun Meiling off the landing —
**plus him**. The page is right and the state file's *conclusion* is right about the notebook writers and
wrong about the household.

**Correct statement for the record: the household is seven women. Six of them keep the notebook. Sun
Meiling does not, and that is the whole of her refusal in miniature.** Recorded as adjudicated item 53.

Nine chairs: eight in two rows of four against the wall of the second sub-level and one square to a door
four feet out (Ch 95, `:45`), **and the ninth chair is still on the third floor of the Reading and is the
one nobody came back for** (Ch 95, `:73` and `:101`). **Consistent.** 258 charts: consistent in Ch 68, 74,
78. 112 lines: consistent in Ch 87, 97.

### D. Every interval number, on one screen

**This is a reading list, not a pass/fail gate.** It was run over all fifty chapters:

```
grep -noE '(for|in|since|by|across|about|after|until) (a|an|one|two|...|thirty-one)? ?(day|days|week|weeks|month|months|night|nights|hour|hours|year|years|fortnight)[a-z]*' chapters/volume-02/chapter-*.md
```

**Every interval was traced to an anchor inside its own chapter or to an earlier chapter's printed figure.
The D2 sweep in §0 is the part of this list that crossed a month boundary.** The remainder breaks into
three groups:

1. **Anchored and correct.** Ch 71's *five days* (22 − 17) · Ch 74's *eight days* (25 − 17) · Ch 74's
   *twelve days* in Tessa's rudeness · Ch 80's *seven days* of the return · Ch 84/85/93/94/99/100's firsts,
   seconds and months, all checkable inside their own chapters · Ch 91's notice dated the 9th and put face
   up on the 11th · Ch 95's *two days* · Ch 99's *eighteen days* (the 19th − the 1st).
2. **Durations of service, of a document, or of a clinical history** — not date-checkable and correctly so:
   nineteen years (Drant), eleven years (Tessa, Ines, the fourth book), twenty-nine years (Faber), three
   years and four months (Ottilie Prebble), seventeen weeks (Colm's arithmetic, verified), four months
   (Colm, Ines, Marguerite).
3. **D3. Nine intervals that do not trace.** Recorded below.

---

## 14. D3. Nine intervals this audit found and did not repair

**These are new. They are the output of reading gate D and they are not D1 and not D2.** They are
recorded with their arithmetic and **they are left on the page**, because repairing a second cluster
across five more reviewed chapters is the "repairs the whole volume" this audit was told not to do. **They
are the first thing the next repair pass should take.**

| # | Chapter:line | On the page | The spine says |
| --- | --- | --- | --- |
| 1 | `chapter-0059.md:127` | *From here that is **five weeks and a bit*** | The 25th of M−1 to the 25th of M is one month. Four weeks and two days. The sentence is contradicted by the two figures beside it (*twelve days* of it so far, *six* from the Review). |
| 2 | `chapter-0071.md:21` | *you have been standing still for **three weeks** and nothing is coming in* | The Review is the 13th of M−1; Ch 71 is the 22nd of M. Thirty-nine days. And *nothing is coming in* has been five days (Ch 71 itself). |
| 3 | `chapter-0073.md:17` | *for **four weeks** now the actual paper of your figure has been out of the Fourth Branch* | The standing's first strip is the 3rd of M; Ch 73 is the 24th. Twenty-one days. Three weeks. |
| 4 | `chapter-0073.md:27` | *a straight answer about the standing for **four weeks*** and *I found out on **the fourth** with a strip in it* | The 4th to the 24th is twenty days. Three weeks. |
| 5 | `chapter-0073.md:49` | *Your figure has not gone up one grain in **four weeks*** | The figure read 8,138 from the 13th of M−1. To the 24th of M is forty-one days. Six weeks. |
| 6 | `chapter-0074.md:143` | *You have not spent in **twelve days*** | Same anchor as 5. Forty-two days. Six weeks. **This one is the worst, because it is the sentence that carries the scene's clinical argument** — it is the proof that holding his turned lines has taken the cold out of her hands. |
| 7 | `chapter-0076.md:9`, `:11`, `:13`, `:61`, `:67`, `:135` | *You have not come up here for **three weeks*** (six times) | The register corridor, Ch 76 is the 27th of M. Not anchored anywhere on the page that this audit could trace. |
| 8 | `chapter-0079.md:11` | *I have been driving past this stop at the end of a shift for **six weeks*** | Not anchored. Beatrix's shift pattern has no date on it. |
| 9 | `chapter-0100.md:19` | *Three unsigned papers have gone back up three floors from that desk in **two months*** | She names them: the 31st of M, yesterday (the 18th of M+1), and the 19th. That is twenty days. Three weeks. |

**Why these were not repaired, stated plainly.** This audit was told that an audit which repairs the whole
volume is not an audit, and that the one prose repair it must make is D2. Items 1–8 are a cluster with the
same shape as D1 but in a batch that has been reviewed twice already, and resolving them properly means
deciding what the Batch 0003 writers believed the calendar was doing — which is a judgement about another
batch's spine, and belongs in the repair pass that has to carry the decision. Item 9 is in the volume's
best chapter and is a two-word fix, and it is recorded rather than made because applying it here would open
the question of why the other eight were left.

**Nothing here changes a date the reader is asked to derive a later date from.** All nine are interval
statements inside a scene. **A Volume 3 writer may derive nothing from them.**

---

## 15. The two state files that propagated defects into canon

`state/chapter-summaries.md` recorded Ch 93's *thirteen days* and Ch 92's *twenty-two weeks* as settled
facts, and `state/continuity.md` repeated both. **A state file asserting a figure is not evidence that the
figure is right, and this is why the same two classes keep reappearing.**

**Checked again, on the page, not against the note:**

| Defect | State file said | Page says now | Verdict |
| --- | --- | --- | --- |
| Ch 93's deadline | *thirteen days* | *until the third of next month* | **Correct on the page and in the state file.** Verified: `grep -in "thirteen days" chapter-0093.md` → nothing. |
| Ch 92's pad | *twenty-two weeks* | *Seventeen weeks* (`chapter-0092.md:11`, `:43`) | **Correct on the page and in the state file.** |
| Ch 83's grey day | *tenth/eleventh* | **twelfth** — repaired by this audit | **The state files carried the review's figure. Corrected in §0 and in `state/continuity.md`.** |
| Ch 87's elapsed count | *fourteen days past the twenty-three* | **fifteen** — repaired by this audit | **As above.** |
| The month | *thirty days* | **M−1 thirty, M thirty-one** | **The blanket figure was wrong and is struck. §0.** |
| The household | *six women* | **seven women; six keep the notebook** | **Corrected in §9-C.** |
| Ch 69's title | bank entry 19, *The Second Attendance* | **The Fourth Box** | **The page governs. §9.** |

**No other summary contradicts the page it summarises.** Spot-checked against `state/chapter-summaries.md`
for Ch 81, 92, 93, 97, 98, 99 and 100 and against the volume index: all agree.

---

## 16. What this audit could not settle

1. **The length of month M+1.** No interval on the page crosses its end, because the volume closes on the
   29th of it. **A Volume 3 writer must derive from a chapter's own anchor.**
2. **Whether months in Ostara are meant to be uniform.** Nothing in the bible, the series outline or the
   forty-one month-length statements on the page says either way. **This audit settled only that M−1 is
   thirty and M is thirty-one, and that is what the page says.**
3. **Ch 76's and Ch 79's week counts (D3 items 7 and 8)** have no anchor on the page and this audit did not
   invent one.
4. **Whether Sun Meiling's refusal is "closed" in the outline's sense.** The page states, restates and pays
   for it and does not close it. **The page governs and the thread is open.** §8.
5. **The prose.** This audit read the page for structure, continuity and arithmetic. It did not re-read
   fifty chapters as a reader looking for the prose. **A batch may not certify itself, and this audit does
   not certify the prose either.**

---

## The standing instruction, restated once because it is the finding

**A count is not a reading.** Every mechanical gate above was run and its output printed. **Every one of
them passed on the Batch 0005 text that carried four real violations**, and the most consequential fact in
this volume — the length of a month — was wrong in two state files, wrong in two reviewed chapters, and
invisible to all of them.

**The repair pass found it by reading Chapter 79's first sentence and Chapter 81's first sentence and
asking whether they could both be true.**