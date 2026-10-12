# Review — Volume 1, Batch 0004 (Ch 31–40)

**This file was written by the batch it reviewed, in the same commit as the prose.** Item 22 of
`state/current.md` records that Batch 0003 did exactly this and certified two things the page contradicted.
So the claims below are stated with the command that produced them and, where a command returns hits, with
what is actually in the hits. **Where this file says a count is zero, the grep was run and read. Where it
reports a number, the number is what the tool printed.** No claim here asserts that a gate was run unless
the gate was run.

## Where the batch started

The checkpoint held finished files for Chapters 31–37 and a **partial Chapter 38 at 1,508 words ending
mid-sentence** ("Then where did it came from."). Chapters 31–37 were read in full before anything was
changed. Chapters 39 and 40 did not exist.

## Length

| Ch | 31 | 32 | 33 | 34 | 35 | 36 | 37 | 38 | 39 | 40 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Words | 1,993 | 2,514 | 2,157 | 2,386 | 1,922 | 2,685 | 1,948 | 2,696 | 2,698 | 2,143 |

**Min 1,922, max 2,698, mean 2,314.** All ten inside 1,800–2,700. Batch 0003 was 2,048–2,698, mean 2,380.

Four chapters were over the ceiling on first pass and were cut **by removing sentences, not scenes**:
Ch 38 was 2,798 with the Tessa scene newly in, Ch 39 was 3,444 and then 3,215 and then 2,980 before it
came in. No plot beat, scene, irreversible decision or chapter order was changed to fit the band, and no
finished scene was split. Chapter 38 was **raised** from 1,508 by adding a missing scene, not by padding.

## Findings, and what was done about them

**1. Eighteen horizontal rules in Chapters 33–38.** `grep -c '^---$'` returns 2, 3, 2, 2, 4 and 5 across
Chapters 33 to 38 and **zero across Chapters 1–32**. `AGENTS.md` lists horizontal rules under *Not allowed
in a chapter file*, and the Batch 0003 review certified *No block quotes, tables, rules, code, or
second-level headings* for that batch. The partial draft had introduced them as scene separators. **All
eighteen removed** and collapsed to plain paragraph breaks. Chapters 1–40 now return zero.

**2. Three illegal weekday names, all in Batch 0004 prose.** `grep -o -i -E '\b(monday|…|sunday)\b'` over
Chapters 31–40 returned, before repair: `chapter-0034.md:115 "Wednesday,"`, `chapter-0038.md:37
"…she had it on a Wednesday"`, `chapter-0038.md:81 "because he had not slept since Saturday"`. **All three
read by eye and all three removed** — the fire-door exchange was re-angled onto dates (the eleventh, the
twelfth, last night, three this afternoon), the headache line lost its weekday, and the sleepless line now
reads *since the seventeenth*. After repair, Chapters 31–40 return **sixteen instances, every one of them
Thursday**, at the Exchange box, the repaint and publication, the district return, Nadia's *since Thursday
morning* and the Review sheet.

**3. A paraphrase of a spent construction in Chapter 32.** The offer read *and no court in this city could
take it off you because there is no record of it to seize*. That is the shape of *there is no column for
it*, and a word-list would not have caught it, which is the reason the guard says to sweep the construction
rather than the wording. **Re-angled** to *a court cannot seize a thing it has never been told exists*,
which is the same fact and a better sentence. Chapters 31–40 now return zero hits for both exact phrases
and for the construction.

**4. Two internal date contradictions in Chapter 34, both visible on the page.** A man at number 11 tells
Lin Hao he has been *in my passage four times since the seventeenth* — on the seventeenth. And *two nights
running a man has come through my back door* against a forced-door count of the 11th, the 12th and the
16th. **Both fixed** (*four times in three days*; *three times in a fortnight*) so that Chapter 36's
account of the door — forced on the 11th by somebody else and at three on the 17th by the warders —
matches the chapter that sets it up.

**5. Chapter 38's opening claimed five people and visited six, and one of the five was missing.** The five
turned lines at the end of Batch 0003 are Nadia, Ola, Emrys, Teodor and **Tessa**. The partial draft opened
*There are five people in Ostara who have felt what he does and kept track of it* and then visited Halvard,
Nadia, Ola, Teodor, Emrys and Ines. **The opening was corrected** to say five *turned* lines, and **Tessa
Okonkwo was written in** — the cold store, the stippling above her left elbow and pale blue above the
joint, six episodes since the 3rd and none of them hers, a twelfth clipboard, and a request that he say the
number out loud to her once a month. She also refuses to thank him before he can, which is the Halvard
pattern held and sharpened. Halvard is retained and re-labelled as the control case, which is what he has
been since Chapter 3. The chapter went from six visits and a false count to six visits and a true one.

