# CURRENT — Ranked by Desire · 950 chapters on disk, nineteen volumes, every volume closed, no phase open

**COMPACTED 2026-10-15.** This file used to be twenty-four stacked blocks, 423 KB, in which each block announced that it superseded the ones below and none of them was ever deleted. The live head block and the one beneath it were, by the file's own instruction, "the whole of what you inherit", which left 1,320 of 1,395 lines as dead weight. Every measurement that was in it is still on disk in `reviews/volume-19/` and in `state/archive/`, and §8 says exactly where. Nothing a later writer needs was dropped; what went is restatement.

## 1 · Where the manuscript is

950 chapter files across nineteen volumes, fifty a volume, all finished prose. Nine hundred and fifty H1 title lines and no two of them alike. The last chapter on disk is `chapters/volume-19/chapter-0950.md`, *Not One Name*, the thirtieth of December of year twelve, and it is the close of Volume 19.

Every volume carries its own close audit under `reviews/`. Volume 19's is `reviews/volume-19/volume-close.md`, which is the current authority on 901–950, and it repaired thirty-six single phrases across twenty-one chapters without moving a beat, a scene, a decision, a figure, a title, a form ordinal or a chapter date.

**One stale prompt is still on disk, and it is the one thing in `workspace/` a dispatch could pick up.** Every writing, batch, continuation and close phase carries `.done`. **One directory does not: `workspace/volume-10/volume-plan/`, which still holds a Volume 10 planning prompt from October 2026 and carries a `.retired` marker instead of a `.done` marker.** `scripts/novel_runner.sh` selects the first `PROMPT.md` in sorted order that lacks `.done` and `.blocked`, and its selection loop **does not test `.retired`** — the retire sweep honours `.retired`, the selection loop does not. That directory sorts ahead of everything in Volume 19. **Its prompt says it is writing `outline/volume-10.md`, which exists, and the volume behind it was closed nine volumes ago. Do not run it.** It is controller state and this phase did not touch it.

**The book is not finished in the sense `outline/ending.md` defines.** See §2.

## 2 · Three things this repository is waiting on, and none of them is a writer's decision

**THE OVERRUN, WHICH IS THE BIG ONE.** `NOVEL_SPEC.md`, `outline/series.md` and `outline/ending.md` all fix the book at five hundred chapters across ten volumes, and `outline/ending.md` heads itself *Volume 10, Returned (chapters 451–500)* and reads *Ch 498: the last chapter*. The manuscript runs to nine hundred and fifty across nineteen volumes. Nine volumes exist that no series outline and no ending outline planned. The flag has been open since Volume 19's planning pass and is carried, still open, at §7 of `state/open-threads.md`, and the close audit states both readings and makes neither. **This is a series decision about files a writing phase may not rewrite, and it is not made here. It is one line in `state/open-threads.md`, by whoever is told to write it.** `scripts/completion_guard.py` returns *ok, 950 chapters reaches planned 500*, because its test is one-sided: it refuses a manuscript short of the plan and has no test for one long of it. Do not read that exit code as a verdict.

**THE PHASE LEDGER, AND THE STALE PROMPT IT LEAVES BEHIND.** `PHASE_SYSTEM.md` says the selector chooses the next phase by reading `state/phase-ledger.json`. That file has never existed and is not in any commit. No script reads it; the runner falls back to scanning `workspace/` for `PROMPT.md` files without `.done`, sorted by path, first one wins. Marker files carry presence and absence only — no ordering, no chapter range, no completion state. **The consequence is measured and it is in §1: one stale Volume 10 planning prompt is selectable today, because the selection loop does not test `.retired`.** `state/phase-ledger.json` is a controller file and this phase may not create it; the marker is runner state and this phase may not set it.

**THE VOLUME-CLOSE PHASE THAT WROTE A BATCH.** `PHASE_SYSTEM.md` says a volume audit must not attempt to rewrite the entire volume. Commit `bd55252`, `novel: complete batch-0005 (chapters 941-950, THE USE) and close volume 19`, wrote the ten chapters, wrote the cards, and wrote its own successor prompt in one commit. It produced correct prose and a closed volume, so nothing is being undone, but the procedure is wrong and it is a controller file. **The duplicate dispatch of `workspace/volume-19/batch-0004/` burned four runs and produced nothing before being marked done, and its refusal was correct: the book is nine hundred and fifty chapters, not nine hundred and sixty.**

