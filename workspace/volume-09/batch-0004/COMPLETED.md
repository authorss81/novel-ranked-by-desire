# Batch 0004 — completed out of band. Do not re-run this phase.

**Chapters 433–442 are on disk and are final.** They were written by the run committed as `dbe2b88`,
reviewed and repaired in `bbe82c7`, and re-reviewed and re-repaired in `32d59c3`. The reason trail for both
repair passes is `reviews/volume-09/batch-0004-and-0005-repair.md`.

**Batch 0005 (Chapters 443–450) was written and closed on the strength of these chapters**, and its eight
chapters, the Volume 9 state records and `workspace/volume-09/volume-close/PROMPT.md` were all written
against them. Re-running this phase would restart ten finished chapters and desynchronise eight later ones.

## Why this directory sat open for so long

The phase was left without a `.done` marker after its review-fix pass committed, and a provider outage
afterwards wrote `.attempts`, `.deferred` and `.retry-after` into it (`7eda800`). Those backoff markers are
read by `scripts/novel_runner.sh` but not by the GitHub selector in `.github/workflows/novels.yml`, which
picks the **first** `PROMPT.md` lacking `.done`/`.blocked`. Batch 0004 sorted ahead of
`workspace/volume-09/volume-close/`, so every tick burned a writer call here and the volume close never
started. One such call — `9de2744` — wrote no chapters at all.

## What was done

`.done` written here; `.attempts`, `.deferred` and `.retry-after` removed, which is the cleanup
`scripts/novel_runner.sh` performs on the same lines that write `.done`. **No chapter file was opened,
no prose was altered, and no marker belonging to any other phase was touched.**

The live phase is `workspace/volume-09/volume-close/PROMPT.md`.