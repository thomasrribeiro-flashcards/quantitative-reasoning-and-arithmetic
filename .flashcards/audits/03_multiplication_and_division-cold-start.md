# Cold-start audit — 03_multiplication_and_division

- Date: 2026-07-23
- Auditor: authoring agent (claude-fable-5), isolated fresh-agent regeneration
- Method: the chapter design ledger and concept-dependency ledger below were
  frozen before card drafting. After drafting, every scheduled front (Q: or P:
  block, including figure alt text and supplied premises) was scanned in
  intended first-learning order for domain-bearing terms, symbols,
  representations, and procedures, and each dependency was recorded before the
  answer was consulted. Each resolves to one of: **inbound** (Chapter 1 or 2
  scheduled cards, per the machine-resolved closure), **earlier** (established
  by a scheduled Chapter 3 card that precedes it), or **self** (defined on the
  same front before first use, using only established language).
- Inbound closure: `chapter:02_addition_and_subtraction`, whose own closure
  includes `chapter:01_quantities_and_whole_numbers`. No external decks, no
  assumed tools. No other chapter is inbound; explicit edges are in force.

## Inbound frontier (Chapters 1–2)

From Chapter 1: quantity and numeral; counting; zero; whole numbers; digits;
place value (ones, tens, hundreds); placeholder zero; number line with
rightward growth; comparison symbols `<` and `>`; exact value vs. estimate;
rounding to the nearest ten or hundred with the round-half-up-at-halfway
convention; IDENTIFY/PLAN/EXECUTE/EVALUATE problem labels; figure grammar: an
outlined loop encloses a stated group (exactly ten in Chapters 1–2).

From Chapter 2: addition, `+`, `=`, sum/total; part–whole diagram; operation;
number-line jumps; column alignment of digits; regrouping as an equal-value
exchange; subtraction, `-`, difference; removal, comparison, and unknown-part
meanings; inverse operations and inverse checks; place-by-place computation;
estimate, bound, and alignment error diagnosis; compensation.

## Chapter design ledger (frozen before drafting)

Retrieval targets → card forms, in scheduled order:

| # | Form | Target | Numbers |
|---|---|---|---|
| 1 | Q | Equal groups; multiplication; `×`; factor; product; groups-first reading convention (teaching bridge, supported translation; total supplied) | 4×6=24 example; 3×8=24 task |
| 2 | Q | Multiplication computed as repeated addition | 4×6 → 6+6+6+6=24 |
| 3 | Q | Array grammar (rows, columns); array → multiplication translation (figure 1) | 3 rows of 5 → 15 |
| 4 | Q | Order of factors leaves the product unchanged (turned array) | 3×5 = 5×3 |
| 5 | Q | Edge cases from meaning: ×1 and ×0 | 6×1, 6×0 |
| 6 | Q | Multiplying by ten via place value | 7×10=70 |
| 7 | Q | Split a two-digit factor; partial products joined by addition | 3×24=72 |
| 8 | Q | Diagnose forgotten ones partial product | 4×27≠87; =108 |
| 9 | P | Analyzed IPEE: equal-rows product via partial products; repeated-addition and bound checks | 6×14=84 |
| 10 | Q | Division; sharing meaning; `÷`; quotient (teaching bridge, supported translation) | 15÷5=3 |
| 11 | Q | Grouping meaning; same statement answers two questions (figure 2) | 12÷3=4 |
| 12 | Q | Discriminate sharing vs. grouping in word situations | 20÷5=4 |
| 13 | Q | Division and multiplication as inverse operations; find/check a quotient | 42÷6=7 |
| 14 | Q | Why dividing by zero has no answer; contrast 0÷n | 8÷0; 0÷8 |
| 15 | Q | Remainder; division-with-remainder notation (figure 3) | 14÷4=3 r 2 |
| 16 | Q | Diagnose an oversized remainder; rebuild-and-bound check | 17÷5=3 r 2 |
| 17 | Q | Interpret a remainder in context (one more group needed) | 26÷4 → 7 boats |
| 18 | P | Completion: quotient and remainder from a supplied start | 53÷8=6 r 5 |
| 19 | P | Independent grouping division by building up groups | 72÷6=12 |
| 20 | Q | Mixed discrimination: addition vs. multiplication cue | 18+3 vs 3×18 |
| 21 | P | Mixed: choose operations, execute, interpret remainder, check | 90 tulips, vases of 12 |

Problem progression: analyzed (9) → completion (18) → independent (19) →
mixed (21), per the deck blueprint. Clozes: none — no exact, compact,
already-understood target exists before these meanings are first built
(consistent with the deck-wide zero-cloze plan).

Figure opportunities (assessed by retrieval role):