**AND ONE ARITHMETIC ERROR IN A CLOSED PHASE'S PROMPT, ALREADY ADJUDICATED IN PLACE.** Question 10 of `workspace/volume-19/volume-close/PROMPT.md` prints **340** as the inside-the-five-batches figure. **It is 312.** The volume's five batches contain 312 days of spine and the seam carries 20, and 312 + 48 of seam across the four boundaries is 360, which is `4,289 - 3,929`, one year exactly, the fifth time running. 340 is the whole span from 901 to 950, and 340 + 20 = 360. The prompt carries an adjudication note under its own heading saying so; its instruction text was left unedited, because it is a closed phase's specification of record. **The figure that is correct is in §5 of this file.**

## 3 · The batch map, because the number means two different things in this volume

| Chapters | Outline cards of record | Phase directory | Movement |
| --- | --- | --- | --- |
| 901–910 | `outline/batches/volume-19-batch-0001.md` | `workspace/volume-19/batch-0001/` | one, *The Winter* |
| 911–920 | `outline/batches/volume-19-batch-0002.md` | `workspace/volume-19/batch-0002/` | two, *The Telling* |
| 921–930 | `outline/batches/volume-19-batch-0003.md` | **none** — written through `workspace/continuation/next-0011/` | three, *The Lane* |
| 931–940 | `outline/batches/volume-19-batch-0004.md` | `workspace/volume-19/batch-0003/` | four, *The Refusal* |
| 941–950 | `outline/batches/volume-19-batch-0005.md` | `workspace/volume-19/batch-0004/` | five, *The Use* |

**The drift starts at 921–930, which took a continuation slot instead of a batch directory, and from there every directory number in this volume is one behind the card number.** Volumes 17 and 18 agree between the two systems. **Resolve a batch by its chapter range and never by its number.**

## 4 · The four decisions that may not be restaged

1. **940 — no list of comers, ever, including a count.** Said out loud with the door open and both carriers in that passage. It closes keeping hours by keeping people. **No chapter may keep a roll, an index, a count, a bracket, a figure for a quarter or a total of who comes, and none may hand one to anybody, and the office corrects no copy of the card in any form.** Restoring a count needs a second decision taken out loud in that room.
2. **930 — the second written refusal stands and no third is promised.** There will not be a third. **No chapter may produce a third refusal on paper or restore one.**
3. **920 — he lets the slate stand.** The sooner figure is not rubbed out anywhere and the third figure is still unchalked and still owed. **No chapter may rub out the sooner figure, chalk the third one, or separate the two figures.**
4. **933 and 923 own the passage and the landing** respectively, and nobody names them or restages them. **943 is Dagmar Oyelowo**, five hundred and fifty-five chapters after 388, and no chapter may manufacture a gift for her or put her on a roll.

## 5 · The spine and the standing figures at 950

Day zero is the first of February of year one. **A month is thirty days and has no thirty-first, and a year runs from the first of February to the thirtieth of January, with a January labelled by the February that follows it.** February is therefore the first month and January the twelfth, so June is the fifth and January the twelfth. The volume says this in its own words at `chapter-0933.md`:25, where a character glosses *the fourth month* as *in May*. **No interval anywhere in this book may be derived against a real calendar. Subtract day numbers.**

Two methods, sharing no constant, agree on every date in the volume. Method A: `(y-1) x 360 + off[month] + (d-1)`, offsets October 240, November 270, December 300. Method B: `30 x ((y-1) x 12 + pos[month]) + (d-1)`, zero-indexed, October 8, November 9, December 10.

| | 901 | 910 | 920 | 930 | 940 | 950 |
| --- | --- | --- | --- | --- | --- | --- |
| date | 20 Jan y12 | 23 Mar y12 | 3 Jun y12 | 12 Aug y12 | 21 Oct y12 | 30 Dec y12 |
| spine | 3,949 | 4,012 | 4,082 | 4,151 | 4,220 | 4,289 |

The seam to Volume 18 is `3,949 - 3,929 = 20`. **The five batch interiors run `63 · 63 · 62 · 62 · 62` and sum to 312, and the five seams run `20 · 7 · 7 · 7 · 7` and sum to 48.** So `312 + 48 = 360 = 4,289 - 3,929`, exactly one year, the fifth time running. **340 is the span from 901 to 950 and is not the interior figure** — see §2.

