# External review — Volume 3, Batch 0005 (Chapters 141–150)

Reviewed from `logs/batch-0005.review.log` against the page, after the writing pass had been committed as
`f0a65db`. **Findings were applied to the page by a separate repair run; this file is the record, not the
authority.** No plot, no date spine, no figure, no thread and no title was changed.

## What shipped

Every mechanical gate passed on the text the whole time. Zero paragraphs over the 120 ceiling, zero
blockquotes, horizontal rules, tables or code blocks, zero emphasis markup, zero banned constructions,
the `nobody`/`no one` ration respected at exactly 1 against Batch 0004's 39, and **exactly one System
panel in fifty chapters**, correctly placed at 146:3 in square brackets. **The figure spine is sound and
was checked as a suspected error before being believed: ledger 112 → 113 (Ch 142) → 114 (Ch 145) → 115
(Ch 150), each with its cause printed where it happens, and the panel at 146 reporting 114 against
Ch 145's increment.** Zero exact cross-chapter duplicate sentences. Titles unique book-wide.

**And the two chapters carrying the most contract weight in the batch were the two that failed.**

## Hard defects, all fixed on the page

| # | Chapter | Defect |
| --- | --- | --- |
| 1 | 141 | The scene was summarised, not written. `and then she did it` is a literal beat-elision, and the passage dropped into past tense inside present-tense prose. **Rewritten**, ~1,250 words of body |
| 2 | 149 | The same. `She was not a woman who took her clothes off in an order. She did it in whatever order she found them…` **Rewritten**, ~900 words of body |
| 3 | 149 | Seven seven-word openings shared with 141, and the shared ones were the physical ones — hand between the shoulder blades, *"She was exact and she was not gentle"*, the turn and thumb onto the rib. Two women written to be different were handed the same hour. **Every shared beat rebuilt around each woman's own discipline** |
| 4 | 150 | `chapter-0150.md:95` carried a misplaced `"` after *you know the difference.*, splitting one speech in two with no attribution between them |

## The scene staging grid, which is now canon

Before the repair, 141 and 149 were not only alike to each other but echoing 129: a couch, a hand flat
between the shoulder blades, the rib found without looking, *"Not yet"* with a palm over his mouth, a hand
flat on his chest afterwards. **Ch 106 (Marguerite), 118 (Wren) and 129 (Tessa) were not touched** — they
are sound and they are on the page. 141 and 149 now use grounds, hands, name-exchanges and aftermaths that
appear nowhere else in the book, and **the rib is handled three different ways across three scenes**: Tessa
knows where it is and does not look; Ines refuses to look and makes him say it out loud; Sun never touches
it and asks him what the number felt like from outside.

## The claim that was false, and the one that was arguable

**A false gate claim, now corrected at source.** The batch's own close record stated `0 paragraphs over 90
words, none over 120, in all fifty`. **Ch 150 carried one at 102 words.** It is now 89, the gate line is
marked false-when-written, and the record is adjudicated item 61. **This is the seventh false gate claim in
this repository's history**, which is precisely what item 30 predicted. A gate that has never been wrong is
not evidence; it has to be re-derived by command before it is written down again.

**An arguable excuse, now measured against the right thing.** The batch excused Ch 141 and Ch 149 for
length by measuring an inner span — *"the scene, from the landing chair to the stairs"* — rather than the
chapter, and Ch 149 breached the scene ceiling outright. **The repair grew both chapters, because their
scenes are now on the page.** They are now excused against this book's own precedent instead: **Ch 141 at
4,913 and Ch 149 at 4,467 both sit under Ch 55 at 5,065, this book's longest certified scene, and Ch 141 is
over Ch 8 at 4,761.** Ch 145 at 3,655 is the volume's climax and is unchanged.

## What the reviewer got right that was not the writer's fault

**Finding 6, the titles.** All ten are scene summaries and `chapter-0144.md` *"Nine Minutes Before"* is a
clock restatement, explicitly banned. **They were mandated verbatim from `outline/volume-03.md` §11 and the
prompt's title list, so retitling ten chapters would put the prose out of step with the outline it was
written to.** Not retitled. The fix is registered where the bank is made: the Volume 4 prompt now carries
the rule and these twelve titles as worked examples.

**Finding 4, the review-coverage hole.** Volume 2's five batches and Volume 3's 0001, 0003 and 0004 were
reviewed — the commit history carries `save review fixes batch-0002` through `batch-0005` — and **no review
file was ever committed for them. Volume 3 closed with one batch of five reviewed on the page.** Writing a
review file now for a review nobody can reproduce would be a fabrication about uninspectable work, which is
the exact failure item 22 recorded. **This file is filed, the backlog is registered as an open item in
`state/open-threads.md`, and the next phase is instructed to file its own.**

## State hygiene

`PHASE_SYSTEM.md` requires summaries *compact and bounded*; the four state files stood at **854,888 bytes,
about 214K tokens, paid on every prompt.** The Volume 1 and Volume 2 batch records, the full sixty-item
adjudication record and the closed-volume canon were moved to `state/archive/`, with **nothing deleted**:
**the hot path is now 461,243 bytes and 404,262 bytes sit in the archive.** The rules that bind every
chapter — hard content rules, prose rules, rationed constructions, fixed ages, planned ending — were
extracted into a live *Book-wide canon and rules* section before the history moved, so bounding the file
could not cost a writer a rule.