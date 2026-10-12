# Volume 1 Close — Audit

**Volume 1, Chapters 1–50.** Read against `outline/volume-01.md`, `outline/series.md`, `outline/ending.md`,
`bible/power-system.md`, `bible/terminology.md`, `bible/characters.md`, and the three state files.

**This is an audit and it wrote no prose.** Nine findings are recorded at the end. None of them is a
recommendation to rewrite Volume 1, and none is applied. Three of them are state-file certifications that
the page contradicts, which is the failure this pipeline has produced nine times already and which no
gate in this repository can see.

**How claims are marked.**

- **Mechanical** — a command was run and its output read, here or reproduced below.
- **Judgement** — a reading. No command verifies it and this file does not pretend otherwise.
- **Correction** — a state-file claim that the page contradicts, with the chapter and line.

The Batch 0005 review ran seven gates, reported all seven accurately, and every one of twelve defects in
that batch was invisible to all seven. That is the standing fact this audit begins from. Commands are
cheap and they catch real things. **They are not a reading.** Every mechanical claim below names the
command. Every judgement below names the chapter.

---

## 1. The volume promise

> In this volume, **Lin Hao must hold rank six through the Winter Review**, or **the reservoir is
> requisitioned by the Fourth Branch and he never gets it back**.

**Answer: he held six. The promise is paid.**

The band is struck on the Review morning, Ch 47, and the strike is spoken twice in the same chapter —
once at the counter and once at the table — from the same plate:

> "Provisional six. Floor eight thousand one hundred and forty-one. Reading eight thousand one hundred
> and thirty-eight. Three grains down. Inside tolerance by nothing." — `chapter-0047.md:55`

> "Rank six," the chair said. "Held. Not provisional. Seated on a witnessed deed of this day."
> — `chapter-0048.md:59`

**The cost, stated on the page, and the chapter that states it: Ch 48, all four terms.**

| Cost | Where on the page |
| --- | --- |
| A line in his own ledger reading himself | `chapter-0048.md:51` — "a line in his own ledger that said himself, which had never been there before and should never be" |
| Three feeders turning at once | `chapter-0048.md:45` — Nell Ardery, Garrick Neve, the yard checker, named, "Three feeders turning at once. Eight turned where there had been five." |
| The cab promise to Beatrix Halm broken | `chapter-0048.md:55` — "it could not be mended, because a line that said himself could not be taken out" |
| The option of being invisible closed | `chapter-0048.md:53` — "could never again be a man who cleaned washrooms without being looked at" |

**Mechanical (panel census).** `grep -n '^\[' chapters/volume-01/chapter-*.md` returns ten hits in
fifty chapters, one each in Ch 3, 4, 6, 13, 19, 25, 30, 37, 40, 48. No chapter carries two. No two panels
are byte-identical. The Batch 0002 defect of a repeated panel has not recurred.

**Judgement.** The promise landed as a win and a wound in the same scene, which is what the volume
outline asked for and more than it asked for. Rhee does not get the reservoir. The Fourth Branch is not
being audited. Ninety-one people know a man in a washroom told the truth in front of his colleagues.

---

## 2. Earned, or seated

**He was seated. The prompt's sentence is the most important thing this phase produces and it is
recorded here in the form the record must take:**

> **The volume promise was met by a different mechanism than the one planned. This was the right call.
> The consequence is live: he holds rank six on an instrument, and he is 11,862 grains under his own
> band.**

**What was planned.** `outline/volume-01.md:39–49` and the Batch 0004 and 0005 blocks set the mechanism
as *thirty witnessed deeds and nineteen hands*: a witnessed deed scores 400, band six opens at 20,000,
and the gap is closed by committing deeds in public at a visible rate.

**What the page does instead.** Mechanical:

- Band six = 20,000, stated at `chapter-0040.md:30`.
- Published standing = 8,141, at `chapter-0040.md:30`.
- 20,000 − 8,141 = **11,859**, stated on the page at `chapter-0040.md:30` and worked at
  `chapter-0040.md:32` — "Eleven eight hundred and fifty-nine, divided by four hundred, is twenty-nine
  and a bit."
- The reading at the Review = 8,138, `chapter-0047.md:55` and `chapter-0047.md:63`.
- 20,000 − 8,138 = **11,862**.

**Judgement.** Thirty deeds in six weeks requires thirty witnesses and a public rate. He has nineteen
people and no twentieth, and the reason he has no twentieth is on the page: the only people he can reach
are the people relief would mark, and a cold minute into a marked person is a reportable episode, and
three in a season gets a file. That is `chapter-0043.md:99` and `chapter-0045.md:51`. **The planned
mechanism was arithmetically unavailable to the character the volume had built.** Seating him on an
instrument was the only version of the promise he could actually keep.

