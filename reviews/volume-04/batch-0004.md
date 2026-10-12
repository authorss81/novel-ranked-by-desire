# Volume 4, Batch 0004 — review file (Chapters 181–190)

**This is not a review of the prose.** A review is a separate run. **What goes in this file is the gate
output and the honesty about it**, so that the next writer and the next reviewer do not have to
reconstruct either. The drafting record — the day map, the Gate A interval trace with its seven errors, the
Gate B date subtraction, the canon proposals, the named length exceptions — is the Batch 0004 block at the
head of `state/open-threads.md`.

## What shipped

Ten finished chapters, 181 to 190, one a day from the first to the tenth of May, no shared dates and no
gaps. **Escalation step 4 of 5, The Five Names, entered at 181. The card that fixes May at thirty days is on
the page in the first chapter, and every interval in the batch is subtractable against it.**

| Ch | Title | Words | What it did |
| --- | --- | --- | --- |
| 181 | The Re-Issued Form | 2,116 | **The card**, printed in full, fixing M+5 at thirty days; and the only instrument that makes a household produce one of its own members |
| 182 | To Be Withdrawn | 2,521 | **One of the six asks to be unfindable on purpose**, and is argued out of it by nobody |
| 183 | The Bench Order | 2,433 | **Wren Kallo's first secret**, kept from him; the bench order; the bare slot at seven days |
| 184 | The Long Form | 2,011 | **The irreversible decision.** His own figure into a legal document for the first time in five volumes |
| 185 | The Service File | 2,582 | **The batch midpoint.** The fifth name, ninety seconds, in front of nine operators, for a reason that is not him |
| 186 | Absent With Reason | 2,307 | **Sun Meiling is asked, once, to be on something**, and answers in the form's own grammar |
| 187 | No Entitlement Established | 1,913 | The correction signed; and the household learns it has bought nothing at a counter |
| 188 | The Unfunded Clinic | 1,981 | Tessa answers a notice with no name on it in a queue, and puts a card with her name on it |
| 189 | The Signal Cabin | 3,855 | **The scene.** Beatrix Halm, asked to stop writing minutes down |
| 190 | The Household Roll | 2,141 | A clerk reads the board; the certificate's arithmetic; and what is actually the instrument |

Total 23,860 words. **Ten unique titles, all from the volume's §11 bank, none over 90 characters, zero
duplicates book-wide against all 190 existing chapter titles.**

## Gate output

Re-derived by command **after the last edit**, not before it.

```
ls chapters/volume-04/                                                   → 40
titles unique book-wide (190 files)                                      → NONE
titles over 90 characters                                                → 0
titles 181–190 against outline/volume-04.md §11                          → exact, ten for ten, in order
wc -w, 181 to 190   2116/2521/2433/2011/2582/2307/1913/1981/3855/2141   → total 23,860
horizontal rules                                                          → 0
blockquotes                                                              → 0
bold, underscore, single-asterisk italic markup                          → 0  (3 italics in the first pass, removed)
planning-register terms (reservoir, quiet account, concil, ninth seal, channel) → 0
system panels                                                            → 0, and none is due: no count turns
ages                                                                     → 0
meta-language in 181–190                                                 → 0  (1 in the first pass, cut)
rationed constructions (there is no form / no column / record remained /
  nobody thanked / nobody asked / nobody knew / He wanted, concretely /
  , his X meant)                                                          → 0
nobody / no one / no-one                                                 → 0, against a ration of 1  (11 in the first pass)
weekday names other than Thursday                                         → 0  (7 in the first pass)
the word Thursday                                                        → 11, every one of them instrument-derived
church / chaplain / congregation / null room / quiet number               → 0 in 181–190
not a tank / he is a door                                                 → 0
his name used in Ch 189                                                   → 0
(six|seven|eight|nine|ten|eleven|twelve) (women|people|chairs|men|notebooks|lines) → 14 hits, all read,
                                                                              all justified; see below
paragraphs over 90 words, whole of chapters/volume-04/                   → 0 over the whole volume; none over 120; longest in the batch 89
paragraphs containing an internal newline, whole volume                   → 0
duplication gate: 8+ word sentences, 40+ word paragraphs, 8-grams,
  intra- and cross-chapter, over all 40 files                            → clean for Batch 0004
```

