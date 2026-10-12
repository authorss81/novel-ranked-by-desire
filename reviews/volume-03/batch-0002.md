# External review — Volume 3, Batch 0002 (Chapters 111–120)

Reviewer did not write the batch. Read all ten chapters against the page and against
`outline/volume-03.md`, then ran the batch's own mechanical gates. **Findings were applied to the page
by a separate repair run; this file is the record, not the authority.** No plot, no date spine, no
outline, no ending was changed.

## What shipped

Every mechanical gate passed on the text the whole time. Zero system panels, zero ages, zero emphasis
markup, zero blockquotes, zero horizontal rules, no paragraph over 90 words, the two-column tool
correctly left undescribed, Wren named first in a document at 116 as required. **Three byte-identical
duplications, a structurally broken chapter and one untraced figure shipped through every one of them.**
The batch's own close record claimed fourteen wording-level repairs, clean paragraph gates, and a Gate A
in which "every figure above was subtracted from two printed dates." None of those three claims was
true of the page.

## Hard defects, all fixed on the page

| # | Chapter | Defect |
| --- | --- | --- |
| 1 | 120 | Closing beat printed twice, byte-identical, as the batch's last beat |
| 2 | 111 | Sabine Rooke's "That is the roll / proving looks like when it has furniture" printed twice |
| 3 | 118 | "That is the only thing anybody can say about it" repeated across two consecutive speeches |
| 4 | 117 | Day runs backwards then forwards: home, then the desk, then noon and four; two trips home; the chapter's decision landed after he was in bed |
| 5 | 116 | Envelope sealed twice with the runner's tray between the two seals |
| 6 | 116 | The second door placed "in the other building" against three lines placing it in this one |
| 7 | 116 | "has benched that tool" — not a word |
| 8 | 115 | "and she has never seen him" — no antecedent until eleven lines later |
| 9 | 114 | Stray holding-ward paragraph interrupting the arcade bench, closing on a self-cancelling clause |
| 10 | 120 | "gone nowhere at four for sixteen days" traces to nothing on the page |
| 11 | 118 | Five-to-four repair did not sweep; `:69` still said "three of them" |

## Repetition the gate targets

- **118's irreversible decision spent four times on one construction.** Now once — and the replacement
  beat (she writes it on a bench paper and hands it across) does more work than the repetition did.
- **120's "a man who makes his own mass is a man who can be regulated"** said twice. Kept once, in
  Drant's mouth, where it is the strongest sentence in the ten.
- **117's "a clicking and a pause and a clicking"** twice, once in a house with no machine in it.
- **113 quoted Nadia's forty-word speech twice**, the second as the closing beat.
- **Simile family:** "like a hand on a rail" and "like a hand on his wrist", each twice.
- **"Nobody asked"** — the first construction on `AGENTS.md`'s watch-list, and marked "note spent" in
  the batch's own prompt — ran four times. Now once, at 118:27, in Wren's voice.

## The scene at 118

3,041 words, of which roughly 700 was sex, and that section summarised itself. Against `AGENTS.md`:
*Write the actual scene. Implication and fade-to-black are not the target. The scene is the product.*

Now 3,476 words, inside the outline's 2,600–3,900 band, with the scene roughly doubled and written:
the mouth on the junction of his neck and shoulder; the exchange about saying it again *in the morning*
and what he will be in the morning; and the beat where she moves the screwdriver and the plate to the
far end of the bench and squares them before she goes on — putting the bench in order so that afterward
nothing on it can be said to have fallen over.

The compliance clause (*"I am not impaired and I have had water and bread and nothing else, and I am
awake, and nobody has told me to say this"*) was a checklist, not a voice. It is now one line of
character. The consent it was standing in for is still on the page — "I want it," he said — and the door
is still unlocked, turned by her own hand, with the key put where both can see it.

## State-file integrity

- **`state/current.md` had two `# Current State` H1s**, and the live one had the Batch 0001 record
  stacked inside it under an unlabelled paragraph with duplicate bold labels, contradicting the live
  block twice: it put the sixth space *empty* when Ch 120 fills it, and put *Batch 0002* next when
  Batch 0002 had run. **This is the highest-risk item in the repo for the next writer.** Removed, and
  the boundary marked.
- **Off-by-one-month label, propagated to five files.** The batch stands in M+2; the hearing is the 29th
  of M+3, which is **next** month, not "the month after next". Every printed figure was correct
  (40 = 11 + 29) — the label was wrong. Corrected in `current.md`, `continuity.md`,
  `chapter-summaries.md`, `open-threads.md` and the Batch 0003 prompt. **The chapters never used the
  phrase.**
- **Bench order dated one day late in two state files** — the page says dated *yesterday* from the 17th,
  i.e. the **16th**. Corrected.
- **An overstated repair.** `open-threads.md` recorded a "five weeks" figure as cut; it was
  contradicted in dialogue and both readings now stand on the page, one after the other.
- **Figure staleness.** The visitors' book ran 13 → 14 with no caller shown making the change, and the
  19th and 20th reused the 13th's figure as live. Now two named figures with a bridge, stated at 113.

## Next-batch prompt (`workspace/volume-03/batch-0003/PROMPT.md`)

Six defects, all fixed in the prompt: two different demands merged into one "26th" (and the merge would
have put Sun on hall paper against the prompt's own lock); "she has told three of them" inheriting the
un-swept line from 118:69; the 103 courtesy claimed to pay at 128–130 in one place and at 143 in two
others; both irreversible-decision candidates failing `AGENTS.md` (one is a discovery, one is reported
offstage); a scene band narrowed from the outline's 2,600–3,900 without a note; and a rationed-constructions
list that banned "nobody thanked" while omitting "nobody asked".

Its date spine is otherwise clean: 121–130 = the 21st–30th of M+2 per outline §12, countdown 39→30
continuous with Ch 120's printed forty.

## What is genuinely good, and must not be lost in a future repair

The countdown spine is exact throughout — 49 (20+29), 48, 47, 46, 45, 44, 43, 42 ("six weeks", 6×7
exact), 41, 40 (11+29). Dates check against §12 by subtraction, not by the weekday name. The household
arithmetic at 119 — six names against a file saying more, the seventh line being Sun, and a refusal that
costs Runa and cannot be taken back — is the batch's real turn: it changes the situation rather than
explaining it. Drant's line at 120:49 is the strongest sentence in the ten.

## The lesson

**No gate in this repository catches a sentence printed twice.** The paragraph gate measures paragraphs.
The word gate counts words. A duplicated paragraph passes all of them. A repair pass now diffs the batch
against itself for repeated sentences before it claims the paragraph gates are clean.

And, for the fourth time in this pipeline: **a repair asserted in a state file was absent from the page
it described.** Repair #6 of the batch's own list — "five people corrected to four" — was done at 118:31
and not done at 118:69. The repair list was true and the page was not, and a grep cannot tell the
difference. Item 22 in `state/current.md` already records this as the structural fix: **a review is a
separate run, and a writer's own record of its own repairs is a claim to be re-run, not a claim to be
trusted.**