# Pilot cold-start audit

Deck: `mathematics/quantitative-reasoning-and-arithmetic`
Pilot chapter: `flashcards/01_quantities_and_whole_numbers.md`
Audit date: 2026-07-17
Learner contract: no confirmed mathematical knowledge, subject knowledge, or
tools. Common concrete words such as apple, tray, shelf, box, left, and right
are treated as everyday language; every technical mathematical meaning is
established on a scheduled front.

## Resolved inbound closure

`flashcards deck prerequisites . --chapter 1 --json` resolves:

- prerequisite decks: none;
- earlier local chapters: none;
- assumed tools: none.

Therefore every mathematical dependency below must be established on the same
front or an earlier scheduled front.

## Front-first dependency record

This table was completed from an extraction of `Q:` and `P:` fronts only,
before the corresponding answers and solutions were checked.

| Front | Target | Dependencies required to parse and attempt | Allowed source or earlier establishment | Front-first finding |
|---:|---|---|---|---|
| 01 | Relate numeral to quantity | amount/quantity; numeral; “how many?” | Both technical terms are defined on Front 01 in a concrete tray-label situation. | Attempt is supported. |
| 02 | Distinguish quantity from numeral | quantity; numeral | Front 01. | Attempt is supported with reduced scaffolding. |
| 03 | Diagnose a skipped-item count | counting-word order; one-to-one touch; final-count meaning; actual amount | Front 03 gives a fixed-order example, the complete procedure, and the final-count meaning; quantity was established on Front 01. | Attempt is supported. |
| 04 | Use zero for none | whole number; complete item; zero symbol; quantity | Front 04 defines whole numbers, displays the initial numeral sequence, and explicitly maps `0` to none; quantity is from Front 01. | Attempt is supported. |
| 05 | Retrieve whole-number category | complete-item count; none; whole number | Front 04. | Attempt is supported. |
| 06 | Translate grouped objects to a two-digit numeral | digit; tens/ones positions; group of ten; single item; figure grammar | Front 06 defines digit and both positions; the front figure and alt text show one outlined group containing ten counters and two separate counters. Numeral/quantity are from Front 01. | Attempt is supported visually and textually. |
| 07 | Retrieve a digit's place value | digit; numeral; tens place; represented amount | Front 06. | Attempt is supported. |
| 08 | Interpret placeholder zero | right-to-left places; ones/tens/hundreds; zero as no groups | All are stated on Front 08; digit/place meaning is from Fronts 06–07. | Attempt is supported. |
| 09 | Diagnose ignored place | digit; hundreds place; place determines value | Fronts 06–08. | Attempt is supported. |
| 10 | Compare positions on a whole-number line | line grammar; labeled marked spots; rightward growth; greater quantity | Front 10 defines the representation and rightward rule; the original figure and alt text identify A at 2 and B at 5; quantity is from Front 01. | Attempt is supported visually and textually. |
| 11 | Choose a comparison symbol | `<`; `>`; less than; greater than; compare 8 and 3 | Both symbols and readings are stated on Front 11; comparison by ordering is established on Front 10. The learner chooses between two complete comparisons, so no blank-slot symbol is assumed. | Attempt is supported. |
| 12 | Classify a report as estimated | exact amount; estimate; precise count; “about” | Both categories are defined and contrasted on Front 12; counting is from Front 03. | Attempt is supported. |
| 13 | Retrieve when estimation is appropriate | estimate; exact amount; appropriate precision | Front 12. “Appropriate” is everyday decision language, not a mathematical procedure. | Attempt is supported. |
| 14 | Round 46 to the nearest ten | rounding; nearest ten; ending in zero; closer; halfway; higher-ten convention; number-line grammar | Front 14 defines the method and tie convention; number-line grammar is from Front 10; exact/estimate is from Front 12. The original figure and alt text supply endpoints, midpoint, and 46's position. | Attempt is supported visually and textually. |
| 15 | Apply nearest-ten rounding in a stockroom | exact count; estimate; nearest ten; 67 | Fronts 12 and 14. The stockroom context adds no domain-specific knowledge. | Attempt is supported as the first analyzed problem. |
| 16 | Diagnose wrong-direction rounding | nearest ten; lower/higher ten; ones-digit rule; 62 and 70 | Front 16 states the complete ones-digit shortcut before asking for diagnosis; the rounding meaning comes from Fronts 14–15. | Attempt is supported. |
| 17 | Transfer rounding to nearest hundred | nearest-place idea; neighboring hundreds; halfway; closeness | Front 17 explicitly states the new hundreds case and halfway value; rounding logic is from Front 14; hundreds place is from Front 08. | Attempt is supported. |
| 18 | Independently round an attendance count | exact count; nearest hundred; 372; attendance/visitors | Fronts 12, 14, and 17. “Turnstile,” “visitors,” and “community update” are ordinary context; no unit conversion or later operation is required. | Attempt is supported as an independent application. |

