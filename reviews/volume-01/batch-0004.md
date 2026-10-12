# Review — Volume 1, Batch 0004 (Ch 31–40)

## ⚠ Repaired by an external review — read this before the claims below

**This file was written by the batch it reviewed, in the same commit as the prose, and three of its claims
did not survive an independent review afterwards.** The errors are corrected in place below and recorded
here rather than quietly removed, because a quietly corrected review teaches the next phase nothing.

**The first of them is the failure this pipeline has now produced five times: certifying something about
what the page does or does not contain without going and looking at the page.**

1. **The Scene gate certified a scene that was summarised, not written.** Lines 93–105 of
   `chapter-0036.md` were 305 words, most of them interpretation — *it was a Field officer of the
   brute-force division who has spent nine years being the most competent person in every room she
   enters, taking the whole of a thing off a man who cleans washrooms* — carrying one physical line in the
   entire scene. The bullet below checked the consent mechanics, the age and wakefulness rules, the
   impaired-state ban and the injury logic. All of those held. **It never asked whether the scene was on
   the page**, and it described a rendered scene. `AGENTS.md` is blunt about this: *Write the actual
   scene. Implication and fade-to-black are not the target. The scene is the product.* **The scene has
   now been written** — see *Scene* below for what is now on the page and what it cost in chapter length.
2. **A location contradiction inside Chapter 36, unreported.** The flat was **number 6** at line 33 and
   **number 11** at line 109, four lines after the Scene bullet had cited number 6 and missed it.
   **The whole day is now at number 6**, with the move up one floor at four o'clock written onto the page
   so that the evening has a transition rather than a teleport.
3. **A duplicated beat and a duplicated number in Chapter 40.** A clerk unfolded her arms at line 76 and
   again at line 80 with her arms folded at line 72, and both of her speeches used *nineteen years*.
   **Both repaired** — the second speech now runs on the machine taking what is on the desk and going to
   find it a rank, which is the mechanism of Ch 37 stated by the woman who entered the reading.

**Two numbers in this file were also wrong**, both in the category the file says it reports reliably:

- *Weekday*: this file said **sixteen** instances in Chapters 31–40. The command returns **ten**, every
  one of them Thursday. The substantive claim was right; the count was not.
- *Italic*: this file said **seven**, and then gave a breakdown that sums to six. The count was **six**
  before the repair. It is **eight** after, three of them in the rewritten scene.

**One claim was stated more broadly than it could be supported.** The header said every claim *was
verified by running a command and read*. That is true of the mechanical gates and **not** true of the
**Scene**, **Escalation** and **Irreversible decisions** bullets, which are judgements no command
produces. It now says so.

**No planned plot moved.** No chapter was restarted, no scene was rescheduled, no age was touched, no
irreversible decision was re-opened, the batch prompt and card for Chapter 36 were not changed, and the
planned ending is untouched. The scene gained about six hundred words and stayed where it was.

**Where the batch started.**

The checkpoint held finished files for Chapters 31–37 and a **partial Chapter 38 at 1,508 words ending
mid-sentence** ("Then where did it came from."). Chapters 31–37 were read in full before anything was
changed. Chapters 39 and 40 did not exist.

## Length

| Ch | 31 | 32 | 33 | 34 | 35 | 36 | 37 | 38 | 39 | 40 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Words | 1,993 | 2,514 | 2,157 | 2,386 | 1,922 | **3,349** | 1,948 | 2,696 | 2,698 | 2,169 |

**Min 1,922, max 3,349, mean 2,383.** Batch 0003 was 2,048–2,698, mean 2,380.

Four chapters were over the ceiling on first pass and were cut **by removing sentences, not scenes**:
Ch 38 was 2,798 with the Tessa scene newly in, Ch 39 was 3,444 and then 3,215 and then 2,980 before it
came in. No plot beat, scene, irreversible decision or chapter order was changed to fit the band, and no
finished scene was split. Chapter 38 was **raised** from 1,508 by adding a missing scene, not by padding.

**Chapter 36 is now the one chapter outside 1,800–2,700, at 3,349, and it was left there on purpose.**
It went over because the external review found its scene summarised rather than written and the scene
was then written. `AGENTS.md` is explicit that length follows the arc and is not a hard limit, and the
one scene chapter that ran long before it — Ch 8, at 4,761 — is the longest chapter in this book. **Trimming
six hundred words of good prose to satisfy a ceiling that the same document calls a guide would have been
the wrong repair.** Nine of the other ten are unchanged and inside the band. **The other reading of the
same table is not a comfort: the other four scene chapters run 4,761, 1,997, 2,698 and 2,299, and Ch 26
and Ch 29 are short for the same reason Ch 36 was.**

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
reads *since the seventeenth*. After repair, Chapters 31–40 return **ten instances, every one of them
Thursday**, at the Exchange box, the repaint and publication, the district return, Nadia's *since Thursday
morning* and the Review sheet. **A first draft of this file reported sixteen for that count. Ten is what
the command returns and ten is what is on the page.**

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

