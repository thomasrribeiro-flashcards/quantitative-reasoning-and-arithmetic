# Pilot cold-start audit

Deck: `mathematics/quantitative-reasoning-and-arithmetic`
Pilot chapter: `flashcards/01_quantities_and_whole_numbers.md`
Audit date: 2026-07-22 (fresh regeneration; the previous pilot was blanked and
was not reconstructed)
Learner contract: no confirmed mathematical knowledge, subject knowledge, or
tools. Everyday adult language — jars, shelves, boxes, shells, chairs, left,
right, closer, farther — is treated as known. Recognition of the written
symbols 0–9 as marks that can be copied is treated as basic literacy, but
every mathematical meaning attached to any symbol is established on a
scheduled front. Spoken counting words are not assumed known in fixed order
until a scheduled front presents them.

## Resolved inbound closure

`flashcards deck prerequisites . --chapter 1 --json` resolves:

- prerequisite decks: none;
- earlier local chapters: none;
- assumed tools: none.

Therefore every mathematical dependency below must be established on the same
front or on an earlier scheduled front (`Q:`/`A:`, `C:`, or `P:`/`S:` block).
Prose, headings, and tables are never accepted as establishment points.

## Front-first dependency record

The 18 fronts were extracted and scanned in order, and each row below was
completed before the corresponding answer or solution was read. Card IDs are
the stable IDs assigned by `flashcards deck stabilize .`.

