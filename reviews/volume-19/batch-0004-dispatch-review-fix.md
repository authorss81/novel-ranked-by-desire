# Volume 19 · batch-0004 dispatch · review-fix pass

**THE FINDINGS ARE IN `logs/batch-0004.review.log`. THIS PASS ANSWERS FINDINGS 4, 5, 6 AND 7, ROUTES FINDINGS 1, 2, 3 AND 8 WITHOUT PATCHING THEM, AND CONTRADICTS NOTHING THE REVIEW SAID ABOUT THE MANUSCRIPT. NO CHAPTER WAS OPENED. NO PROSE WAS WRITTEN. `outline/ending.md`, `outline/series.md`, `NOVEL_SPEC.md`, `outline/volume-19.md`, `outline/batches/` AND `bible/` WERE NOT TOUCHED. NO CARD BEAT, SCENE, DECISION, FIGURE, TITLE, FORM ORDINAL OR CHAPTER DATE MOVED. NO NEW ENEMY. NO NEXT PHASE, BATCH DIRECTORY OR VOLUME-CLOSE PROMPT WAS CREATED.**

## 0 · WHAT THE REVIEW FOUND, AND WHAT IS ACTUALLY TRUE OF THE MANUSCRIPT

The review's findings are process findings, not prose findings, and it says so itself: *"The duplicate dispatch did not corrupt the manuscript, and this is worth stating plainly."* Re-measured from disk in this pass before anything was edited:

- 950 chapter files across nineteen directories, fifty a volume, zero chapters missing.
- 950 H1 title lines, `uniq -d` empty across all of them.
- `chapters/volume-19/` holds 0901 to 0950 and the volume-close audit is applied to it.

**So nothing in the manuscript needed repair and none was attempted. What needed repair was the state the next writer inherits, and that is what this pass fixed.**

## 1 · FINDINGS 4, 5 AND 6 ANSWERED — THE STATE FILES ARE COMPACTED

**The problem, in the review's own measurement.** `state/current.md` was 423,391 bytes in twenty-four stacked blocks, each opening by announcing that it superseded the blocks below it and none of them ever being deleted. The file's own instruction was that the live head block and the one beneath it are "the whole of what you inherit", which left 1,320 of 1,395 lines as dead weight by its own terms. The mandated read set came to roughly 1.36 MB, about 335k tokens, which does not fit a context window and which is the mechanical cause of the two `novel: back off batch-0004 (all writer models unavailable)` commits the review identifies at `830203c` and `4a7f45c`. **The back-off was never an availability problem and this pass removes the cause of it.**

**What was done.** Each of the four state files in the read set was reduced to its live block and nothing else. Nothing was deleted without being kept: the full pre-compaction text of all four is byte-for-byte in `state/archive/`, taken from the commit before this one, following the convention that directory already uses for Volumes 1 to 16.

| File | Was | Now | What is left |
| --- | --- | --- | --- |
| `state/current.md` | 423,391 · 1,395 lines · 24 blocks | **18,922** · 113 lines | Rewritten in plain register: where the manuscript is, the unrouted decisions, the stale selectable prompt, the batch map, the four decisions that may not be restaged, the spine and standing figures, the production gate, where the detail lives |
| `state/chapter-summaries.md` | 274,103 · 13 blocks | **23,196** · 44 lines | The ten rows for 941–950 verbatim, plus a map of where every earlier row lives |
| `state/open-threads.md` | 149,665 · 22 blocks | **14,891** · 57 lines | The live thread block verbatim — both closures, the one thread opened at 947, eleven advanced threads, what a later volume may open, may not open, may not close, and the overrun flag |
| `state/continuity.md` | 136,707 · 22 blocks | **13,210** · 47 lines | The live canon block verbatim — the calendar, the four standing practices, the ink, and the full may-not row |
| **read set total** | **983,866** | **70,219** | **a 93 per cent cut** |

**AND THE REPETITION IS GONE WITH THEM.** Finding 6 named the repeated supersede construction as a named review-fail, because it appeared twenty-four times at the top of `state/current.md` in the loudest register the file had. It now appears nowhere in the read set, and each of the four files opens in plain prose with one line saying what it holds and where the rest is.