**The fourteen hits on the counted-noun gate, read one by one.** *six people* at 181, in a district officer
saying that one of six people would go into that kitchen and fix the other five. *six women* at 182, in a
household that will be certified on six whether the roll says five or not. *six women* at 183, a roll that
has had six names on it since the thirtieth and is written by a character who does not know about the rule
struck through it on the second. *six women in it* and *six women* and *six women* at 185: six women at a
kitchen table, six on the certificate, six in a district book. *nine people* three times at 185: the nine
operators in the car, which the prompt requires. *eleven people* at 185 is *two hundred and eleven people*
in the Cobb Street hall, which is Ch 145. *six lines* at 187 is six lines under a form number. *six women* at
187 is the six the certificate binds. *six women* at 182, *six people* at 189 is six people in a kitchen.
*eight people* at 190 is eight people who watched a clerk read a board, being six women, him and the clerk. **All fourteen are load-bearing and
none of them is an enumeration of the household without a list named.**

## What the gate output does not tell you

**It did not see the seven interval errors in Gate A**, all of which are a correct word attached to the wrong
number and none of which uses a banned word:

- Ch 183 gave **nine days** for the eleven establishments reading the notice, twice — 28 April to 3 May is **five**
- Ch 184 said the roll was **two days old** on the fourth of May, twice — 30 April to 4 May is **four**
- Ch 187 said the women had spent **five days** behind something — the roll went up on the thirtieth, and 30 April to 7 May is **seven**
- Ch 190 said the pale rectangle had been bare **six weeks**, three times, in three places — 26 April to 10 May is **fourteen days**, and a fortnight is the exact answer and six weeks is neither the answer nor a plausible rounding of it
- Ch 189 gave **a fortnight and a half** for three weeks of a missing book, and **the fourteenth of April** for **the thirteenth**, which is Ch 133 and had to be read on the page rather than subtracted
- Ch 185 said **about fifty days** where fifty-two is the answer and Ch 182 said **about fifty days** where fifty-five is

**It did not see the worse thing, which happened during the batch rather than in it.** The pass that broke
paragraphs over ninety words used a sentence regex that required a full stop followed by whitespace, so any
paragraph ending `since."` lost its final sentence. **Nine sentences were deleted across the batch.** In
Chapter 189 that included the whole of the reason Beatrix Halm has not been able to write in her book for
three weeks, and in Chapter 190 the sentence that says the certificate is the only thing that makes a
household a household. **Every gate in this file returned zero on the damaged chapters**, because a deleted
sentence leaves shorter paragraphs and no banned words and no duplicate. It was found by diffing the
sentence sets of the ten files against a copy taken before the script ran. **A script that rewrites prose is
a gate with no output at all**, and the batch's regression test is now that copy.

**It also did not see four things a reviewer should attack first**, set out in full at the foot of the
Batch 0004 close record in `state/open-threads.md`:

1. Whether Chapter 183 is doing two chapters' work — a card cross-check, a repaint, a bare slot and Wren
   Kallo's best material in one morning.
2. Whether Chapter 186 is a refusal or a victory. Sun Meiling ends Volume 4 more findable than she has ever
   been, which is the one thing she has refused in six documents, and nobody says so out loud.
3. Whether the roll on the wall is still doing work after Chapter 190, when the district clerk says on the
   page that it is not the instrument and has no force at all.
4. Whether the household has enough left to lose before Chapter 199 — five named, one struck, one entered as
   absent with reason, and a certificate that will bind them all to a guild broker whether they consent or not.

## Named length exceptions

**Ch 189 runs 3,855 words**, inside the 2,600–3,900 scene band. It is the batch's only scene and the sex is
the product: the ask in a signal operator's own register, a records clerk who is kind to her once, five
terms in plain statements and not numbered, the act written out in the cabin's furniture, and her last act.
**It borrows no ground, hand, name-exchange or aftermath from any of the ten scenes in §10 of the volume
outline, and Chapter 169 and Chapter 179 were both opened and read before it was drafted.**