**And it cost the book its engine.** The gap is now the sharpest live fact in the novel and it is not
resolvable by the mechanism Volume 1 spent fifty chapters on. He cannot close 11,862 grains with the
account, because the account does not score (`bible/power-system.md:157` — "It cannot raise his rank.
Not one grain of it is scoreable"), and he cannot close it with deeds because the deeds run through the
ledger. **B26 is open and it is the volume's live consequence, not a loose end.**

**Mechanical (the reservoir never scores).** Search across all fifty chapters for a grain credited to
the account returns one hit, `chapter-0025.md:39` — "Four hundred grains went somewhere" — which is the
wrong-direction spend, where four hundred grains move into a *figure* rather than into a body, and the
chapter's whole subject is that the figure moved and the body did not. Ch 48's answer contains "Four
hundred of it came off a woman with a basket" (`chapter-0048.md:23`), which is the **composition** of
the standing, not an addition to it. **Nothing in Volume 1 lets the reservoir score a grain.**

---

## 3. Every thread, at the close

**Judgement throughout, checked against the chapter named in each row.** "Advanced" means the page moved
it; "unchanged" means it is still exactly where Batch 0005 found it. **No thread is closed by a volume
ending.**

### Seeded threads

| # | Status at the close | Traced to |
| --- | --- | --- |
| **T1** Lin Wei's file | **Advanced by exactly one folio and must advance no further.** 4,112 folios, 4,111 sealed, one open at the back by Wing order, never called. Transfer receipt, Lin Wei's hand, 214,000 grains, the eleventh three years ago, into an account the index does not contain. Under it in Wing print: the file of the person who received it is Held Account One. There is no Held Account Zero. | Ch 50, lines 5–27 |
| **T2** Who keeps his file clean | **Unchanged, by design.** Planted Ch 7 and Ch 10, untouched since. Search for a later answer returns nothing. Must not be answered before Volume 3. | Ch 7, Ch 10 |
| **T3** Church of the Quiet Number | **Unchanged.** Last named in Ch 10. The rank-five clerk in grey, the same petition every morning for three years, four auditors refused to read it. Not developed. Must not develop before Volume 4. | Ch 10 |
| **T4** The Unscored in the Saltworks cordon | **Untouched.** Not named in Volume 1. | — |
| **T5** Tessa's inventory | **Advanced every batch.** Rack of eleven clipboards in Batch 0003, twelve at Ch 38, **seventeen at the close of Ch 49, eighteen before nightfall in Ch 50.** Stippling past the left elbow, pale blue above the joint, right forearm begun. She charts the three new colds herself in Ch 48 and then sits looking at her own arms. | Ch 26, 38, 48, 49, 50 |
| **T6** Agnete Lindqvist | **Untouched.** Not named in Volume 1. | — |
| **T7** Petra Ilyin | **Untouched.** Not named in Volume 1. | — |
| **T8** Ines losing her twenties | **Untouched.** Search for *twenties* across Chapters 1–50 returns nothing. She does say the volume of what she holds — 4,109 files in her head at Ch 8, forty files on Lantern Row at Ch 7 — which is the seed. The loss is not yet visible. | Ch 7, Ch 8 |
| **T9** Nadia can only go down | **Advanced.** Carried up one floor at a price, twice: `chapter-0029.md` and `chapter-0049.md:45` — "she rang the bell and took the car up one floor, as far as she went." She refuses to be spent, in her own words, twice: "do not spend me." | Ch 29, 38, 44, 49 |
| **T10** Sun Meiling | **Untouched and correctly so.** Not named in any chapter. She is Volume 2's plant. | — |
| **T11** Why there is no rank ten | **Untouched.** Not hinted. | — |
| **T12** Wren Kallo | **Untouched.** Not named in Volume 1. | — |

### Batch threads, B1–B35

| # | Status at the close | Traced to |
| --- | --- | --- |
| **B1** Colm Deveraux's 1,001 grains | **Unchanged.** Last named Ch 6. A frightened supply supervisor who locked an office and has not been seen since. Owed. | Ch 6 |
| **B2** The untouchable lines | **Advanced and inverted.** Was "accrual is proximity, the rate drops when you become known." At the close the rule is the reverse: the figure moves wherever he stands and the faces stop when he leaves the corridor. 91 lines, and he walked into the Review crowds to get them. | Ch 22, 30, 34, 48 |
| **B3** Nadia has told everybody | **Advanced and paid into a household.** Sixty-one people by four o'clock in Ch 29, the whole Vestry by the weekend. At the close she is holding her own car at the terminus past midnight with nobody telling her to. | Ch 29, 49, 50 |
| **B4** Ola's notebook | **Advanced.** Forty-one pages at Ch 10, twenty-two new entries by Ch 38, forty pages and more by Ch 50 with the Review finding copied under the re-read. *Nobody has asked me to do this* spent once, Ch 38. She is clerking. | Ch 11, 38, 50 |
| **B5** Ding D. Duarte | **Unchanged and the cleanest open thread in the book.** Petition 4118, refused, alive in the Vestry, unnamed in the ledger. Ines says her name aloud in Ch 8 and nowhere after. | Ch 7, 8 |
| **B6** Bernt Halse | **Unchanged.** Taken the 9th at ten past ten in the morning, not out. Ditta on the benches. The arithmetic Lin Hao cannot complete is on the page at Ch 10 and is not completed at Ch 50. | Ch 5, 10 |
| **B7** The two-year gap | **Unchanged.** Do not resolve. Volume 8. | Ch 7 |
| **B8** Tessa's cold-store box | **Advanced.** Eleven clipboards to eighteen. | Ch 26, 50 |
| **B9** The audit opens Monday the 19th | **Paid.** The ninety-one were read on the 3rd. Eighty-two settled, nine did not, and the five who unsettled are on the corridor board by name. | Ch 27, 28, 29 |
| **B10** Ines cannot file what she knows | **Paid and reopened.** The illegal premises register requisition at four in the morning stands discharged. What replaces it is sharper: she cannot decide whether to file the himself line, and Ch 49 has her say so in words. | Ch 44, 49 |
| **B11** Beatrix's four years | **Advanced, then broken.** She gave him the whole book on a price, spent the favour, and the price was broken in the square at Ch 48. She names it without heat and does not forgive it in a speech. September is still hers. | Ch 17, 38, 49 |
| **B12** Rank five held | **Superseded.** He is six. | Ch 19, 47 |
| **B13** Tobias filed to Rhee | **Paid.** He filed, he was destroyed by a true document of his own making, he is off the board again, and the declaration that did it is still the first page of his file. | Ch 22, 23, 39, 49 |
| **B14** Rhee's offer | **Closed forever, on the page.** Refused in the exact mechanism he specified, through two inches of door, and he says he will do the audit the normal way after this one. Does not return. | Ch 21, 28 |
| **B15** Runa's sealed order | **Partly answered.** It was not Rhee's and not Tobias's, and it was written about a shape. Who wrote it is **unchanged.** | Ch 20, 39 |
| **B16** The Classification Wing register | **Unchanged and not resolved.** Nine years, thirty-one entries, the oldest still running, his the thirty-first dated the 3rd with the finding number now beside it. Must not resolve before Volume 2. | Ch 30, 39, 48 |
| **B17** The second person | **Untouched, correctly.** Tessa's second-of-May clipboard, 2,640, appears in Ch 47 line 21 — Ines puts it on the table in the corridor outside the Review — and neither of them touches it. **The Ch 48 hinge was not spent.** | Ch 47, 49 |
| **B18** Tobias off the filing register | **Advanced.** Twenty-nine months re-opened by hand, the annexe boxes, the statement in the front of his own file. He is still owed something and still will not take it in a speech. | Ch 23, 49 |
| **B19** The five struck through | **Paid twice.** Struck by declaration in Ch 28, put back by his own statement in Ch 39, and struck a second time **by instrument** at the Review in Ch 49. That is the only clean thing the volume does to that board. | Ch 28, 39, 49, 50 |
| **B20** Emrys Vaz, 441 | **Unchanged and heavier.** He can still only go down. He is named in the declaration at Ch 39 and knows all of it. | Ch 37, 39 |
| **B21** The fifth figure | **Live and permanent.** 8,141 printed on a public tile on his name, in the largest type in Ostara. | Ch 30 |
| **B22** Ines's paper | **Paid.** The month ran out, the rota name was said aloud on the 20th, and **the word itself was not given.** That is a decision, not a fact, and it is still standing. | Ch 38, 44, 49 |
| **B23** The statement against himself | **Paid and irreversible.** Five names back on the board, a Reading Office query on his own standing, and the declaration standing at the front of Runa's file above the observation of the 6th with the finding number beside it. | Ch 39, 49, 50 |
| **B24** The Reading Office query | **Paid.** Closed in Ch 49 — "A witnessed answer in the room is an instrument. You hold one now." | Ch 49 |
| **B25** A provisional band is not carried into review | **Paid, and it is the mechanism of the climax.** The panel seats him on standing; standing is a five; the requisition and the finding are the instruments that put him back on six. | Ch 40, 47, 48 |
| **B26** The eleven thousand eight hundred and fifty-nine | **Open, and it is now 11,862.** Never closed by a score. It cannot be closed by a score. | Ch 40, 48 |
| **B27** Tobias is on a board again | **Paid.** Off by instrument, with the declaration remaining. | Ch 49, 50 |
| **B28** Tessa's rack is at twelve | **Advanced** to seventeen, eighteen before nightfall. | Ch 38, 49, 50 |
| **B29** Solveig Rask's column of thirty-one | **Unchanged.** The column came off the table at Ch 46 — "Solveig has taken the column off the table" — and the valuation with it. Do not resolve before Volume 2. | Ch 32, 33, 46 |
| **B30** The broker in Bellhouse | **Paid.** It is why the terms came back, and why the house is holding him unsigned. | Ch 45, 46 |
| **B31** The himself line | **Open and new.** 91 lines, 8 turned, one reading himself. No auditor has seen it. Ines cannot decide whether to file it and says so on the page. | Ch 48, 49 |
| **B32** Three new turned at once | **Open.** Named: Nell Ardery, Garrick Neve, the yard checker. The pattern now points at the Review room. | Ch 48 |
| **B33** Held Account One | **Open.** T1 advanced by exactly one folio. There is no Zero. | Ch 50 |
| **B34** Beatrix's broken price | **Open.** Named without heat, not forgiven in a speech. September still hers. | Ch 49 |
| **B35** Held six on an instrument | **Open and new.** A rank-six petitioner standing 11,862 grains under his own band is a shape the Office has no procedure for. This is Volume 2's institutional pressure. | Ch 48, 50 |

**Judgement.** Thirty-five threads opened, thirty-five carried, none closed by the volume ending. Four
paid (B9, B19, B24, B25), one superseded (B12), five advanced past their Volume 1 beat (T5, B2, B3, B4,
B8), and twenty-six live. **That is correct and not a failure.** A volume that closes its own threads and
leaves the reader nothing to press on has failed in the other direction.

---

## 4. Relationships — six scenes, what each changed

**Mechanical (the census).** `outline/volume-01.md`'s scene table and `outline/series.md`'s scene-budget
table agree: 8, 17, 26, 29, 36, 46. Gaps 9, 9, 3, 7, 10. **Two gaps under eight — 26→29 at 3 and 29→36
at 7 — and they are the two `outline/series.md:232–240` names and locks.** Every other gap in the volume
is between 8 and 14, and the largest is 10. The census is confirmed and the lock holds.

**Judgement, and the scenes were checked by reading the scene rather than by counting words.** For each:
what it changed, whether the change is on the page, and what the woman now wants that she did not want
before.

| Ch | Woman | What it changed | On the page? | What she now wants that she did not before |
| --- | --- | --- | --- | --- |
| **8** | **Ines Duarte** | She can feel the ledger through contact and reads nine names she can identify out of it. She writes a tenth in pencil: Ola Bright, not on his file, not on hers, not on any list in the city. | **Yes**, and it is the closing beat — `chapter-0008.md` line 227 onward: "I have held four thousand one hundred and nine files in my head… And that was not a document. That was people." | She wanted a file with two rooms in it. She now wants **to audit the unrecorded case**, and she cannot report him. Her professional danger and her partner status are the same fact from this chapter on. |
| **17** | **Beatrix Halm** | She hands over four years of turned-line geography on a price agreed out loud before anything started: spend them on people, not on yourself. Nine turned lines is a legible shape and the dot is a house. | **Yes**, and the triangulation is the last third of the chapter. | She wanted four years of being told her headaches are a condition. She now wants **a use**, and she has named what he owes her for it. The promise survives to Ch 48 and dies there. |
| **26** | **Tessa Okonkwo** | She tells him the cost is not only his: she pays cold minutes out of her own body, she is running out of room in her own inventory, and she has a date for somebody else doing what he did in May. She takes her position out loud — not as one of his, as the person who holds it. | **Yes.** The stippling is described before anything else happens in the room. | She wanted to treat somebody without writing the file. She now wants **him to be visible in a corridor where ninety-one people can watch**, and she says a man who cleans washrooms cannot do what comes next otherwise. **She designs Ch 28 before he does.** |
| **29** | **Nadia Ferrous** | She comes to say one thing badly and says it: everything she feels is a floor, she has never gone up, and on Thursday she felt him go up with her hand on the brake. Then she carries the car up one floor at a price, so it cannot be a thing that happened to her, and asks for her choosing of every part of it to be on the record. | **Yes**, and the last line is her telling nine people at the top of her lungs. | She wanted to be told what she is living with. She now wants **him, specifically, and out loud**, and has said so. She is not a mystery and was never going to be one. |
| **36** | **Runa Sato** | She falsifies her own report — false in four places including him — and tells him what that costs her before she writes it. Both injured, neither impaired, the injury constraining rather than causing. | **Yes.** The report is written at nine that night with the district clerk asleep on a chair, and the falsification is read back verbatim. | She wanted to be measured by what she did rather than what her file says. She now has **a file that is a lie in her own hand**, which is the most expensive thing she could want and she took it anyway. |
| **46** | **Marguerite Vale** | He refuses the line a second time — in her own rooms, in bed, for appetite rather than principle — and she keeps investing anyway. The terms stay down. | **Yes**, and the refusal carries its worse reason with it, and she names it: "The first reason was principle. This one is appetite." | She wanted a position that does not depend on the Vant. She now wants **a man who asked for the date instead of the money**, and she says she will hold that line signed or unsigned. |

**Judgement.** Six scenes, six different women, six different things changed, and **no two scenes run the
same emotional direction**: one is a decision against her own interest (Ines), one is a purchase (Beatrix),
one is a professional alliance designed before the crisis (Tessa), one is an assertion of want (Nadia),
one is a felony for his sake (Runa), one is appetite named honestly and refused anyway (Marguerite). The
scene budget is met and the shapes are not interchangeable.

**Correction 1 — the scene in Ch 46 is on the page, and the file that certified it is right to say so.**
It is 1,959 words, adults, awake, unrestrained, unmedicated, consent taken in plain statements before
anything starts, the tender arm respected and named, violence and sex in separate registers. Read in
full, not certified.

---

## 5. Power progression and its costs

**Mechanical — the grain spine, every published figure, every chapter it appears in.**

| Chapter | Figure | Where |
| --- | --- | --- |
| Ch 1 | 3,412, no interval | `chapter-0001.md` |
| Ch 3 | 3,393 (−19) | `chapter-0003.md` |
| Ch 4 | 3,481 (+88) | `chapter-0004.md` |
| Ch 5 | 3,568 (+87) | `chapter-0005.md` |
| Ch 13 | 4,012 | `chapter-0013.md:15` |
| Ch 15 | 4,412 (+400) | `chapter-0015.md:67` |
| Ch 18 | 4,612 (+200) | `chapter-0018.md`, per continuity Batch 0002 |
| **Ch 19** | **8,141 (+3,529 aggregate)** | `chapter-0019.md` |
| Ch 30–44 | 8,141 published | eleven chapters |
| Ch 44 re-read | 8,140 (−1) | `chapter-0044.md:27` |
| Ch 45 | 8,139 (−2) | `chapter-0045.md` |
| **Ch 47 / Ch 48** | **8,138 (−3)** | `chapter-0047.md:55`, `chapter-0048.md:31` |

**The spine in the prompt's form: 4,012 → 8,141 → 8,138.** Correct. The figure rose once, held for twenty-five
chapters, and drifted down three grains across four readings. **It never crossed 20,000.**

**Mechanical — the drift ladder is closed and the proof is on the page.** 8,140 / 8,139 / 8,138 in
Ch 44, 45, 47. **Four down lapses a band, and Ch 47 shows it happening to a man who held five for six
years** — `chapter-0047.md:49`. Three is the tolerance, and the volume proves it by showing what four
does. That is the correct way to establish a rule.

**Mechanical — the ledger.** 3/0 (Ch 3) → 9/1 (Ch 4) → 14/2 (Ch 6) → 16/3 (Ch 13) → 19/3 (Ch 18, 19)
→ 19/4 (Ch 25) → 19/5 (Ch 30) → **41/5 (Ch 34)** → 91/**8** (Ch 48). **Lines only ever rise.** The one
interval where the count holds while the figure moves — Ch 19 to Ch 30, and Ch 30 to Ch 34 — has a cause
stated on the page both times: he gave up the long ride on the 29th so the faces stopped coming, and he
walked the arc on purpose on the 15th because he had nineteen people and no way to get a twentieth.

**No cost was quietly refunded.** Checked one by one:

| Cost | Status at the close |
| --- | --- |
| Grey at the left temple, from Ch 4 | **Still there at Ch 50**, aching. `chapter-0048.md:79`, `chapter-0050.md`. |
| A forearm that will bear a sleeve | Came off the sling in Ch 45. **This is recovery of an injury, not a refund of a cost** — the arm was broken in Ch 36 and it mends. |
| The five turned at Ch 38, located and named | **All five still located at Ch 49.** Not healed, not forgiven, not reset. |
| The left elbow crossed, the right forearm begun | **Worse at Ch 48 and Ch 50**, not better. |
| Colm Deveraux locked and frightened | **Still locked.** No scene, no speech. |
| The cab promise | **Broken.** Named without heat. Cannot be mended and is not. |
| Anonymity | **Gone.** Permanently. Named in Ch 48. |
| Rhee's offer | **Closed forever in Ch 28**, and the volume says so. |
| The Ines debt | **Discharged in Ch 22** and explicitly not re-run. |
| The himself line | **Still in the ledger.** Nobody can take it out. |

**Nothing in Volume 1 lets the reservoir score a grain.** Checked above, §2.

---

## 6. World consistency

**Mechanical — the Planning-register ban. `grep -niE '\breservoir\b|\bquiet account\b|\bconcil\b|ninth seal|\bchannel\b'`
over all fifty files returns zero hits.** Confirmed across the whole volume, not the last batch.
Chapters 1–50 contain none of the five words.

**Mechanical — weekday names.** Only **Thursday** and **Monday the nineteenth** may be spoken. Total
spoken occurrences of Thursday across the volume: 80. Non-Thursday weekday occurrences, less the two
permitted instances of *Monday the nineteenth* in Ch 4 line 127 and Ch 5 line 43: **58.** Distributed
Ch 1 (6), 2 (4), 3 (4), 4 (7), 5 (5), 6 (8), 7 (7), 8 (3), 9 (2), 10 (9), 11 (1), 19 (2). Chapters
12–18 and **20–50** are clean. **The census in `state/current.md` item 23 and in `state/open-threads.md`
is exact and is confirmed here at 58.** Three are bare and unambiguous: `chapter-0002.md:109`,
`chapter-0006.md:19`, `chapter-0006.md:27`.

**Mechanical — the reserved constructions.**

| Construction | Status |
| --- | --- |
| *there is no form for this* | All three escalations spent, Ch 5, 6, 7. **Two survive and both are canonical uses** — `chapter-0006.md:27` is Colm's bureaucratic frustration, `chapter-0007.md:117` is Ines correcting him (*there is no form for the whole floor*). No paraphrase found anywhere. |
| *there is no column for it* | Spent once, Ch 1, and not again. Ch 23's *there was a column for it* is the deliberate inversion and is correct. |
| *nobody thanked him* | **The sentence** is spent once, Ch 50:69, and nowhere else in the volume. **The construction is not** — `chapter-0012.md:19` reads *"Nobody thanked the boy."*, same construction and different object, 38 chapters earlier. The row as first written said "and nowhere else in the volume" of the construction and was false. See *Corrections to this audit*. |
| *nobody asked* | **Ambiguous as written, and now split.** The **note** — "Nobody has asked me to do this", `chapter-0038.md:83`, in Ola's own hand — is spent once and is Ch 38's. The **motif** — *nobody asked him, nobody had ever asked, nobody's ever asked* — runs **fourteen times** across Ch 11, 12, 13, 15, 16, 22, 23, 26 (twice), 27, 28, 34, 38 and 43, and is deliberate texture rather than a rationed construction: the subject of Volume 1 is the unrecorded and the unasked-for. **Motif available, note spent.** |
| *the record remained* | **Zero occurrences.** |

**Mechanical — markdown.** No horizontal rules in any of the fifty files. No blockquotes, no code blocks,
no tables. **Bold: zero across all fifty chapters.** Italic: 101 instances, concentrated in Chapters 1–13
(where the document text needs it) and falling to zero from Ch 40 on. No chapter exceeds the 120-word
paragraph ceiling.

**Judgement — ages.** Canon fixes twelve ages and forbids the prose from stating or implying a different
one. `bible/characters.md` says no chapter announces an age; `state/continuity.md` adds that none is
stated in narration or dialogue. **The census of five residual instances (Ch 3, 8, 16, 18, 29) is
incomplete. It is seven. See Corrections 2 and 3.**

**Judgement — world facts.** Ranks and bands match `bible/power-system.md` on every appearance. Rank six
is 20,000 everywhere. Rank five is 8,000. The Exchange prices the deed and not the man (Ch 18's 200, not
400). Accrual is proximity. A relieved body presents as *too well*. A routed body presents as *no better
and no worse with a figure that has jumped*. Classification is a room with no window and a door that is
not locked from inside. None of these contradicts the bible.

---

## 7. The planned climax and the resolution

**Ch 48 is the irreversible decision and it landed.** Named in `outline/volume-01.md:98–104` before the
chapter was written: he takes the open-question slot and uses the reservoir **on himself**, once, for the
first time in the book, and the answer is true. That is what the page does.

**It is irreversible in the sense `AGENTS.md` requires** — done, costly, and an option closed:

- **Done.** In front of nine chairs and sixty witnesses, with a clerk's machine on the table.
- **Costs him something real.** A line in his own ledger that reads himself, three named people turned in
  four seconds, a promise given in a cab that cannot be mended, the option of being invisible.
- **Closes an option.** He can never again be a man who cleans washrooms without being looked at.

**It is the volume's escalation peak and the stage moves.** He went from investigating the system (Ch 1–20)
to manipulating it (Ch 15's staged rescue, Ch 25's aimed spend, Ch 28's declared public reading) to
**breaking it** (Ch 39's statement against himself, Ch 48's spend on himself in a room). The system has not
yet reacted to him — that is Volume 2 and Volume 3.

**Ch 50 is the final image and it is the image the outline specified.** `outline/volume-01.md:126–131`:
the Fourth Branch washroom, second floor, no carpet, a filed petition drying on the counter beside the
soap, the Board nine streets away with his name on a tile he does not go and look at, three people in the
building feeling something cold that night and none of them knowing why. **Every element is on the page**
at `chapter-0050.md:55–69`. He turns the petition face down halfway through because a washroom counter is
no place to leave a brother's hand uncovered.

**Does the volume end changed, or merely informed? Changed.** Six things are different at Ch 50 that were
not different at Ch 1: his anonymity, his ledger, his brother's file, his standing with a broker, his
position in a building of ninety-one people, and the number of people he can touch without harming. The
answer to the prompt's question is that he ends seated rather than promoted, and that is a change of a
different kind from the one the volume planned.

---

## 8. The eight scene gaps

**Mechanical, counted.** Scenes at 8, 17, 26, 29, 36, 46. Gaps: **9, 9, 3, 7, 10.**

Two gaps are under the soft floor of eight: **26→29 (three)** and **29→36 (seven)**. Both are named and
locked in `outline/series.md:232–240`, in `outline/volume-01.md`, in `state/current.md`, and in the
canon-change guard in `state/open-threads.md`. **The census is confirmed, the lock holds, and no scene may
be moved to fix either.** The largest gap in the volume is ten, inside the band.

---

## 9. The canon-change guard

**Mechanical and confirmed by reading the flag blocks in `state/open-threads.md` against the page.**

| Flag | Claim | Page |
| --- | --- | --- |
| **Marguerite's terms** | Refused **twice**, never accepted, never signed, never in force. | **Confirmed.** Ch 33 refused standing up in writing with REFUSED initialled; Ch 46 refused in bed for appetite with the worse reason attached. Ch 47 line 45 has her sitting in the public seats "with the terms down and unsigned". Ch 49 and Ch 50 both carry the terms still down. **The terms are not accepted anywhere in Chapters 1–50.** |
| **The open-question ruling** | An instrument ruling, not a scoring ruling. The reservoir scores nothing. | **Confirmed.** Ch 48's ruling is spelled out at line 35 and the plate reads 8,138 at line 31. No 400 is awarded. |
| **The Review tolerance** | 8,140 / 8,139 / 8,138, three grains, four lapses. | **Confirmed.** Ch 44, 45, 47, and Ch 47 line 49 shows four lapsing a man. |
| **Ch 42 and Ch 44 the same day** | Ch 42 backtracks to the 22nd deliberately and the page anchors it. | **Confirmed.** `chapter-0042.md` names the 22nd in its opening; Ch 41 is the 26th; Ch 43 the 28th; Ch 44 the 29th. |
| **The May clipboard** | Untouched; the Ch 48 hinge not spent. | **Confirmed.** Named in Ch 47 line 21 by Ines and never answered. The word Channel appears nowhere. |
| **The himself line** | One line reading himself, no auditor has seen it. | **Confirmed.** Ch 48 line 51, Ch 49 line 53. |
| **Tobias's declaration** | Standing at the front of the Field file. | **Confirmed.** Ch 49 line 35, Ch 50 line 57. |
| **Rhee's offer** | Closed permanently in Ch 28, not re-opened. | **Confirmed.** No occurrence of the offer in Chapters 31–50. |
| **The fifth figure** | 8,141 on a tile, and it is **not** the Volume 10 second line. | **Confirmed.** No occurrence of *unrecorded — carried by* or its shape in Chapters 1–50. |
| **No new final enemy** | No final enemy introduced in Volume 1. | **Confirmed.** Opposition on the page is Rhee (Ch 20–30), Tobias (Ch 5–49), and the institutional weight of the Bureau. Ferreira is named in no chapter. |

**Correction 4 — the outline says the opposite and the page is canon.** `outline/volume-01.md:307`
(*Marguerite's terms are accepted for the wrong reason*) is contradicted by Ch 46 and has been recorded as
contradicted in `state/open-threads.md` since the Batch 0005 review repair. **The prompt's instruction is
honoured: the terms were refused twice and not accepted.** `outline/ending.md` is untouched.

---

## Corrections

Nine. **None is repaired here.** An audit that repairs the volume is not an audit. Each is written up
because a reader is actively mis-served, or because a state file certifies something the page contradicts
— which is the specific failure this pipeline has produced nine times. **Correction 8 was itself false
and has been withdrawn by the external review at the end of this file; the audit now carries nine
findings of which eight stand.**

**Correction 1 — `chapter-0046.md:37` states Marguerite Vale's age in dialogue.** *Judgement, traced.*
"I am forty-one years of keeping books for money and I am good at it and I enjoy it." The figure is
canon-correct (`bible/characters.md` fixes her at 41) and the sentence is her voice at the top of the
best scene in the volume, and `bible/characters.md` says *no chapter announces an age*. The Batch 0005
review ran `grep -rin "years old|in his forties|in her thirties|about sixty|years of my life"` and
reported **no hits** — and that grep does not match *forty-one years of keeping books*, which is the same
class of bare number-age the Batch 0003 review repair added to the gate for Ch 29. **The gate was widened
once and not widened far enough.** A later phase may strike the number and leave the sentence. Not
repaired here.

**Correction 2 — `chapter-0002.md:21` and `chapter-0037.md:57` state Lin Hao's age in narration.**
*Judgement, traced.*

> "He had spent twenty-five years wanting a number that was not on that board." — Ch 2:21

> "He had wanted that number since he was fifteen years old and had spent ten years not being it." —
> Ch 37:57

Both are canon-correct (he is 25). Neither was ever registered. The five-instance census in
`state/current.md` item 25 and in `state/open-threads.md` names Ch 3, 8, 16, 18 and 29 and is
**incomplete by two**, both of them the protagonist and both in narration, which is the exact category the
census was built to catch. **Not repaired.** Ch 2 is a certified opening chapter and Ch 37 is a certified
climax chapter, and "twenty-five years" in Ch 2 is doing the work of the whole want.

**Correction 3 — the residual age census is seven, not five.** The full list as the page stands:

| Ch | Line | Text | Whose | Canon |
| --- | --- | --- | --- | --- |
| 2 | 21 | "twenty-five years wanting a number" / "since he was nineteen" | Lin Hao | correct |
| 3 | 29 | "an ordinary man in his forties on a tram" | walk-on | — |
| 8 | 297 | "said by a woman in her thirties in a lamp-lit room" | walk-on | — |
| 16 | 31 | "he is seventeen" | Emrys Vaz | correct |
| 18 | 39 | "a man called Emrys Vaz who is seventeen" | Emrys Vaz | correct |
| 29 | 91 | "twenty-three years of my life" | Nadia Ferrous | correct |
| **37** | **57** | **"since he was fifteen years old"** | **Lin Hao** | **correct** |
| **46** | **37** | **"I am forty-one years of keeping books for money"** | **Marguerite Vale** | **correct** |
| **8** | 297 | also carries the bare *"Friday night"* | — | illegal weekday |

**Four of the seven are canon-correct.** The register exists so that a grep cannot be the thing that finds
a decision. It is now seven, and **three of the seven are the protagonist or a core partner**, which the
census did not represent.

**Correction 4 — the eight-in-a-row closing construction.** *Mechanical, and the most serious finding in
this file.* Chapters **42, 43, 44, 45, 46, 47, 48 and 49** — eight consecutive chapters — close on a
paragraph carrying **"He wanted, concretely,"**.

**The test this file first printed was wrong, and it is corrected here at the top of the correction
rather than left in the state files that inherited it.** The test given was: read the last non-heading,
non-panel paragraph and test whether it **begins** with the string. **That test returns five, not eight.**
Ch 47, 48 and 49 carry the construction **inside** the final paragraph instead of opening it —
`chapter-0047.md:81`, `chapter-0048.md:79`, `chapter-0049.md:80` — so a repair pass running the command as
first printed would have concluded that three of the eight were not there, repaired five endings, and left
three chapters still running the same construction. **The finding is sound and unchanged. The reproduction
is fixed.**

**The test that actually reproduces it, and its complete output:**

```
for f in chapters/volume-01/chapter-*.md; do
  last=$(awk 'NF && $0 !~ /^#/ && $0 !~ /^\[/ {line=$0} END{print line}' "$f")
  case "$last" in *"He wanted, concretely"*) echo "$(basename "$f" .md) CONTAINS";; esac
done
```

```
chapter-0042 CONTAINS
chapter-0043 CONTAINS
chapter-0044 CONTAINS
chapter-0045 CONTAINS
chapter-0046 CONTAINS
chapter-0047 CONTAINS
chapter-0048 CONTAINS
chapter-0049 CONTAINS
```

**Eight files, eight consecutive chapters, one instance each, and in every one it is in the final
paragraph.** Ch 41 and Ch 50 are in other shapes. The distinction that matters for a repair pass: **five
chapters open the final paragraph on the string (42, 43, 44, 45, 46) and three embed it one or two
sentences in (47, 48, 49).** A construction that runs eight chapters long runs eight chapters long
whether it opens the paragraph or sits inside it.

`AGENTS.md` fails a batch for using the same rhetorical construction as emphasis more than twice running.
**Eight in a row is worse than the ten the Batch 0005 review repair caught** — and the repair caught the
ten, rewrote seven endings, and **put this in the seven**. The Batch 0005 review file records the fix as
*"the For <person>, his <verb> meant closing ran in all ten chapters in a row… It now appears in Ch 41,
44 and 48 only."* That claim is **true** — the old construction really is down to three, in Ch 41:93,
Ch 44:113 and Ch 48:77, none adjacent, no subject repeated. **It is also incomplete**, because the review
checked the construction it had been told about and not the construction the page actually ended on.

The good prose underneath is kept in seven of the eight. Only the opening clause and, in Ch 42, the
adverb need to change. **This is recorded as a finding and is not repaired here**, because it is eight
chapters of endings in four certified batches and the ripple is wide. It is the first item a repair phase
should take.

**Correction 5 — `state/current.md` certifies a Rhee thread that is not on the page.** *Mechanical.*
`state/current.md:15` reads: *"He held it. Rhee does not have it and is preparing to go over his head."*
`outline/volume-01.md:117` says the same. **`grep -rn '\bRhee\b' chapters/volume-01/` returns 25 hits and
the last one is `chapter-0030.md:17`, a retrospective sentence inside a subordinate clause.** He has no
line, no scene and no presence in Chapters 31–50 — twenty chapters, including the volume's climax and its
resolution. **"Preparing to go over his head" is not on any page.** The first half is true and is
sufficient: the offer was refused in Ch 28 and closed forever. **The second half is a plan the outline
hoped for and the page did not deliver.** Corrected in `state/current.md`. **This is the tenth false
certification of this shape in this pipeline, and the first one about a character rather than about a
count.**

**Correction 6 — `state/current.md` item 25 and `state/open-threads.md` under-register the ages.** See
Corrections 2 and 3. Corrected in both files, and the five becomes seven.

**Correction 7 — the italic census in `state/continuity.md` is Batch 0004's, not the volume's.**
*Mechanical.* The Batch 0005 review reports italic at **zero across all ten of its chapters**, which is
correct: `grep -oE '(^|[^*])\*[^*][^*]*\*([^*]|$)'` over Ch 40–50 returns 0 in every file. Across
Chapters 1–50 the figure is **101**, concentrated in Chapters 1–13 and falling to zero from Ch 40.
Recorded so that a Volume 2 writer does not read the batch figure as the book figure.

**Correction 8 — `state/current.md`'s `nobody` budget figures. WITHDRAWN, and the state file it
corrected was right.** *Mechanical, and wrong as first written.* The totals are correct and survive:
**`nobody` runs twelve times across Ch 41–50 and `no one` three times, fifteen together.** The
per-chapter split and the conclusion are not, and both were checked again against the page:

| Ch | 41 | 42 | 43 | 44 | 45 | 46 | 47 | 48 | 49 | 50 | total |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| `nobody` | 2 | 1 | 4 | 1 | 0 | 0 | 0 | 1 | 0 | 3 | **12** |
| `no one` | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 1 | 1 | **3** |
| both | 2 | 1 | 4 | 1 | 0 | 0 | 0 | 2 | 1 | 4 | **15** |

**Ch 50 carries three `nobody` — lines 47 ("Nobody does"), 51 ("Spending on nobody at all") and 69
("Nobody has thanked him") — and one `no one` at line 65. That is four.** This file first printed the
`nobody` run as *3, 2, 1, 4, 1, 0, 0, 0, 1, 0*, which puts three in Ch 41 and zero in Ch 50; the page has
two and three. **The `no one` reading (Ch 48, 49, 50) and both totals were right.** The Batch 0005
review's own per-chapter figures (41:2, 42:1, 43:4, 44:1, 45:0, 46:0, 47:0, 48:2, 49:1, 50:4 = 15) count
the two words together and are correct in every cell.

**The correction this file made to `state/current.md` is itself withdrawn.** The state said *"fifteen
times across Batch 0005's ten chapters, four of them in Ch 50"* — which is **exactly right**, and which
this audit replaced with a false claim that Ch 50 carried two. `state/current.md` has been restored to the
true split. **This is the eleventh false certification in this pipeline and the second in this file: it
corrected an accurate file against an inaccurate count of its own, and did so on the strength of a
per-chapter sequence it had not re-run.**

**Correction 9 — `state/chapter-summaries.md` Ch 41 says the Review sits in the sixth week from the
3rd; the page anchors it elsewhere.** *Judgement, traced.* `state/current.md` and `state/continuity.md`
agree that "the sixth week" is the sixth week from the 3rd, the Thursday he declared the reading, and that
the week begins on the 7th. Ch 40 counts forward eleven days from the 26th to reach it, which is
consistent. `state/chapter-summaries.md`'s Ch 41 entry opens with the bare date and does not contradict
anything. **Recorded as checked and consistent; no change made.** This is listed because the prompt asks
for the summaries to be touched **only** where the page contradicts one, and in this case it does not.

---

## What this audit could not settle

Three things. They are recorded rather than guessed at.

1. **Whether Ch 42's backtrack from the 26th to the 22nd is legible to a reader.** The page anchors it in
   its own first line and `state/continuity.md` explains it, but a reader moving through Chapter 42
   without the state file meets a Thursday that is four days earlier than the chapter before it. **Judgement:
   it reads as a deliberate reach back and the anchoring is sufficient.** A reader is not actively mis-served.
2. **Whether the Band 0005 change of the closing construction improved or degraded the endings.** Ch 41,
   44 and 48 are strong. Ch 42, 43 and 49 in particular end on a want that is satisfied inside the same
   chapter, which is a weaker shape than a want that opens forward. **Judgement: it is a weaker shape and
   it is not a reader-breaking one.** Corrected per Correction 4.
3. **Whether the ledger should have grown past 91.** Nothing requires it to. It rose fifty lines in five
   weeks of standing in public rooms, which is stated with a cause and is the only route the book offers.
   **Judgement: correct, and it is the volume's own trap closing behind him.**

---

## Verdict

**Volume 1 is closed, and it closes changed.** The promise is paid, the mechanism was different from the
one planned and the difference was correct, and the cost of the difference is live on the plate and in
every state file that names it. Six scenes, six women, six different changes. Three reversible costs
recovered and nothing else. No thread closed by the ending, which is correct.

**Nine findings. Eight of them are state-file or gate corrections and one is a prose defect that four
certified batches missed.** Eight in a row is the same failure the Batch 0005 review caught and fixed and
then re-created while fixing it, which is worth saying plainly: **the repair checked the construction it
knew about.** The repair phase that comes next should start with Correction 4 and should not be asked to
fix it by reading only.

*Everything in this file was checked by running a command and reading the output, or by reading the
chapter and naming it. Nothing in it is a count standing in for a reading.*

---

## External review of this audit, and what was corrected

**This section is not part of the audit.** An external reviewer read the audit above against the page and
found three defects **in the audit itself**. All three were re-verified before anything was changed, and
all three are now corrected in place above and in `state/current.md` and `state/open-threads.md`. **No
chapter prose was touched. No plot moved. Correction 4's finding stands as a finding and is still
unrepaired.** The three are recorded together because they are one failure wearing three coats: **in each
case the audit ran a narrower test than the finding required and then reported a test it had not run.**

### E1 — Correction 4's reproduction test was mis-specified

**The finding is sound. The command printed beside it does not produce the output printed beside it.**
The test as given asked whether the final paragraph *begins* with "He wanted, concretely," and it returns
**five** — Ch 42, 43, 44, 45, 46. **Ch 47, 48 and 49 embed the construction mid-paragraph**
(`chapter-0047.md:81`, `chapter-0048.md:79`, `chapter-0049.md:80`). A repair pass running the command as
documented would have found three of the eight missing and left them running.

Corrected: the test now asks whether the final paragraph **contains** the string, and prints its real
output — eight. **The mis-specification had already propagated into `state/current.md` item 35 and into
the Volume 2 prompt**, which instructs the next phase to read that item. Both are fixed.

### E2 — Correction 8 was false, and it overwrote a correct state file

The audit reported Ch 50 as carrying *"one `nobody` and one `no one`"* and corrected `state/current.md`
for saying four. **Ch 50 carries three `nobody` — lines 47, 51, 69 — and one `no one` at line 65.** The
per-chapter `nobody` sequence the audit printed (3, 2, 1, 4, 1, 0, 0, 0, 1, 0) puts three in Ch 41 and
zero in Ch 50; the page has two and three. **Only the totals — twelve `nobody`, three `no one`, fifteen
together — survive.** The state file the audit corrected was right in every particular the audit
overwrote it on. **Correction 8 is withdrawn rather than reissued**, the true table is in its place, and
`state/current.md` has been restored to the accurate per-chapter split.

### E3 — a retired construction was re-certified as spent-once, and promoted into a standing rule

§6 certified *nobody thanked him* as *"Spent once, Ch 50's last line, and nowhere else in the volume."*
`chapter-0012.md:19` reads **"Nobody thanked the boy."** Same construction, different object, 38 chapters
earlier. `AGENTS.md` names *nobody thanked* by name among its banned reflexes, so the certification was
promoted into an active standing rule at `state/open-threads.md`: *"The standing answer is spent as
scheduled… No chapter may spend it again."* **The book has used the construction twice; the state believed
once; Volume 2 was locked out of a construction already over budget.**

**A neighbouring row of the same table had the same disease and was found while checking this one.** This
reviewer's own first pass at it asserted, without checking, that the *nobody asked* row "holds". **It does
not hold as written.** Checking it against the page: the **note** in Ola's hand is spent once at Ch 38 and
that part is true, but the **motif** runs **fourteen times** across Ch 11–43 and is deliberate texture, not
a rationed construction. Both halves are now recorded. **The first count in that check was also wrong** —
a case-sensitive pattern returned eleven and missed Ch 34 and Ch 38, which is the same defect a third time
in a different costume. **The lesson below is not optional and is not decorative; it was nearly made again
inside the repair that exists to enforce it.**

**What is now recorded, and it is narrower and more accurate than either the audit's claim or the
reviewer's.** The Batch 0003 review repair had already found this instance and already ruled on it
(`state/open-threads.md`): *a near-miss that does not spend the sentence, and the construction should be
treated as retired and not merely rationed.* **That ruling was correct and the close audit silently deleted
it by writing an absolute negative over the top of it.** The corrected position, which holds both:

- **The sentence** — *Nobody has thanked him* — is spent **once**, at Ch 50:69. Unchanged.
- **The construction** — *nobody thanked &lt;anyone&gt;* — occurs **twice**, Ch 12:19 and Ch 50:69, and is
  **retired entirely**. No Volume 2 chapter may use it in any form, with any object.

**The prose is left alone.** `chapter-0012.md:19` is a boy holding a strap for a crate of boots at the
Cordwain gate, it predates every feeder in the book, and the sentence is doing the thematic work of the
chapter. **The defect was in the record, not on the page, and the record is what has been fixed.**

### On the audit's own closing line

The audit ends by observing that the Batch 0005 repair *checked the construction it knew about*. **That
observation turns out to describe Correction 4 in this file**, which checked a stricter test than the
defect required and so reported a test it had not run. The instinct was right and the execution was the
failure it names. **The operative lesson is now stated once, in `state/current.md`, and it is narrower
than *a count is not a reading*: a command that runs is not the same command as the claim it is attached
to, and a correction made against an unverified per-chapter sequence is a new certification, not the end
of one.**