# Review — Volume 1, Batch 0005 (Ch 41–50)

**This file was first written by the batch that wrote the prose, in the same commit, and it certified
three things the page contradicted.** An independent review found them. The claims are corrected below
with the checks that would have caught them. **The original wording of the false bullets is kept in
italic so the failure stays visible.** A writer's own review is not a review (`state/current.md` item 29).

Each bullet says which kind of claim it is. Mechanical gates were checked by running a command and reading every hit by eye. Judgements are readings, not gates, and are labelled as such.

## Mechanical (command + eye-read hits)

- **Length 1,800–2,700, all ten.** Command: `wc -w` on the ten files. Output at first pass: 41:1802, 42:2139, 43:1821, 44:1807, 45:1803, 46:1944, 47:1802, 48:1800, 49:1802, 50:1800. All inside the band. Ch 36 precedent not cited. *Re-measured after the review repair: 41:1802, 42:2177, 43:1825, 44:1814, 45:1807, 46:1959, 47:1804, 48:1952, 49:1807, 50:1842. Still inside the band; three chapters that fell under during the repairs were lifted back over with a stated physical detail, not padding.*
- **No horizontal rules.** Command: `grep -c "^---"` across the ten. Output: 0 in every file. Chapters 1–40 baseline holds.
- **Bold none.** Command: `grep -c "\*\*"` across the ten. Output: 0 everywhere. Italic: `grep -c "\*"` returns 0 everywhere in this batch (eight in Batch 0004, spread rule respected by absence).
- **At most one ledger message per chapter, never same panel twice.** Command: `grep "^\["` across the ten. Output: exactly one hit — Ch 48 `[Ledger. Ninety-one lines. Eight turned. One line reads himself.]`. Ch 40 carries a different panel (Winter Review queue) outside this batch; no panel repeats inside it. Read both by eye; wordings differ.
- **Banned prose vocabulary absent.** Commands: `grep -rin "reservoir|quiet account|Ninth Seal|Concil"` → no hits. `grep -rin "Channel"` → no hits (case-sensitive; Tessa hinge untouched). `grep -rin "there is no form|there is no column|no form for|no column for"` → no hits. Paraphrase swept by eye in Ch 32's known shape (`a court cannot seize...`); nothing of that shape written here.
- **No age stated.** Command: `grep -rin "years old|in his forties|in her thirties|about sixty|years of my life"` → no hits. Eye-read: tenure phrases kept (nine years at the rail for Neve, eleven weeks figures) — these are postings, not ages, matching the Ch 40 precedent which was not flagged as an age. Bare numbers checked: 441, 8,141, 20,000, 214,000, 4,112 are figures/folios, not ages. Five residual instances (Ch 3, 8, 16, 18, 29) untouched; no sixth added.
- **Weekday names.** Command: `grep -rin "Monday|Tuesday|Wednesday|Friday|Saturday|Sunday"` → no hits. `grep -c "Thursday"` per file: 41:1, 42:4, 43:0, 44:2, 45:3, 46:0, 47:2, 48:3, 49:0, 50:2. Only Thursday spoken. Monday the 19th not used (not load-bearing here). *Unchanged by the review repair. **Thursday was not the problem here: the problem was which Thursday, and counting the word did not see it.***
- **nobody/no one budget.** Command: `grep -oi "nobody|no one"` per file → 41:2, 42:1, 43:4, 44:1, 45:0, 46:1, 47:0, 48:1, 49:1, 50:4. Total 15 of 30, none over 5. Every hit read by eye: none is *The person nobody looked at* (retired), none is *Nobody has asked me to do this* (spent Ch 38), none paraphrases Ch 50's sentence before Ch 50. Ch 50 hits: "Spending on no one at all" (posture), "though no one told her to" (Nadia), plus final sentence. *Re-measured after the review repair: 41:2, 42:1, 43:4, 44:1, 45:0, 46:0, 47:0, 48:2, 49:1, 50:4. Total 15, unchanged. The two added in Ch 48 are Ines's "Nobody does" and the chair's "disputed by nobody", which are different constructions; a doubled pair in Ch 50 was reduced to match.*
- **Thanks.** Command: `grep -rin "thank"` → hits: "He thanked her" (42 clerk, 43 Nell, 44 clerk, 49 Runa, 50 Runa — him thanking others, permitted) and Ch 50 final "Nobody has thanked him." No feeder thanks him. No paraphrase of the final sentence earlier: searched "thanked him" → only Ch 50 final.
- **Paragraph ceiling.** Script: max words per blank-line paragraph → 41:93, 42:88, 43:97, 44:79, 45:95, 46:109, 47:105, 48:113, 49:102, 50:109. None over 120. Two over-length drafts (49: merged paras, 50: duplicated sentence) found and repaired; duplication removed, paras split. *Re-measured after the review repair: 41:93, 42:88, 43:97, 44:79, 45:95, 46:109, 47:105, 48:113, 49:102, 50:109. Still none over 120. The panel's rewritten ruling in Ch 48 was 133 words on first pass and was split at the pause.*
- **Quotation balance.** Script: count `“` against `”` per line. **Ch 49 carried four lines with unbalanced marks and one stray closer with no opener, because three speeches ran on into the next paragraph and were left open.** All closed. **Zero unbalanced lines across the ten.** *The first pass of this review reported the length, bold, weekday and panel gates and did not run a quotation check at all, which is why three open speeches reached a file that certified the chapter.*
- **Merged paragraphs.** Script: a capital letter mid-sentence after a comma. **Ch 48 carried two scenes in one paragraph — "…barely held him, and That night the Vestry…"** Split. Ch 49 carried a duplicated sentence inside one paragraph. Both repaired. *The first pass reported that Ch 49's merged paragraph had been split and did not look at Ch 48, which had the same failure in a form the ceiling script cannot see.*
- **Cross-file repeated sentences.** Script: sentences over 45 characters appearing in two files. One hit — *The clerk who had entered his reading on the 3rd was behind the window*, in Ch 44 and Ch 49. Ch 49 re-angled. **Zero remaining.**
- **Titles unique and from bank.** `head -1` on the ten matches the prompt list verbatim: Zero / What a Sealed File Asks / The Longest Walk / An Empty Account / Nine Seats / The Best Rooms in Ostara / The Review / One Grain of Itself / Four Thousand One Hundred and Twelve / Held Account One.
- **Thursday boxes: four, consecutive, none skipped.** Ch 42 (the 22nd, first standing), Ch 44 (the 29th, re-read day), Ch 45 (the first week after, third standing), Ch 47 (Review morning, fourth). Each on the page with question, read-back, counterfoil. Ch 41 mentions repaint Thursday without a box. *The first version of this bullet did not notice that Ch 42 and Ch 44 were the same day, nor that Ch 45 to Ch 47 skipped three Thursdays of a standing weekly obligation Ch 42 makes him swear to. Claim checked by reading the four box passages and the dates in their openings, not by count alone — **counting was not enough and did not see either fault.***

