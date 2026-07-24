# Chapter 9 cold-start audit — percents (2026-07-23 isolated regeneration)

## Learner contract and resolved closure

- Learner: foundational cold-start; no confirmed mathematical, tool, or
  subject prerequisites outside this deck.
- Machine-resolved inbound closure for `09_percents` (edge mode: explicit):
  chapters 01–08. Chapters 01–07 arrive as validator-resolved capability
  summaries; chapter 08's complete scheduled cards are available. No external
  decks; no assumed tools.
- Allowed inbound capabilities: whole numbers, place value, number line,
  comparison, rounding (Ch. 1); addition, subtraction, inverse-operation
  checks (Ch. 2); multiplication, division, remainders, arrays (Ch. 3);
  expressions, operation order, factors and multiples, powers (Ch. 4); signed
  numbers (Ch. 5); fractions, equivalent fractions, simplest form via shared
  factors, mixed numbers, fraction operations, fraction of a quantity
  (Ch. 6); decimals, decimal place value, fraction–decimal equivalence,
  decimal operations, decimal rounding (Ch. 7); ratio, "for every," colon
  notation, equivalent ratio, scale factor, ratio simplest form, ratio table,
  double number line, rate, unit rate, "per means for each one,"
  proportional relationship (Ch. 8, verified against its full card text).
- Money notation (dollar, cent, \$ sign, two decimal places) is recorded as
  **established** in Chapter 7 by the deck concept ledger in `CARD_README.md`
  (Ch. 7 fronts 13–14, 27), so money contexts are inbound.
- No inbound edge was added beyond the resolved sandbox closure.

## Concept frontier: new ideas introduced in this chapter

| Concept, symbol, or representation | Required on which front? | Allowed inbound source or earlier establishment | First supported retrieval | Later application | Status |
|---|---|---|---|---|---|
| Percent, "per cent"/per hundred, \(\%\) symbol | Fronts 1–27 | Front 1 defines the comparison-to-100 and the symbol, bridging from Ch. 8's "per" | Front 1 (write 61 per 100 as a percent) | Every later front | established |
| Hundred-grid representation (100 equal small squares, each 1%) | Front 2 | Grammar stated on Front 2 itself using Ch. 6 equal-parts language | Front 2 (count and name 27%) | Grid is not reused; the per-hundred meaning it anchors recurs throughout | established |
| Percent → decimal conversion | Fronts 3, 14, 18, 20, 22, 26 | Front 3 teaches via hundredths (Ch. 7 place value) | Front 3 (6% → 0.06) | Problems 14, 21, 22; fronts 17, 18, 20, 26 | established |
| Decimal → percent conversion | Front 4 | Front 4 teaches via naming hundredths, with the tenths-renaming step shown on 0.7 | Front 4 (0.4 → 40%) | Cross-form comparison (Front 7) | established |
| Percent → fraction conversion | Fronts 5, 15 | Front 5 teaches via denominator 100 plus Ch. 6 simplifying | Front 5 (85% → 17/20) | Problem 15 (25% = 1/4) | established |
| Fraction → percent conversion | Fronts 6, 12, 16, 23–25 | Front 6 teaches via equivalent fraction with denominator 100 (Ch. 6 scaling) | Front 6 (7/20 → 35%) | Fronts 7, 12; Problems 16, 27; change fronts 23–25 | established |
| 100% as the whole; percents above 100 as times-the-whole | Front 8 | Defined on Front 8 from 100/100 and decimal 1.5 | Front 8 (125% → 1.25 times) | Percent-change framing (a rise can exceed the start) | established |
| Percent of a quantity (multiply by decimal or fraction form) | Fronts 9, 14, 17, 18, 20–22, 26 | Front 9 bridges from Ch. 6 fraction-of-quantity ("of" means multiply) | Front 9 (30% of 80) | Problems 14, 21, 22; consumer fronts 17–20; Front 26 | established |
| 10% mental anchor (divide by 10; halve/double for 5%/20%) | Fronts 10, 14, 21, 22 | Front 10 teaches from 10% = 1/10 | Front 10 (10% of 250) | EVALUATE checks of Problems 14, 21, 22 | established |
| Whole / part / percent-rate roles | Fronts 11, 12, 13, 14, 16, 19 | Front 11 names the three roles, bridging "rate ... per one" (Ch. 8 unit rate) to "per hundred"; part/whole wording follows Ch. 6/8 usage | Front 11 (name roles in a stated case) | Fronts 12–13; Problems 14–16; Front 19 | established |
| Find the rate (part over whole, convert) | Fronts 12, 16, 19, 23 | Front 12 teaches with 18 of 24 | Front 12 (13 of 20) | Problem 16; Front 19; percent-change division reuses the same move | established |
| Find the whole (scale down to 10%, up to 100%) | Fronts 13, 15 | Front 13 teaches via ratio-table scaling (Ch. 8) | Front 13 (60% is 42 → 70) | Problem 15 (fraction-form variant) | established |
| Discount, "off," sale price | Fronts 17, 19, 20, 21 | Front 17 defines all three with a worked $50 example | Front 17 ($30 puzzle, 10% off) | Fronts 19–20; Problem 21 | established |
| Sales tax and tip as add-on percents | Fronts 18, 22 | Front 18 defines both as one structure: a percent of the pre-addition amount, added | Front 18 ($40 meal, 15% tip) | Problem 22 | established |
| Price-breakdown bar (original split into sale price + discount) | Front 19 | Bar grammar stated on the front and in alt text; segment labels are the givens | Front 19 (read 15/60 → 25%) | none (single-use representation) | established |
| Percent change; increase measured against the start | Fronts 23, 24, 25, 27 | Front 23 defines change ÷ starting amount, with before/after bars described on the front | Front 23 (40 → 50 from the figure) | Fronts 24–25; Problem 27 | established |
| Percent decrease and the changed-baseline contrast | Front 24 | Front 24 applies Front 23's definition with the start switched | Front 24 ($25 → $20) | Problem 27's EVALUATE reasoning | established |
| Percentage point | Fronts 25, 27 | Front 25 defines the direct difference of two percents against percent change | Front 25 (40% → 50%: 10 points vs 25%) | Problem 27 | established |
| Successive percents act on the current baseline | Front 26 | Front 26 computes both steps explicitly | Front 26 ($100 up 10%, down 10%) | none (boundary card) | established |

