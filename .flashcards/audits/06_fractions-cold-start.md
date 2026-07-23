# Chapter 6 cold-start audit — `flashcards/06_fractions.md`

Audit date: 2026-07-23. Isolated fresh-agent regeneration; the previous
implementation was intentionally blanked and was not consulted.

## 1. Frozen learner contract

Resolved closure (`.flashcards/prerequisites/graph.json`, edge mode
`explicit`, target `06_fractions`):

- Direct local prerequisite with complete scheduled cards:
  `05_signed_quantities` — signed-number, signed-number-line,
  opposite-number, absolute-distance, signed-addition, signed-subtraction.
- Transitive local prerequisites reduced to validator-resolved capability
  summaries:
  - `01_quantities_and_whole_numbers`: quantity, whole-number, place-value,
    whole-number-line, whole-number-comparison, rounding-whole-numbers.
  - `02_addition_and_subtraction`: whole-number-addition,
    whole-number-subtraction, inverse-operation-check,
    whole-number-regrouping.
  - `03_multiplication_and_division`: whole-number-multiplication,
    whole-number-division, division-remainder, array-representation.
  - `04_operation_structure_and_factors`: arithmetic-expression,
    operation-order, factor-and-multiple, prime-and-composite,
    whole-number-power.
- External deck closure: none. Assumed tools: none.

Everything else is treated as unseen. Because Chapters 1–4 arrive only as
capability summaries, compound terms not certain to be established there
(notably "common factor" and "common multiple") are re-bridged in one
clause at first use rather than assumed.

Frozen concept frontier at chapter start: whole numbers and place value;
the number line including negative positions, equal spacing, opposites,
and distance from zero; comparison with \(<\) and \(>\); the four
whole-number operations with symbols \(+\), \(-\), \(\times\), \(\div\);
inverse-operation checks; division with remainder; equal-groups and array
pictures; grouping marks in expressions; factors and multiples; signed
addition and subtraction. No fraction vocabulary, notation, or procedure
is inbound.

## 2. Chapter dependency ledger

| Concept, symbol, or representation | Required on which front? | Allowed inbound source or earlier establishment | First supported retrieval | Later application | Status |
|---|---|---|---|---|---|
| Equal parts of a whole; part names (halves…fifths) | 01 | Explained on Front 01 | Front 01 (read strip) | 02–05, 09, 11, 24, 26 | established |
| Fraction notation \(\frac{a}{b}\); numerator; denominator; unit fraction | 01 | Explained on Front 01 | Front 03 (roles) | whole chapter | established |
| Equal-parts requirement | 02 | Front 01 definition; misconception repaired on 02 | Front 02 | 11 (equal-length strips) | established |
| Unit-fraction size vs denominator | 04 | Explained on Front 04 | Front 04 | 16 (same-numerator compare), 26 | established |
| Fractions as number-line points | 05 | Front 05 extends inbound whole/signed number line | Front 05 (read dot) | 07, 15, 21 | established |
| \(\frac{n}{n}=1\) | 06 | Explained on Front 06 | Front 06 | 09 (four fourths remake a whole), 26 | established |
| Opposite of a fraction | 07 | Ch. 5 opposites + Front 05 positions | Front 07 | none in this chapter (kept alive for Ch. 7+) | established |
| Fraction as division \(a \div b = \frac{a}{b}\) | 08 (P1), 09 | Analyzed sharing problem P1 (Front 08) | Front 09 (both directions) | 10 (remainder conversion), 31 | established |
| Improper fraction; mixed number | 10 | Explained on Front 10 via inbound division-remainder | Front 10 (convert 11/4) | Front 11 (reverse) | established |
| Mixed → single fraction | 11 | Explained on Front 11 | Front 11 (convert 3 1/5) | none (intentional; operations stay in fraction form) | established |
| Equivalent fractions | 12 | Explained on Front 12 with strips figure | Front 12 (read 3/6) | 13–15, 18–20, 23, P3, P6 | established |
| Scaling rule (multiply both numbers) | 13 | Explained on Front 13 | Front 13 (2/5 = 8/20) | P2, 18, 23, P3, P6 | established |
| Common factor (re-bridged); simplest form | 14 | One-clause bridge + definition on Front 14 | Front 14 (simplify 12/18) | 21 (simplify result), P2 check | established |
| Same-denominator comparison | 16 | Explained on Front 16 | Front 16 | 22 (reasonableness), P6 | established |
| Same-numerator comparison | 17 | Front 04 part-size idea | Front 17 | P6 (method inventory) | established |
| Common denominator; common multiple (re-bridged) | 18 | Explained on Front 18 | Front 18 (rename to 15ths) | 20, 22–24, P3, P6 | established |
| Benchmark \(\frac{1}{2}\) | 19 | Explained on Front 19 | Front 19 | 33 (estimation), P6 | established |
| Add-1-to-both misconception | 20 | Diagnosed on Front 20 using 18's method | Front 20 | — | established |
| Same-denominator add/subtract | 21 | Explained on Front 21 | Front 21 (7/10 − 3/10) | 22–24, P3 | established |
| Add-tops-add-bottoms misconception | 22 | Diagnosed on Front 22 via benchmark reasonableness | Front 22 | — | established |
| Unlike-denominator add/subtract | 23 | Explained on Front 23 | Front 23 (complete 1/2 + 1/3) | P3 (faded) | established |
| Fraction of a quantity (denominator groups, numerator taken) | 25 | Explained on Front 25 with set figure; uses inbound ÷ and × | Front 25 (3/4 of 12) | 26, P4 | established |
| \(\times\) as "of" | 26 | Explained on Front 26 | Front 26 (2/5 × 30) | P4, 28–29 | established |
| Fraction × fraction rule | 28 | Explained on Front 28 (part-of-a-part recut) | Front 28 (2/3 × 4/5) | 32 (P5 check), P6 evaluate | established |
| Multiplying-shrinks insight | 29 | Diagnosed on Front 29 | Front 29 | 30 (dividing grows) | established |
| Division by a fraction as how-many-groups | 30 | Explained on Front 30 with figure; inbound grouping division | Front 30 (3 ÷ 1/4) | 31, P5 | established |
| Reciprocal; multiply-by-reciprocal rule | 31 | Explained and derived on Front 31 | Front 31 (9 ÷ 3/4) | P5 | established |
| Benchmark estimation of sums | 33 | Front 19 benchmarks extended on Front 33 | Front 33 | — | established |