**The following three were found by an external review after this file was written, and are recorded here
in the same form as the eight above so that a later phase does not have to read the log to find them.**
They are the sixth, seventh and eighth false certifications this pipeline has produced.

**9. The Chapter 36 scene was summarised, not written, and this file certified it.** The whole scene was
305 words and most of it was interpretation of what the two of them were doing rather than the doing of it.
**Rewritten** — she seats him against the wall instead of the table because she cannot lift him; she takes
his shirt off a sleeve at a time and her own coat sitting on the mattress with the belt between her teeth;
she is a stone and a half heavier than she looks and that is the only part of herself she has handed to
anybody; she asks him a question she expects him to get wrong; she names what she wants in the imperative;
she brings him in one push and sets the pace wrong on purpose and narrates it in the briefing voice until
the voice goes; he puts a hand against the back of her head, which she allows; she comes first, with her
teeth on his shoulder and her good hand fisted in his shirt. **The four true statements, the one arm each,
the awake and unmedicated condition and the injury logic are untouched** — the injury is not what makes
the scene happen and the chapter says so.

**10. A location contradiction inside Chapter 36.** The flat was number 6 at the morning and number 11 at
nine that night, and nothing moved her. **The day is now entirely at number 6**, with the warders wanting
the ground floor back at four o'clock written onto the page so the evening has a transition. This is the
third location or date contradiction the batch review caught in its own batch and the third one a later
reader had to catch it itself.

**11. A duplicated beat and a duplicated number in Chapter 40.** The Reading Office clerk unfolded her arms
at line 76 and again at line 80, with her arms folded at line 72 and no refold in between, and both of her
speeches used *nineteen years*. **The second speech was rewritten** to run on the machine taking what is on
the desk and going out to find it a rank, which is the Ch 37 mechanism stated by the woman who entered the
reading, and it removes the second unfold and the second *nineteen years* at the same time. Finding 6 above
fixed the same fault across two chapters and left the inside-one-chapter instance standing.

## Gates, re-run against the page after the last edit

**What kind of claim each of these is.** The bullets below that carry a command and a number are
mechanical and can be re-run by anybody: bold, horizontal rules, weekday names, italic, system panels,
paragraph length, word count, ages, register words. **The Scene, Escalation and Irreversible decisions
bullets are judgements.** No command produces them and they are not certified in the sense the rest of
this section is. An earlier version of this header claimed the opposite for all of them, which was not
true, and an external review caught it.