**Four anchors, and every figure in the book is derived against one of them rather than carried down from a chapter above it.**

- **The quarter-ends** are 4,019 · 4,109 · 4,199 · 4,289, carrying sheets forty-five, forty-six, forty-seven and forty-eight. The rail breaks at those four chapters and at no other chapter in the volume.
- **The rail** is measured from `4,199`, the thirtieth of September, on which the forty-seventh sheet went up: 28 · 35 · 42 · 49 · 56 · 63 · 70 · 77 · 84 · 90 across 941–950. It breaks once, at 950, and the figure there looks like a jump and is the same rail running out its quarter.
- **The drawer** is measured from `2,420`, the twenty-first of October of the seventh year: 1,807 to 1,869 across 941–950, decomposing as `60 x 30 + 7` through `62 x 30 + 9`. **The sixty-first month at 945 and the sixty-second at 949 are named once each in their own footers and neither is an event.**
- **The head** at 950 is `4,289 - 1,499 = 2,790 = 31 x 90`, thirty-two sheets and thirty-one quarters, differing by one. It is printed at quarter-ends and at no other chapter, and it is printed at 950 at a counter under a window in the passage off Cordwain by the man who is paid nothing there.

**Standing figures, unchanged at 950.** The head stands at eight hundred and fifty-two in the office's own hand and is printed at quarter-ends only — a figure that has not moved, and not the same thing as the arithmetic above, which is the head against its own drawer · the second column is four lines and is not going to be five · the bundle is twenty-six things, nothing off it and nothing on it · the standing sheet carries six lines in the office's hand, the last entered on the second of December of the ninth year, and **no seventh goes in anywhere** · his own blank row is a thousand two hundred and seven days old with a space in the middle of it and nothing in the space · the drawer has been shut since the twenty-first of October of the seventh year, sixty-two months and nine days at 950, and **may never be opened by anybody including him** · the register is never upstairs overnight · the inside of his coat on the left is empty and nothing goes into it.

**The one thing this office put in ink in a year is three lines on a card.** It came down off three nails at about eleven on the thirtieth of December of year twelve and a second card with the same three lines and **not one name** went up on the same three nails at about a quarter past eleven, in his own hand, with the holes about a quarter of an inch wider than they were in November. The three lines are a street, a door at the head of four flights off a third court, and hours between a quarter to ten and half past five on working mornings, five days in seven, and at no other hour. **There is no transcript of that card anywhere in the world, no copy of it, and no list of anybody.**

## 6 · The gate this book is written to

These are production rules, not plot, and a batch that breaks one is a batch that needs repair.

- **Length.** Chapters run 1,800–2,700 words. Volume 19: 101,383 words over fifty chapters, minimum 1,803, maximum 2,697, and no chapter leaves the band.
- **Paragraphs.** Most run two to four sentences. Nothing over roughly ninety words, nothing over roughly one hundred and twenty. Longest paragraph in Volume 19: ninety words.
- **Markdown.** Title as the one H1, section headings below it, plain paragraphs, sparing emphasis, and system messages inside square brackets on their own line. **No bold, blockquote, code fence, table or rule appears anywhere in Volume 19, and Volume 19 carries no square-bracket panel either.** Earlier volumes do carry panels — thirty-two square-bracket lines in the book as a whole, none of them after Volume 19 — so "none" is a fact about this volume and not about the manuscript.
- **Numbers in prose.** No Arabic digit, no year numeral, no day of the week, no form ordinal on a chapter day, and no ordinal month reference that does not fit its chapter. Dates are days and months of a thirty-day year and nothing else.
- **Ages.** **No announced age for any person, ever.** The instrument that catches it is a grep for `about` followed by a number, plus a human eye on every hit, plus the three forms a grep does not catch: `since I was X`, `X years old`, and `a man/woman/girl/boy of X`. **Dagmar Oyelowo, Wenna Raut, Perla Quist and the boy with the paste brush are not aged and may never be aged on the page.**
- **The fourth wall.** No character or narrator names a chapter, a volume, a page, a reader or a book structure. The class grep includes `manuscript` and `opposition` and returns zero.
- **Date glosses.** A gloss is computed from the previous chapter's own month, never carried forward, and written last, after the arithmetic. Same month reads *the N of this one*; a crossing reads *the N of last month* and names the crossing as itself. **Both forms are correct and both are used on purpose.**
- **Watch-constructions.** `nobody asked`, `nobody was thanked`, `there is no form`, `there is no column`, `the record remained`, `nobody knew`. Effective once or twice and dead by the tenth. Volume 19: narration two, speech three, across ten chapters, and no chapter carries more than one of either.
- **Scenes.** Five a volume, each a different woman, reported and not certified. The per-woman gaps are reported and may not be certified. **No scene is manufactured into a gift, and no impaired state — sedation, exhaustion, toxin, restraint, psychic contact, trance, seal — is ever the mechanism.**
- **Repetition across chapters.** A gram count cannot tell a house clause from a restaged sentence, so the instrument is a longest common contiguous word run between two files. Volume 19's longest true run between two files is the drawer footer clause. The one real restaging found in the volume was repaired at 923.
- **AND THE RULE THIS FILE LEARNED THE HARD WAY: a gate row is a claim, not a check.** Four passes in Volume 19 published a clean row on the announced-age gate while it was broken. **Measure from disk in the pass that reports. Name the instrument. Make the per-file row add up to the total.**

