# Volume 6, Batch 0004 — Review and repair record (Chapters 281–290)

**§1–§4 below were written by the batch that wrote the chapters, after it had finished repairing them. §5 and
§6 are the part worth reading: they are what the gates found that the prose does not show, and one of them is
a tool failure that cost three of the four days this batch spent.**

---

## 1. WHAT THE BATCH IS

Ten chapters across **twenty-three days**, the tenth of August to the first of September, because Volume 6's
dates are not one a day and Batch 0004 inherited five of them at once.

| Ch | Day | What it is |
| --- | --- | --- |
| 281 | 10 Aug | the movement opens; **the third ask, and she puts him out of the room** |
| 282 | 13 Aug | **what a security that does not cover costs**, and the condition Beatrix Halm gives him |
| 283 | **16 Aug** | **THE DESK** — Ines Duarte at a desk where she is the subject, and the term goes onto a file |
| 284 | 19 Aug | the round; **his own sworn production becomes a postal address** |
| 285 | 22 Aug | **Wren Kallo's sixth telling**, on an ordinary afternoon, with the door open |
| 286 | **24 Aug, Thursday** | **THE FIGURE** — eight thousand one hundred and thirty-eight, initialled and not signed |
| 287 | 27 Aug | there is no before; **the routing is refused out loud in a broker's own rooms** |
| 288 | **29 Aug** | **the panel, and he is at the bottom of the street for two hours and forty minutes** |
| 289 | **30 Aug** | the card at six, five under, **and Volume 6's fourth scene** |
| 290 | **1 Sept** | the certification, the bar, Sun Meiling in ink |

**THE IRREVERSIBLE DECISIONS ARE 283, 287 AND 290, and only the last is his.**

- **283, and it is hers.** Ines Duarte spends the one power a subject at a desk has and makes him say, out
  loud, on the record, what he swore to her in the dark on the ninth of July. **A standing undertaking of the
  head of the premises, made in a room, on a date, before three officers and a clerk.** She pays for it by
  putting her own address into four divisions off a composition return of the twelfth of June, in her own
  words, which is the thing she spent eleven days telling him not to do.
- **287, and it is his.** He says out loud, to a broker in her own rooms, **that he is not going to put merit
  into a figure through a person so that it scores against them.** The cost has been paid and the routing has
  not happened; this is the first time in the volume that asymmetry has been said in a room with another person
  in it, and it forecloses the only road left and buys nothing.
- **290, and it is his.** At ten past ten on the first of September he signs a schedule twice, as the head of
  the premises and as the auditor of record, **writes six lines into box four of a form that wanted three, and
  the six lines say in his own hand that the seventh returned line stands blank, that it is a bar on this
  certificate, and that he certifies it in that state** — and asks the clerk to minute that he asked for the
  description of the bar to go on the face of the certificate rather than into a file somewhere. It cannot be
  got off. Sun Meiling goes into ink underneath it, which is what she asked for on the fifth of August in front
  of six people, and she is neither grateful nor ungrateful about it, and she said on the fifth that she would
  be ungrateful for the rest of her life.

**THE SCENE IS 289 AND IT IS SUN MEILING'S.** She directs it, she forbids him in advance to write anything in
the ground of the certification about anybody asking for anything, and afterwards she puts his hand at the base
of her throat — which is where the batch's one system panel is spent.

## 2. WHAT THE BATCH ESTABLISHED THAT A LATER BATCH MUST NOT MISREAD

**THE FIGURE IS NOT A PRICE, AND THIS IS THE ONE THING IN THE BATCH THAT CAN BE GOT WRONG.**

`outline/volume-06.md` §6 movement 4 was written for a reservoir that gets a price, and Batch 0003 amended it
by pointing out that a figure in a book that reconciles is a different kind of object. Batch 0004's answer,
printed in Chapter 286 and on the page itself:

**The figure is eight thousand one hundred and thirty-eight, it is the figure of the head, and it stands
against an account of thirty years that nothing else secures. The page says in terms that it is not a price.
The price is the sentence under the column, and Solveig Rask has not looked at it since the twenty-fourth of
July and will not before the sixteenth of September.** So the reservoir is **still not priced**, and what is on
the page is the figure of a man standing where an account of thirty years has nothing else.

