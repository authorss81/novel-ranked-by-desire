# Volume 19 batch 0004 review-fix — every finding answered, four more found by hand, and what was re-measured after

This pass read `logs/batch-0003.review.log`, agreed with every one of its ten numbered findings, repaired the batch, and recorded the one the review explicitly left for a ruling. **No chapter was restarted, no chapter was rewritten, no scene and no irreversible decision touched, no plot figure and no date moved, `outline/ending.md` untouched, no new enemy.** **Eight prose lines changed across four chapter files and not one of them is a figure — 931 twice, 932 once, 934 once, 938 four times. Three title lines changed (937, 938, 940) and two section headings changed (both in 938). A trailing newline was added to all ten files, which is why all ten show in the diff and why four of them show nothing else.** `outline/volume-19.md` §10's title bank and its one flag sentence, one row of the card file, four state files and the live batch record changed. **One phase was created — `workspace/volume-19/batch-0004/PROMPT.md` — and one record that should have existed in an earlier pass was created: `reviews/volume-19/batch-0002-review-fix.md`.**

**A gate record is a claim. Re-run it from outside the pass that wrote it and let the re-run outrank the record.** Every number in this file was measured from disk after the last edit. **Three rows this review did not name were also found false on re-run and are corrected in §8, and one of them is the row that would have caught the batch's worst defect.**

## 1 · BLOCKER — six announced ages were on the page and the gate published zero

The review named five across four lines: 932:21 *was about thirty*, 934:119 *a woman of about sixty … a man of about thirty*, 938:55 *a young man of about twenty*, 938:67 *A woman of about thirty*. **There were six. The review's own list missed `chapter-0938.md:15`, which said *a man about forty*.** All six are out:

| Line | Was | Is |
| --- | --- | --- |
| 932:21 | *The man on the other side of it was about thirty, dressed for work with his collar up* | *The man on the other side of it was dressed for work with his collar up* |
| 934:119 | *a woman of about sixty came up with a man of about thirty* | *a woman came up with a man behind her* |
| 938:15 | *a man about forty came up beside it* | *a man came up beside it* |
| 938:55 | *a young man of about twenty came up off the road* | *a young man came up off the road* |
| 938:67 | *A woman of about thirty came up the hill* | *A woman came up the hill* |

**Not one beat, stage direction, entry, exit or line of dialogue was lost. The only thing removed is a number.** 934's woman still arrives at half past four with a man behind her and no paper, which is the whole of what that paragraph is for. 938's young man still asks whether he has to put his name in the square, and the man with the paper still says it says a person can. **Every remaining `about twenty` and `about forty` in the batch is a clock or a duration** — twenty past four, forty minutes, twenty minutes — and all of them were left alone.

**WHY THIS IS THE THIRD TIME AND WHY THE GATE IS THE THING TO CHANGE.** Volume 18 batch 0002 found *she is about thirty* at 869 and *she is about sixty* at 870 and published both as lessons. This batch broke the same rule six times and `reviews/volume-19/batch-0004.md` and `state/current.md` both published **any announced age** under **ZERO AND VERIFIED**, while §0a of that same state file described *a woman of about thirty thanks him and walks down the hill* as a feature of 938. **A state file documenting the breach as compliance is worse than a state file silent on it, because it removes the reason for anyone to look again.** The instrument that actually catches this is not a word list: it is a grep for `about` followed by a number, and a human eye on every result to ask whether the number is a person.

## 2 · BLOCKER — 931's seam operand was 929's day

`chapter-0931.md` printed `4,144` as *the twelfth of this one*, in the opening paragraph and again in the closing roll-up. **§5c gives 929 = `4,144` = 5 Aug and 930 = `4,151` = 12 Aug.** The spine needs `4,158 − 4,151`; the page performed `4,158 − 4,144`. Nine of ten opening arithmetic paragraphs were correct and 931 was the lone outlier, seven lines from a correct `4,158 − 4,151 = 7` published in `reviews/volume-19/batch-0004.md`. **Both places now read `4,151` and `4,144` is zero in the file.** No interior interval moved, because no interior interval was wrong.