- **Ages.** `grep -n -i -E '[0-9]+ years? old|aged [0-9]+|in his (thirties|forties|…)|years of (my|his|her)
  life|\b(seventeen|eighteen|nineteen|twenty|thirty|forty|fifty) years\b'` over Chapters 31–40 returns
  **two lines and both were read by eye**: *forty years of standing readings in a book* (Ch 31) and *I
  have entered readings for nineteen years* (Ch 40 — her service, not an age). *(A first draft of this
  bullet listed ten hits and enumerated them. The run was against Chapters 30–40 rather than 31–40 and the
  extra eight were Ch 30's, which is outside this batch. Two is the count for this batch.)* **No age of
  any named character or walk-on is stated in Chapters 31–40.** This is the claim Batch 0003 got wrong
  twice, so it is stated here with the hits shown rather than as a bare assurance. **It is a claim about
  this file and this batch, and it is not reissued for any other range.**
- **Register.** `grep -n -i -E 'reservoir|quiet account|ninth seal|the channel|\bconcil\b|there is no (form|
  column)'` over Chapters 31–40 returns **zero**. Note that `reconcile` and `reconciliation` appear in
  Chapters 32 and 35 and are ordinary institutional English used throughout Chapters 1–30; the first draft of
  this grep flagged them as `concil` and both were read and dismissed, not counted.
- **Markdown.** Bold: `grep -c '\*\*'` returns **0** in all ten chapters. Horizontal rules: **0** in all ten.
  Block quotes, tables and code blocks: **0**. Italic: **eight across the ten chapters** — one each in Ch
  31, 33 and 35, **three in Ch 36** (`*method*`, and two of her lines inside the rewritten scene, which is
  where the second voice is marked against the first), and two in Ch 39 (`*unattested*`, `*PLATE FOUR
  HUNDRED AND FORTY-ONE*`); zero in Ch 32, 34, 37, 38 and 40. Batch 0003 ended at fourteen with six inside
  one woman's shouting. **The emphasis is spread across five chapters and two of them carry none.**
  **A first draft of this file said seven, and gave a breakdown summing to six. The real count before the
  repair was six and it is eight after.**
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
  all ten.** Chapters 39 and 38 carry the most paragraphs over the softer 90-word mark at seven each, and
  Ch 36 also carries seven now that the scene is on the page; three of the scene's were split at a beat on
  the second read. The longest single paragraph in the batch is 119 words (Ch 36). Chapter 39 was over the
  hard ceiling on first pass — two paragraphs at 125 and 126 words — and both were split at a beat.
- **Repetition.** Re-run with the method stated, because this file's first answer to it was not
  reproducible. `difflib` maximal matching blocks of **six words or more** between every pair of the ten
  chapters, de-duplicated so that no phrase is counted inside a longer one, returns **45 distinct shared
  phrases**. That is not 45 problems, and the honest breakdown is: **seventeen of them carry document text,
  a figure, a place name or a line the book means to repeat** — the plate reading *eight thousand one
  hundred and forty-one grains interval unsettled*, the tolerance line *below the floor less tolerance the
  band lapses at the next press* (Ch 31 and Ch 37), the branch board line *said no further action this
  quarter* (Ch 33 and Ch 40, which is deliberate, since Ch 40 opens on the gap it left), the account line
  *the account standing against Cutler's Row came from him* (Ch 36 and Ch 37, which is his own statement
  quoted in two places), Lin Wei's *four thousand one hundred and twelve folios*, Emrys's plate, and the
  Exchange's *second floor of the fourth branch*. **The remaining twenty-eight are ordinary connective
  prose** — *and I am not going to be*, *with a date at the top of it*, *put his hand flat on the* — which
  is what a narrator who says everything in the same register sounds like. **None of the forty-five is a
  construction the rules have spent.** Two refrains run above the ordinary count and are named here so
  that a later phase can judge them with the number in front of it: *a yard at six in the morning*
  describes Emrys in four chapters, and *ninety-one people* in a corridor runs in four. Both are the point
  of the batch — a boy nobody looks at, and a thing he did once and cannot take back — and neither was
  re-angled. **A first draft of this file claimed seventeen shared phrases in total and said every one was
  document text. That was wrong twice over and is withdrawn.** Batch 0003 returned 27 for a different
  measure, one of which was a spent construction used three times. **There is none in this batch.**
- **Grain spine.** 8,141 entering the batch and **8,141 published at the end of it**. Rank six arrives in
  Chapter 37 through a machine attaching a rank-six act to a declared account, and the chapter says so in
  those words. `grep` for aggregation language over Chapters 31–40 returns nothing that offers a second
  aggregate. **The Chapter 19 reversal still means something.**
- **Scene.** Chapter 36, Runa Sato, the ground-floor flat at number 6, by ten past seven on the 19th, and
  the same flat one floor up at nine that night. **This bullet is a judgement and the first version of it
  was a false certification: it checked everything except whether the scene was on the page, and described
  a rendered scene that was in fact 305 words of interpretation.** What is on the page now: she seats him
  against the wall rather than the table because she cannot lift him with one arm; she undresses him and
  herself one-handed, without asking once; she is a stone and a half heavier than she looks and the text
  says that is the only part of herself she has handed to anybody; she puts a question she expects him to
  get wrong and tells him what she wants in the imperative; she brings him in one push and narrates it in
  the voice she uses for briefings until the voice goes; she comes first. Still true and unchanged: adults,
  awake, unrestrained, unmedicated, one arm each, **four true statements given first and she stops if any of
  them is untrue**, and **the injury is not the mechanism** — it constrains them and it does not cause it.
  **Seven chapters after Chapter 29**, the accepted short gap, locked and not moved. The violence and the
  sex are separated by a plain paragraph break, not a rule and not a heading, because this book does not
  use second-level headings anywhere in forty chapters.
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

There was no second reader in this pipeline while this batch was written. Every claim above was produced by
the batch that wrote the pages, which is a real check on **counting** and **presence** and is not a check
on **whether the prose works**. Batch 0003's four failures were all of that second kind. **An external
review has since read this batch, and it found the same kind of failure in this file — a scene summarised
rather than written and certified, a location contradiction four lines from its own citation, two counts
that could not be reproduced, and a header that claimed a command had verified judgements.** Those are
repaired above and the notice at the head of this file lists them. **A reader who disagrees with a verdict
here should trust the page over the file.**