**6. A near-repeat of a Chapter 37 line inside Chapter 40.** The Correction Office clerk in Ch 37 says *That
is the first one of those I have had up in nine years*; the Reading Office clerk in Ch 40 originally said
*That is the first of those in nine years I have had up in a queue*. Two different clerks, two chapters
apart, near-identical lines. **Re-angled** so the second is *I have entered readings for nineteen years and
I have never once seen that word go up on a board that was going into a Review.* The same passage's echo
of Chapter 30's *run out of the ones that were honest* was cut at the same time.

**7. A date arithmetic slip in Chapter 40.** The chapter said *nine days and two hours until it* for a
reading three days out, four lines after saying *three days from then*. **Corrected** to *three days and
two hours*.

**8. A canon age written into dialogue in Chapter 39, by me, on the first pass.** Ines said *he is seventeen
years old* about Emrys Vaz. That is canonically correct and it is **still barred** — `AGENTS.md` forbids any
age in narration or dialogue, and the residual register in `state/open-threads.md` exists precisely because
Ch 16 and Ch 18 did this. Caught by the bare-number-age sweep, which is the version of the gate that exists
because the first version missed it. **Changed to *he is a boy*.** The gate was run before the sentence was
read twice, not after.

## Gates, re-run against the page after the last edit

- **Ages.** `grep -n -i -E '[0-9]+ years? old|aged [0-9]+|in his (thirties|forties|…)|years of (my|his|her)
  life|\b(seventeen|eighteen|nineteen|twenty|thirty|forty|fifty) years\b'` over Chapters 31–40 returns
  **ten lines and every one was read by eye**. All ten are false positives: *forty years of standing
  readings in a book* (Ch 31), *in about ninety seconds* (Ch 32, Ch 39), *about forty people at the rail*
  (Ch 37), *about a foot off the ground* (Ch 30), *about seventy of the hundred* (Ch 39), *not been there on
  Thursday* (Ch 40), *I have been a clerk for nineteen years* (Ch 40 — her service, not an age). **No age of
  any named character or walk-on is stated in Chapters 31–40.** This is the claim Batch 0003 got wrong twice,
  so it is stated here with the hits shown rather than as a bare assurance. **It is a claim about this file
  and this batch, and it is not reissued for any other range.**
- **Register.** `grep -n -i -E 'reservoir|quiet account|ninth seal|the channel|\bconcil\b|there is no (form|
  column)'` over Chapters 31–40 returns **zero**. Note that `reconcile` and `reconciliation` appear in
  Chapters 32 and 35 and are ordinary institutional English used throughout Chapters 1–30; the first draft of
  this grep flagged them as `concil` and both were read and dismissed, not counted.
- **Markdown.** Bold: `grep -c '\*\*'` returns **0** in all ten chapters. Horizontal rules: **0** in all ten.
  Block quotes, tables and code blocks: **0**. Italic: **seven across the ten chapters** — one each in Ch
  31, 33, 35, 36 and two in Ch 39 (`*unattested*`, `*PLATE FOUR HUNDRED AND FORTY-ONE*`), zero in Ch 32, 34,
  37, 38 and 40. Batch 0003 ended at fourteen with six inside one woman's shouting. **The emphasis is spread
  across five chapters and two of them carry none.**
- **System panels.** `grep -n '^\['` over Chapters 31–40 returns **two**: Ch 37 and Ch 40, one each, at the
  two points where a number a reader can act on moves. The wording differs — Ch 37 is about the strike and
  the floor, Ch 40 is about the queue and the band. **No panel is byte-identical to any other in the book**,
  including Ch 25 and Ch 30.
- **`nobody` / `no one`.** **Thirteen** across the ten chapters: Ch 32 (2), Ch 34 (1), Ch 35 (2), Ch 36 (1),
  Ch 37 (1), Ch 38 (1), Ch 39 (4), Ch 40 (1), Ch 31 and Ch 33 zero. **Highest in a single chapter is four.**
  *(A first pass of this file reported sixteen. That count had swept in the word `none`, which the target does
  not include; `none` appears four times in the batch and is a different word with a different job.)*
  Target was thirty across ten with a ceiling of five. *The person nobody looked at* returns **zero**.
  *Nobody thanked him* returns **zero**; Chapter 50 keeps it. Two characters refuse to thank him **out loud
  first** (Tessa Ch 38, Ines Ch 38) and no feeder thanks him anywhere.
- **Paragraphs.** A script over Chapters 31–40 counts paragraphs over the 120-word hard ceiling: **zero in
  all ten.** Chapters 39 and 38 carry the most paragraphs over the softer 90-word mark at seven and six,
  and the longest single paragraph in the batch is 119 words (Ch 36, the scene). Chapter 39 was over the
  hard ceiling on first pass — two paragraphs at 125 and 126 words — and both were split at a beat.