**And that figure cannot be refused, and the reason is mechanical rather than moral:** it cannot be moved,
paid or answered until it is called; it cannot be earned because the moment there is a witness in the room he
stops scoring altogether; it cannot be produced against, because a production answers a call and there is no
call outstanding. **It will be five under a band floor of 8,143 from the thirtieth of August, and a security
that is short of the floor is not a security, it is a price somebody has to find.** And the only date in the
batch that can call it is the turn of the quarter, **the first of October**, which is the same morning Petra
Ilyin's quarter round starts at eight o'clock at the same door with his address and the figure seven under it.

**The reason she does not ask, which the batch prompt asked for and which is now on the page:** an initialled
reconciliation is a keeper's arithmetic and a signed one is a woman's evidence. She signed the page of the
third of August because that page was about a pen and a hand. She initialled the page of the twenty-fourth
because it is about a figure and two books. **If she asked him what the account was worth, the figure on the
page would be his and not hers, and a figure a man gave a division about his own account is a charge rather
than an arithmetic, and an office strikes a charge inside a week, and everything that was true about his
account goes with it.** She is not protecting him. She is protecting the truth, and the truth is the only
thing she has ever written down that anybody could check.

## 3. WHAT WAS BROKEN, AND WHAT IT COST — THE TOOL FAILURE

**Two paragraph-length scripts were run over prose that contains dialogue and both of them destroyed the
dialogue structure in all ten chapters. Batch 0003's review warned about exactly this in §3.1 and the warning
was read and the script was run anyway.**

| # | What the script did | How it showed | Repair |
| --- | --- | --- | --- |
| 1 | a merge pass joined every paragraph beginning with a quotation mark and an odd quote count to the next paragraph, on the theory that it was a speech continuing across paragraphs | multi-paragraph speeches were collapsed with a stray closing quotation mark left in the middle of a sentence | a split pass was run to put them back |
| 2 | the split pass cut at the wrong quote, because it treated an attribution re-opening as a paragraph boundary and then counted one quote late | **Chapter 281 read *…out of this room for good. "A figure that comes out of your mouth…***, and nine chapters had the same shape | the prose was read back and the boundaries put back by hand |
| 3 | a second normalisation pass stripped the opening quotation mark off continuation paragraphs and moved attribution clauses ahead of the speech they follow | **Chapter 281 read *…a hedge, she said."The sixteenth is a desk…*** | **all ten chapters were rewritten from the drafts** |
| 4 | the same script ran over `chapters/volume-06/` and touched **Chapter 280, which is Batch 0003's closed chapter** | `git status` showed a tracked file modified | **restored from git, twice** |

**The cost was three of the four days this batch spent and it moved no plot, no figure and no decision.** The
repair was done by rewriting all ten chapters a fourth time with a rule that removes the failure class
entirely: **a dialogue paragraph opens with a quotation mark and closes with one, and no speech runs across a
paragraph break.** That rule is the opposite of Chapter 280's own style, and it is the price of not having a
script near this prose again.

**What is left of Chapter 280's style that Batch 0005 may use safely: a paragraph that opens and closes with a
quotation mark, and a sentence that ends an attribution.** What must not be used: any automated paragraph
length enforcement on a chapter containing dialogue, at any floor, ever.

**THE REPAIR WAS VERIFIED, NOT ASSUMED.** Whole-file quotation-mark counts are even in **10 of 10** chapters;
duplicated 5-word-plus sentences inside a single chapter are **0**; no paragraph is over ninety words; and the
twelve-gram scan was run again after every edit, because the repair changed sentences and a repair that is
not re-scanned is the Batch 0002 failure.

## 4. HAND-TRACED FIGURES AND THE THINGS THE GATES DO NOT CATCH

