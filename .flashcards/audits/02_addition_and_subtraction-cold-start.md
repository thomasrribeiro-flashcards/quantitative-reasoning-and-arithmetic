# Cold-start audit — 02_addition_and_subtraction

- Date: 2026-07-22
- Auditor: authoring agent (claude-fable-5), isolated fresh-agent regeneration
- Method: front-first scan. Every scheduled front (Q: or P: block, including
  figure alt text and supplied premises) was audited for domain-bearing terms,
  symbols, representations, and procedures before its answer was consulted.
  Each dependency was resolved to one of: **inbound** (Chapter 1 scheduled
  cards, per the machine-resolved closure), **earlier** (established by a
  scheduled Chapter 2 card that precedes it), or **self** (defined on the same
  front before first use, using only established language).
- Inbound closure: `chapter:01_quantities_and_whole_numbers` only. No external
  decks, no assumed tools.

## Inbound frontier (Chapter 1)

Quantity and numeral; counting; zero; whole numbers; digits; place value
(ones, tens, hundreds); placeholder zero; the number line with rightward
growth; comparison symbols `<` and `>`; exact value vs. estimate; rounding to
the nearest ten or hundred with the round-half-up-at-halfway convention;
IDENTIFY/PLAN/EXECUTE/EVALUATE problem labels; figure grammar: an outlined
loop encloses exactly ten counters.

## Front-by-front audit

Cards listed in scheduled order.

1. `4fb884a8` — Q, addition bridge (4 + 2).
   Dependencies: quantity (inbound); joining as everyday word (self, grounded
   in melons/crates example); addition, `+`, "plus", `=`, "equals", sum, total
   (self: all defined on this front before the task).
2. `76250e53` — Q, part–whole diagram figure (6 and 3, whole unknown).
   Dependencies: part–whole diagram, part, whole, `?`-marks-the-unknown
   convention (self); sum (earlier: card 1); figure alt text uses only
   box/numeral language (inbound/self). Answer not leaked by figure: whole
   box shows `?`.
3. `af2ffc94` — Q, operation defined; choose operation for 12 + 5.
   Dependencies: operation (self); addition, total (earlier: card 1).
4. `d8c5b8c0` — P, analyzed 32 + 45.
   Front dependencies: joining context only (earlier: cards 1, 3). Solution
   uses place value, rounding/estimate, IPEE labels (inbound); place-by-place
   addition is taught by this card's PLAN/EXECUTE (self).
5. `4f183af4` — Q, open number line figure (34 + 23).
   Dependencies: number line, rightward growth, tens/ones (inbound); jump
   (self: defined on front); sum (earlier: card 1); landing mark labeled `?`
   (convention from card 2). Figure shows +20 and +3 with proportional
   lengths; answer 57 not shown.
6. `7430e7b3` — Q, column alignment for 46 + 31.
   Dependencies: column (self: defined on front); digit, place (inbound);
   sum (earlier: card 1). The fenced layout is display, not a new notation
   beyond stacking numerals.
7. `6899fbee` — Q, regrouping exchange figure (12 ones).
   Dependencies: ones/tens places, digit capacity of a place (inbound);
   regrouping, equal-value exchange (self); loop-of-ten figure grammar
   (inbound, and restated on the front). Figure shows 12 ones ↔ 1 ten +
   2 ones with a "same quantity" arrow; the written tens/ones digits asked
   for are not printed in the figure.
8. `c6a1c8c2` — P, completion 38 + 27 (ones step supplied).
   Front dependencies: regrouping exchange (earlier: card 7); ones (inbound);
   supplied premise 8 + 7 = 15 uses established addition (card 1). Solution's
   "carry" is introduced there in apposition to "the exchanged ten" (self).
9. `fd3fab76` — Q, subtraction bridge (9 − 4).
   Dependencies: removal as everyday word (self, grounded in plums example);
   subtraction, `-`, "minus", difference (self: defined on front).
10. `7a94c9d8` — Q, choose operation for 17 − 6.
    Dependencies: operation (earlier: card 3); addition (card 1); subtraction
    (earlier: card 9).
11. `2f56a072` — Q, comparison meaning (12 − 8).
    Dependencies: comparison sense of subtraction (self: defined on front);
    difference (earlier: card 9); "how many more" comparison language
    (inbound: Chapter 1 comparison).
12. `6c3bc458` — Q, unknown part (15 − 9).
    Dependencies: part–whole diagram, part, whole (earlier: card 2);
    subtraction, removal (earlier: card 9); missing-part-by-subtraction
    (self: derived on front from part–whole meaning).