- **Included — `equal_groups_array`**: rows/columns are a genuinely spatial
  grammar; translating the array to a multiplication statement is the
  retrieval decision (front shows the array, not the product).
- **Included — `sharing_vs_grouping`**: the two division meanings differ only
  in what is fixed (number of groups vs. size of groups); two arrangements of
  the same 12 counters make that structural contrast inspectable.
- **Included — `remainder_groups`**: an incomplete final group is a spatial
  fact; reading full groups and leftovers off the picture and assembling the
  statement is the decision.
- **Omitted — multiplication table / fact chart**: leaks the very products the
  learner should reconstruct, and rote-fact drill is outside the smallest
  sufficient set.
- **Omitted — number-line jump picture for repeated addition**: Chapter 2's
  open-number-line grammar already covers rightward jumps; words suffice and a
  figure would add no new retrieval decision.
- **Omitted — turned-array second figure for card 4**: the rotation is
  described in one sentence about the card-3 array; a second drawing would
  reveal the equality it asks the learner to reason out.

## Concept-dependency ledger

| Concept, symbol, or representation | Required on front(s) | Inbound source or first establishment | First supported retrieval | Later application | Status |
|---|---|---|---|---|---|
| Equal groups | 1–5, 9–12, 15 | Front 1 defines separate groups holding exactly the same quantity | Front 1 translation | All products, quotients, remainders | established |
| Multiplication, `×`, "times" | 1 onward | Front 1 defines the operation and symbol on a supplied-total example | Front 1 writes 3×8=24 | Every later product and inverse check | established |
| Factor, product | 1 onward | Front 1 names both on the worked example | Front 1 names them for 3×8 | Order property (4), partial products (7–9) | established |
| Groups-first reading (first factor counts groups) | 1, 3, 5, 6 | Front 1 states the deck convention | Front 3 applies it to rows | Fronts 5–9, all problem cards | established |
| Repeated addition computes a product | 2, 9 | Front 2 shows 3 groups of 7 as 7+7+7 | Front 2 computes 4×6 | EVALUATE check in problem 9 | established |
| Array, row, column | 3–4, 9 | Front 3 defines rows/columns on the figure (column bridged from Ch. 2 digit columns) | Front 3 translates the array | Front 4 order property; problem 9 rows context | established |
| Order of factors (commutativity) | 4 | Front 4 derives it from turning the card-3 array | Front 4 explains equality | Fact reuse in later quotient searches | established |
| ×1 and ×0 | 5 | Front 5 asks for both directly from the front-1 meaning | Front 5 | Zero/one boundary sense throughout | established |
| Multiplying by ten | 6, 9, 19, 21 | Front 6 links "groups of ten" to the Ch. 1 tens place | Front 6 | Partial products (7–9), build-up division (19, 21) | established |
| Partial products (split, multiply, join) | 7–9, 20–21 | Front 7 teaches split-into-tens-and-ones with separate equations | Front 7 computes 3×24 | Diagnosis 8; problems 9, 21 | established |
| Division, `÷`, "divided by", quotient | 10 onward | Front 10 defines the operation, symbol, and result name on a sharing example | Front 10 writes 15÷5=3 | All quotients, remainders, checks | established |
| Sharing meaning (equal shares; deal one at a time) | 10–12 | Front 10 | Front 10 | Discrimination 12; mixed problem 21 | established |
| Grouping meaning (how many groups of a size) | 11–12, 15–19, 21 | Front 11 defines it against sharing on the two-panel figure | Front 11 states each panel's question | Remainders, build-up division, problem 21 | established |
| Loop-encloses-one-group figure grammar (this chapter) | 11, 15 | Restated on each figure front (Ch. 1–2 loops held exactly ten; here each loop is one group) | Front 11 reads the panels | Front 15 reads full groups | established |
| Division–multiplication inverse | 13–16, 18–19, 21 | Front 13 defines it by analogy to the Ch. 2 addition–subtraction inverse | Front 13 finds 42÷6 | Rebuild checks on 16, 18, 19, 21 | established |
| Undefined (division by zero has no answer) | 14 | Front 14 derives it from the inverse relationship | Front 14 | Boundary sense for later fraction work (outside this chapter) | established |
| Remainder; "3 remainder 2" notation | 15–19, 21 | Front 15 defines leftover-below-group-size on a prose example, then the figure | Front 15 writes 14÷4=3 r 2 | Diagnosis 16, interpretation 17, problems 18–19, 21 | established |
| Remainder bound and rebuild check | 16, 18–19, 21 | Front 16 derives the bound from "as many full groups as possible"; rebuild check shown on the same front | Front 16 corrects 17÷5 | Problems 18, 19, 21 EVALUATE steps | established |
| Remainder interpretation (extra group needed) | 17, 21 | Front 17 poses the booked-boats decision with the division supplied | Front 17 | Mixed problem 21 | established |
| Build-up method for larger quotients | 18–19, 21 | Problem 18's supplied start models multiply-and-subtract; problem 19's PLAN names build-up from ten groups | Problem 18 completion | Problems 19 and 21 | established |
| Addition-vs-multiplication cue ("3 more" vs. "each/every") | 20–21 | Front 20 presents the paired situations and asks for the decisive cue | Front 20 | Mixed problem 21 | established |