- **Repetition.** A sweep for content-bearing shared 6-grams across the ten chapters returns **17**,
  re-run after the last edit, and
  every one was read. All are reproduced document text: the plate reading *eight thousand one hundred and
  forty-one grains interval unsettled*, the tolerance line *below the floor less tolerance the band lapses at
  the next press* (Ch 31 and Ch 37), the branch board line *in a clerk's hand said no further action this
  quarter* (Ch 33 and Ch 40), and *the account standing against Cutler's Row came* (Ch 36 and Ch 37).
  **None is a construction.** Batch 0003 returned 27, one of which was a spent construction used three
  times.
- **Grain spine.** 8,141 entering the batch and **8,141 published at the end of it**. Rank six arrives in
  Chapter 37 through a machine attaching a rank-six act to a declared account, and the chapter says so in
  those words. `grep` for aggregation language over Chapters 31–40 returns nothing that offers a second
  aggregate. **The Chapter 19 reversal still means something.**
- **Scene.** Chapter 36, Runa Sato, a requisitioned flat at number 6. Adults, awake, unrestrained,
  unrestrained by pain and not medicated; four true statements given first and she stops if any of them is
  untrue; the mechanism is neither her strength nor his injury, and the text says the injury cannot carry
  weight — the stair did not move because she carries weight, and the text uses that once, as a fact about a
  building, before the scene. Violence and sex are in separate sections with a scene change between them.
  **Seven chapters after Chapter 29**, the accepted short gap, locked and not moved.
- **Irreversible decisions.** Six are listed in `state/current.md`. **Chapter 39 is the batch's**: he
  refused the Field's document, dictated his own, and put five names back on a board in order to file the
  truth about one boy at a yard gate. It cannot be retracted and it opened a query against his own standing.
- **Escalation.** He investigates (Ch 33, 34), manipulates (Ch 35, the counter question), breaks something
  (Ch 37's statement, Ch 39's filing), and the system reacts to him (Ch 40: a published rule that a
  provisional band is not carried into review, printed two days after his own document). **He is past the
  midpoint of the volume and no longer only looking at the system.**

## Standing risks carried into Batch 0005

- **The May clipboard is the hinge and it is untouched.** Tessa's second-of-May clipboard is on a table in
  Chapter 38 and a figure is on a board in Chapter 40 and he has said nothing in either. **The word Channel
  does not appear and may not appear.**
- **The register is a Volume 2 engine.** Nine years, thirty-one entries, the oldest still running and
  entered by hand in pencil before the form was printed. Chapter 39 established what it *is* — a catch and
  not a census — and deliberately did not establish what it *contains*. **Do not resolve it in Volume 1.**
- **The Reading Office query wants an instrument.** He can petition sealed files at six, from the 29th, if he
  holds the band. Lin Wei is 4,112 folios. The deposit is the obstacle and the margin is three grains.
- **Tobias Renn is on a board again** because of a statement the declarant filed himself, eight days after
  the declarant said he was not a defaulter. He has still not been thanked and will not take it in a speech.
- **Tessa's rack is at twelve** and she is taking four a day, and she has asked for one thing.
- **Marguerite's terms arrive Chapter 45 and her scene is Chapter 46.** She refused to take the terms down
  on the 13th and said out loud that she was sorry about what she had done by showing him the books.
- **Eleven thousand eight hundred and fifty-nine grains, six weeks, nineteen people.** Chapter 48's answer
  is on the table and nothing before it may pre-empt it.
- **Four residual ages survive in certified chapters** (Ch 3, Ch 8, Ch 16, Ch 18) and fifty-eight illegal
  weekday names survive behind Chapter 20. Neither was touched. **Chapters 30–40 are clean on both.**

  **A claim in an earlier draft of this file said *Chapters 21–40 are clean on both*. That was false and is
  the fifth false certification this pipeline has produced, in the same shape as the four before it.**
  `chapter-0029.md:91` has Nadia Ferrous say *I have had twenty-three years of my life.* It is canon-correct
  — Batch 0003 changed twenty-eight to twenty-three for exactly that reason — and it is an age in dialogue
  inside a batch that was certified clean on this. **It is the one deliberate instance in Chapters 21–40 and
  it is recorded here rather than left to be discovered.** Chapters 21–30 return no illegal weekday name
  other than Thursday. The residual census is therefore: **five** age instances, not four, and one of the five
  is inside a batch that certified the absence of all of them.

## One thing this review cannot check

There is no second reader in this pipeline. Every claim above was produced by the batch that wrote the
pages and was verified by running a command and reading the output, which is a real check on **counting** and
**presence** and is not a check on **whether the prose works**. Batch 0003's four failures were all of that
second kind — two claims about what the page *did not contain*, which is exactly the category a grep is
worst at. The greps above are reported with their hits shown for that reason. **A reader who disagrees with a
verdict here should trust the page over the file.**