No row is blocked. No front borrows Chapter 7+ vocabulary (no decimals,
percents, ratios, rates, or measurement units appear anywhere, including
problem contexts, figures, and alt text).

## 3. Front-by-front simulation

Fronts numbered in file order (34 scheduled cards: 28 `Q:/A:`, 6 `P:/S:`).
For each front, the dependency list was completed before the answer was
inspected.

1. **equal parts / notation (fig equal_parts).** Needs: whole numbers,
   counting, "cut into parts" (everyday). All fraction terms are defined
   on this front; the figure's grammar (strip, vertical dividers, hatch
   shading) is described in the prompt and alt text. Attempt possible:
   count 5 parts, 3 shaded. OK.
2. **unequal pieces.** Needs Front 01's equal-parts definition. OK.
3. **window panes.** Supported retrieval of Front 01 roles. OK.
4. **1/3 vs 1/8.** Needs Front 01 naming; comparison language inbound. OK.
5. **number line (fig fraction_line).** Needs inbound number-line marks and
   equal spacing (Ch. 1/5); partition recipe taught on this front. OK.
6. **n/n = 1.** Needs Fronts 01, 05. OK.
7. **opposite of 3/4.** Needs Ch. 5 opposites/distance (complete cards
   available) and Front 05. OK.
8. **P1 sharing bars.** Needs whole-number division and remainder (Ch. 3
   summary capability), Front 01 fourths. Fraction-as-division is the
   problem's own discovery, fully worked (analyzed example). OK.
9. **a ÷ b both directions.** Needs P1's established relation, stated again
   on the front. OK.
10. **improper → mixed.** Needs Front 06 (4/4 remakes a whole) and inbound
    division-remainder; both notations defined here. OK.
11. **mixed → improper.** Needs Front 10 notation; counting parts via
    inbound multiplication. OK.
12. **equivalence (fig equivalence_strips).** Needs Front 01 part names
    ("halves/fourths/sixths" label the strips), Front 02 equal parts;
    "equivalent" defined here; dashed-guide grammar described on the
    front. OK.
13. **scaling rule.** Needs Front 12; sliver story told here; inbound
    multiplication. OK.
14. **simplest form.** Needs Front 13 reverse direction; "common factor"
    re-bridged in one clause (factor itself inbound from Ch. 4). OK.
15. **P2 completion 3/4 = ?/12.** Needs Front 13 rule; plan supplied. OK.
16. **same-denominator compare.** Needs Front 01; inbound comparison and
    number line. OK.