## Front-by-front audit

Cards listed in scheduled order. (Completed after drafting; see below.)

1. `e3f6f26a` — Q, equal groups and multiplication bridge (3×8, total supplied).
   Dependencies: quantity, counting confirmation (inbound); group as everyday
   word grounded in candle-box example (self); equal groups, multiplication,
   `×`, "times", factor, product, groups-first convention (self: all defined
   on this front before the task). The task's total 24 is supplied, so no
   uncomputable step is required.
2. `9a2e6f6b` — Q, repeated addition for 4×6.
   Dependencies: multiplication, factors, product, groups-first reading
   (earlier: card 1); addition and sum (inbound, Ch. 2); the
   group-size-added-once-per-group pattern (self: shown for 3×7 before the
   4×6 task).
3. `41f1b6dd` — Q, array figure translation.
   Dependencies: array, row, column (self: defined on front; "column" bridged
   explicitly from Ch. 2 digit columns); equal groups, multiplication
   statement, product (earlier: cards 1–2); figure grammar (self: arrows mark
   one row and one column; alt text uses only established words). Product 15
   not shown in figure or alt text.
4. `13cfae43` — Q, order of factors via the turned array.
   Dependencies: array, rows/columns (earlier: card 3); product, factors
   (earlier: card 1); counting invariance (inbound: quantity does not change
   when nothing is added or removed, Ch. 1–2 language).
5. `88e8b7fe` — Q, ×1 and ×0.
   Dependencies: equal-groups meaning and groups-first reading (earlier:
   card 1); zero as a count of none (inbound, Ch. 1).
6. `bd35b644` — Q, multiplying by ten.
   Dependencies: groups of ten and the tens place (inbound, Ch. 1);
   multiplication statement and groups-first reading (earlier: card 1).
7. `ff40656e` — Q, partial products for 3×24.
   Dependencies: place-value split of 24 (inbound, Ch. 1); multiplication and
   groups-first reading (card 1); multiplying by ten (earlier: card 6);
   joining partial results by addition as separate equations (inbound, Ch. 2;
   no operation-order convention used); the split-multiply-join method itself
   (self: stated on front).
8. `dbd7a1af` — Q, diagnosis of 4×27=87.
   Dependencies: partial products (earlier: card 7); the flawed reasoning is
   quoted as the object of diagnosis (self); addition check values (inbound).