| Front | Card ID (suffix) | Target | Dependencies required to parse and attempt | Allowed source or earlier establishment | Front-first finding |
|---:|---|---|---|---|---|
| 01 | …6501831b | Relate numeral to quantity | quantity; numeral; "how many" | Both technical terms are defined on Front 01 itself in the pantry-shelf situation; the 6 is described as "the written symbol," so no numeric meaning is presupposed. | Attempt is supported. |
| 02 | …acf8ca | Discriminate quantity from numeral | quantity; numeral | Front 01. The wall symbol 9 is again introduced as a painted symbol. | Attempt is supported with reduced scaffolding. |
| 03 | …db5f73 | Diagnose a skipped-item count | fixed counting-word order; one-word-per-item touching; last-word-is-the-quantity rule; quantity | Front 03 states all three rules and displays the sequence "one, two, three, four, five, and so on" before the diagnosis is requested; quantity is from Front 01. | Attempt is supported. |
| 04 | …5d1c22d | Use zero for none | whole number; zero; count of complete items; quantity | Front 04 lists the numerals 0–5, defines whole number, and maps 0 to "none at all"; counting is from Front 03; quantity from Front 01. | Attempt is supported. |
| 05 | …b62979d* | Retrieve the whole-number category | counts of complete items; count of none | Front 04. | Attempt is supported. |
| 06 | …4e657fd5* | Translate grouped counters to a two-digit numeral | digit; place; ones place; tens place; two-digit numeral; group of ten; figure grammar | Front 06 defines digit, place, ones, and tens, and states that every outlined loop holds exactly ten counters; the figure and alt text show two loops and five singles; numeral/quantity from Front 01; "ten" as a counting word from Front 03's "and so on" sequence. | Attempt is supported visually and textually. |
| 07 | …0461dc534* | Retrieve what a tens digit records | numeral 73; digit; tens place | Front 06 established digits, places, and reading two-digit numerals. | Attempt is supported. |
| 08 | …567ccc1f* | Interpret placeholder zero | right-to-left place order; hundreds; 100 as ten tens; zero as "no groups" | All stated on Front 08 itself; ones/tens from Front 06; zero from Front 04. | Attempt is supported. |
| 09 | …97900a2d* | Diagnose ignored place | numeral 380; hundreds place; place decides what a digit counts | Fronts 06 and 08. | Attempt is supported. |
| 10 | …62bdf05* | Compare positions on a number line | number line; evenly spaced marks; rightward growth; dot-on-mark convention; larger quantity | Front 10 defines the representation, the rightward rule, and the dot convention; the figure and alt text place A at 3 and B at 8; quantity from Front 01; "larger" is everyday comparison language. | Attempt is supported visually and textually. |
| 11 | …2509629* | Choose the true comparison statement | `<`; `>`; readings; open-side rule | Both symbols, both readings, and the open-side rule are stated on Front 11; ordering of quantities is from Front 10. The learner chooses between two complete statements, so no blank-slot notation is assumed. | Attempt is supported. |
| 12 | …9e1dc130* | Classify a report as an estimate | exact; estimate; signal words "about"/"roughly"; complete count | Both categories are defined and contrasted on Front 12; complete counting is from Front 03; the numeral 30 is readable from Front 06. | Attempt is supported. |
| 13 | …b59d18d* | Retrieve when an estimate is appropriate | estimate; exact count; speed/cost trade-off | Front 12. "Roughly enough chairs" is everyday decision language. | Attempt is supported. |
| 14 | …85768cb54* | Round 38 to the nearest ten | rounding; nearest ten; surrounding tens; halfway value ends in 5; higher-ten tie convention; number-line stretch | Front 14 defines the method and states the tie convention; number-line grammar is from Front 10; the figure and alt text supply 30, 40, the labeled halfway value 35, and the dot on 38; two-digit numerals from Front 06. | Attempt is supported visually and textually. |
| 15 | …837610294* | Apply nearest-ten rounding (analyzed problem) | exact count; nearest ten; locate 73 between tens; compare 73 with the halfway value | Fronts 03/12 (exact count), 14 (method and halfway comparison, demonstrated concretely in Answer 14 on the 30–40 stretch); comparing 73 with 75 reduces to the shared-tens, ones-digit comparison available from Fronts 06 and 11. The garden context adds no domain knowledge. | Attempt is supported as the first analyzed problem. |
| 16 | …3648a7a7c2* | Diagnose wrong-direction rounding via the ones-digit shortcut | ones digit; complete 0–4 / 5–9 shortcut; nearest ten | Front 16 states the full shortcut before asking for the diagnosis; ones digit from Front 06; rounding meaning from Fronts 14–15. | Attempt is supported. |
| 17 | …426531a701* | Transfer rounding to the nearest hundred | nearest hundred; numbers ending in 00; halfway ends in 50; tie convention | All stated on Front 17; hundreds place from Front 08; rounding logic from Front 14. | Attempt is supported. |
| 18 | …f0ea5d4e* | Independently round a checkout count | exact count; nearest hundred; locate 649 between hundreds | Fronts 03/12, 17 (nearest hundred), 14 (halfway logic). "Newsletter," "summer program," and "checked out" are ordinary context. | Attempt is supported as the independent, faded application. |

*Suffixes shorten the `card-alias` where the `card-id` suffix would be
ambiguous in prose; full IDs are in the chapter file.

## Adversarial probes and their resolutions

Each probe below was raised against the fronts alone and had to be resolved
from earlier scheduled blocks or the learner contract.

- **Multi-digit comparison hidden inside rounding (Fronts 15, 18).** Deciding
  that 73 is below 75 (and 649 below 650) requires comparing multi-digit
  numbers, which no front teaches as a named procedure. Resolution: Answer 14
  demonstrates the comparison concretely as position on the drawn 30–40
  stretch, and the shared-leading-digit case reduces to single-digit
  comparison established on Fronts 06 and 11. Both problem solutions also
  verify by distances that can be checked by counting marks (Front 03 plus
  Front 10), so no unestablished subtraction procedure is required to grade
  oneself. Judged resolved; no repair needed.
- **English number names.** No front or answer requires reading or producing
  multi-digit English number names ("seventy," "twenty-five"); all
  multi-digit values appear as numerals, which Fronts 06 and 08 establish.
  One violation was found and repaired (see below).