**THE LIVE BLOCKS WENT IN BYTE-FOR-BYTE, AND IT WAS CHECKED.** Every non-empty line of the pre-compaction live block was asserted present in the new file: continuity 21 of 21, open-threads 25 of 25, chapter-summaries 10 of 10. **The canon was not retyped, reworded or tidied. It was carried.** What was dropped from each file is superseded per-batch restatement of measurements already recorded in `reviews/` and in git, and the dropped blocks are named in the archive file's own heading.

## 2 · FINDING 7 ANSWERED — THE BATCH MAP, AND THE RULE THAT GOES WITH IT

**The ambiguity.** `outline/batches/volume-19-batch-0004.md` is chapters 931–940 and `workspace/volume-19/batch-0004/` is chapters 941–950. The same name resolves to different chapters in the two systems.

**Found on disk, not assumed.** Volumes 17 and 18 agree between the two systems, all ten of their directories. The drift is Volume 19 only, and it has one cause: **921–930 was written through `workspace/continuation/next-0011/` instead of taking a batch directory, so every directory number in the volume from that point is one behind the card number.** Measured directly from the ten `PROMPT.md` headings.

**The fix is a table and a rule, not a rename.** `state/current.md` §3 now carries the full map — chapters, card, directory, movement — and the rule that **a batch is resolved by its chapter range and never by its number.** Renaming the directories would move runner state and rewrite closed phases' specifications, which is worse than the ambiguity and is controller work.

## 3 · FINDINGS 1, 2, 3 AND 8 ROUTED, NOT PATCHED, AND WHY

**Finding 1, the overrun, is the serious one and this pass does not resolve it.** The manuscript is 950 chapters in nineteen volumes; `NOVEL_SPEC.md`, `outline/series.md` and `outline/ending.md` fix the book at five hundred across ten. **The flag was already open before this review and is still open.** It was raised in Volume 19's planning pass, carried in every batch block since, restated at §7 of `state/open-threads.md` and at §17 of the close audit, and every one of those records says the same thing: *this is a series decision about a file a writing phase may not rewrite.* **Closing it means editing `outline/ending.md` or `NOVEL_SPEC.md`, which is a change to the planned ending, and this phase was told not to change the planned plot. So it is not closed here. It is made louder and it is now at the head of `state/open-threads.md`, where §7 refers to it, and at §2 of `state/current.md`, where the one-sided guard is explained so that nobody reads `completion-guard: ok, 950 chapters reaches planned 500` as a verdict.**

**Finding 2, the close phase that wrote a batch, is history and there is nothing to undo.** `bd55252` wrote 941–950 correctly, wrote the cards, and chained to itself. The prose is sound, the volume is closed, and the audit is applied. Reversing any of it would discard thirty-six repairs and reopen a closed volume. It is recorded at §2 of `state/current.md` as a procedure failure in a controller file, and left.

**Finding 3, `state/phase-ledger.json` never having existed, cannot be fixed by this phase.** It is named in the writer contract as a file this role may not edit, and `PHASE_SYSTEM.md` names it as the selector's input. The runner has fallen back to marker scanning since the beginning and the review is right that presence flags alone cannot order phases. **Recorded at §2. Not created.** The review also found a contradiction between the two documents that name the file; that contradiction is in the controller's hands and is named here so it is not rediscovered from scratch.

**Finding 8, `.wip-conflict` sitting beside `.done` in `workspace/volume-19/batch-0004/`, was left alone.** Those are runner markers and the runner keys on `.done`. Editing workflow markers is not a writer's business, and on this one the reviewer is right that it is cosmetic.

**AND THIS IS THE ONE PLACE THE REVIEW IS WRONG, WHICH THE PASS DISAGREES WITH ON THE RECORD.** That cosmetic category is not cosmetic. `workspace/volume-10/volume-plan/` still holds a Volume 10 planning prompt from October 2026 and carries a **`.retired` marker with no `.done`**, in a directory that sorts ahead of everything in Volume 19. `scripts/novel_runner.sh` selects the first `PROMPT.md` in sorted order lacking `.done` and `.blocked`, and **that loop does not test `.retired`** — the retire sweep at line 80 does, the selection loop at line 179 does not. **A dispatch of this workflow can open a prompt that says it is writing `outline/volume-10.md`, a file that exists, behind a volume that closed nine volumes ago.** Measured from disk this pass: 122 prompts in `workspace/`, 122 `.done` markers, one directory carrying a `.done` with no prompt behind it, and one directory carrying a prompt with no `.done` — the Volume 10 planning one.