## 7 · What Volume 19 did, in one line a movement

Against the repaired page of 921–940, per `reviews/volume-19/volume-close.md`.

**One, *The Winter* (901–910):** the office keeps the winter mornings rather than shutting the door, and pays for it in his own hands in the dark. **Two, *The Telling* (911–920):** the head of the standing sheet goes into a lane off Cordwain in another man's chalk beside the sooner figure, and he lets the slate stand. **Three, *The Lane* (921–930):** the second written refusal stands and he promises no third, and what that costs is that from 930 the office can only say no by standing in front of you. **Four, *The Refusal* (923–933 inside the batch):** the landing and the return cages at 923, the passage as a scene axis at 933, and at 940 the no-list rule, said aloud with the door open. **Five, *The Use* (941–950):** the three lines go out of a room by somebody's mouth, and at 950 he renews the card in ink — same three lines, same three nails, not one name.

**The volume's second permitted closure is spent and the permitted-to-close count is now zero.** Nothing else may be closed.

## 8 · Where the detail lives

| Question | File |
| --- | --- |
| the close audit of 901–950, the repairs, every gate row with its instrument | `reviews/volume-19/volume-close.md` |
| what each batch of this volume was and what it measured | `reviews/volume-19/batch-0001.md` through `batch-0005.md` |
| what each review-fix pass changed | `reviews/volume-19/batch-000N-review-fix.md` |
| the cards of record, one per chapter, all ten movements | `outline/batches/volume-19-batch-0001.md` through `-0005.md` |
| the volume's own governing document, sections 1 to 10 | `outline/volume-19.md` |
| the people, the ages that may not be printed, and who is who | `bible/characters.md` |
| what a later writer may not contradict | `state/continuity.md` |
| every thread with its status at the close | `state/open-threads.md` |
| the ten summaries a next writer inherits | `state/chapter-summaries.md` |
| everything compacted out of the four state files | `state/archive/` and `git log -- state/` |

## 9 · What was compacted here on 2026-10-15, and how to get it back

`state/current.md`, `state/continuity.md`, `state/open-threads.md` and `state/chapter-summaries.md` were each stripped to their live block after the review recorded in `logs/batch-0004.review.log`, whose findings 4, 5 and 6 are the ones this pass answers. The full pre-compaction text of all four is byte-for-byte in `state/archive/current-v17-v19-superseded.md`, `continuity-v17-v19-superseded.md`, `open-threads-v17-v19-superseded.md` and `chapter-summaries-v17-v19-superseded.md`, and in the commit before this one. **Superseded per-batch restatements of measurements that are already in `reviews/` were dropped from the live files rather than archived a second time; nothing a later writer needs was among them.**

**Not done here, and not done anywhere, because these files belong to GitHub Actions:** `scripts/`, `.github/workflows/`, `.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json` and `state/phase-ledger.json`. The stale `.wip-conflict` marker sitting beside a `.done` marker in `workspace/volume-19/batch-0004/` is controller state and was left alone; the runner keys on `.done`, and that one is harmless.

**One marker is not harmless, and the review that called this class cosmetic was wrong about it.** `workspace/volume-10/volume-plan/` has a `.retired` marker and no `.done`. See §1.