17. **same-numerator compare.** Needs Front 04 part size. OK.
18. **common denominator.** Needs Front 13 renaming; "common multiple"
    re-bridged in one clause (multiple inbound from Ch. 4). OK.
19. **benchmark 1/2.** Needs Front 13 (renaming 1/2 as 4/8, 3/6) and
    Front 16; "benchmark" defined here. OK.
20. **add-1 misconception.** Needs Fronts 13, 18. OK.
21. **same-denominator add/subtract.** Needs Front 01 counting parts,
    inbound +/−; Front 14 for simplest-form answer. OK.
22. **2/5 misconception.** Needs Fronts 18–19 (rename 2/5 and 1/2 to
    tenths, more-than-half reasoning); "reasonableness check" carried by
    the deck since Ch. 1 (estimation capability) and restated in plain
    language. OK.
23. **unlike-denominator addition.** Needs Fronts 18, 21; renames supplied,
    learner completes. OK.
24. **P3 faded 5/6 − 1/4.** Needs Fronts 18, 21, 23; inverse-check habit
    inbound (Ch. 2). OK.
25. **fraction of a set (fig fraction_of_set).** Needs Front 01 roles,
    inbound equal-groups division and multiplication; figure grammar
    (dashed rings = groups) described on the front. OK.
26. **× as "of".** Needs Front 25 procedure; × symbol inbound. OK.
27. **P4 wins 2/3 of 24.** Needs Fronts 25–26; evaluation uses inbound
    subtraction and Front 19 half-benchmark. OK.
28. **fraction × fraction.** Needs Fronts 01, 25–26; recut story told
    here. OK.
29. **1/2 × 8 misconception.** Needs Front 26 meaning of ×. OK.
30. **how many fourths in 3 (fig fraction_groups).** Needs inbound
    how-many-groups division (Ch. 3), Fronts 01, 06; the \(\frac{1}{4}\)
    label on the figure is setup, not the answer (the answer is 12). OK.
31. **reciprocal rule.** Needs Front 30; derivation on the front uses only
    inbound thirds counting; "reciprocal" defined here. OK.
32. **P5 pizzas.** Needs Fronts 30–31. Serving counts avoid measurement
    units. OK.
33. **estimation 7/8 + 11/12.** Needs Fronts 19, 21 (missing-part idea);
    asks for nearest whole number, defined by inbound rounding sense. OK.
34. **P6 method choice 5/8 vs 2/3.** Needs Fronts 16–19 (method
    inventory); the point of the card is discriminating among them. OK.

Answer-side scan for terms later fronts assume: every term introduced in
an answer ("quarters" as a synonym for fourths on Fronts 08/30/31 — used
after fourths are established; "recut" plain language) is either defined
at first use on a front or ordinary language with no technical load.
Figure alt texts use only established grammar and never state the
requested value.

## 4. Repairs made during the scan

- "Common factor" and "common multiple" were initially used bare on
  Fronts 14 and 18; because Chapters 1–4 arrive only as capability
  summaries, both got a one-clause bridge at first use (repair type 2:
  minimal explanatory context).
- Rejected while drafting (repair type 1, recorded in `CARD_README.md`):
  money, length/mass/volume/time units, temperatures, and recipe
  measures as contexts (units belong to Chapter 10, decimals to
  Chapter 7); ratio-language phrasings of comparison; decimal names for
  benchmark values; letter placeholders in the completion problem (a `?`
  is used instead).

## 5. Verification

All arithmetic verified by direct derivation: 11/4 = 2 r 3; 3·5+1 = 16;
12/18 ÷ 6 = 2/3; 2/3 = 10/15 vs 3/5 = 9/15; 2/5 = 12/30 vs 3/6 = 15/30;
7/10 − 3/10 = 4/10 = 2/5; 1/2 + 1/3 = 5/6; 5/6 − 1/4 = 10/12 − 3/12 =
7/12 (restored by adding 3/12); 3/4 of 12 = 9; 2/5 × 30 = 12; 2/3 of
24 = 16; 2/3 × 4/5 = 8/15; 3 ÷ 1/4 = 12; 9 ÷ 3/4 = 12 (12 × 3/4 = 9);
6 ÷ 2/3 = 9 (9 × 2/3 = 6); 7/8 + 11/12 = 43/24, just under 2;
5/8 = 15/24 < 16/24 = 2/3.

Figures inspected as rendered SVG rasters at phone-like width: geometry,
equal spacing, hatching (non-color cue), labels, and dashed guides are
correct; no front figure displays its requested value.

cold_start_status: pass
unresolved_dependencies: 0
