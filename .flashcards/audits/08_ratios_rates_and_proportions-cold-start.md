# Cold-start audit — Chapter 8: Ratios, rates, and proportions

Date: 2026-07-23 (isolated regeneration run)
Scope: `flashcards/08_ratios_rates_and_proportions.md`, 20 scheduled cards
(15 Q/A, 5 P/S, 0 clozes). Audit method per CARD_STANDARD D8: each front
was scanned in scheduling order with its answer covered; every
domain-bearing term, notation, representation, and figure-vocabulary item
on the front was resolved against (a) the machine-resolved inbound closure
(chapters 01–07; chapter 07 full cards, chapters 01–06 capability
summaries) or (b) a *strictly earlier* scheduled card in this chapter.
Only Q:/A:, C:, and P:/S: blocks count as establishing material.

## Inbound closure used (resolution key)

| Key | Capability | Source |
|---|---|---|
| IN-count | Counting, whole numbers, place value, number-line reading | ch01 |
| IN-addsub | Addition, subtraction, "how many more", inverse checks | ch02 |
| IN-muldiv | Multiplication, division, equal groups/sharing, arrays | ch03 |
| IN-factor | Factors, shared factors, order of operations | ch04 |
| IN-frac | Fractions, equivalent fractions (multiply/divide both parts), fraction of a quantity | ch06 |
| IN-dec | Decimal notation, comparison, money notation ($x.yz), decimal division by counting tenths, ×/÷ by 10, multiplication checks | ch07 (full cards) |

Everyday, non-domain vocabulary (markers, erasers, beads, spoonfuls,
tiles, paint drops, "triangles"/"circles" as common shape names, tables
read column-by-column when the front itself states the reading rule) is
not treated as a dependency per D8.

## Front-by-front audit

| # | Card id (prefix) | Front dependencies | Resolution | Status |
|---|---|---|---|---|
| 01 | 9e21147e | subtraction as "how many more"; division as "times as many" (front teaches the multiplicative reading before asking) | IN-addsub; IN-muldiv; teaching front self-establishes "times as many" | pass |
| 02 | 94c0e0fa | "for every" phrasing; ratio term; colon notation (front defines all three before the query) | teaching front self-establishes ratio + colon; IN-count | pass |
| 03 | efbdbac8 | ratio, colon notation; order-of-words rule (front states the rule with a worked contrast before asking) | card 02; teaching front self-establishes order convention | pass |
| 04 | a2152dc2 | ratio in colon form; order convention; counting shapes in a figure; alt-text terms "rows", "triangles", "circles" | cards 02–03; IN-count; everyday shape vocabulary | pass |
| 05 | 983dabff | ratio notation; part-to-part vs fraction-of-whole distinction (front teaches it with 2:3 → 2/5 example); fraction notation; adding parts | card 02; teaching front self-establishes distinction; IN-frac; IN-addsub | pass |
| 06 | 041cd13e | ratio; drink-mix 2:3 context; equivalent ratio + scale factor (front defines both, linked to equivalent fractions); multiplication | card 02 (context and notation); teaching front self-establishes equivalent ratio/scale factor; IN-frac (equivalent-fraction analogy); IN-muldiv | pass |
| 07 | e7af2536 | equivalent ratio by division; shared factor; simplest form (front defines with 12:18 → 2:3 example) | card 06; IN-factor; IN-muldiv; teaching front self-establishes simplest form | pass |
| 08 | d392f7bf | ratios of two mixes; scaling to a common value (front names the strategy: "scaling both ratios to the same amount of sugar") | cards 02, 06; IN-muldiv | pass |
| 09 | 39589f46 | equivalent ratios; scale factor; ratio-table grammar (front defines: each column is 2:3 scaled by a factor); reading a two-row table | card 06; teaching front self-establishes table grammar; IN-count | pass |
| 10 | 742418dc | number lines; aligned zeros; equivalent ratios; double-number-line grammar (front defines: aligned marks are paired by dashed guides); figure alt-text terms | IN-count (number lines); card 06; teaching front self-establishes double-line grammar | pass |
| 11 | 2a06ea67 | "for every" ratio 2:5; double-number-line reading incl. dashed guides and a missing mark; equivalent-ratio completion | cards 02, 06, 10 (grammar taught one card earlier); IN-count | pass |
| 12 | 50d3ea0f | ratio-table grammar with a missing entry; scale factor from one row applied to the other; executing a stated plan | cards 06, 09; IN-muldiv | pass |
| 13 | 0490f170 | ratio between different kinds of quantities; rate, unit rate, "per" (front defines all three with the $12 : 4 notebooks example); money notation; division | card 02; teaching front self-establishes rate/unit rate/"per"; IN-dec (money); IN-muldiv | pass |
| 14 | 00e7d3e9 | unit rate / price per one; money with decimal amounts; decimal division | card 13; IN-dec ($4.50 notation; 45-tenths division method) | pass |
| 15 | d83029b3 | unit rate as price per pen; comparing two rates ("better buy" defined on the front as the lower price per pen); money notation; decimal comparison | card 13; IN-dec (notation, comparison, tenths-counting division; the hundredths-counting step appears only in the solution and is a stated one-line extension of the ch07 tenths method) | pass |
| 16 | 44d90963 | proportional relationship (front defines: every pair forms the same ratio / constant amount per one); ratio; unit rate; money | teaching front self-establishes proportional relationship; cards 02, 13; IN-dec | pass |
| 17 | 8f6a7e7b | proportional relationship; per-one test; ratio-table-style paired columns; equivalent ratios | cards 06, 09, 13, 16; IN-muldiv | pass |
| 18 | 81394737 | proportional relationship; constant difference; testing pairs by forming ratios | card 16 (definition + per-one test); cards 02, 13; IN-addsub | pass |
| 19 | f2504ee5 | "for every" ratio 6:4; equivalent-ratio completion for a larger case | cards 02, 06; scale-factor method from cards 06, 11; IN-muldiv | pass |
| 20 | 24f2e454 | mixture ratio 4:6; equivalence of scaled ratios; additive-vs-multiplicative distinction (the error type is the subject of card 01); diagnosing a wrong pair | cards 01, 02, 06, 07 (simplest form used in solution); card 13 (per-one comparison in solution); IN-addsub, IN-muldiv | pass |

## Sequencing checks

- Every in-chapter dependency above points to a strictly earlier card;
  no front relies on a later card, a figure caption alone, or prose
  outside scheduled blocks.
- No front uses later-chapter terminology: no percent (ch09), no time,
  speed, or measurement-unit rates (ch10), no coordinate graphs, no
  cross-multiplication, no letter variables.
- Money is the only different-kind quantity used in rates, matching the
  ch07 bridge; all other contexts are counted objects.
- Figure alt texts describe structure without leaking answers (the
  ratio-collection alt text names no counts; the beads alt text names the
  question mark, not 15).

cold_start_status: pass
unresolved_dependencies: 0