## Front-by-front scan

Fronts were read in order; each front's dependency list was completed before
its answer was inspected. "Inbound" cites the resolved closure; "F*n*" cites
an earlier front of this chapter.

| # | Card | Front dependencies | Source | Status |
|---|---|---|---|---|
| 1 | 0c887e92 (percent definition) | "for every" and "per" (Ch. 8); comparison to 100 (Ch. 1 numbers); survey/pet/household as everyday words with no technical load | inbound + self-bridge of the new term and symbol | ok |
| 2 | a2ecf3d8 (hundred grid) | % symbol (F1); equal parts (Ch. 6); counting (Ch. 1); grid grammar stated on the front; alt text withholds the count, which is the retrieval target | F1 + inbound + front bridge | ok |
| 3 | 3cd57b9d (% → decimal) | % (F1); hundredths and decimal place value (Ch. 7); fraction notation (Ch. 6) | F1 + inbound | ok |
| 4 | 2bb0a1db (decimal → %) | % (F1); hundredths renaming 0.7 = 0.70 (Ch. 7 trailing-zero equivalence within `decimal-place-value`); worked example 0.35 on the front | F1 + inbound + front bridge | ok |
| 5 | a8cfd180 (% → fraction) | % (F1); simplifying by shared factors (Ch. 6, restated in Ch. 8) | F1 + inbound | ok |
| 6 | 1b0ef704 (fraction → %) | % (F1); equivalent fractions by scaling (Ch. 6); scale-both-numbers language (Ch. 8) | F1 + inbound | ok |
| 7 | 94e7e05e (cross-form comparison) | fraction → % (F6); comparison (Ch. 1) | F6 + inbound | ok |
| 8 | 1eb2fbd0 (100% and beyond) | % (F1); decimals 1.5/1.25 (Ch. 7); "times" (Ch. 3); ticket counts as everyday context | F1 + inbound | ok |
| 9 | b95e8dee (percent of a quantity) | fraction of a quantity and "of" as multiply (Ch. 6); % → decimal (F3); decimal multiplication (Ch. 7) | F3 + inbound | ok |
| 10 | a68ad0a8 (10% anchor) | % → fraction 1/10 (F5 move, shown inline); division by 10 (Ch. 3); halving/doubling (Ch. 3/6) | F5 + inbound | ok |
| 11 | 459d68df (three roles) | % (F1); unit-rate "per one" (Ch. 8) bridged to "per hundred" on the front; internal consistency of the stated example (15% of 40 is 6) verified | F1 + inbound + front bridge | ok |
| 12 | 43516fe1 (find the rate) | part/whole roles (F11); fraction simplification and conversion (F5–F6, Ch. 6) | F5, F6, F11 | ok |
| 13 | 62db9cd4 (find the whole) | roles (F11); ratio-table scaling (Ch. 8); division/multiplication (Ch. 3) | F11 + inbound | ok |
| 14 | 17a422e6 (P1, analyzed find-the-part) | roles (F11); % → decimal (F3); decimal multiplication (Ch. 7); 10% anchor (F10) appears only in EVALUATE | F3, F10, F11 + inbound | ok |
| 15 | c02e9a59 (P2, completion find-the-whole) | % → fraction (F5); quarter (Ch. 6); whole-rebuilding idea (F13); multiplication (Ch. 3) | F5, F13 + inbound | ok |
| 16 | 94baf286 (P3, independent find-the-rate) | find-the-rate method (F12); planting seeds as everyday context | F12 | ok |
| 17 | 5204e0e0 (discount) | money notation (Ch. 7, established); percent of a quantity (F9); subtraction (Ch. 2); new terms defined on the front with a worked example | F9 + inbound + front bridge | ok |
| 18 | 09bdb0d0 (tax and tip) | money (Ch. 7); percent of a quantity (F9); addition (Ch. 2); both new terms are instances of the single add-on structure defined here | F9 + inbound + front bridge | ok |
| 19 | 6b42ef73 (price-breakdown figure) | discount/sale price (F17); part/whole roles (F11); find-the-rate (F12); bar grammar stated on the front and alt text; labels are givens, the 25% answer is not shown | F11, F12, F17 + front bridge | ok |
| 20 | ea4a3904 (subtract-the-number diagnosis) | discount (F17); percent of a quantity (F9); money (Ch. 7) | F9, F17 | ok |
| 21 | 1884fe9a (P4, independent discount) | discount (F17); 10% anchor (F10); decimal subtraction 36 − 5.40 (Ch. 7) | F10, F17 + inbound | ok |
| 22 | 39180f72 (P5, independent tip total) | tip (F18); % → decimal (F3); decimal multiplication and addition (Ch. 7) | F3, F18 + inbound | ok |
| 23 | 570d7ee2 (percent change + figure) | subtraction (Ch. 2); fraction → % (F6/F12 move); before/after bar grammar stated on the front and alt text; percent change defined here | F6 + inbound + front bridge | ok |
| 24 | c020f3c2 (percent decrease, baseline) | percent change (F23); money (Ch. 7) | F23 + inbound | ok |
| 25 | 5844538b (percentage points) | percent change (F23); subtraction of percents (Ch. 2); new term defined on the front with a worked contrast | F23 + front bridge | ok |
| 26 | dda62e21 (successive changes) | percent of a quantity (F9); money (Ch. 7); addition/subtraction (Ch. 2) | F9 + inbound | ok |
| 27 | 08dc6d1b (P6, mixed interpretation) | percentage points (F25); percent change (F23); the quoted headline's misuse of "%" is the object of diagnosis, not a premise | F23, F25 | ok |