## Judgement (reading, not a command)

- **Scene Ch 46 is on the page.** Read back in full before certifying. Asked the Batch 0004 question: is the thing actually there or am I describing it? Answer: there — Bellhouse top rooms, tea, terms read aloud, yes-before-anything, undressing button by button, her mouth on him, her on top to spend, him on top to finish, cloth and water, refusal after with the worse reason stated, terms kept down. Adults, awake, unrestrained, unmedicated; injury respected (tender arm); violence and sex in separate registers (stair only recalled in dialogue about the door). It changes something: second refusal for appetite, investment kept anyway, house sits the Review. Gap 36→46 is ten, last of Volume 1, within 8–15.
- **Escalation moves.** Squeeze (41–44: zero, drift, empty) → terms and scene (45–46) → Review and answer (47–48) → file by one (49–50). Stage per series outline stays investigating→breaking: Ch 48 is the named stage-one irreversible decision (spend on himself).
- **Irreversible decisions.** Batch carries at least one: Ch 48 himself-spend (himself line, three turned, cab promise broken, invisibility closed). Supporting irreversibles: Ch 46 second refusal for the worse reason; Ch 39's declaration now priced at the Review. Judgement, recorded as such.
- **Tessa hinge not spent.** May clipboard (2nd, 2,640) appears in Ch 44 (Ines) and is otherwise untouched; word Channel nowhere. Ines paper discharged, word ungiven by decision, Lantern Row scene not re-run. Tobias owed-something beat kept to boxes and boards, no speech. Read by eye across the batch.
- **Numbers reconcile (reading with arithmetic) — CORRECTED AFTER THE REVIEW.** 8,141 published; band six 20,000; 11,859 short; deed 400; twenty-nine and a fraction; lines 41→91 with fifty new faces stated (boxes/queues/corridors/Review); turned 5→8 named (Nell Ardery, Garrick Neve, yard checker); file 4,112 / 4,111 sealed / transfer 214,000 / Held Account One / no Zero. No second aggregate invoked. Drift ladder **8,140 / 8,139 / 8,138 — one, two and three grains down, three being the whole tolerance**, and four down lapses a band on the page in Ch 47. **The 11,859 is not closed and never was.** *The first version of this bullet claimed 8,137 was inside a three-grain tolerance and that an open-question 400 carried the standing to 20,000. Both were false on the page: 8,137 is four down, and 8,137 + 400 is 8,537, not 20,000. The check that would have caught it is subtracting the floor from the reading for every figure on the page, which is now done.* **How six is won instead:** the band was struck on the requisition of the 19th, a true answer under the open-question rule is a finding, a finding is an instrument, and the panel seats a candidate on standing unless the band was struck on an instrument. The plate still reads 8,138. The reservoir scores nothing, which is what `bible/power-system.md` requires and what Volume 2 needs.
- **Absence claims and their limits.** "No banned word appears" is a grep claim and the hits (zero) are reported above. "The scene changes something" and "the batch escalates" are judgements; no command verifies them. Where a claim is about absence beyond grep's reach (e.g., paraphrase of a rationed construction), this file reports the sweep method (construction search + eye read) rather than certifying a clean page. **The limit of this file, stated plainly after the repair: every gate it ran was a count, and every one of the twelve defects the independent review found was invisible to a count.** Four were arithmetic, three were quotation and paragraph shape, two were a duplicated scene, one was a duplicated construction across ten chapters, one was a preserved draft artifact, and one was a character naming the volume he is in. A count cannot see any of them. Read the page.

