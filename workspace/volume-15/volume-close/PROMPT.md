# VOLUME 15 CLOSE (audit, then record)

**Volume 15 is closed in prose. Chapters 701–750 exist and 750 is the last of them. This is the close phase, not a batch phase. It does not write chapters.** Read `PHASE_SYSTEM.md` under *The volume close*, `AGENTS.md` under *If the volume is complete, create exactly one volume-close prompt*, and `AGENTS.md`'s own instruction that a volume close does not declare the manuscript finished, before starting.

Do not rewrite Volume 15. An audit that repairs the whole volume is not an audit. Prose repairs go into `reviews/volume-15/volume-close.md` as findings with a reason, and are applied **only where a reader is actively mis-served** — and a chapter of 701–750 may be opened for exactly that, and for nothing else.

**`outline/ending.md` is not to be touched by this phase and nothing in it moves. The document fixes canon and Volume 15 inherited it whole.**

## Why this phase exists and what went wrong before it

The pass that wrote 741–750 closed the volume in prose. The card it was working from said the next phase was "nothing else", because the cards were written before anyone had established that 741–750 finish the volume. **`AGENTS.md` is unambiguous: when a batch completes a volume, the writer creates exactly one volume-close prompt.** 741–750 complete it. `outline/volume-15.md` §5b fixes the thirty-second sheet at 750, four lines in the second column at 748–750 and twenty-six things in the bundle at 741 and 750, and there is no `outline/volume-16.md` and no Chapter 751.

**A next-phase prompt that sits in `outline/batches/` is not a phase.** `scripts/novel_runner.sh` enumerates phases only through `find workspace -name PROMPT.md`. The cards for this batch are at `outline/batches/volume-15-batch-0005.md` as the plan of record and the dispatch copy was at `workspace/volume-15/batch-0005/PROMPT.md`; this file is at `workspace/volume-15/volume-close/PROMPT.md`, which is the path the runner finds.

**Chapter 751 must not be drafted by this phase. `state/complete.md` is not this phase's to create either** — it belongs to whoever is told to.

## Part one — the close audit (no prose)

Read `outline/volume-15.md` in full — §1 through §10 — against `state/chapter-summaries.md` for Chapters 701–750, and then against the chapters where a claim can be checked. **Answer every question in writing, with chapter numbers. A claim you cannot trace to a page does not go in the record.**

