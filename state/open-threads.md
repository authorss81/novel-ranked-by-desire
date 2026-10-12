# Open Threads

## Volume 2 Batch 0002 — second verification pass, Chapters 61–70

**The batch was already written, reviewed and repaired on disk when this phase opened.** AGENTS.md is
explicit that a completed chapter is not restarted, so this pass read all ten chapters as prose and ran the
gates rather than rewriting them. **One arithmetic defect was found, one word was changed, and two state-file
misattributions were corrected. Nothing else was touched.**

**A count is not a reading, and this pass is the third demonstration of it in this batch.** Every mechanical
gate passes on the batch. The single defect the pass found was a **date**, and no gate has a date criterion:
horizontal rules zero, bold zero, italic zero, planning-register words zero, weekday names other than
Thursday zero, `there is no form`/`no column` zero, `nobody thanked` zero, `He wanted, concretely` zero,
panels one in ten chapters and never repeated, no announced age, **nobody 19 and no one 0, maximum 4 in any
one chapter**, 920
paragraphs with **none over 90 words and a maximum of 89**, and all seventy titles in the book unique.
**A reader tracking the calendar is the only instrument that catches what this batch got wrong.**

1. **Chapter 63's date — FIXED, `chapter-0063.md:265`.** The line said the branch strip had been lying on
   Sun Meiling's table *"for six days"* after arriving on the fourth. **That puts the chapter on the 10th.**
   `state/continuity.md` records Ch 63 as the **5th**, which places it after Ch 64's explicit sixth and on
   the same day as Ch 66 — so the page contradicted the state file, which is precisely the class of error
   `continuity.md` exists to surface. **Three anchors inside Ch 63 agree with the fifth** — *"I have thought
   about it for four days"* (the 1st), *"you have stood still for twenty-two days"* (the 14th of last month,
   the day after the Review spend), and the sheets coming off the wall on the last day of the month — and
   the sixth-day line was the only dissenter. **Changed to "for a day."** One word, one line.
2. **Two summaries pointed at the wrong chapter — FIXED in `state/chapter-summaries.md`.** The Ch 64
   summary ended on *"he is not the only one being counted, and he has not been for eighteen days"*, which
   is not in Ch 64 at all (Ch 64 ends on the RECIPIENT heading that cannot be unasked, and on Sun re-pinning
   her wall); and the Ch 70 summary retold the beat where a filing clerk on Sun's floor takes the branch
   strip off a colleague and none of the four other people in the corridor looks up — **that beat is in
   Ch 63, where she tells it, and Ch 70 refers back to it rather than repeating it.** Both were checked
   with a `grep` against the page before being changed. **Batch 0003's prompt tells the next writer to read
   Ch 63 and Ch 70 in full; a summary that sends it to the wrong chapter is a defect in the only memory
   that chapter range has.**

**Deliberately not changed.** The Ch 63 gloss *"the fortnight she asked for"* in the summaries: the page
reads *"walking out of my door in September and coming back in a fortnight"* and there was also an October
visit, so a fortnight may be exact for the interval being described. **Not a contradiction, and not enough
certainty to spend a word on.**

**This pass did not write `reviews/volume-02/batch-0002.md` and did not certify the batch.** No
self-certification is permitted, and items 22, 28, 29 and 30 in `state/current.md` are four separate records
of what happens when one is. **The judgement on Ch 63's scene, on the irreversible decisions in Ch 62 and
Ch 69, and on whether the batch's cliffhangers are earned belongs to a phase that did not write them.**

---

**Volume 2 Batch 0002 is written: Chapters 61–70, and a separate review run has now read them and repaired
them.** The full findings are in `logs/next.review.log`; the repairs are recorded immediately below and
carried into `state/continuity.md` and `state/current.md`. **Chapters 51–60 have still had no review, and
that remains the standing problem in this repository.** Batch 0002 read them as prose and found one
reader-checkable arithmetic defect in them — recorded below as D1 and in `state/continuity.md`. It was
written around and not repaired, because that batch did not write those chapters, and **nothing in this
repair pass touched Chapters 51–60.**

## Volume 2 Batch 0002 — review repair, completed

**Seven hard errors and four smaller ones. All were fixed in place in the chapters. The batch was not
restarted, no plot was moved, and the prose that was already good — Ch 63's scene, Ch 70's close — was left
alone.** Findings and where each landed:

1. **Meta leak — FIXED, `chapter-0062.md:131`.** The only instance of *Volume Two* in seventy chapters sat in
   the paragraph carrying the batch's irreversible decision. The line is now in-world, and the paragraph
   after it was **added**, because the repair was not only a substitution: the chapter had been framing the
   cost of the strip as the two-day increment, which is not what he sold. **He did not give them four days.
   He gave them a machine on a wall with a bell on it, once a week, for as long as they care to keep
   printing.** Ch 69's closing paragraph already said *"the only part of it he was going to be able to give
   back was four days and a strip of plate paper"*, and it now lands on a lie he can see.
2. **Perrin Sowe dramatized — FIXED, `chapter-0063.md:265`.** `outline/volume-02.md:34` and `:36` put him off
   the page for the volume. The strip is now taken by **an unnamed filing clerk on Sun Meiling's own floor**,
   who looks at it, gives it back, and is not looked at by the other four people in the corridor. **This is
   the better version and it was the reviewer's own argument:** Ch 70 depends on Sowe never having come down
   that corridor, and on the strip having moved through the building as unremarkable paper.