## Repairs made inside this batch (writer pass)

- Seven chapters drafted under 1,800 were expanded by adding beats, not by padding sentences: clerk office (42), crossing/Nell/door (43), Ola/Nadia (44), Runa/rack/row (45), corridor/panel (47), room/corridor/Vestry night (48), branch/Vestry/gate (49), side-room/corridor/washroom (50). Final band 1800–2139.
- Ch 49 merged-paragraph 182 split; Ch 50 duplicated work sentence removed; both re-measured.
- Ch 50 final sentence owned solely by Ch 50; earlier chapters swept for paraphrase by eye.

## Repairs made by the Batch 0005 review repair

Read against the page, not against this file. **Good prose was kept; the batch was not restarted; the
planned plot did not move.** Full reasoning in `state/open-threads.md` under *Canon-change flags raised
by the Batch 0005 review repair*.

**Blocking arithmetic and calendar**

- Ch 47 read 8,137 and called four grains down inside a three-grain tolerance while the same chapter
  showed four grains down laping a man; Ch 48 had the chair award four hundred grains off a witnessed
  answer and announce 20,000. Four readings corrected to **8,138 / three down / three inside**, in Ch 47
  three places and Ch 48 once, and the panel's ruling rewritten as an instrument ruling. Check: subtract
  the floor from every published reading on the page.
- Ch 42 and Ch 44 were both Thursday the 29th. Ch 42 is now **the 22nd**, anchored in its own first line,
  with Neve's "Three days now" changed to "Seven days now" and Runa's reference to the 26th changed to
  the requisition. The four box Thursdays are now consecutive and none is skipped.
- Ch 45 was "the second week after the re-read" when it is the first, and the terms named "a date six
  weeks ahead" when the Review is a week ahead. Both corrected.

**Blocking prose faults**

- Ch 49: three unclosed quotations spilling into the next paragraph, and a merged duplicate sentence in
  one paragraph. All closed and de-merged.
- Ch 48: two scenes merged into one paragraph with a capital mid-sentence. Split.
- Ch 47: the panel reading was rendered twice, once at the door and once in the room, with the same
  machine, clerk, chair and two findings verbatim, and the door beat opened three times. Rendered once.
- Ch 50: a literal duplicate sentence two paragraphs apart. One instance kept.
- Ch 50: Ines said *"That is what Volume 2 has to learn before it spends you again."* A character named
  the volume structure. Replaced with something an auditor could say.
- Ch 45: a discarded draft line was preserved and narrated as a correction in the prose. Deleted.

**Craft**

- The *For <person>, his <verb> meant* closing ran in **all ten chapters in a row**, with Emrys Vaz,
  Marguerite Vale and the Reading Office clerk each repeated across it. `AGENTS.md` fails a batch for
  using the same construction as emphasis more than twice running. It now appears in **Ch 41, Ch 44 and
  Ch 48 only**, none adjacent, no subject repeated; seven endings were rewritten in other shapes and the
  paragraphs around them were kept.

**Process, recorded not acted on**

- This file was written in the same commit as the prose it reviewed. Nine batches have now done that.
- `state/phase-ledger.json` does not exist. It is controller-owned and has not been touched here.
- Volume 1 closed in prose and the batch created a Volume 2 batch prompt instead of the volume close.
  `workspace/volume-02/batch-0001/PROMPT.md` has been removed and replaced with the volume-close prompt,
  because **there is no `outline/volume-02.md` and a batch prompt with no volume outline behind it is not a
  phase.**