1. **The volume promise.** §1 of `outline/volume-15.md` is one sentence. Did it land? By which chapter, and at what cost stated on the page and not in a state file? **Say plainly whether the promise was met by the mechanism that was planned.**
2. **The volume's own question.** §1 asks what a city does when the first thing it can do about four hundred claims is date them, and an age is the only figure this city has ever acted on. **What is the answer on the page, and where is it stated?** Look at 706, 715, 727, 736, 741, 745, 746, 748 and 750. A claim that can be argued with and a name that can be asked about are the same move; say so if the page says so and say where.
3. **The five irreversible decisions.** 710, 720, 730, 739 and 746, all his. For each: what it closes, what it costs, and whether the cost is stated on the page by a person or only by the narrator. **Verify against §2d of the outline that nothing in 701–750 accidentally resolved one of the things that file forbids.**
4. **The five debts and the five scenes.** 703 Sun Meiling, 713 Runa Sato, 723 Marguerite Vale, 733 Wren Kallo, 743 Nadia Ferrous. Confirm the cadence by arithmetic from the dates: 10, 10, 10, 10, 10, and confirm the per-woman gaps 90, 110, 100, 100, 326 against the chapter day numbers. **Do not certify the per-woman gaps as inside or outside the eight-to-fifteen band; §4 of the outline forbids that and the file is right.**
5. **The register.** 419 before a clerk's hand, eleven since the thirtieth of March, the 409 in two boxes, the empty field at 740, the non-event row at 742. **Confirm by command that no chapter merges a count of pieces of paper with a count of claims or a count of people, and name every place a chapter comes close.**
6. **The one line that went in.** 746. **Trace every consequence of it forward to 750 and state which of them the page actually shows and which are still only predicted.** The prediction at 748 about four hundred kitchens going quiet is *not* shown happening on the page; check whether it is presented as fact and decide whether that is a defect.
7. **The opening thread.** Somebody told her. **State precisely what is established and what is not.** Who told her is not established and may not be established. She is not traced, not named, nobody is sent. **Confirm that no chapter of 701–750 says who it was.**
8. **The two words on the stone.** Confirm by command that they are printed nowhere in 701–750 and then **read every chapter by eye and confirm that no chapter asserts they are the same two words as anything.** The grep cannot see this and the file says so three times.
9. **World consistency.** A month is thirty days, no thirty-first, no day of the week, years running from the first of February to the thirtieth of January with a January labelled by the February that follows it. **Volume 15 contains no January chapter, which is the condition under which the wrong convention has twice produced 2,133 — confirm that no chapter of 701–750 slips.** No announced age for any person. Rank one, a branch night shift, four nights and three off, and nothing that moves him.
10. **The canon-change guard.** Every flag in `state/open-threads.md` carried into this volume, including the ones this volume inherited and did not repair. **`chapter-0729.md` and `chapter-0730.md` print a rail count one higher than the rule and three passes have now named it and none has repaired it. Adjudicate it.** Also adjudicate the discrepancy this volume's own gate found: the state files record 40 parsed footer intervals for 721–730 and a proved reader returns 30 parsed, 0 mismatches, 0 unparsed. **Say which figure is right and correct the record.**
11. **The ending.** Read `outline/ending.md` against 741–750. **Confirm that nothing in the last ten chapters contradicts it, and that the volume's last chapter leaves every thread in that document exactly where it found it.**

## Part two — the close record

Write into the state files.

- `state/current.md` — a `# Volume 15 closed` block: the audit's findings, the spine as the page fixed it, what the batch gate measured, and anything the audit could not settle stated as unsettled.
- `state/continuity.md` — a `# Volume 15 closed` block: the calendar as the page fixed it, the mechanics that are now canon (**the rule of the room in 743 — no days of the week, the date instead — is now standing and any chapter may rely on it**), the second column and what is in it, and what a Volume 16 writer may not contradict.
- `state/open-threads.md` — carry every thread forward with its status at the close. **Nothing is closed by a volume ending.** Note which threads Volume 16 may open and which it must not.
- `state/chapter-summaries.md` — only where the audit found a summary the page contradicts.
- `reviews/volume-15/volume-close.md` — the audit, with every claim marked mechanical (command and output) or judgement, and with the command printed. **Say plainly how each claim was checked. A count is not a reading**: this volume's own writer ran a gate of some forty rows on 741–750, every row passed, and the gate could not see thirty-one weekday names, three fourth-wall hits, thirty-two paragraphs over ninety words, or that a chapter had been built on a construction the volume's own calendar forbids.

## Part three — the next phase

**Do not create it in this phase.** The volume close for Volume 1 created the Volume 2 *planning* phase, because there was no `outline/volume-02.md` and no cards. **Whether Volume 16 is planned is a decision for whoever reads this audit, and this prompt does not make it and does not draft anything that would presuppose it.** If the reading of this audit is that the series is finished, say so in `reviews/volume-15/volume-close.md` and stop. If it is that a Volume 16 is wanted, say what the audit found that the next volume would have to be built out of, and let that be the recommendation.

## What not to do

Do not draft a chapter. Do not create a second next-phase prompt. Do not create `state/complete.md`. Do not modify `scripts/`, `.github/workflows/`, `.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json` or `state/phase-ledger.json`. Do not change anything in `outline/ending.md`. Do not introduce a new enemy. Do not print the figure of the account, the docket's date, or the two words on the stone, anywhere, including in this phase's own findings. Do not send anybody to find the woman who cannot read.