13. `f172bd4d` — Q, inverse operations; check 28 + 14 = 42.
    Dependencies: addition/sum (card 1); subtraction (card 9); inverse
    operations and the check-addition-by-subtraction procedure (self:
    defined and exemplified on front).
14. `9342d310` — Q, place-by-place subtraction 68 − 25.
    Dependencies: tens/ones (inbound); place-by-place structure bridged by
    explicit analogy to place-value addition (earlier: cards 4, 6);
    subtraction (card 9). No regrouping needed (8 ≥ 5, 6 ≥ 2).
15. `a8b241dc` — Q, exchange in the other direction (52 for 52 − 28).
    Dependencies: place-by-place removal (earlier: card 14); regrouping
    exchange and its equal-value property (earlier: card 7; reverse
    direction stated on front, self); whole numbers (inbound); figure
    grammar restated (inbound/card 7). Figure is the same equal-value
    exchange; the regrouped form of 52 asked for is not shown.
16. `086c4e5d` — Q, inverse check of a subtraction (71 − 35 = 36).
    Dependencies: inverse relationship (earlier: card 13); the
    subtraction-checked-by-addition direction (self: derived on front from
    removal splitting the start); difference (card 9).
17. `bbcd0ffb` — P, independent 63 − 47 with inverse check.
    Front dependencies: removal context (card 9); "inverse operation" check
    request (earlier: cards 13 and 16 — the addition-rebuilds-the-start
    procedure is established before this independent use). Solution uses
    exchange (card 15), place-by-place removal (card 14), IPEE (inbound).
18. `f90e3dec` — Q, estimate rejects 487 + 305 = 912.
    Dependencies: rounding to nearest hundred, estimate vs. exact (inbound);
    addition/sum (card 1). The front supplies the rounded values; judging
    the claim against the estimate is the retrieved skill.
19. `a7302adb` — Q, remainder bound rejects 45 − 28 = 63.
    Dependencies: removal (card 9); `>` comparison (inbound); the
    difference-below-start bound (self: stated on front before the task).
20. `6f487817` — Q, column misalignment 46 + 3 = 76.
    Dependencies: columns and why alignment matters (earlier: card 6);
    tens/ones values of digits (inbound).
21. `03f8ffe4` — Q, smaller-from-larger bug 74 − 38 = 44.
    Dependencies: place-by-place removal (card 14); exchange for
    insufficient ones (card 15); order of removal is not swappable (self:
    the front presents the flawed reasoning as the object of diagnosis).
22. `d860f755` — Q, compensation 48 + 26.
    Dependencies: compensation (self: defined and exemplified with 29 + 15
    on front); total, joined parts (card 1); tens-ending-in-0 ease
    (inbound place value).
23. `83ab255e` — P, mixed two-step 94 − 38 then + 25.
    Front dependencies: operation choice (cards 3, 10); removal and joining
    (cards 1, 9); estimate request (inbound). Solution uses exchange
    (card 15), regrouping in addition (card 7), rounding with the half-up
    convention for 25 → 30 (inbound), IPEE (inbound). The estimate is two
    separate one-operation equations; no operation-order convention is used.

## Boundary checks

- No later-chapter material on any front or answer: no multiplication or
  division language ("groups of ten" is Chapter 1 place-value language), no
  money or measurement units (all contexts are counts of discrete objects),
  no fractions, decimals, signed numbers, or letter variables (`?` marks
  every unknown), and no operation-order conventions (multi-step work is
  written as separate equations).
- Sequencing fix applied during this audit: the explanation card
  `086c4e5d` (addition checks a subtraction) was moved ahead of the
  independent problem `bbcd0ffb`, which asks the learner to perform
  that check. IDs and retrieval targets unchanged.
- All arithmetic on cards was re-derived during the scan: 4+2=6, 6+3=9,
  12+5=17, 32+45=77 (est. 30+50=80), 34+23=57, 12 ones = 1 ten 2 ones,
  38+27=65 (est. 40+30=70), 9−4=5, 17−6=11, 12−8=4, 15−9=6, 28+14=42,
  42−14=28, 68−25=43, 52 = 4 tens 12 ones, 71−35=36, 36+35=71, 63−47=16,
  16+47=63, 487+305=792 (est. 800), 45−28=17, 46+3=49, 46+30=76, 74−38=36,
  29+15=30+14=44, 48+26=50+24=74, 94−38=56, 56+25=81 (est. 90−40=50,
  50+30=80). Every halfway rounding (45, 25) rounds up, per the Chapter 1
  convention.
- Figures: three original TikZ sources compiled to SVG with `viewBox`,
  `<title>`, and `<desc>`; inspected at phone width; no front figure prints
  the answer its card asks for.

## Result

cold_start_status: pass
unresolved_dependencies: 0