## Answer and solution check

- All 18 answers or solutions were checked only after the front dependency
  table above was recorded.
- Each answer begins with the grading decision and stays within the concept
  established by its front or an earlier front.
- Whole-number, place-value, comparison, and rounding claims were checked by
  direct representation and boundary examples: `0`, `205`, `302`, `46`, `62`,
  `67`, `286`, and `372`.
- Problem 15 demonstrates the full IPEE structure. Problem 18 intentionally
  fades the separate PLAN heading after that model while retaining a genuine
  evaluation check.
- The IPEE labels first appear in Solution 15; no later pilot front requires
  those labels. No answer introduces an unexplained dependency that a later
  front assumes.

## Repairs made during the scan

| Finding | Severity before repair | Repair |
|---|---|---|
| Front 03 named counting words without showing their fixed order. | major, U7 | Added the explicit sequence “one, two, three, four” before the touch-once procedure. |
| Front 04 asked for zero without displaying the symbol-to-none mapping. | major, U7 | Added the initial numeral sequence and stated that `0` records none. |
| Front 11 used an unexplained square as a blank slot. | major, U7/U8 | Replaced it with a choice between two complete comparisons. |
| Front 16 expected a nearest-ten shortcut after only one analyzed example. | major, U7 | Put the complete ones-digit rule on the front before the diagnosis. |
| Markdown image paths were initially rooted from the repository rather than the chapter directory. | critical, U10 | Changed all three paths to `../figures/...`; validation now resolves every asset. |

## Figures

- Three distinct retrieval roles are present: grouping into tens and ones,
  ordering positions on a number line, and comparing distances for rounding.
- Each figure has editable TikZ source beside its generated SVG and loads
  `figures/tikz-style.tex` from the repository root.
- `flashcards-title` and `flashcards-desc` metadata produced an SVG `<title>`,
  `<desc>`, `role="img"`, `aria-labelledby`, and responsive `viewBox`.
- The grouped counters, letter labels, numerical labels, positions, line
  styles, and endpoint labels provide cues beyond color.
- The three compiled figures were inspected as raster previews at widths from
  481 to 604 pixels. Counters, ticks, labels, and the 46 marker remained
  distinct and legible.
- `flashcards deck render-figures . --check` reports all three outputs current.

## Inventory reconciliation

| Inventory | Planned | Actual | Result |
|---|---:|---:|---|
| Basic `Q:/A:` cards | 16 | 16 | matched |
| Cloze `C:` cards | 0 | 0 | matched; no established compact target justified cloze form |
| Problem `P:/S:` cards | 2 | 2 | matched; one analyzed and one independent/faded |
| Figures | 3 | 3 | matched; grouping, ordering, and rounding roles are distinct |
| Later-chapter cards/figures | 0 at pilot gate | 0 | matched; intentionally blocked pending human approval |

Final validator result: 18 cards, 0 parser warnings, 0 KaTeX errors, 0 image
errors, 0 identity errors, 0 cloze lints, 0 frontmatter lints, and a valid
one-chapter prerequisite graph.

## Gate result

cold_start_status: pass
unresolved_dependencies: 0

The pilot is ready for human review. Chapters 2–10 remain unauthored until
explicit approval.