**Ch 185 runs 2,582 words**, 118 over the 2,700 guide, and the overage is Nadia Ferrous's argument in four
attempts, which is the batch's midpoint and the thing Chapter 190's count of five names is built on.
**Ch 182 runs 2,521** for the same reason at a smaller size. **The other seven run 1,913 to 2,433.**

## Threads, in one line each

Opened: the re-issued return and a correction that wants a signature · the four-page certification schedule
and Doyle · the bench order and the district sheet it feeds · Wren Kallo's held name, never given · the
Exchange's household-entitlement line · the caller at the door · the card at the Vestry hatch · the rule
that a standing household takes the highest standing in it.

Advanced: the bare slot at fourteen days · Wren Kallo (the first secret, the unreadable register) · Beatrix
Halm (off the roll, unprotected, eleven months burned) · Runa Sato (the correction signed, three months
unstarted) · Sun Meiling (absent with reason, four hundred words, the shape for a twelfth time) · Tessa
Okonkwo (the notice answered in the queue, a card on the counter) · Nadia Ferrous (page nine) · Marguerite
Vale (the binding rule stated, an offer made that nobody has taken up).

Left open and not closed: Ines Duarte's review · Runa Sato's three months · the certificate on the
twenty-seventh of June · the five names and two empty rows · the district line with Runa's name under it ·
Wren's name · Marguerite's offer · Tessa's card · the ninth of September · the broken price · the
classification paper dated the nineteenth · the desk's four-line note · **Agnete Lindqvist's eleven years
indoors** · the leak, stopped and unexplained · **the four people who will find out he knew for three days
and did not say.**

## Next

`workspace/volume-04/batch-0005/PROMPT.md`, Volume 4 Batch 0005, Chapters 191–200, the eleventh to the
twentieth of May, **which is where the volume ends.** Chapter 194 is the fourth rib examined in a clinic
and found to be the fourth rib, Chapter 195 is Ines Duarte's and is named *Nothing Said At All*, Chapter 197
is Marguerite Vale's scene in the Exchange sales floor after it closes, and Chapter 199 is the indemnity,
signed in a room where the whole thing is a form.

## Review repair, second pass

**A reviewer read the ten chapters in full and returned: *do not ship as closed*. The prose was not the
problem — it was called the strongest batch so far in dialogue and in the women holding their own ground.
The problem was arithmetic, and it was in the gate file as well as in the prose.** Five hard continuity
errors and five major ones; **three of them sat in rows of this file and of `state/open-threads.md` stamped
*Correct*.** All ten are repaired. **Nothing was restarted, no chapter was rewritten from the top, no
scene was cut, and no planned beat moved.**

The gate output above is now stale in three places and has been amended rather than left to mislead the
next run: the *nine people* hit at 190 is **eight**, the Ch 185 figure is **fifty-two**, and the eight-gram
baseline is **657**, re-derived from the files rather than quoted from an earlier pass.

**The process finding is the one that matters and it is not about prose at all.** `state/open-threads.md`
Gate A marks a row *Correct* by asserting that its subtraction works, and in this batch **the Ch 181 row
for the bare rectangle had subtracted to the third — which is Chapter 183's date — because the row beneath
it was copied rather than recomputed.** A reader of that table cannot tell a checked row from an assumed
one, and Batch 0005 opens on the eleventh of May and will inherit every number in the table as canon. The
table has been repaired row by row, the arithmetic in the Ch 190 row that read *60 − 10 = 50* is now
*27 April → 10 May = 13, and 60 − 13 = 47*, and the countdown is one convention written once at the head
of the file so that a writer cannot re-derive it four ways.

**The second process finding stands and has not gone away: the paragraph-splitting script that deleted nine
sentences left no trace in any mechanical gate.** The regression test for this batch is still the
sentence-set diff against the copy taken before that script ran, and the repair was checked against the
same method — every changed file's sentence set was compared against `HEAD` rather than trusted.

**The four attacks on the batch itself — whether 183 is doing two chapters' work, whether 186 is a refusal
or a victory, whether the roll is still doing work after 190, and whether the household has enough left to
lose before 199 — are unchanged and are not repaired here. They are questions for the writer of Batch 0005
and they are the right four.**