**Found by checking the compacted file's own claims, not by reading the review.** The first draft of `state/current.md` said *no phase directory is open*, and this measurement disproves it. **A state file that publishes a false zero is worse than the tombstone ledger it replaced**, and the house rule this repo already writes down — *a gate row is a claim, not a check* — is why the draft was caught rather than shipped. The corrected statement is at §1 of `state/current.md`, with the runner's two loops set against each other. The marker itself is runner state and was not touched.

## 4 · THREE THINGS THIS PASS FOUND BY HAND, WHICH THE REVIEW DID NOT NAME

**THE MARKER RESIDUE IS NOT COSMETIC.** §3 above. A Volume 10 planning prompt is selectable today because its directory is retired rather than done and the selection loop never reads `.retired`. **This is the one finding of the eight that could damage the manuscript rather than merely waste a dispatch**, and the review filed it under cosmetic.

**THE HEAD HAS TWO FIGURES AND A LATER WRITER COULD CONFUSE THEM.** `state/continuity.md` carries *the head stands at eight hundred and fifty-two*, and the volume's own arithmetic prints `day - 1,499` at every quarter-end, which is 2,790 at 950. Checked against the page before writing anything down: **`chapters/volume-18/chapter-0900.md`:103 prints both figures in one sentence** and finishes the arithmetic to twenty-seven times ninety. The standing figure at the head of the sheet and the head counted against its drawer are two different numbers and both are canon. **A note now stands at the head of `state/continuity.md` so that nobody "corrects" one into the other.** Nothing was changed; a trap was labelled.

**THE PROMPT'S OWN ARITHMETIC IS STILL WRONG IN THE TEXT AND STILL RIGHT IN ITS ADJUDICATION.** Question 10 of `workspace/volume-19/volume-close/PROMPT.md` prints 340 where the figure is 312. The close audit marked it in place and left the instruction text alone, correctly, because it is a closed phase's specification of record. **The corrected figure is now also in `state/current.md`,** with the seam shown, so a reader who takes the prompt's number as the record has somewhere to go.

## 5 · WHAT WAS NOT TOUCHED, CHECKED FROM DISK AFTER THE PASS

**No chapter file was opened for writing.** `git status` shows no change under `chapters/`. No outline, no bible file, no title bank, no card. No spine day, no rail figure, no drawer count, no head figure, no sheet ordinal, no scene, no closure, no thread. `outline/ending.md` is untouched, as it has been in every volume since Volume 1.

**No phase was created.** `workspace/volume-19/` is entirely `.done`, Volume 19 is fifty of fifty chapters and audited, and whether a Volume 20 is wanted is the same decision as the overrun flag and is not this phase's. **Creating a prompt for a volume that may not exist would presuppose the answer to the open question, and `AGENTS.md` asks for the next phase only where the volume has chapters remaining. It has none.** No marker was created, cleared or inverted anywhere in `workspace/`, including on the stale Volume 10 planning directory named in §3.

**No controller file was edited.** `scripts/`, `.github/workflows/`, `.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json`, `state/phase-ledger.json` — all untouched, and `state/phase-ledger.json` still does not exist, which is finding 3 and not a regression.

## 6 · WHAT THE NEXT READER OWES THE NEXT READER

**The read set is now about 70 KB, roughly 18k tokens, and it fits.** A phase prompt can still say *read `state/current.md` in full* and mean it. **The figures in this file were measured after the last edit, from disk, and the read-set total was computed by adding the four files rather than by copying a number printed earlier in the pass.**

**But the compaction does not fix the phase that produced the drift**, and this file should not be read as saying it does. Findings 1, 2 and 3 are the mechanism: a volume prompt forbids the phase from touching `outline/ending.md`, `NOVEL_SPEC.md` runs a one-sided completion test, the selector has no ledger, and the marker convention cannot order two phases in the same volume. **All four of those are controller files. This pass routed them and stopped.**

**The open decision, stated once and left open:** the book is nine hundred and fifty chapters and the plan says five hundred. Whoever is told to write it writes one line in `state/open-threads.md` §0 — the book stops at five hundred, or it does not.