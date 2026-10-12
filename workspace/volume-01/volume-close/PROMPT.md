# Prompt — Volume 1 Close (audit, then record)

**Volume 1 is closed in prose. Chapters 1–50 exist. This is the close phase, not a batch phase. It does not
write chapters.** Read `PHASE_SYSTEM.md` ("The volume close") and `AGENTS.md` ("If the volume is complete,
create exactly one volume-close prompt") before starting.

Do not rewrite Volume 1. An audit that repairs the whole volume is not an audit. Prose repairs go into
`reviews/volume-01/volume-close.md` as findings with a reason, and are applied only where a reader is
actively mis-served.

## Why this phase exists

Batch 0005 closed Volume 1 in prose and, instead of this phase, created a next-batch prompt. That prompt
has been removed, because **there is no `outline/volume-02.md` and no Volume 2 cards**, and a batch prompt
that concedes it has nothing to write against is not a phase. **Chapter 51 must not be drafted until
Volume 2 is planned.**

## Part one — the close audit (no prose)

Read `outline/volume-01.md` in full against `state/chapter-summaries.md` for Chapters 1–50, then against
the chapters where a claim can be checked. Answer each in writing, with the chapter numbers that answer it.
**A claim you cannot trace to a page does not go in the record.**

1. **The volume promise.** `In this volume, Lin Hao must hold rank six through the Winter Review, or the
   reservoir is requisitioned by the Fourth Branch and he never gets it back.` Did he hold six? At what
   cost, stated on the page, and by which chapter?
2. **Was it earned or was it seated?** He holds six on an instrument — the requisition of the 19th plus the
   open-question finding — and his plate still reads 8,138. The volume's declared mechanism was thirty
   witnessed deeds and nineteen hands. **State plainly that the promise was met by a different mechanism
   than the one planned, that this was the right call, and that the consequence is live: he is 11,862
   grains under his own band.** That sentence is the most important thing this phase produces.
3. **Every unresolved promise and mystery.** T1 (the file) through T12, and B1 through B35. For each:
   advanced, unchanged, or paid. T1 advanced by exactly one folio and must advance no further.
4. **Relationships.** Ch 8, 17, 26, 29, 36, 46. What each scene changed, whether the change is on the page,
   and what each woman now wants that she did not want before. Six scenes, the last at a gap of ten.
5. **Power progression and its costs.** The grain spine 4,012 → 8,141 → 8,138. The ledger 19 → 41 → 91
   lines, five → eight turned, one line reading himself. **Check that no cost was quietly refunded** and
   that nothing in Volume 1 lets the reservoir score a grain.
6. **World consistency.** `bible/power-system.md`, `bible/terminology.md`, `bible/characters.md` against the
   page. **Ages, the weekday rule, the reserved constructions, and the Planning-register ban** (no
   *reservoir*, *quiet account*, *Concil*, *Ninth Seal* or *Channel* in Chapters 1–50).
7. **The planned climax and resolution.** Ch 48 is the irreversible decision and Ch 50 is the final image.
   Did each land? Does the volume end changed, or merely informed?
8. **The eight scene gaps.** Two are known and locked (26→29 = 3, 29→36 = 7). Confirm the census.
9. **Register of the canon-change guard.** Every flag in `state/open-threads.md`, including the Batch 0005
   review repair. **Confirm that the terms were refused twice and not accepted**, because
   `outline/volume-01.md` says the opposite and the page is canon.

## Part two — the close record

Write into the state files. Do not start Volume 2 prose.

- `state/current.md` — replace the Volume 1 header, the closing table, what he knows, the voice note and
  the scene budget with what the audit actually found. **Items 1 to 33 in Adjudicated contradictions stay
  closed. Add the audit's own conclusions as new numbered items, including anything the audit could not
  settle.**
- `state/continuity.md` — add a `# Volume 1 closed` block: the calendar as the page fixed it, the
  mechanics that are now canon (the open-question rule, the instrument ruling, the three-grain tolerance
  and the drift ladder), and what a Volume 2 writer may not contradict.
- `state/open-threads.md` — carry every thread forward with its status at the close. **Nothing is closed
  by a volume ending.** Note which threads Volume 2 may open and which it must not.
- `state/chapter-summaries.md` — only where the audit found a summary the page contradicts.
- `reviews/volume-01/volume-close.md` — the audit, with each claim marked mechanical (command and output)
  or judgement. **Say plainly how each claim was checked. A count is not a reading** — the Batch 0005
  review ran seven gates, all passed, and every one of twelve defects in the batch was invisible to all
  seven.

## Part three — the next phase

Create **exactly one** prompt: **`workspace/volume-02/volume-plan/`**, a Volume 2 planning phase. **Not a
batch prompt.** There are no Volume 2 cards and there must not be any until the volume outline exists.

It must require, in this order:

1. `outline/volume-02.md` — the volume in the required form: *In this volume, **Lin Hao must learn what is
   in him before he spends it on himself again**, or **the Classification Wing classifies the account and
   empties him out at rank one**.* Major locations, factions, escalation sequence, scene schedule, and a
   **title bank of 50 names, unique against `outline/volume-01.md`**, because Volume 1's fifty are all
   spent.
2. `outline/batches/volume-02-batch-0001.md` — detailed cards for Chapters 51–60.
3. It must plan **Sun Meiling** (T10), who has waited three years for the right question, and **plant** her
   without starting her. **Chapter 55 is her first scene and is immovable. Chapter 63 is immovable** and is
   the sentence that unlocks Volume 8. Volume 2's five scenes are 55, 63, 74, 86, 97.
4. It must plan **Alma Quayle's office noticing the thirty-first entry's finding number**, and it must
   **not classify him in Batch 0001**. **No new final enemy.** Anouk Ferreira is the Council chair and is
   not yet on the page; Sowe is Lin Wei's colleague, the man who filed instead of donating.
5. It must decide where the **held-account** pressure comes from. He now holds six with no merit behind
   the band. An Office that has no procedure for that is the natural instrument, and it must not be the
   same pressure as Volume 1's.

## What not to do

Do not draft a chapter. Do not create a second next-phase prompt. Do not modify `scripts/`,
`.github/workflows/`, `.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`,
`OUTLINE_GUIDE.md`, `opencode.json`, or `state/phase-ledger.json`. Do not introduce a final enemy. Do not
change the planned ending in `outline/ending.md`.