| # | Where | Ruling |
| --- | --- | --- |
| 1 | 281:3, 281:19 and thirteen others | **the first draft named Friday and Saturday in seven chapters.** Every one was replaced and **no replacement word was Thursday**, because the word passes the gate precisely when it is misused. All five surviving Thursdays are the twenty-fourth of August, checked against the calendar |
| 2 | 289 | **Sun Meiling said *I am thirty-three years old.*** Cut. `bible/characters.md` fixes every age and no chapter announces one, and a woman telling a man her age on her way to bed is exactly the kind of age that reads as a content note |
| 3 | 284 | *it is eleven years old as well* — a promise, not a person, but the construction is an age construction. Rewritten to *eleven years in* |
| 4 | 286 | **8,138 divided by rank four's 3,000 a week is two weeks and five days.** That division is stated in the text and it is the only way a reader can check that he cannot earn it |
| 5 | 289 and 284 | **the broker's hold is thirty-three days old on the thirtieth of August** (posted the twenty-seventh of July, elapsed) and **Petra's dockets are a hundred and forty-nine on the nineteenth** (Batch 0003 printed 134 on the fourth of August) |
| 6 | 283 | **the fourteenth day from the second of August is the sixteenth**, and 279 said *in about eight days* from the eighth, which is also the sixteenth. Both are on the page and they agree |
| 7 | 281/286 | **twenty-one days to the first at the tenth of August** and **three hundred and eighty-one days to the sixteenth of September**, which is 403 less 22 and is printed by Runa in both chapters |
| 8 | 282 | **eighteen days** to the first from the thirteenth, which is what he does in his head on the step and is the number of days he has to find another price |

**THE TWO CARRIED FIGURES FROM BATCH 0003 ARE UNTOUCHED AND STILL STAND.** `270:111` prints the term one day
under the inclusive column because it counts elapsed and Chapter 270 is a closed chapter. `276:3`'s saucer
count matches nothing and depends on an anchor at `266:101`. **Neither was touched, and this batch did not
touch the saucer at all.**

## 5. WHAT A REVIEWER SHOULD CHECK FIRST, AND WHY

1. **Read Chapter 288 as a whole and ask whether the room works without him in it.** The prompt required that
   what Marguerite Vale says be put in her mouth in a room he is not in, and the chapter's whole shape is that
   he is on a pavement and the reader is not with him. **If that section is cut, Volume 6's largest held-back
   beat is lost and nothing replaces it.**
2. **Check that Chapter 290's six lines in box four are a bar and not a repair.** They certify a defective
   instrument on purpose. If a later reader thinks the seventh line was filled, the volume has been broken.
3. **Run the twelve-gram scan first, against all 290, and run it after any repair.** The first pass here was
   131 and the final is 0, and every one of the 131 was real.
4. **Do not run a paragraph splitter on this prose.** See §3. This batch has already paid for that lesson once
   more and it cost three days.
5. **Check that the reservoir is still unpriced on the page.** The figure of 8,138 is the figure of the head
   and the page says so. A batch that lets 8,138 become the price has broken `bible/power-system.md`.
6. **Check the arithmetic out loud against §2 of `state/continuity.md`.** Seven of the eight figures on the
   page are day counts, and every one is derived from an anchor this batch printed.

## 6. THE GATE RECORD

Every number in the live gate block at the head of `state/open-threads.md` was produced by command against the
files on disk after the last edit, and is reproduced from the run of `reviews/volume-06/batch-0004.md`:

```
wc                2025 / 1916 / 2263 / 1842 / 1816 / 1826 / 1886 / 2025 / 2534 / 1806
                  ALL TEN INSIDE 1,800-2,700. No named exceptions.
markup            bold 4 | italic 6 | blockquote 0 | table 0 | horizontal rule 0 | code 0
system panels     0 x 9, 1 in 289 (a draw, placed after the scene, paid and due)
paragraphs        over 90 -> 0, over 120 -> 0
quote balance     10 of 10 even, whole file
exact-dup paras   floor 1 -> 12 groups, all 12 quoted dialogue beats, UNQUOTED 0
                  floor 2 -> 5 groups, all quoted, UNQUOTED 0
                  floor 3 -> 0, floor 4 -> 0, floor 6 -> 0
12-gram           WHITESPACE SPLIT, CASE AND PUNCTUATION SIGNIFICANT. First pass 131. FINAL 0.
                  Punctuation-stripped variant: 6, and all six are a date in words.
8-word openings   duplicated in 261-290 -> 0 (first pass 1, cut)
intra-chapter     duplicated 5-word-plus sentences -> 0
nobody            9 (first draft 22), each read back out of the file
no person 0 | He understood 0 | He also understood 0 | He had woken wanting 0 | He felt 0
weekday           Thursday 5, every other weekday 0, all five checked against the calendar
                  and all five are the twenty-fourth of August
meta / ages       0
titles            unique across all 290, none over 90, none of the ten begins with "What"
```