- **Counting words beyond five (Front 06's "ten").** Front 03 presents the
  counting sequence with "and so on," and Front 06 restates "every outlined
  loop holds exactly ten counters," so the learner never needs to count to
  ten unaided. Judged resolved.
- **Figure-reading conventions.** Each figure-bearing front (06, 10, 14)
  states its own reading rules in words (loops hold ten; dots sit on marks;
  the dashed guide marks the halfway value) and the alt text restates the
  same content, so no figure assumes prior diagram literacy. Judged resolved.
- **Tie convention never exercised as a trap.** The tie ("ends in 5") is
  stated on Fronts 14, 16, and 17 but no scheduled item requires applying it
  to a tie case; a tie-ending analyzed problem was considered and rejected at
  design time so the first analyzed problem would isolate the closer-ten
  decision. This is a deliberate scope choice, recorded in the CARD_README
  rejected-examples ledger, not an unresolved dependency.

## Answer and solution check

- All 18 answers and solutions were checked only after the front table above
  was recorded.
- Each answer opens with the gradeable decision and stays within concepts
  established by its own front or an earlier scheduled block.
- Arithmetic was verified by direct derivation: 38 → 40 (distances 2 vs 8),
  73 → 70 (3 vs 7), 84 → 80 (4 vs 6), 452 → 500 (48 vs 52), 649 → 600
  (49 vs 51); place-value claims checked at 25, 73, 507, 380.
- Problem 15 models the full IDENTIFY/PLAN/EXECUTE/EVALUATE structure;
  Problem 18 fades to solution-plus-EVALUATE while keeping a genuine check
  and an adversarial distractor (the large ones digit 9 tempting a round-up).
  The IPEE labels first appear in Solution 15 and no later front requires
  them.

## Repairs made during the scan

| Finding | Severity before repair | Repair |
|---|---|---|
| Answer 06 read the total aloud as "twenty-five," a multi-digit English number name never established on any scheduled front (the deck ledger rejects such names). | major, D8 | Replaced with the numeral: "make 25 counters in all." |

No front-side repairs were required: the chapter was authored from the
completed concept-dependency ledger, and the subsequent front-only scan
confirmed each front against that ledger.

## Figures

- Three distinct retrieval roles: grouping counters into tens and ones
  (`tens_and_ones`), ordering positions on a number line
  (`number_line_comparison`), and locating a value against a halfway guide
  for rounding (`rounding_nearest_ten`).
- Each figure has editable TikZ source beside its same-named SVG and loads
  `figures/tikz-style.tex` from the repository root.
- `% flashcards-title:` / `% flashcards-desc:` metadata produced SVG
  `<title>`, `<desc>`, `role="img"`, `aria-labelledby`, and a responsive
  `viewBox` in all three outputs.
- Non-color cues throughout: outlined loops, letter labels A/B, numeric
  labels, tick lengths, and a dashed halfway guide; dots carry both fill and
  a contrasting border.
- All three compiled figures were inspected as raster previews at 560 px
  width; counters, ticks, labels 30/35/38/40, and both dots remained distinct
  and legible at phone scale.
- `flashcards deck render-figures . --check` reports all three outputs
  current.

## Inventory reconciliation

| Inventory | Planned | Actual | Result |
|---|---:|---:|---|
| Basic `Q:/A:` cards | 16 | 16 | matched |
| Cloze `C:` cards | 0 | 0 | matched; no established compact target justified cloze form |
| Problem `P:/S:` cards | 2 | 2 | matched; one analyzed (IPEE modeled), one independent/faded |
| Figures | 3 | 3 | matched; grouping, ordering, and rounding roles are distinct |
| Later-chapter cards/figures | 0 at pilot gate | 0 | matched; intentionally blocked pending human approval |

Final validator result: 18 cards (16 basic, 0 cloze, 2 problem), 0 parser
warnings, 0 KaTeX errors, 0 image errors, 0 identity errors, 0 cloze lints,
0 frontmatter lints; stable IDs present for all 18 blocks; prerequisite graph
valid (1 chapter, 0 external decks).

## Gate result

cold_start_status: pass
unresolved_dependencies: 0

The regenerated pilot is ready for human review. Chapters 2–10 remain
unauthored until explicit approval.