3. **Ch 69 map date and tense — FIXED, `chapter-0069.md:187`.** "Had gone up on the nineteenth," in past
   perfect, on the seventeenth, against `:53` and against `chapter-0070.md:11`. Now forward-looking and on
   the **twentieth**. (The rewrite also removed the only non-Thursday weekday name in the batch, which the
   reviewer's mechanical pass had not caught because it was introduced during repair.)
4. **Ch 69 schedule dates — FIXED, `chapter-0069.md:23` and `:29`.** "Five dates written down in front of
   you on the twenty-seventh," and "in front of you on the twenty-fourth." **Ch 60 puts all five dates in a
   column on the 18th of last month**, which is where they now are.
5. **Ch 69 count — FIXED, `chapter-0069.md:33`.** "Four before the twenty-fourth" followed by six dates with
   the seventeenth duplicated and the 17th and 24th filed as schedule dates when Ch 61 established them as
   standing Thursdays. Now: **three after this one — the 21st on the schedule, the 24th and 31st on the
   standing**, four days apart then three then seven. The adjacent "**eighth** week of the strip" was also
   wrong: the strip commences on the 3rd, so the 31st is the **fifth** week.
6. **Attendance ordinals — FIXED at `chapter-0069.md:161` and `:3` of `chapter-0070.md`; `chapter-0062.md`
   and `chapter-0067.md` checked and found sound.** *The review was right that the ordinals could not all be
   true and wrong about why.* Ch 62 and Ch 67 are correct: the register runs one unbroken count across both
   instruments, so the 3rd is the first kept *of the standing* and the 12th is the **fourth kept** and is
   not a standing Thursday. Ch 67 now says so in the open. Ch 69's "**seventh of the standing, fourth of the
   schedule**" was the impossible one — on the 17th it is the **third of the standing and no schedule date
   at all**. Ch 70's opening claimed "you are fourth, and the fifth is on the thirty-first" and its closing
   said "fifth of the schedule"; the schedule **closes** on the 21st and the 31st is a standing date.
   **The full arithmetic is now written into `state/continuity.md` and is the authority for any ordinal.**
7. **Ch 68's count — FIXED, `chapter-0068.md:71` and `:95`.** 258 was an eleven-year total in the drawer and
   a four-year total on the Office's form and in her answer. **Everything is now eleven years, including the
   request.** "Four weeks to answer" is a turnaround time and was left alone.
8. **Retired construction paraphrased — FIXED, `chapter-0064.md:89`.** *"because there is no rule for one"*
   is the skeleton of the retired *there is no form for this*. Replaced with Ines's own fact: **every form in
   the wing prints the address before the name, so nothing in four years of reading them has ever been built
   to carry a man with nowhere in it, and she stopped looking two years ago and told nobody.**
9. **Dangling "Mine," — FIXED, `chapter-0069.md:5-9`.** The runner's ninth entry now has a referent and
   Lin Hao names it before Runa Sato claims it. **"Seventh floor of the standing" also became "seventh entry"**
   — it was the same confusion.
10. **The increment-as-cost framing — FIXED with item 1.** The weekly standing is roughly four attendances a
    month against three under the old schedule; the change is not the increment, it is that the entire
    cadence now runs off a printed strip in his own corridor.
11. **Title — FIXED, `chapter-0069.md:1`.** *The Second Attendance* contradicted its own last line and
    described the scene rather than naming it. Now ***The Fourth Box***, after the empty one.
    **THE TITLE BANK IS THE SOURCE OF THE ERROR** — `workspace/volume-02/batch-0002/PROMPT.md:11-14` supplies
    `69 The Second Attendance`, and the writer took it as instructed. **That bank is spent and closed, it is
    not to be reused, and a bank entry that contradicts a chapter's own arithmetic must be overridden by
    the chapter rather than obeyed.** *Checked: `The Fourth Box` is unique across all seventy titles and
    under 90 characters.* The batch-0003 bank (`workspace/volume-02/batch-0003/PROMPT.md:13-15`) is
    unaffected and is live.

**Not defects, noted so a later run does not chase them.** The "forty-one minutes" in Ch 61 and Ch 69 is an
intentional motif. The "about forty times" in `chapter-0070.md` is a count of occasions, not an age, and is
inside the no-ages gate.

**The batch's own standing rule holds and was the right rule.** *"A count is not a reading."* Every
mechanical gate passed on the unrepaired text and every one of the seven hard errors was invisible to all of
them. The gates are re-run on the repaired text below.

## What Volume 2 Batch 0002 has opened, after Ch 70

| # | Thread | Status at the end of Ch 70 |
| --- | --- | --- |
| **B46** | **The weekly strip.** The branch plate-office strip goes to the Wing every Thursday, on his shift, in his own corridor, **not a copy**, for the rest of a standing with no end date. It discharges the three ruled lines and holds the interval at seven days. | **Open and irreversible. The batch's decision.** It also arms a dated clock: the band carries three grains of tolerance, he is at 8,138 against a floor of 8,141, and the figure is now printed in public once a week. |
| **B47** | **The flat figure is public.** The Exchange queue has begun saying *flat* out loud and the wrong explanation is assembling itself: a standing that does not rise is a standing with nothing going into it. Garrick Neve declined to correct it. | **Open and worse than it looks.** The wrong answer is simple and it is what a man builds a whole thing out of, and it will finish inside a fortnight unless somebody corrects it. **This is the cost of B46, paid in other people's reading of him.** |
| **B48** | **The fourth book.** A volume the Wing keeps for every entry the register could not take, five headings and a ruled sixth space, his page carrying twenty days of dates since the eighth. **She does not read it, she keeps it.** She wrote the sixth heading herself, in her own hand, on the twentieth. | **Open. Two words long and not on the page.** Alma Quayle is named offstage and is in no room. Volume 7's approach is being built in Volume 2 without being answered. |
| **B49** | **The Office asks where he was, not what he is.** Three ruled lines: days attended, persons spoken with, **addresses**. The register keeps addresses and no faces; his ledger keeps faces and no addresses; the third line is the join. | **Open and now the sharpest institutional threat.** The refusal he made in the sixth week was to surrender faces. It did not touch this, and Ch 61's runner says so to him at a counter. |
| **B50** | **The second attendance.** A nine-year-old procedure, never used: attendance for a person named on an analyst's sheet. Three buff squares dated the **nineteenth** for Nell Ardery, Garrick Neve and the yard checker, with an empty fourth box. | **Open and dated. Not narrated in this batch and not to be invented:** the nineteenth happens offstage. **A source may not be in the room** — Drant's new rule, written on the twentieth. |
| **B51** | **The acknowledgement.** His hand, minuted: the three episodes were caused at his hand, are his cost, and are not evidence against the persons in which they occurred. | **Open and irreversible. The batch's second decision.** It is the same shape as what his brother did in a public hall, it cannot be unsaid, and it cannot be classified because it is not a score, a figure or a conduct finding. **This is the seed of every public reading in Volume 3.** |
| **B52** | **A map of one event.** The thirty-one marks along the Ferrier arc are a pattern of where he walks, not of what he does. The dot is a single spend. If he spends again the dot becomes real and an analyst can draw him. | **Open, and it converges with B40.** Standing still is now doing two kinds of damage: the mass goes flat (Tessa) and the map becomes true (Ruta). **Ruta's third-colour line went up on the twentieth and he was not allowed to read it.** |
| **B53** | **He is a shape with no place in it.** Sun Meiling's finding from eleven years of sheets. Every shape she has has a place; his does not. | **Open, and it cuts both ways.** A map cannot hold a man with no address, and a man with no address can be neither found nor cleared. **The single fact that defeats the Office's map also defeats his defence when somebody comes with paper.** Volume 3's whole problem. |
| **B54** | **PERRIN SOWE.** Named on the consult line and on the respondent's form. Veil-Research, third floor, a window on the yard, nine years. **In no room.** He answered a departmental consult three years ago about a transfer memo with no name; Sun drafted four lines and what went back was his. He took the branch strip off a colleague's hand in the corridor on the fourth and said nothing. **He has never come down her corridor in three years.** | **Open. The thread, not the man.** Volume 2 may name the consult line, the memo and the answer and may not put him in a room. **Whether Lin Wei is alive is unknown to every character on the page and must stay that way until Volume 8.** |
| **B55** | **The woman with the notebook.** A booked seat, no badge, four turns on the Ferrier line, asking operators for their counts and whether they can feel it when it goes. She got his name off a signalman at the Yard end. **Nadia gave it to her in a lift, on purpose, having worked it out first.** | **Open, and she is faster than the Wing.** The Office does not yet know about Nadia and the woman does not know what Nadia is. **Both of those are load-bearing for Volume 3.** |
| **B56** | **The woman in the dark coat.** Now also working Marguerite's porters. Eighteen days. The Office has begun asking the same question she is. | **Open.** Two collectors, no badge on either, and the household is being counted from outside. |
| **B57** | **Beatrix has taken him off her list** since the thirteenth and he has never asked. A passenger is somebody she could refuse, and she told him so. **The ninth of September is hers since June and is now known to three women in the household, who have made a rule about it.** | **Open.** The ungiven word is live: she has used one about four hundred times since June and never about him, because a word commits her to an answer she does not have. **September is untouched and is not this volume's.** |
| **B58** | **Tessa is going to hand her own chart to an Office** on the twentieth, as a control: 258 cases, cause not established, and one case with a cause, her own arms. | **Open, and hers rather than his.** She is the first person in the household to put something into that office on purpose, and the reason is that a control makes two hundred and fifty-eight patients stop being a line. **Volume 10's Ch 483 is seeded here and must not be anticipated.** |
| **B59** | **Ines's sheet is in his coat.** Four sides, going in on the seventh, with **RECIPIENT** printed over a blank twelfth line. | **Open. B31 and B44 have become one physical object and it is on a man who gets taken.** Shared custody is over and she says so without pretending it is a favour. |

**Nothing was closed in this batch.** The query, the file, both calendars, the nineteenth, the twentieth, the
twenty-first, the twenty-fourth, the twenty-fifth, the thirty-first, September and the four true things are
all still live and now all have dates.



**Carried past the Volume 1 close and into Volume 2 planning.** Every thread below was checked against
the page at the close audit and its status updated. **Nothing is closed by a volume ending and this phase
closed none — twenty-six live batch threads and all twelve seeded threads carried forward.** Full working
with chapter-and-line citations is in `reviews/volume-01/volume-close.md` §3. Volume 2 outline
(`outline/volume-02.md`) and Batch 0001 cards (`outline/batches/volume-02-batch-0001.md`) exist and the
batch they govern has been written.

## What Volume 2 has opened, after Batch 0001

| # | Thread | Status at the end of Ch 60 |
| --- | --- | --- |
| **B36** | **The attendance calendar.** 18th kept, 24th kept, then every nine days: the 3rd, the 12th, the 21st of next month, written in a column in front of him. | **Open and dated — the batch's spine and Volume 2's institutional pressure made concrete.** Three of the three written dates fall before the twenty-fifth. The 21st is four days inside it. |
| **B37** | **Ruling 112 is the join.** The ruling number is on his plate and in red ink in the margin of the thirty-first register line. The printed public sheet does not carry the ink. | **Open. The single most actionable fact of the batch.** Any office anywhere can now join a plate to a register line with a number. |
| **B38** | **The names are being assembled without him.** A woman in a dark coat with no paper asked Colm Deveraux for names at the counter of his own floor, said *that was very useful*, and got a second answer about arithmetic. | **Open, and it is the direct consequence of Ch 54's refusal.** He paid with a calendar and it protected nobody. |
| **B39** | **A buff Wing attendance slip under the yard gate tallies**, his name in pencil, rubbed out and rewritten, no date, no box marked. | **Open. The Office has started at the yard instead of at him.** He got it off the checker; the checker wrote his own chart up anyway. |
| **B40** | **A settled mass reads as too well.** Tessa's 261 charts, a rack at twenty-two boards, and a district that improves faster than medicine. | **Open — this is the volume's real engine and it is not classification.** Stillness is the failure condition and the Office does not have to do anything. |
| **B41** | **The thin dated sheet.** Classification paper, prepared, unsigned, in a drawer on the second sub-level. Third sub-level, no window. | **Open and NOT entered.** Shown only as an unopened drawer. **It must not be signed in Batch 0002.** |
| **B42** | **Sun Meiling's one sentence**, held back until he has stood still long enough for a mass to go flat. | **Open. T10 is now started.** The sentence that unlocks Volume 8 is on a page in a drawer on the first floor of Veil-Research and is not read. **Ch 63 is immovable and is where she says it.** |
| **B43** | **Anneke Roos's consult line.** A Veil-Research consult answered three years ago about a transfer memo with no name, initialled S.M., copied eleven times, never read. | **Open. T10's evidence and the only thing that connects the Wing to a research house.** |
| **B44** | **Ines's four-sided sheet** — the line, the arithmetic, the one question. Shown to nobody. Shared custody, not a court order. | **Open. B31 is now shared between two auditors.** The Reading Office has asked her formally for the source of the line; she answered with a question. |
| **B45** | **Ding D. Duarte put her own name on an intake sheet** for a chest, unprompted, four years of being kept away from a doctor. | **Open, and B5 has moved. Lin Hao asked not one question, in a queue of two hundred, and that restraint is now the debt.** |

## What Volume 2 has not opened, and must not

**T1's second folio. The May clipboard. The word *Channel*. The Church. The Unscored.** **Rhee** — no
line, no scene, no mention, and the offer stays closed. **Alma Quayle, Anouk Ferreira and Perrin Sowe
are not on any page** and none of them is a new enemy. **No classification entered.** **No second folio.**
**No scene before Ch 63.** **No new partner started** — Sun Meiling entered as core and unsworn with all
three reasons stated on the page before anything happened, and no other woman entered the household,
refused it, or left.

---

**Carried past the Volume 1 close and into Volume 2 planning.** Every thread below was checked against
the page at the close audit and its status updated. **Nothing is closed by a volume ending and this phase
closed none — twenty-six live batch threads and all twelve seeded threads carried forward.** Full working
with chapter-and-line citations is in `reviews/volume-01/volume-close.md` §3. Volume 2 outline
(`outline/volume-02.md`) and Batch 0001 cards (`outline/batches/volume-02-batch-0001.md`) now exist;
no prose written.

**The standing answer to "does he get thanked" is spent as scheduled: Chapter 50, `Nobody has thanked
him.` No chapter in any later volume may spend that sentence again, and `the record remained` is
untouched across fifty chapters and remains available.**

## What Volume 2 may open and what it must not

**VOLUME 2 BATCH 0001 WRITTEN, Ch 51–60.** Header, starting position and scene schedule in
`state/current.md`; outline at `outline/volume-02.md`, cards at
`outline/batches/volume-02-batch-0001.md`. **Classification held open and never entered. No second folio.
No Rhee. No scene before Ch 55.** T10 is planted, started at 55 and **binding at 63**, which is immovable.

**MAY OPEN.** The held-account pressure — a rank-six petitioner 11,862 grains under his own band, which
is a shape the Office has no procedure for. Alma Quayle noticing the thirty-first entry's finding number.
The Classification Wing register (B16, B29) and Solveig Rask's column. T2, who keeps his file clean
(no answer before Volume 3). T9, Nadia and the floor. B1 Colm Deveraux. B5 Ding D. Duarte. B6 Bernt
Halse and Ditta. B7 the two-year gap — Volume 8, not before. **Opened in Batch 0001: B36–B45.**

**MUST NOT OPEN.** T1's second folio — **Volume 2 must not open a second folio in the first batch, and
Batch 0001 opened none; Batch 0002 must not either.** T3, the Church, before Volume 4. T4, the Unscored,
before Volume 6. T6, T7, T11, T12. **The May clipboard and the word *Channel* are the Volume 5 hinge and
neither has been touched.** Rhee's offer is closed forever and Rhee himself is off the page after
Chapter 30. The Planning-register words — *reservoir*, *quiet account*, *Concil*, *Ninth Seal*, *Channel*
— never appear in prose. **No new final enemy.**

## Seeded at bootstrap

| # | Thread | Lands in | Status at the close of Volume 1 |
| --- | --- | --- | --- |
| T1 | Lin Wei's file: 4,112 folios, 4,111 sealed, one not. Held Account One. | Ch 49–50 | **Advanced by exactly one folio and must advance no further.** Ch 50: transfer receipt, Lin Wei's hand, 214,000 grains, the eleventh three years ago, into an account the index does not contain. Under it in Wing print: the receiver's file is **Held Account One. There is no Held Account Zero.** |
| T2 | Who is keeping Lin Hao's file deliberately clean inside the Bureau? | V3 (Adeyemi) | **Open — planted in Ch 7 and Ch 10 and untouched since. Do not answer before Volume 3.** |
| T3 | The Church of the Quiet Number, eleven thousand members, illegal because it is right. | V4 | **Open — planted hard in Ch 10 and not named again.** A rank-five clerk in grey has filed the same refused petition from the chapel step every morning for three years; four auditors have refused to read it. Four lines planted; do not develop before Volume 4. |
| T4 | The Unscored in the Saltworks cordon. | V6 | **Open — untouched. Not named in Volume 1.** |
| T5 | Tessa Okonkwo's inventory of injuries is running out of room. | V3–V4 | **Open and advanced every batch.** Rack of eleven clipboards (Batch 0003) → twelve (Ch 38) → **seventeen at the close of Ch 49, eighteen before nightfall in Ch 50.** Stippling past the left elbow, pale blue above the joint, right forearm begun. She charts the three new colds herself in Ch 48 and then sits looking at her own arms. |
| T6 | Agnete Lindqvist has not been outside a null room in eleven years. | V4, Ch 169 | **Open — untouched.** |
| T7 | Petra Ilyin is under an eleven-year promise she cannot remember making. | V5, Ch 214 | **Open — untouched.** |
| T8 | Ines is losing her twenties to the records she holds. | V9, Ch 446 | **Open — planted in Ch 8 and advanced.** She says the volume of what she holds (4,109 files in her head, forty files on Lantern Row) but the loss itself is not visible on the page and the word *twenties* appears nowhere in Chapters 1–50. |
| T9 | Nadia can only go down, never up. | V7 | **Open and advanced.** Carried up one floor at a price twice — Ch 29 and Ch 49. She refuses to be spent in her own words, twice: *do not spend me*. |
| T10 | Sun Meiling has waited three years for the right question. | V2, Ch 63 | **STARTED — planted by name at Ch 52 and Ch 53, first scene at Ch 55.** She is core and unsworn and all three reasons are given out loud on the page before anything happens. **She has confirmed to herself that he is the address and not the source, and she agrees to keep working without filing him.** The sentence that unlocks Volume 8 is on a page she has not read to him and will not read until he has stood still long enough for a mass to go flat — **a condition, not a date, and the refusal to give a date is deliberate.** **Ch 63 is immovable.** |
| T11 | Why there is no rank ten. | V9 | **Open — untouched, not hinted.** |
| T12 | Wren Kallo cannot keep a secret, and is therefore already a leak by the time she joins. | V3, Ch 118 | **Open — untouched.** |

## Opened by Batch 0001

| # | Thread | Status at end of Ch 10 |
| --- | --- | --- |
| B1 | **Colm Deveraux's 1,001 grains.** Lin Hao's first wrong-direction spend. The man is frightened, has locked an office, and now knows Lin Hao by name. | Open. Must be paid. A frightened supply supervisor is a supply supervisor who tells somebody. |
| B2 | **The eleven untouchable lines.** Accrual is proximity. The moment he becomes a known quantity to any of them the rate drops. | Open. This is the engine of the whole book and Batch 0002's first public act tests it. |
| B3 | **Nadia Ferrous has told the entire Vestry arcade**, including a man from the Church of the Quiet Number who took notes. | Open and urgent. She is 23, loud, entirely an adult, and has no idea what she is doing. |
| B4 | **Ola Bright's notebook.** Forty-one pages, eleven entries over four months from the 4th of June, never four in a week, two places. Her sister's open mouth plus her pencil is a triangulable pattern. | Open. Three episodes is the reportable threshold. |
| B5 | **Ding D. Duarte.** Petition 4118 — filed *by Ines*, re a dependent sibling — the long stair, 300 grains, refused in four days. Alive, in the Vestry, unnamed in the ledger. | Open. The first name in his brother's objection that Lin Hao can prove. |
| B6 | **Bernt Halse**, taken Thursday the 9th at ten past ten in the morning — twelve hours before Lin Hao put account into Colm Deveraux, at the same clock time — and not out. Ditta on the Vestry benches since six on Friday. | Open. Lin Hao has done arithmetic with his face about it and concluded he did not cause it. The reader is not permitted an answer either. |
| B7 | **The two-year gap in his own file** and the cross-reference card. | Open. Do not resolve. Volume 8. |
| B8 | **Tessa Okonkwo's cold-store box.** Relieved bodies present as too well. | Open. Her first scene is Chapter 26; the box is the reason she is interested. |
| B9 | **The audit opens Monday the nineteenth.** Eight days away at the close of Chapter 10. Nine of ninety-one go down. Lin Hao knows he is one of the nine. | Open — Batch 0002's clock. |
| B10 | **Ines cannot file what she knows.** She has an illegal premises register requisition at four in the morning and Hester Quill has written her face down. | Open. Her exposure is now on paper in two places. |

## Opened by Batch 0002

| # | Thread | Status at end of Ch 20 |
| --- | --- | --- |
| B11 | **Beatrix's four years.** Turned-line geography of the Ferrier arc, plus one name in the back already on a staff register. | Open — his only uninterceptionable source, bought with a promise to spend on people. |
| B12 | **Rank five held.** 8,141 grains, white tile, private office, right to be asked. First tile move in his life. | Open — what five buys against the draw-down and the Field. |
| B13 | **Tobias filed to Rhee.** Discrepancy reported honestly out of branch loyalty; he has the other eight unsettled names on a sheet and files Fridays, and Lin Hao is number four on it, and he said *I did not put you there* and gave him **about six weeks**. | Open — did the Field order predate Tobias? The six weeks is the same six weeks the Winter Review sits in, and that is now on the page in Tobias's mouth. |
| B14 | **Rhee's offer.** Fully specified on the page: plate reissued in the branch name, four times a week for two hours in the deputy's own room, on the record, credited to the Branch and not to him. Audit deferred **fourteen days** against the nine he asked for. | Open — employment vs ownership; his only deadline spent. Rhee said out loud that the day he wants out is the day an office asks a question. |
| B15 | **Runa Sato's sealed order and file.** Looked at him before Rhee's door. Wax seal as on his brother's card. She says the order is neither Rhee's nor Tobias's, was written **before the twentieth**, and that she has read four other files this month of people who fit the same shape. | Open — who wrote it, how much true, and how many people fit the shape before him. |
| B1–B10 | Carried. Colm still locked and frightened; eleven untouchable lines now nineteen with a map and a favour unpaid to Beatrix not to spend anybody new until the ninety-one are read; Nadia louder (fourth minute, charging rent joke); Ola's book left with her plus Church notes already out; Ding alive unnamed in ledger; Bernt still down, Ditta on benches; gap unanswered; Tessa box waiting; audit deferred not lifted; Ines exposure unchanged. | Open. |

## Deliberately unanswered at the end of Batch 0001

Who filled the account before Wednesday. Why Nadia Ferrous had already felt a cold minute before Chapter 4.
What it costs him to be visible. Whether Colm Deveraux will report. Whether Ines's illegality is the
last of it. What a fourth cold minute in a Vestry lift does to a woman with an exercise book.

## Deliberately unanswered at the end of Batch 0002

Superseded in part by Batch 0003 and kept because four of the six are still open. Who wrote the Field
order, and why it was written before there was anything on the record worth ordering — **partly answered
in Ch 21: the order was not Rhee's and not Tobias's, and it was written about a shape, not a man.**
Whether the name in the back of Beatrix's TURNED column is a Branch rota name — **answered in Ch 23:
it is Emrys Vaz.** Whether the held 3,529 can be held back next time, and if not, whether the band can
be taken off a man as easily as it is put on — **still open and now heavier, because Batch 0003 proved
that an account can be published by a machine.** And what Beatrix means by September — **still open,
still her.**

## Opened by Batch 0003

| # | Thread | Status at end of Ch 30 |
| --- | --- | --- |
| B16 | **The Classification Wing register.** Nine years old, thirty-one accounts, plate numbers and no names, opened by hand in pencil before the form was printed. The oldest entry is the only one still running and predates Lin Wei by six years. | Open — the largest open question in the book and the direct engine of Batch 0005. Runa Sato had never seen the page before the 10th. Do not resolve before Volume 2. |
| B17 | **The second person.** Tessa's clipboard dated the second of May: a man who came in with shaking hands at 2,640 and went out shaking, four months before Lin Hao ever aimed anything on purpose. Same figure as Teodor Mace's, two months later, in a counting house. | Open — the channel answer. Tessa has the date and the figure and has not asked. Lin Hao has not offered. This is the Ch 48 hinge. |
| B18 | **Tobias Renn off the filing register.** Twenty-nine months of correct filings re-opened by hand, then the boxes in the sub-levels' annexe, no deputy arranged. He filed himself, in the front of his own file, in four true lines, and refused the witness line he offered. | Open — he is the only person in this book destroyed by a true document, and he did it to himself because Lin Hao was silent. He is owed something and he will not be forgiven in a speech. |
| B19 | **The five struck through.** Ottoline Barret, Emrys Vaz, Tobias Renn and two others unsettle on the 3rd and were struck off the board by a declaration rather than by evidence. If the declaration is ever found to be wrong, all five are back. | Open — a lever with a date on it. The quarterly re-read is the first place it can be pulled. |
| B20 | **Emrys Vaz, 441.** Handed a plate at the north gate on the 3rd for the first time in his life, one of the three ticks in Beatrix's column, and back on the yard rota at six by the 10th having said nothing to anybody. He understood all of it in a corridor and has no words for it. | Open — a witness who knows what he is looking at. **T9 stays open: he can only go down.** |
| B21 | **The fifth figure.** 8,141 printed on a public tile because a declared unsettled reading cannot be banded. The raw figure of nineteen people is now in the largest type in Ostara, on his name. | Open — the machine has published the account. Everything he did to stay illegible is on a wall, permanently. |
| B22 | **Ines's paper.** She has his written undertaking not to use the rota name for a month, signed, against her chest. The month expires around the 20th of next month. | Open — she will ask, and what he tells her is a decision, not a fact. |
| B1–B15 | Carried. Colm still locked; **Beatrix's favour discharged** on the 3rd and her three ticks therefore still where they were; Nadia in the household and uncontainable; Ola's book in her hands; Ding alive and unnamed in the ledger; Bernt still down and Ditta on the benches; the gap unanswered; Tessa's rack now eleven; **Rhee's offer closed forever**; Tobias's register gone; Ines's exposure unchanged. | Open. |

## Deliberately unanswered at the end of Batch 0003

Who fed the account before the register was opened by hand in pencil, nine years ago, and why the oldest
of the thirty-one is the only one still running. What the second person did in May and why they stopped.
Whether the 2,640 on Tessa's clipboard and the 2,640 on Teodor Mace's plate are the same account
moving, which would mean the routing has a route of its own. What Runa's office does with a man whose
exact figure is now printed on a tile. What Tobias Renn will do with the one true thing he has, which is
that he was offered a witness line and refused it. And whether a man with nineteen people, who can only
ever have those nineteen, can climb to six without spending one of them.

**The standing answer is still no, at the top of all of them: nobody thanks him, and no chapter may
arrange for anybody to.** The Batch 0003 draft put "there is no version of the week in which anybody
thanked him" into Chapter 30 and it was cut, because Chapter 50 owns that sentence.

## Opened by Batch 0004

| # | Thread | Status at end of Ch 40 |
| --- | --- | --- |
| B23 | **The statement he filed against himself.** Ch 39: five names struck by declaration and not by evidence, Emrys Vaz named, plate 441, his own hand and signature, in the front of Runa Sato's file above the observation of the 6th. It put five names back on the branch board and opened a Reading Office query against his own standing. | **Open — the batch's central irreversible decision.** He gave away the only thing protecting ninety-one colleagues in order to file the truth about one boy. It is not repairable by retracting it. |
| B24 | **The Reading Office query.** A query wants an instrument. The clerk who entered his reading on the 3rd owns it and cannot invent one. He can petition sealed files at six — after the 29th, if he holds the band at all. | Open — the mechanism that turns his own filing into an instrument he has to earn. Batch 0005's clock. |
| B25 | **A provisional band is not carried into review.** Printed on the queue sheet on the 24th, two days after his filing. The Review strikes the band off the figure on the day, in a room, from the plate. 8,141 is a five. | Open — closes his six at the Review and is the reason Batch 0005 exists. |
| B26 | **Eleven thousand eight hundred and sixty-two grains.** Band six opens at 20,000; published standing is 8,141; a witnessed deed scores 400; he needs twenty-nine in six weeks and has nineteen people and no twentieth. *(This cell read 11,859 until the `volume-plan` review. That figure belongs to a plate reading 8,137, which the Batch 0005 repair changed to 8,138 at Ch 47. See `state/current.md` item 31.)* | **Open — NOT closed by Ch 48, and this is now the sharpest fact in the book.** He holds six on an instrument and the plate still reads 8,138. Nothing the account did was converted into a grain. Volume 2 starts 11,862 grains short of the band he is standing on, and the Classification Wing is the party that would like to know how. |
| B27 | **Tobias Renn is on a board again**, third one down, because of a statement the declarant filed himself, eight days after signing an employer attestation that was not a favour. | Open — B18 deepened. He has still not been thanked and will not take it in a speech. |
| B28 | **Tessa's rack is at twelve** and she is taking four a day and has crossed her left elbow. She will not stop. She has asked him once a month to say the number out loud to her, and not the names. | Open — the cost of the climb has a body on it. T5 continues. |
| B29 | **Solveig Rask's column of thirty-one plate numbers over nine years**, and a valuation requiring a rate known to two people. His is the thirty-first, entered on the 3rd, and it is the only entry with a date in the last eleven days. | Open — the register's engine. **Do not resolve before Volume 2.** |
| B30 | **A broker in Bellhouse told the Vant house that a man in a washroom asked for the date instead of the money.** Marguerite Vale said she was sorry about it. | Open — pays off at Ch 45–46. The refusal was published inside the house and that is why the terms come back. |
| B1–B22 | Carried. Colm still locked and frightened; Nadia uncontainable and refusing to be spent; Ola's book now has twenty-two entries in a week; Ding alive and unnamed in the ledger; Bernt still down and Ditta on the benches; the gap unanswered; **Tessa's May clipboard untouched, as required**; Rhee's offer closed forever and not re-opened; the ninety-one back on the wall from the 26th. | Open. |

## Opened by Batch 0005 — status at the Volume 1 close

| # | Thread | Status at the close of Volume 1 |
| --- | --- | --- |
| B31 | **The himself line.** Ninety-one lines, eight turned, one reading himself. | **Open — Volume 2 engine.** No auditor has seen it. Ines says in Ch 49 that she does not know what a Bureau does with a line it has never had to read, and that she cannot decide whether to file it, which is not the same as deciding not to. |
| B31a | **The himself line, after Batch 0001.** | **Still unfiled and now on two desks.** It was **stated aloud and dictated into a minute in a Wing inventory room** in Ch 58 — one line, reads himself, permanent, the office has it by his mouth and not by any hand. Ines has it on a four-sided sheet in her own rooms. **Runa Sato refused to answer for it in writing.** Two auditors and a clerk now hold it and none of them has filed it. |
| B35 | **Held six on an instrument.** The band came off a requisition, not off merit, and the open-question answer supplied the instrument. | **Open — Volume 2's institutional pressure, and the volume's live consequence.** A rank-six petitioner standing **11,862 grains under his own band** is a shape the Office has no procedure for. **20,000 − 8,138. Never closed by a score and cannot be.** |
| B32 | **Three new turned at once.** Nell Ardery, Garrick Neve, yard checker. Three in four seconds in a room. | **Open.** Ines names the consequence in Ch 49: *an analyst could put a dot on a wall map and the dot would be that room.* |
| B33 | **Held Account One.** Transfer receipt 214,000 grains, Lin Wei's hand, account the index does not contain. No Zero. | **Open — T1 advanced by one folio. 4,111 sealed. Volume 2 must not open a second.** |
| B34 | **Beatrix's broken price.** Cab promise broken in the square. | **Open — named without heat, not forgiven in a speech.** September still hers. |
| B23–B30 | Declaration stands with the finding number beside it (Ch 49, Ch 50); query closed by witnessed answer; provisional replaced by held six, **seated on an instrument and not on merit**; the 11,859 is **still on the plate** and was never closed; Tobias off the board by instrument but the declaration remains; Tessa at seventeen boards; Solveig's column came off the table at Ch 46; the Bellhouse house behind him unsigned. | **Open.** |
| B1–B22 | Colm still locked and frightened (**untouched since Ch 6**); Nadia at three and unspent; Ola clerking; Ding alive and unnamed in the ledger; Bernt still down; the gap unanswered; **the May clipboard untouched**; Rhee's offer closed forever and Rhee himself off the page after Ch 30. | **Open.** |

## What the close audit corrected in this file

- **The residual age census is seven, not five** *— superseded, twice over.* The close audit added two
  unregistered instances to the five: **`chapter-0002.md:21`** ("He had spent twenty-five years wanting a
  number") and **`chapter-0037.md:57`** ("since he was fifteen years old") — **both Lin Hao, both in
  narration** — together with **`chapter-0046.md:37`** ("I am forty-one years of keeping books for money",
  Marguerite Vale, in dialogue). **The `volume-plan` review then added a ninth and found that this label
  had been saying seven against a table of eight.** **The governing figures are now nine chapters and ten
  announced ages, five of them the protagonist or a core partner, and the table under *Canon-change flags
  raised by the Batch 0003 review repair* is the one that governs.** Canon is not contradicted at eight of
  the ten; the prose rule is. **A grep will not find the Chapter 20 instance** — a writer making a
  deliberate decision registers it here at the moment of the decision.
- **The canon-change guard's list of "five residual ages" is replaced in full** by the table above. Nothing
  is adopted, nothing is repaired, and the earlier entries stand as written.

## Deliberately unanswered at the end of Batch 0005

Who fed the account before the register’s hand-pencil entry nine years ago. What the 214,000 bought its receiver, and why the receiver’s file is One with no Zero. What a himself line does to a ledger across a season. Whether held six survives Volume 2’s measurement. And whether giving the rota word would cost Ines or save her.

**The standing answer is spent as scheduled: Nobody has thanked him (Ch 50). No chapter may spend that
sentence again.** **And the construction behind it is retired, not rationed** — *nobody thanked &lt;anyone&gt;*
is spent **once**, at `chapter-0012.md:19` ("Nobody thanked the boy."). Ch 50:69 is *"Nobody has thanked
him"*, a different construction. **No chapter in Volume 2 or after may use it with any object.** The close
audit briefly certified the construction as spent-once-and-nowhere-else and wrote an absolute negative
over the Batch 0003 ruling below; that certification was false and is corrected. See item 45 in
`state/current.md`.

## Deliberately unanswered at the end of Batch 0004

Why the oldest of the thirty-one register entries predates the printed column and is still running. What
the second person did in May and why they stopped — **Tessa's clipboard is still on the table in Chapter
38 and he still did not say a word about it.** Whether Solveig Rask's valuation is right. Who reads the
document he filed and what they do with it on the 29th. Whether giving back the ninety-one was worth one
boy. And whether a man who cannot climb and will not spend anybody can be six in a room in six weeks.

**The standing answer is unchanged: nobody thanks him, and no chapter may arrange for anybody to.**

## Adjudicated contradictions — closed, do not re-open

Seventeen canon questions were decided before or during Batch 0001, three more during the Batch 0002
review repair, one more during the Batch 0003 pass and four more during the Batch 0003 review repair.
The full list with the reasoning is in `state/current.md` under **Adjudicated contradictions**. In short,
so that a later phase can tell a settled question from an open one:

- The brother's file opens at **Ch 372** on a rank he does not hold; rank nine at 409 buys him nothing
  about it.
- **Ines's Volume 1 scene is Chapter 8.** Chapter 17 is Beatrix Halm's, and this is not to be revised.
- **Twelve partners, nine sworn in.** Four women can leave: Ines (out 246, back 271), Wren Kallo, Sun
  Meiling, Dagmar Oyelowo. The law binds the plate and the bond, **not** shared quarters.
- The Channel is **Volume 5**, not Volume 4.
- The book is **ten volumes**. The "nine volumes" in `premise.md`, `ending.md` and `characters.md` mean
  *nine before the last* and are correct.
- **No age is stated in narration anywhere in Chapters 21–30** — **this was certified and it was false
  too.** The claim was made after a first certification for Chapters 11–20 was found false, it was put
  in `reviews/volume-01/batch-0003.md` as verified, and `chapter-0028.md` stated a walk-on's age in
  prose while `state/chapter-summaries.md` carried "A man of sixty" on the line above it. Corrected on
  the page and **withdrawn, not reissued.** The equivalent claim for Chapters 11–20 was false for the
  same reason: Ch 16 and Ch 18 each state Emrys Vaz's age. A certification that outlives the page it
  certifies is worse than no certification. **Match bare number-ages in dialogue as well as narration.**
- **All three escalations of *there is no form for this* are spent and none remain before Volume 7.**
  Neither is *there is no column for it*, and a **paraphrase of the first was cut from Chapter 27** in
  the Batch 0003 pass. Sweep for the construction, not for the exact wording.
- **A System panel is never repeated.** It appears only where the count turns, at most one per chapter.
  Batch 0002: Chapters 13 and 19. Batch 0003: **Chapters 25 and 30**, and the two panels differ.
- The grain spine is 4,012 → 4,412 → 4,612 → **8,141**, and the last step is a held Branch aggregate he
  cannot repeat. **The figure does not move in Batch 0003.** It is 8,141 at Chapter 30 and must still be
  8,141 at the start of Batch 0004. There is no second aggregate and there never will be one.
- **The ledger is nineteen lines and lines only ever rise.** Nineteen lines at the end of Batch 0003
  with **five** turned. Forty-one in Batch 0004, ninety-one in Batch 0005. Any plan to take it to
  seventeen is wrong.
- **The ledger count held steady for a stated reason**, not by accident: he gave up the long ride on the
  29th, so the figure keeps moving and the faces stop coming. No later batch may have the count stop
  for any other reason.
- **No weekday name is canonical in this book.** Count in dates and intervals. Only Thursday and Monday
  the 19th may be spoken, and only where the world turns on them. **Batch 0003 is clean and is not the
  whole book: fifty-eight illegal names survive behind Ch 20 and are now item 23 in
  `state/current.md`.**
- **Every chapter lands between 1,800 and 2,700 words.** A gate exists in the prompt and the cards.
  Batch 0003 landed at **2,048–2,698, mean 2,380**.

## Canon-change guard

Any proposal to change a fixed canon item, to move a character's age, to reschedule a scene, to change
the ending, or to introduce a final enemy not already named here goes in this file as a flagged
proposal with a reason, before it is written into a chapter. It is not silently adopted.

**Reconciled, no canon change.** The household is **twelve partners, nine sworn in.** Wren Kallo, Sun
Meiling and Dagmar Oyelowo are not on the standing household roll recognised at Chapter 402, each for a
stated reason, fixed in `bible/characters.md`. The roll binds the plate and the bond, **not** shared
quarters, which is what lets Ines Duarte be sworn in at Ch 402 while keeping her own rooms on Lantern Row
after Ch 271. Any batch that puts a fourth woman outside the sworn nine, that has a sworn woman leave
without explaining it, or that puts Ines back under his roof, is changing canon and must flag it here
first.

**The four who use the option to leave, fixed and countable:** Ines (out at 246, back at 271), Wren
Kallo, Sun Meiling, Dagmar Oyelowo (each refusing the plate and the quarters, for the reasons in the
characters file). The old wording — "two who can leave" in the series outline against "at least three"
in the themes file — is closed; both now say four, and they mean the same four people.

**Closed:** the Chapter 10 card was headed *Not Back That Shift* while the fixed title bank in
`outline/volume-01.md` gives that chapter as *No One Keeps the Diary*. The title bank governed, the
chapter was written under it, and the card heading has been corrected to match. No canon change.

**Known and accepted: two short scene gaps in Volume 1.** Chapters 26 and 29 are three apart and 29 to 36
is seven, against a soft floor of eight. Both are locked inside Batch 0003, whose climax is specified as
Ch 26–28 and whose title bank gives Ch 27 to the Thursday line; separating them would break the batch
plan. Every other gap in the book is between eight and fourteen. Do not "fix" these in a later batch by
moving Tessa's or Nadia's scene — if it ever must be fixed, it is a Volume 1 re-plan, flagged here
first.

**Closed:** Volume 10's fifth scene was scheduled at Ch 492 with the wording "nine women, one account,"
which described the Ch 473 household argument that `outline/ending.md` already owns. The table entry now
sits at **Ch 494** with `ending.md`'s own dispersed-household wording. `ending.md` governs; the table
followed. Chapter 447's "Final scene" is now **Ch 446, the close of the climb** — Ines opens the last
volume at 454 — and `T8` above was repointed to match.

## Canon-change flags raised by Batch 0003 — adopted, none contrary to canon

These are recorded because a later phase must be able to tell a decision this batch made from a
decision it inherited. **No canon was changed, no age was moved, no scene was moved, and the planned
ending was not touched.**

- **Rhee's offer is closed permanently in Chapter 28.** `bible/characters.md` and the volume outline
  treat it as live. It is now on the page as refused, in the exact mechanism Rhee specified, with the
  refusal cost in front of the reader in the shape he described. **It does not come back in Volume 1**,
  and Batch 0004 may not re-open it.
- **Beatrix's favour is discharged** as of the 3rd, because the ninety-one were read. Her three ticks
  stand where they were. The ninth is still her, in September.
- **The Ines debt is discharged** in Chapter 22 and the uncomfortable half of it is the transaction,
  not the book. No later batch may re-run this scene.
- **The ledger holds at nineteen lines with five turned** and this is stated on the page with a cause,
  not left unexplained. Lines rise to forty-one in Batch 0004 and ninety-one in Batch 0005.
- **The fifth figure on the public tile is 8,141**, the exact grain figure, and the reason is a real
  institutional one: a declared unsettled reading cannot be banded. **The Board gains a fifth figure on
  one tile.** This is not the Volume 10 second line (`UNRECORDED — CARRIED BY`), which must not be
  anticipated, repeated or referred back to. The two are different facts in different volumes and a
  later phase must not let one become the other.
- **The Classification Wing register is nine years old with thirty-one entries.** It is a new piece of
  world. It is a Volume 2 engine and it does not answer T2, T3 or the brother's file.
- **Tessa Okonkwo is a turned line** as of Chapter 26, and **Beatrix's fourth year of counting is
  unaffected.** Neither is a household change. No woman's plate, bond or quarters are altered.
- **The census of residual announced ages is NINE chapters carrying TEN instances, not five, not seven.**
  `state/current.md` item 25 and this file both carried five. The close audit found two more and neither
  had ever been registered. **A third, in Chapter 20, was missed by the close audit and by every gate before
  it, and was found by the `volume-plan` review.**

| Chapter | Line | Text | Whose | Canon |
| --- | --- | --- | --- | --- |
| **Ch 2** | **21** | "He had spent **twenty-five years** wanting a number" / "He had wanted it since he was **nineteen**" | **Lin Hao** | **TWO instances, and CONTESTED — see below** |
| Ch 3 | 29 | "an ordinary man **in his forties** on a tram" | walk-on | — |
| Ch 8 | 297 | "said by a woman **in her thirties** in a lamp-lit room" | walk-on | — |
| Ch 16 | 31 | "he is **seventeen**, and he has never in his life been asked to attest anything" | **Emrys Vaz** | correct |
| Ch 18 | 39 | "a man called Emrys Vaz who is **seventeen**" | **Emrys Vaz** | correct |
| **Ch 20** | **67** | "a thing he had been able to do since **he was nineteen**" | **Lin Hao** | **correct** |
| Ch 29 | 91 | "I have had **twenty-three years of my life** and I would like that noted" | **Nadia Ferrous** | correct |
| **Ch 37** | **57** | "since he was **fifteen years old** and had spent ten years not being it" | **Lin Hao** | correct |
| **Ch 46** | **37** | "I am **forty-one years** of keeping books for money" | **Marguerite Vale** | correct |

  **Nine chapters, ten instances. Five of them are the protagonist or a core partner** — Ch 2, Ch 20,
  Ch 29, Ch 37 and Ch 46. Ch 37 is the proof that the same man is aged consistently elsewhere: fifteen plus
  ten years is twenty-five, which is Lin Hao's canon age. Ch 3, Ch 8 and the two Emrys Vaz rows are a
  walk-on, a walk-on, and a feeder who is not one of the core five.

  **`chapter-0002.md:21` is the one row that cannot be certified, and it is the reason the census is not
  simply "ten correct instances."** The same paragraph says he spent **twenty-five years** wanting a number
  and that he had wanted it **since he was nineteen**. Lin Hao is **twenty-five** (`bible/characters.md`),
  so the wanting began six years ago. Twenty-five is his age, not a duration, and the sentence reads as a
  duration. **Flagged, not rewritten**: Ch 2 is a certified opening chapter and a repair pass that touched
  it uninvited would be exactly the wide ripple this census has refused twice. **A Volume 2 writer must not
  build on "he has wanted it since he was nineteen" as a load-bearing span without deciding this first.**

  The gate must match a bare number followed by *years of &lt;gerund/noun-phrase&gt;* and *since he/she was
  &lt;number&gt;*, not only *years old* and *aged*. **None of the nine unstruck.** Ch 20:67 slipped because no
  gate had ever swept Chapter 20 — the census was built chapter by chapter as things were found, and the one
  chapter nobody thought to sweep was the one that had it.
- **The lesson, which is now the operative rule for Volume 2:** an auditor looking for ages will find
  mistakes and will not look for decisions, so **a deliberate instance has to be registered by whoever
  makes the decision. A grep can never be the thing that finds it.** *And the second half, learned the hard
  way here: a census whose own table disagrees with its own label is not a census. The label said seven
  while the table listed eight, and four files repeated the label rather than the table.*
- **`chapter-0012.md:19` reads "Nobody thanked the boy."** A near-miss on *nobody thanked him*, which is
  Chapter 50's and unavailable earlier. It is a boy holding a strap for a crate of boots at the Cordwain
  gate and it predates any feeder, so it does not spend the sentence — but it is close enough that the
  construction should be treated as **retired** and not merely rationed. Logged, not changed.
  **CONFIRMED AT THE CLOSE AND STILL BINDING.** The Volume 1 close audit certified the construction as
  *"spent once, Ch 50's last line, and nowhere else in the volume"* — false, and it deleted this ruling by
  writing over it. **This entry governs: the sentence is Ch 50's, the construction is spent once and is
  gone for good.** The prose at Ch 12:19 stands and is not to be altered.
  *("spent twice" was the wording here and it was wrong. Ch 50:69 reads **"Nobody has thanked him"**, which
  is a different construction; `grep -rniE "nobody (ever )?thanked" chapters/volume-01/` returns **one**
  hit. Only the count was wrong. The retirement is unaffected and stands.)*
- **Fifty-eight illegal weekday names survive behind Chapter 20** — Ch 1 (6), 2 (4), 3 (4), 4 (7), 5 (5),
  6 (8), 7 (7), 8 (3), 9 (2), 10 (9), 11 (1), 19 (2); Chapters 12–18 are clean. Three are bare:
  `chapter-0002.md:109`, `chapter-0006.md:19`, `chapter-0006.md:27`. **Flagged as an open repair, not
  fixed**, for the same reason as the ages: nineteen certified chapters is not a file to rewrite inside
  a review repair. **Confirmed at exactly 58 by the close audit**, counting every non-Thursday weekday
  occurrence less the two permitted *Monday the nineteenth* in Ch 4 and Ch 5. **Chapters 20–50 are clean.**

## Canon-change flags raised by the Batch 0003 review repair

- **Nadia Ferrous's age was wrong on the page.** `chapter-0029.md` had her say she had "had twenty-eight
  years of my life." `bible/characters.md` fixes her at **23**. **Canon governed; the page was corrected
  to twenty-three.** No canon changed — the age was never moved, it was contradicted, and the
  contradiction is removed. Logged here because the age gate missed it: the gate scanned narration and
  this was dialogue, so the gate now matches bare number-ages in speech as well as narration.
- **A walk-on's age was struck from Chapter 28** ("the man at the front was about sixty"), because the
  batch had certified that Chapters 21–30 stated no ages anywhere. The certification is withdrawn rather
  than rewritten, and `state/chapter-summaries.md` no longer carries "A man of sixty".
- **`reviews/volume-01/batch-0003.md` was written by the batch it reviewed**, in the same commit as the
  writer work, and it certified two claims the page contradicted. The file now carries the external
  findings that overturned it. **A writer's own review is not a review**, and no batch after this one
  may treat its self-certification as the gate.
- **No planned plot moved.** Ch 30's account register was tightened where narration flatly converted
  "entries are not persons" into "thirty-one people"; the conversion is now his inference, which is what
  the page was already doing two lines later. One spent construction in Ch 27 was re-angled. Nothing
  else in Chapters 21–30 was touched, and no scene, beat, decision or ending changed.

## Canon-change flags raised by Batch 0004 — adopted, none contrary to canon

Recorded because a later phase must be able to tell a decision this batch made from one it inherited.
**No canon was changed, no age was moved, no scene was moved, and the planned ending was not touched.**

- **Rhee's offer was not re-opened.** The Batch 0003 flag closed it permanently in Ch 28. It does not
  appear anywhere in Chapters 31–40, including by implication.
- **Marguerite Vale does not have a scene in this batch.** She is in Bellhouse in Ch 32 and Ch 33, refuses
  to take the terms down, and is not in the room again. **Her scene is Chapter 46** per the volume
  scene schedule and is not available earlier.
- **Solveig Rask does not appear.** She is named, her books are on a table, and four lines in her hand are
  read aloud. Her arithmetic is correct about the 400 first entry, which is the frightening part, and it is
  left unresolved.
- **The ledger rises to forty-one lines with five turned**, and the rise is on the page with its cause
  stated in Ch 34. **Lines only ever rise.** He spends nobody in this batch, so the turned count holds for
  the first time while the line count moves. **T9 is unaffected: Emrys can still only go down.**
- **The batch's irreversible decision is Ch 39**: he refuses Runa Sato's document, dictates his own, and
  gives up the wall of ninety-one names to file the truth about one boy. Five names come back on the board
  on the 26th. This is the escalation step from *manipulating* to *breaking*, and it is deliberate.
- **Tessa Okonkwo's cost has worsened on the page** and **her rack is at twelve**. This is T5 advancing,
  not a new thread and not a changed canon. Her forearms are worse, not healed.
- **Ines's paper is discharged** — the month ran out on the 20th and she stated the rota name out loud in
  Ch 38. He did not give her the word. **B22 is spent and must not be re-run.**
- **The May clipboard is untouched.** Tessa's second-of-May clipboard is on the table in Ch 38 and in the
  corridor board of Ch 40 and he says nothing about it in either. **This is the Ch 48 hinge and it was not
  spent.** The word Channel does not appear anywhere in Chapters 31–40.
- **A known date wobble is flagged, not fixed.** The Batch 0004 card for Ch 31 says *at nine on a
  Thursday*; Ch 30 fixes the 10th as a repaint-and-publication Thursday and Ch 31 is the 11th. Weekday
  names are not canonical in this book, the page never names the day, and nothing a reader can check is
  wrong. **The card line is the leftover.**
- **The Batch 0004 card for the Volume 1 ledger line said the count would go *down*** ("he stops spending,
  which is the first time the count goes down") in `outline/volume-01.md`'s Batch 0004 block. What goes
  down is the *turned* count, which holds at five because he spends nobody. **Lines rise to forty-one.**
  The page is right and the outline's phrasing is ambiguous; no change made to either.

## Canon-change flags raised by the Batch 0004 review repair

An independent review read the batch after the batch that wrote it had certified itself. **No canon was
changed, no age was moved, no scene was moved, no irreversible decision was re-opened, and the planned
ending is untouched.** The flags are recorded because a later phase must be able to tell these from
decisions this batch made on purpose.

- **The Chapter 36 scene was summarised, not written, and the batch's review certified it.** Lines 93–105
  were 305 words carrying one physical line; the Scene gate checked consent, wakefulness, the
  impaired-state ban and the injury logic and never asked whether the scene was on the page. **The scene
  has been written in full.** `AGENTS.md` on Adult Content is unambiguous: *the scene is the product.*
- **Ch 36 is now 3,349 words and is the one chapter of the batch outside 1,800–2,700.** It was left there
  rather than trimmed, because the repair that made it long was the repair that made it a scene, and
  `AGENTS.md` is explicit that chapter length follows the arc and is not a hard limit. **A later phase
  may not cite this chapter as precedent for running long.** The two scene chapters before it ran 4,761
  and 4,066; Ch 29, the other scene, ran 2,299.
- **A location contradiction inside Ch 36** — number 6 in the morning, number 11 at night, nothing moving
  her between. The day is now at number 6 throughout, with the move up one floor at four o'clock on the
  page. **Number 11 is Halvard Rees's flat** and is fixed as such.
- **Ch 40's Reading Office clerk unfolded her arms twice without refolding and used *nineteen years* in
  both speeches.** The second speech was rewritten and the duplication is gone. It now runs on the machine
  taking what is on the desk and going out to find it a rank, which is the Ch 37 mechanism said by the
  woman who entered the reading. **No world fact changed**; the chapter had already said a machine made
  the band.
- **Two counts in `reviews/volume-01/batch-0004.md` could not be reproduced** — weekday names (sixteen
  claimed, **ten** actual) and italic (seven claimed with a breakdown summing to six, **six** actual,
  **eight** after the repair). Both corrected in the file, with the failed numbers left visible.
- **The cross-chapter repetition figure carried in `state/continuity.md` was wrong** — 17 claimed as all
  document text, **45** actual by a stated method, of which seventeen carry document text, a figure, a
  place name or a line the book means to repeat, and twenty-eight are ordinary connective prose. Corrected
  in both files. **None of them is a spent construction.**
- **Self-review was structural, not a regression.** All four batches wrote their own review in the writer
  commit. `.opencode/agent/novel-reviewer.md` exists and the workflow probes it, but reviews are authored
  by the writer phase, which is why findings 1 to 3 above reached a file that certified them. **A writer's
  own review is not a review.** Carried forward to Batch 0005: write the review, then re-read the page
  against it, and record the command and its output for anything mechanical and **say plainly that a
  judgement is a judgement**.

## Canon-change flags raised by the Batch 0005 review repair

An independent review read the batch after the batch that wrote it had certified itself — the ninth
instance of that, recorded in `state/current.md` as item 29. **No canon was changed, no age was moved, no
scene was moved, no irreversible decision was re-opened, and the planned ending is untouched.** Recorded
because a later phase must be able to tell these from decisions the batch made on purpose.

- **The volume outline and the page disagree about Marguerite, and the page is now the canon.**
  `outline/volume-01.md`'s Batch 0005 block requires *"Marguerite's terms are accepted for the wrong
  reason."* **Chapter 46 refuses them, twice — Ch 33 standing in writing and Ch 46 in bed, for appetite
  rather than principle.** That is a stronger beat than acceptance-for-appetite and it is what the scene
  needed, but it contradicts the outline and it is now fixed here. **A later batch may not find the
  terms accepted, signed, or in force.** They stay down, unsigned, with the house behind him regardless,
  through the whole of Volume 1.
- **The volume outline is corrected in the one place the page forced it.** `outline/volume-01.md` says
  the open-question slot "gets him rank six," which is true, and the batch draft then made it get him
  rank six *arithmetically*, by scoring four hundred grains off a witnessed answer and jumping 8,137 to
  20,000. **It does not, and it must not.** The panel's ruling is now an instrument ruling: the band was
  struck on a requisition, a true answer under the open-question rule is a finding, a finding is an
  instrument, and a candidate is seated on standing *unless the band was struck on an instrument.* Six,
  held, on the requisition. **The reservoir scores nothing.** The 11,859 was never closed.
- **Ch 47's tolerance arithmetic was wrong on the page.** It read 8,137 and called four grains down
  inside a three-grain tolerance, and the same chapter showed four grains down laping a man. **The Review
  reading is now 8,138 — three down, three inside, at the edge — and four down still lapses.** The
  drift ladder is 8,140, 8,139, 8,138 and nothing else. `bible/power-system.md` and the grain spine in
  this file are unchanged: the published figure is still 8,141 and the figure only ever drifts down.
- **Ch 42 and Ch 44 were the same day.** Ch 42 is now **Thursday the 22nd**, four days behind Ch 41, and
  Neve's "Seven days now" fixes it. **Ch 42 backtracks and the page anchors the backtrack.** The four box
  Thursdays are consecutive and none is skipped, which is what Runa's standing instruction requires and
  what the first draft quietly broke.
- **`reviews/volume-01/batch-0005.md` was self-certification again**, in the same commit as the prose it
  reviewed, and its *Numbers reconcile* bullet certified 8,137 as inside a three-grain tolerance and
  endorsed a 400 that crossed 20,000. **Both claims were false on the page they were written about.** The
  bullet now carries the corrected arithmetic and names the check that would have caught it. **Item 29
  stands: the review phase must be a separate run.**
- **The chapter-ending construction ran ten times in a row.** *For <person>, his <verb> meant* is now in
  **Ch 41, Ch 44 and Ch 48 only**, with no two adjacent and no subject repeated across the run. Seven
  endings were rewritten in other shapes. **The good prose under them was kept.**
- **The volume-close phase was skipped.** The batch closed Volume 1 in prose and created a Volume 2 batch
  prompt instead, which `AGENTS.md` and `PHASE_SYSTEM.md` do not allow. **There is no `outline/volume-02.md`
  and no Volume 2 cards.** `workspace/volume-02/batch-0001/PROMPT.md` has been removed and the volume-close
  prompt written in its place. **Volume 2 must be planned and closed out before Chapter 51 is drafted.**
- **Repairs made inside the batch's own prose:** three unclosed quotations and a merged duplicate in
  Ch 49, a merged two-scene paragraph in Ch 48, a duplicated sentence and a meta leak naming Volume 2 in a
  character's mouth in Ch 50, a preserved revision artifact in Ch 45, and one duplicated panel-reading
  scene in Ch 47. **No scene, no beat, no decision and no ending changed.**

## Markdown and gate repairs made inside Batch 0004, recorded so a later phase does not re-open them

- **Eighteen horizontal rules were removed from Chapters 33–38.** `AGENTS.md` bans them and **Chapters
  1–32 had zero**. The draft written before the checkpoint had introduced them as scene separators.
  Collapsed to plain paragraph breaks.
- **Three illegal weekday names removed from Ch 34 and Ch 38** (a Wednesday in the fire-door exchange, a
  Wednesday and a Saturday in Ch 38's Nadia and Ines beats). All three were in Batch 0004 prose and all
  three are gone. **Chapters 31–40 now speak Thursday and nothing else.**
- **A paraphrase of *there is no form for this* was removed from Ch 32** (*because there is no record of it
  to seize*) and re-angled. The construction, not the wording, was the target.
- **Two internal date contradictions in Ch 34 were fixed**: a man could not have seen Lin Hao "four times
  since the seventeenth" on the seventeenth, and "two nights running" did not match the forced-door count.
- **Chapter 38 was a partial file at the checkpoint** — 1,508 words, ending mid-scene. It now stands at
  2,696 with the fifth turned line (Tessa Okonkwo) added, because the draft visited six people while
  claiming five and omitted one of the five turned lines entirely.

## Canon-change flags raised by the Volume 1 close audit

An audit, not a writer. **It changed no prose in Chapters 1–50, moved no age, moved no scene, re-opened no
irreversible decision, and did not touch `outline/ending.md`.** It corrected four state files against the
page and recorded nine findings. **Nothing below is a canon change; every entry is either a correction of a
file that was wrong, or a finding a later repair phase should take first.** **One of the nine — Correction
8 — was itself false and has been withdrawn, and the reproduction test printed against Correction 4 was
mis-specified and has been corrected; both are marked in place.**

- **CORRECTION — `state/current.md` said Rhee was "preparing to go over his head." He is not, and it is on
  no page.** `outline/volume-01.md`'s *Concrete resolution* says the same. Mechanical: `grep -rn '\bRhee\b'
  chapters/volume-01/` returns 25 hits and the last is `chapter-0030.md:17`, a retrospective clause inside a
  subordinate sentence. **Rhee has no line, no scene and no presence in Chapters 31–50 — twenty chapters
  including the climax and the resolution.** The first half of the claim is true and sufficient: the offer
  was refused in Ch 28 and closed permanently there. **The state file and the outline both corrected. A
  Volume 2 writer may not invent a Rhee scene without flagging it here first, and may not re-open the
  offer.** This is the tenth false certification of this shape in this pipeline and the first about a
  character rather than about a count.
- **FINDING — eight consecutive chapters close on the same construction.** Chapters **42, 43, 44, 45, 46,
  47, 48 and 49** all end on a paragraph carrying **`He wanted, concretely`** — *no trailing comma; with
  one the match returns seven and drops Ch 42.* **Five open the final
  paragraph on the string (42–46); three embed it inside the final paragraph (`chapter-0047.md:81`,
  `chapter-0048.md:79`, `chapter-0049.md:80`).** Ch 41 and Ch 50 are in other shapes. `AGENTS.md` fails a
  batch for the same construction more than twice running. **The Batch 0005 review repair caught the
  ten-in-a-row *For &lt;person&gt;, his &lt;verb&gt; meant* closing, rewrote seven endings, and put this in
  the seven.** Its claim that the old construction is now in Ch 41, 44 and 48 only is **true** and was
  verified here; the repair checked the construction it had been told about and not the one the page ended
  on. **Not repaired here — eight endings across four certified batches is a wide ripple, and an audit
  that repairs the volume is not an audit.** It is the first item a repair phase should take and **the good
  prose underneath is kept in seven of the eight; only the opening clause needs to change.**
  *(**The reproduction test printed for this finding was mis-specified and has been corrected.** It asked
  whether the final paragraph **begins** with the string and returns **five**, not eight — a repair pass
  running it as printed would have repaired five endings and left three chapters running the construction.
  The test now asks whether the final paragraph **contains** the string and returns eight. **The string
  itself was then quoted wrongly in six places across three files — with a trailing comma, which matches
  seven.** Working and output are in `reviews/volume-01/volume-close.md`, Correction 4.)*
- **CORRECTION — the residual age census is seven, not five** *(superseded by the `volume-plan` review,
  which found the label disagreed with its own table and that a ninth instance — `chapter-0020.md:67` — was
  on the page and unregistered. The governing figures are nine chapters and ten announced ages, five of
  them the protagonist or a core partner. Registered in full above.)* Two were never on any list and both
  are Lin Hao in narration.
- **WITHDRAWN — the close audit's `nobody` correction was false and this entry now stands corrected.**
  The audit reported `state/current.md`'s *"fifteen times across Batch 0005's ten chapters, four of them
  in Ch 50"* as wrong, on the basis of a per-chapter sequence it printed as 3, 2, 1, 4, 1, 0, 0, 0, 1, 0.
  **The page has 2, 1, 4, 1, 0, 0, 0, 1, 0, 3** — the audit put three in Ch 41 and zero in Ch 50, and
  Ch 50 actually carries **three `nobody` (lines 47, 51, 69) and one `no one` (line 65), which is four.**
  Only the totals survived the audit's check: twelve `nobody`, three `no one`, fifteen together.
  **`state/current.md`'s original sentence was right in every particular the audit corrected it on, and has
  been restored.** Immaterial to the budget either way; the correction was withdrawn rather than reissued,
  because an eleventh false certification is worse than an inaccurate footnote.
- **CORRECTION — `state/continuity.md`'s H1 sections were not in the order the file claimed.** The
  `Batch 0005` block sat at the bottom of the file while its own header read *"Appended above Batch 0004.
  Nothing below altered."* A writer reading top-down would have taken Batch 0004's mechanics as the most
  recent canon. **The stack is now newest-first**, which is the convention the Batch 0002 repair
  established, and a `# Volume 1 closed` block sits above them. **Content integrity was verified line by
  line against `HEAD`: zero lines lost.**
- **CONFIRMED AND NOT CHANGED — Marguerite's terms.** Refused **twice**, standing in writing on the 13th
  (Ch 33) and in her own rooms for appetite rather than principle (Ch 46). Kept down and unsigned in Ch 47,
  49 and 50. **The terms are not accepted, signed or in force anywhere in Chapters 1–50, and a later batch
  may not find them so.** `outline/volume-01.md`'s *"Marguerite's terms are accepted for the wrong reason"*
  remains contradicted by the page, and the page is canon.
- **CONFIRMED AND NOT CHANGED — nothing lets the account score a grain.** Checked across all fifty
  chapters. The reservoir's hard limit in `bible/power-system.md` holds on the page.
- **CONFIRMED AND NOT CHANGED — no new final enemy, and the ending is untouched.** Ferreira, Quayle and
  Sowe are all named in no chapter of Volume 1. `outline/ending.md` was not modified.

## Flags raised by the external review of the Volume 1 close audit

A reviewer, not a writer, and not a prose pass. **It changed no chapter, moved no age, moved no scene,
re-opened no irreversible decision, and did not touch `outline/ending.md`.** All three findings were
re-verified against the page before anything was written down. **Every one of them is a defect in the
close audit's own claims, and two of them were defects of the same kind: a command that was narrower than
the finding it was attached to, reported as though it were the whole finding.**

- **CORRECTION — the audit's reproduction test for the eight-in-a-row ending did not reproduce it.** It
  asked whether the final paragraph **begins** with `He wanted, concretely` and returns **five**
  (Ch 42–46). **Ch 47, 48 and 49 carry it inside the final paragraph**, at `chapter-0047.md:81`,
  `chapter-0048.md:79` and `chapter-0049.md:80`. **The finding is eight consecutive chapters and is
  unchanged; the command printed beside it returned five and was printed beside eight.** Corrected in
  `reviews/volume-01/volume-close.md`, in `state/current.md` item 35 and in the entry above. **The
  mis-specification had reached `state/current.md` and would have reached the Volume 2 prompt through it.**
  *A second, later correction: the string itself was then quoted **with a trailing comma** in six places
  across three files, and a test pasted from any of them returns **seven**, dropping Ch 42
  ("concretely **and immediately**"). The string is `He wanted, concretely`, no comma. All six corrected.
  The mis-specification had two generations and the second one came from copying the string out of prose
  instead of out of the command.*
- **CORRECTION — the audit re-certified a retired construction and promoted it into a standing rule.**
  §6 of the audit certified *nobody thanked him* as *"spent once, Ch 50's last line, and nowhere else in
  the volume."* **`chapter-0012.md:19` reads "Nobody thanked the boy."** The Batch 0003 review repair had
  already found that instance and already ruled the construction **retired rather than rationed**; the
  close audit wrote its absolute negative over the top of that ruling and deleted it. **Corrected: the
  sentence "Nobody has thanked him" is Ch 50:69's alone; the construction `nobody thanked <object>` is
  spent once, at Ch 12:19, and is gone for good.** The prose at
  Ch 12:19 is load-bearing and stands. See the entry under *Canon-change flags raised by the Batch 0003
  review repair*, which governs.
  *("spent twice" was the wording this correction first carried. `grep -rniE "nobody (ever )?thanked"
  chapters/volume-01/` returns **one** hit. Ch 50:69 is a different construction and does not count. The
  retirement stands; only the count was wrong.)*
- **CORRECTION — a neighbouring row of the same table was ambiguous and read as a certification.** The
  audit certified *nobody asked* as *"Spent once, Ch 38, in Ola's own hand. Not available again."* The
  **note** is spent once and that is true. **The motif is not rationed at all**: *nobody asked him, nobody
  had ever asked, nobody's ever asked* runs **fourteen times** across Ch 11, 12, 13, 15, 16, 22, 23, 26
  (twice), 27, 28, 34, 38 and 43, and it is deliberate texture, because the subject of Volume 1 is the
  unrecorded and the unasked-for. **Motif available, note spent.** Recorded so a Volume 2 writer does not
  ration a motif the book uses fourteen times, and does not spend the note a second time.
- **WITHDRAWN — the audit's `nobody` correction overwrote an accurate state file.** Withdrawn in place in
  the list above and restored in `state/current.md`. **This is the eleventh false certification of this
  shape in this pipeline and the second of the three inside the close audit itself.**

**Standing rule for the next phase, stated once: a command that runs is not the command the claim is
attached to, and a correction made against an unverified per-chapter sequence is a new certification, not
the end of one.** Three defects in one file, all that shape.

**Standing rule for Volume 2 Batch 0002, and the counts it ran.** This phase wrote Chapters 61–70 and did
**not** write a review of them. Nine batches in this repository have written their own review and every one
was wrong about the prose it described; item 29 in `state/current.md` records that the fix is a separate run.
**Every mechanical gate below was run and every one passed: zero horizontal rules, zero bold, zero italic,
zero planning-register words, zero weekday names other than Thursday (nine Thursdays), zero banned
constructions (*there is no form*, *no column for*, *nobody thanked*, *He wanted, concretely*), one system
panel in ten chapters and never repeated, `nobody`/`no one` at 19 with a per-chapter maximum of 4, no
paragraph over 89 words and none over 120, no duplicate paragraph of twelve words or more, no sentence of nine
words or more repeated anywhere in the batch, and ten titles unique against the fifty in Volume 1 and all
under 90 characters. Chapter lengths run 2,363 to 5,012, with Ch 63 the scene chapter and over the guide on
purpose, on the same grounds and with the same warning as Ch 55.** Those are counts. **A count is not a
reading, and nothing above certifies that the prose is good, that the batch's midpoint and climax occurred, or
that either irreversible decision costs anything.** The next phase that reads this batch must assume all
three are unverified.

**Standing rule for Volume 2 Batch 0001, stated because the batch itself had to work around it: this
phase wrote Chapters 51–60 and it did NOT write a review of them.** Nine batches in this repository have
certified themselves and every one of those certifications was wrong about the prose it described, and
item 29 in `state/current.md` records that the structural fix is not a prose discipline but a separate
run. **The chapters have had every mechanical gate run against them and they pass: zero horizontal rules,
zero bold, zero italic, zero non-Thursday weekday names, zero planning-register words, two system panels
in ten chapters and never repeated, `nobody`/`no one` at 28 with a per-chapter maximum of 5, no paragraph
over 114 words, no duplicate paragraph and no repeated sentence of nine words or more across the batch,
all ten titles unique against the fifty in Volume 1 and all under 90 characters.** Those are counts. **A
count is not a reading, and nothing above certifies that the prose is good, that the batch's midpoint and
climax occurred, or that the irreversible decision costs anything.** The next phase that reads this batch
must assume all three are unverified.