No front introduces more than one independent new idea before that idea's
first supported retrieval, with one deliberate pairing: Front 18 introduces
"sales tax" and "tip" together because both are the same add-on-percent
structure and a single grading decision (compute the total) covers it; they
are not independent mechanisms.

## Figures and alt text

- `hundred_grid.svg`: front-only setup; the alt text and SVG desc withhold
  the shaded count (the retrieval target) and describe the block position so
  the description does not leak the answer; sighted counting is the task, as
  with the Ch. 8 shape-collection figure. Grid verified at 27 shaded cells.
- `price_breakdown.svg`: labels ($60, $45, $15) are givens; the answer (25%)
  appears nowhere in the figure. Bracket, divider line, and text labels give
  redundant non-color segmentation cues.
- `before_after_bars.svg`: labels (40, 50) are givens; the answer (25%) is
  absent. The dashed guide plus the differently shaded extra piece give a
  redundant non-color cue. Bar lengths are to scale (4 : 5 units).
- All three compiled from TikZ via `flashcards deck render-figures`; each SVG
  has `viewBox`, `role='img'`, and meaningful `<title>`/`<desc>`, and was
  inspected at phone-like width.

## Arithmetic verification

Every stated value was verified by direct derivation and an inverse or bound
check: all conversions (6% = 0.06, 0.4 = 40%, 85% = 17/20, 7/20 = 35%,
3/4 = 75%), 0.30 × 80 = 24, 250 ÷ 10 = 25, 12/48 = 25%, 13/20 = 65%,
42 ÷ 6 = 7 → 70 with 0.60 × 70 = 42, 0.45 × 300 = 135 with the 120 + 15
anchor check, 4 × 14 = 56 with 0.25 × 56 = 14, 60/80 = 75% with
0.75 × 80 = 60, 0.10 × 30 = 3 → 27, 0.15 × 40 = 6 → 46, 15/60 = 25%,
0.25 × 80 = 20 → 60, 3.60 + 1.80 = 5.40 → 30.60 with 5.40 + 30.60 = 36,
0.18 × 45 = 8.10 → 53.10 bounded by 9.00, 10/40 = 25%, 5/25 = 20%,
6/30 = 20%, 50 − 40 = 10 points with 10/40 = 25%, 110 − 11 = 99, and
30 − 20 = 10 points with 10/20 = 50%. The percentage-point versus
percent-change convention was verified against a current external reference
recorded in the deck source register.

## Rejected dependencies

Tempting examples rejected for borrowing outside the closure are recorded in
`CARD_README.md` (interest rates, measurement units, data-graph contexts,
algebraic solving, per-hour rates).

## Result

Every front dependency maps to confirmed inbound knowledge or an earlier
establishment point in this chapter. No blocked rows remain.

```text
cold_start_status: pass
unresolved_dependencies: 0
```