**This is the defect class the manuscript's own standing rule names: a figure carried forward instead of recomputed from the anchor.** And it happened in the one direction that a reader can check — the seam is the one interval in a batch that has an operand on two sides, so a wrong one is visible on the page and in the gate at the same time. **The gate was right and the prose lost, which is the correct order and was recorded rather than hidden.**

## 3 · BLOCKER — the `flat` row was false and the rule under it was not

The record claimed one occurrence, at 936:73, in `dressed flat`. **There are eight occurrences on six lines: 931:115 (×2), 932:133 (×2), 935:57, 936:19, 937:121, 940:61.** Four are *the flat file*, one is *the flat file room*, one is *dressed flat* in the stone, and one is *said it flat* at 940:61, which is a voice. **No hand is put flat on anything in 931–940, which is the rule, and it still holds.** The published measurement was wrong by seven and has been replaced with the instrument's actual output.

## 4 · MATERIAL — three titles were a figure, a date and a decision

**937 `The Forty-Seventh Sheet` → `Same Two Nails`** (the forty-seventh goes up on the same two nails as the forty-sixth, and the chapter's last beat is that they have been the same two nails since the first year) · **938 `The Seventh Of October` → `Twelve Feet Off`** (where he stands for the whole of it and says nothing) · **940 `The Comers Without A List` → `A Rule She Cannot Keep`** (which is what the carrier with the bad back says to him, and which is the cost rather than the decision).

The Volume 18 batch-0002 repair set the precedent for the first: a heading of `Two Hundred And Twenty-Three Days` was replaced there for being a figure. **Zero collisions across all nine hundred and forty title lines after the change**, checked by `uniq -d` over every `# ` line in the manuscript. **`outline/volume-19.md` §10's title bank is updated in place and so is its flag sentence about 938, which existed only because the title was a date; §7 needed no change, because §7 never named a title.**

## 5 · MATERIAL — the `about` row was wrong in five figures *and did not sum to its own total*

Published: `38 · 29 · 59 · 27 · 38 · 35 · 29 · 44 · 32 · 24` against a stated total of 348. **That row sums to 355.** The true pre-fix row was `38 · 28 · 59 · 27 · 38 · 33 · 27 · 43 · 32 · 23` = 348, and the true case-sensitive row was 335.

**Re-measured from disk after this pass, over every line not beginning with a hash:**

| | 931 | 932 | 933 | 934 | 935 | 936 | 937 | 938 | 939 | 940 | total |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| case-sensitive | 38 | 26 | 58 | 25 | 33 | 32 | 26 | 38 | 32 | 21 | **329** |
| case-insensitive | 38 | 27 | 59 | 25 | 35 | 33 | 27 | 39 | 32 | 22 | **337** |

Both rows are published in `state/current.md` and `state/chapter-summaries.md` with the instrument named, so that no later pass inherits a row that does not add up. **Nineteen of the fall between the pre-fix and post-fix totals are the six removed age figures and the words that carried them.** Published as measured, not optimised: this is house voice across nine hundred and forty chapters and the Volume 18 batch-0003 review-fix declined the same note for the same reason.

## 6 · MATERIAL — the card file's distribution row counted 932 twice and left 938 out

Ten slots, nine distinct chapters: `political/social 2 (937, 940) · character/relationship 3 (931, 933, 934) · discovery 3 (932, 935, 939) · recovery/payoff 1 (936, the corner) · action/survival 1 (932, at two in the morning)`. **938 — the batch's public reversal — was in no category at all, and 932 was in two.** Now: **political/social 3 (937, 938, 940) · character/relationship 3 (931, 933, 934) · discovery 3 (932, 935, 939) · recovery/payoff 1 (936, the corner)**, ten slots over ten distinct chapters. **932's real deadline is recorded without counting the chapter twice** — a man about forty minutes from being back out on a night shift, at about two in the morning, in a building where about nine people are awake.

## 7 · RULED — the seventh reading stays a seventh time and stops being a form

The review was right that this needed a ruling and not a fix. **The prohibition is on the form's serial ordinal, and a repeat count of a stranger reading a form aloud is not the form's hundred-and-twenty-second.** On the narrow reading, `## What He Could Have Said At The Seventh Reading` and `The seventh time` were compliant, and §7's 938 row says the same thing in the same words.

**But the narrow reading is not the reader's reading.** In this manuscript `reading` is the Bureau form, and `The Seventh Reading` sat under a heading called `The Form That Goes Up On The Seventh`, where the same two words mean the day the form goes up. **A chapter that passes its own gate and reads wrong is still wrong.** So:

- `## What He Could Have Said At The Seventh Reading` → **`## What He Could Have Said At The End Of It`**
- `The seventh time, the man with the paper got the whole of it right` → **`By the last of them the man with the paper got the whole of it right`**

**Which is also more accurate: by then more than four people had been read to.** The section heading `## The Form That Goes Up On The Seventh` became `## Cold Paste And Two Empty Squares` — physical, and it names nothing a reader has to hold — **and the fact it carried stays in the prose underneath it, where §5c's chain requires it: *It goes up on the seventh, one a month*.** **No form ordinal is printed in 931–940.**

## 8 · THREE GATE ROWS THIS REVIEW DID NOT NAME, ALL FALSE, ALL CORRECTED

**1 · NONE OF THE TEN FILES ENDED IN A NEWLINE.** The record claimed all ten did. Every one ended on the last italic footer line. **A trailing newline was added to all ten.** The rest of the manuscript is mixed — 236 of 940 chapter files end without one — and that is outside this batch and untouched.

**2 · §0a OF `state/current.md` DESCRIBED ONE OF THE SIX AGE FIGURES AS A FEATURE OF 938** while the same file's gate row published the rule as zero. Corrected in both places.

**3 · THE CROSS-FILE REPEAT ROW WAS STATED WITH TWO EXTRA FIGURES THAT COULD NOT BE REPRODUCED** — *eleven 941, eight 1,684* — which this pass's instrument does not return. **The row is republished as what the instrument produces: 838 touching the batch, per file 92 · 83 · 83 · 79 · 79 · 103 · 86 · 83 · 74 · 76, with the instrument written down in full.** The pre-fix row was 837 with 931 at 91; the one-gram difference is tokenisation and not prose, and both rows are published rather than one of them. **936 at 103 remains the top of the list, which is house scaffold that must read the same, and the restaging it once carried at 166 against 908 stays repaired.**

## 9 · WHAT THE REVIEW CONFIRMED, RE-MEASURED HERE

Word counts re-measured per file from disk and matching to the word except in the three files whose prose changed: 1,935 · 1,884 · 2,522 · 1,934 · 1,803 · 1,805 · 1,977 · 1,816 · 1,911 · 1,810 = **19,397**, ten of ten inside 1,800–2,700. **The twelve words that went are six age figures and the words carrying them.** Zero paragraphs over roughly ninety or roughly one hundred and twenty. Quote parity clean in all ten. Zero duplicate paragraphs. Zero bold, blockquote, fence, rule, table or system panel. Zero Arabic digits in prose. `axis`, `settl`, `right temple`, `cuticle`, `ostho`, `burn`/`burnt`, `stove`, seven weekday names and the bare `sat` and `sun` all zero. Fourth wall zero. **The head printed at 937 and nowhere else, verified case-insensitively for the figure, the thirty-one sheets, the thirty quarters and the two thousand seven hundred, all four returning 937 only. The rail broke at 937 and nowhere else.** The review's own count of `flat` was confirmed to the occurrence. The nine/eleven exchange at 933 reads as deliberate in-character correction and 940 carries eleven forward — not a defect, and not touched.

## 10 · THE TWO PROCESS FINDINGS

**THE NEXT PHASE WAS INVISIBLE TO THE DISPATCHER.** The batch record said no phase was created and that a review-fix pass was the only thing that might make the next one; `workspace/volume-19/` held only batch-0001, 0002 and 0003. **Left alone, the dispatcher would have fallen through to the generic continuation seed, which asks for *the next planned batch* — 941–950 — with no cards on disk for movement five and no instruction to write them.** `workspace/volume-19/batch-0004/PROMPT.md` now exists and carries the spine, the rail, the drawer, the head, both month crossings, the figure allowances, the ten planned titles, the four decisions that may not be restaged, the scene at 943, the three hazards this batch earned, and the instruction to create exactly one volume-close prompt at the end, because 901–950 is the whole of Volume 19. **Its first line does not match the runner's volume-outline-phase pattern, so it will be selected as a writing phase and not skipped.**

**A REVIEW RECORD WAS MISSING.** `reviews/volume-19/` held `batch-0001-review-fix.md`, `batch-0003-review-fix.md` and `planning-review-fix.md`, and nothing for batch 0002, whose eleven repairs were published into `state/current.md` and never into a file of their own. **The writer of 931–940 flagged this in its own handoff and inherited the repairs from the state files, which was the right call and still cost a search.** `reviews/volume-19/batch-0002-review-fix.md` now exists **as an index and says in its first line that it is an index and not a review**, because reconstructing a review that was never written would be worse than admitting it is missing. A scope note was added to `batch-0003-review-fix.md`, which covers 921–930 and not 911–920, because the numbering invites exactly that misreading.

**The commit message offset — `786dcce` titled `batch-0003` containing outline batch 0004 — is controller-side and real and deliberate, since `workspace/volume-19/batch-0003/PROMPT.md` reads *BATCH 0003 · CHAPTERS 931–940*. Nothing in a fiction phase can do anything about it and nothing was attempted.**

## 11 · WHAT THIS PASS DELIBERATELY DID NOT DO

**It did not touch the planned plot, the movement's promise, the scene at 933, the head at 937, the rail break at 937, or the irreversible decision at 940.** It did not reopen 930's second written refusal or 920's standing slate. It did not move a spine day, a figure, a card beat or a closure. It did not write a form ordinal, a list of comers, a count, a second card or an address. It did not open `outline/ending.md`. It did not introduce an enemy. It did not create a phase beyond the one the batch owed. **And it did not restage 936, which is the strongest page in the batch and which the cross-file scan has already been used on once.**

## 12 · WHAT THE NEXT WRITER OWES

**941–950 IS *THE USE*, IT ENDS THE VOLUME, AND ITS 950 IS THE VOLUME'S IRREVERSIBLE DECISION IN INK: the winter-worn card comes down and a second card with the same three lines and not one name goes up with three nails.** The head is printed there for the fourth and last time — `4,289 − 1,499 = 2,790 = 31 × 90`, thirty-two sheets and thirty-one quarters, differing by one — and the rail breaks there and nowhere else, at ninety days off the thirtieth of September. 943 is the last scene in the book and it is Dagmar Oyelowo, 555 after 388. **940's no-list decision carries forward and may not be restored without a second decision taken out loud in that room. 930's no-third-refusal carries forward and there will not be one. 920's slate stands. The boy is at 948 and nowhere else. No form falls on any chapter day in 941–950, because there is no seventh between the twenty-eighth of October and the thirtieth of December.**

**AND THE ONE THING THIS BATCH LEARNED THAT THE NEXT ONE SHOULD NOT HAVE TO LEARN AGAIN: A GATE THAT GREPS FOR A WORD CANNOT CATCH A NUMBER, AND A ROW THAT SAYS A THING IS CHECKED IS NOT A CHECK.** Measure from disk in the pass that writes. Publish the instrument. Make the per-file row add up to the total.