9. `c9c9dfc4` — P, analyzed 6 rows of 14 chairs.
   Front dependencies: rows context (earlier: card 3); equal groups (card 1).
   Solution uses IPEE labels (inbound), partial products (card 7),
   repeated addition (card 2), and a more-than-6×10 bound using `>' comparison
   (inbound, Ch. 1; 6×10 from card 6).
10. `9c7bd4a7` — Q, division sharing bridge (15÷5).
    Dependencies: sharing/dealing as everyday actions grounded in the cracker
    example (self); division, `÷`, "divided by", quotient (self: defined on
    front); equal groups (earlier: card 1); multiplication check in answer
    (earlier: card 13 is later — the check appears only in the answer as
    5×3=15 with repeated addition fallback, both established by cards 1–2).
11. `6f0f6e35` — Q, grouping meaning on the two-panel figure.
    Dependencies: sharing meaning and quotient (earlier: card 10); grouping
    meaning (self: defined on front); loop-marks-one-group grammar for this
    figure (self: restated on front, replacing the Ch. 1–2 loop-of-ten);
    figure alt text uses only counters/loops/labels language (inbound/self).
    The visible 4s are setup for the meaning question, not the target.
12. `4a2c150b` — Q, sharing vs. grouping in words (20÷5).
    Dependencies: both meanings (earlier: cards 10–11); quotient (card 10).
13. `21f5b7c0` — Q, inverse operations find/check 42÷6.
    Dependencies: inverse operations concept (inbound, Ch. 2
    addition–subtraction; extended by explicit analogy, self); grouping
    meaning (earlier: card 11); multiplication rebuild (earlier: card 1).
14. `5f9be0d3` — Q, division by zero.
    Dependencies: inverse relationship (earlier: card 13); ×0 (earlier:
    card 5); sharing meaning for 0÷8 (earlier: card 10); "undefined" (self:
    introduced as the name for has-no-answer).
15. `8d264a3e` — Q, remainder figure (14÷4).
    Dependencies: grouping division (earlier: card 11); remainder and the
    "quotient remainder r" statement form (self: defined on a prose 7÷2
    example before the figure task); loop-marks-one-group grammar (earlier:
    card 11, restated); figure alt text describes loops and loose counters
    only — the assembled statement is the answer.
16. `2a7a2a29` — Q, oversized remainder diagnosis (17÷5).
    Dependencies: grouping-makes-as-many-full-groups-as-possible (earlier:
    card 11, restated on front); remainder notation (earlier: card 15);
    rebuild arithmetic supplied on front uses established multiplication and
    addition (cards 1, 7; inbound).
17. `03c090e4` — Q, remainder interpretation (26 hikers).
    Dependencies: division-with-remainder statement (earlier: card 15;
    the division result is supplied on the front); grouping meaning
    (card 11); the decision itself — whether leftover people need one more
    group — is the retrieval target.
18. `7f0891fb` — P, completion 53÷8 from a supplied start.
    Front dependencies: grouping division (card 11), remainder (card 15),
    multiplication fact supplied (6×8=48, established form); the completion
    steps need subtraction (inbound, Ch. 2) and the remainder bound
    (earlier: card 16).
19. `e355b0d2` — P, independent 72÷6.
    Front dependencies: grouping context only (cards 11, 15). Solution uses
    build-up via tens (cards 6, 18), subtraction (inbound), inverse check
    (card 13), IPEE (inbound).
20. `b0b9e2c7` — Q, addition vs. multiplication cue (18 and 3).
    Dependencies: addition choice (inbound, Ch. 2 operation choice);
    multiplication and equal-groups cue (earlier: cards 1, 3); the
    discrimination itself is the target.
21. `2e01e1a5` — P, mixed tulip-vase problem.
    Front dependencies: equal groups (card 1), capacity wording "each vase
    holds exactly 12" (established cue, card 20), enough/not-enough
    comparison (inbound, Ch. 1 `<`/`>` and Ch. 2 comparison). Solution uses
    multiplication with partial products (card 7), comparison (inbound),
    grouping division with remainder (cards 11, 15–16), the one-more-group
    interpretation (card 17), and an inverse-style capacity check (card 13).

## Boundary checks

- No later-chapter material on any front or answer: no operation-order
  conventions or mixed expressions (multi-step work is written as separate
  equations, matching the Chapter 2 precedent); no "factor of a number,"
  multiple, divisibility, prime, or power language (Chapter 4); no signed
  numbers, fractions (no "half," no fractional shares — every division
  context uses whole counts), decimals, money, or measurement units; no
  letter variables (`?` or prose marks unknowns); no long-division or
  bracket notation — every division is a `÷` statement.
- The word "remainder" is introduced here and does not collide with
  Chapter 2's "remaining amount" prose: front 15 defines it as the leftover
  count in a grouping division, below the group size.
- All arithmetic on cards was re-derived during the scan: 4×6=24 (6+6+6+6:
  6+6=12, 12+6=18, 18+6=24), 3×8=24, 3×7=21, 3×5=15=5×3, 6×1=6, 6×0=0,
  7×10=70, 3×24: 3×20=60, 3×4=12, 60+12=72; 4×27: 4×20=80, 4×7=28,
  80+28=108 (the flawed 80+7=87 rechecked); 6×14: 6×10=60, 6×4=24,
  60+24=84, bound 84>60, repeated addition 14,28,42,56,70,84; 15÷5=3
  (5×3=15); 12÷3=4 both meanings (3×4=12, 4×3=12); 20÷5=4 (5×4=20);
  42÷6=7 (7×6=42); 8×0=0 and no n with n×0=8; 0÷8=0; 7÷2=3 r 1 (3×2=6,
  6+1=7); 14÷4=3 r 2 (3×4=12, 12+2=14, 2<4); 17÷5: 2×5=10, 10+7=17 but
  7>5; correct 3×5=15, 15+2=17, 2<5; 26÷4=6 r 2 (6×4=24, 24+2=26), 7
  boats; 53÷8: 6×8=48, 53−48=5, 5<8, so 6 r 5; 72÷6: 10×6=60, 72−60=12,
  2×6=12, quotient 12, check 12×6=72; 18+3=21, 3×18: 3×10=30, 3×8=24,
  30+24=54; 90 tulips: 7×12=84, 84<90, 90−84=6, 6<12, so 90÷12=7 r 6,
  8 vases, check 8×12=96, 96>90.
- Figures: three original TikZ sources compiled to SVG with `viewBox`,
  `<title>`, and `<desc>`; inspected at phone width; no front figure prints
  the product, quotient, or statement its card asks for.

## Result

cold_start_status: pass
unresolved_dependencies: 0
