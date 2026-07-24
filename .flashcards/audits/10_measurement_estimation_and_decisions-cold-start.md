# Chapter 10 cold-start audit — measurement, estimation, and decisions

Date: 2026-07-23 (isolated fresh-agent regeneration)
Scope: `flashcards/10_measurement_estimation_and_decisions.md` (25 scheduled
cards: 20 basic, 0 cloze, 5 problems) and its three figures under
`figures/10_measurement_estimation_and_decisions/`.

## Frozen learner contract

Inbound knowledge is exactly the machine-resolved local closure (chapters
1–9 of this deck), no external decks, no assumed tools. Capabilities used
from the closure:

- Ch. 1: quantity, whole numbers, place value, number line, comparison,
  rounding to tens/hundreds, exact-versus-estimated amounts, one-by-one
  counting.
- Ch. 2: whole-number addition/subtraction, inverse-operation checks.
- Ch. 3: multiplication, division, remainders.
- Ch. 4: operation order in expressions (used in \(4 + 6 \times 0.1\)).
- Ch. 5: signed quantities (not needed by any Chapter 10 front).
- Ch. 6: fractions, fraction of a quantity (half of 60; a fifth of a
  liter; a quarter of 1000).
- Ch. 7: decimal place value, tenths/hundredths, trailing-zero numeric
  equality (4.3 = 4.30 as numbers), decimal operations including
  place-shift multiplication/division by 10/100/1000, decimal rounding,
  the half-up tie convention, money notation (dollars and cents), and
  decimal division by scaling both numbers by 10.
- Ch. 8: ratio, rate, "per," unit rate, better-buy comparison.
- Ch. 9 (direct prerequisite, full scheduled cards read): percent as per
  hundred, percent rate versus amount, discount and sale-price structure
  (discount = rate × original price; pay original minus discount).

Everything else — every unit name, prefix, scale-reading convention, and
precision idea — is treated as unseen and is established on scheduled
fronts inside this chapter.

## Concept-dependency ledger

| Concept, symbol, or representation | Required on front(s) | Inbound source or first explanation | First supported retrieval | Later application | Status |
|---|---|---|---|---|---|
| Measure, unit (repeated fixed amount) | 01 onward | Front 01 defines both with the paper-clip example | Front 01 classifies count vs measurement | Every later front | established |
| Agreed (standard) unit rationale | 02, 04–07, 20 | Front 02 explains why sizes must be shared | Front 02 diagnoses the hand-width mismatch | Unit identities 04–07; missing-unit critique 20 | established |
| Measurement as approximate nearest-unit report | 03, 08–10, 22 | Front 03 contrasts exact counts with between-marks positions | Front 03 explains the contrast | Precision (09), intervals (10–11), false precision (22) | established |
| Meter, centimeter, kilometer; centi-/kilo- prefixes | 04, 08–10, 12–13, 15–16, 18, 20, 22 | Front 04 defines all three with benchmarks (door handle, fingernail, city blocks) | Front 04 chooses km for town distances | Scale reading, conversions, problems | established |
| Gram, kilogram, mass | 05, 14, 19 | Front 05 defines with paper-clip/textbook benchmarks; "how heavy" is a labeled simplification (mass–weight deferred) | Front 05 chooses g for an apple | Conversion 14; kind-mismatch 19 | established |
| Liter, milliliter, capacity; milli- prefix | 06, 19, 21, 24 | Front 06 defines with bottle/spoon benchmarks | Front 06 chooses mL for a medicine dose | Reasonableness 21; better-buy P24 | established |
| Second, minute, hour; 60-based structure | 07, 17 | Front 07 states 60 s = 1 min, 60 min = 1 h and contrasts with the tens pattern | Front 07 computes minutes in 2 h | Diagnosis 17 (1.5 h) | established |
| Instrument scale, labeled marks, small steps, pointer reading | 08, P12 | Front 08 states the ruler grammar on the front with the figure | Front 08 reads arrow A at a labeled mark | P12 reads arrow B between marks (faded) | established |
| Precision claimed by last written place | 09, 22 | Front 09 defines precision and the report-versus-number distinction | Front 09 compares 4.3 cm with 4.30 cm | False-precision critique 22 | established |
| Rounded-value interval (continuous) | 10, P23 | Front 10 defines the band on the figure and restates the half-up tie rule | Front 10 reads the band edges (5.5, under 6.5) | Count version 11; propagation P23 | established |
| Rounded-value interval (whole counts) | 11, P23 | Front 11 extends the interval idea to counted people | Front 11 finds 65–74 for "70" | P23 adds two intervals | established |
| Converting; smaller-unit-multiplies, bigger-unit-divides | 13–19, P16, P24 | Front 13 defines conversion and the multiply direction as a "per" rate; Front 14 the divide direction | Fronts 13–14 convert one value each | Map 15, problems P16/P24, additions 18 | established |
| Conversion map grammar (aligned zeros, dashed pairing guides) | 15 | Stated on Front 15's own front with the figure | Front 15 completes the 2.5 km pairing | Reinforces both conversion directions | established |
| Same-kind versus different-kind quantities | 18–19 | Front 18 shows same-kind different-unit addition; Front 19 shows kinds that no conversion links | Fronts 18–19 each make one decision | Unit checks in P16/P24 | established |
| Benchmark reasonableness, missing unit, false precision | 20–22 | Each front states its own critique structure using established benchmarks | One decision per front | Mixed decisions P23–P25 | established |
| Unit price per liter | P24 | Ch. 8 unit rate + Ch. 7 money, combined with Front 06/14 conversions | P24 executes the comparison | — | established |
| Percent-discount structure reuse | P25 | Ch. 9 scheduled cards (discount = rate × original; pay original minus discount) | P25 identifies the missing whole | — | established |

## Front-by-front scan

Fronts were read in file order; each front's dependency list was completed
before its answer was inspected.

| Front (card-id prefix) | New or required knowledge on the front | Source | Finding |
|---|---|---|---|
| 01 f6f33461 | measure, unit; counting | defined here; Ch. 1 | ok |
| 02 d4bee79f | unit size vs amount | Front 01 | ok |
| 03 36eee8dc | exact count vs approximate measurement | Front 01; Ch. 1 counting | ok |
| 04 c5515974 | meter, cm, km, centi-, kilo-, \(\frac{1}{100}\) | defined here; Ch. 6 fractions | repaired: "12-minute walk" benchmark used time units before Front 07 — replaced with "ten city blocks" |
| 05 0a088403 | gram, kilogram, mass | defined here; kilo- from 04 | ok (mass-as-heaviness noted as labeled simplification) |
| 06 3546f4b7 | liter, milliliter, capacity, milli- | defined here; Ch. 6 fractions | ok |
| 07 00f2d833 | second, minute, hour; 60-base | defined here; Ch. 3 multiplication | ok |
| 08 834d7c5a | scale grammar; tenths | defined here on front; Ch. 7 decimals | ok |
| 09 75dba8aa | precision; 4.3 = 4.30 numerically | defined here; Ch. 7 trailing zeros | ok |
| 10 735cdd77 | rounded-value interval; half-up tie rule | defined here; rule restated on front; Ch. 7 rounding | ok |
| 11 04d508cc | interval for counts | Front 10; Ch. 1 rounding | ok |
| P12 3ccc72bf | scale reading, decimal combination | Front 08; Ch. 7; Ch. 4 operation order in \(4 + 6 \times 0.1\) | ok (plan supplied — faded, not independent) |
| 13 1003ac79 | converting; "per" rate; ×100 | defined here; Ch. 8 rate; Ch. 3 | ok |
| 14 1f414364 | ÷1000, digit shift | Front 13 direction logic; Ch. 7 place shift | ok |
| 15 46ff9e28 | conversion-map grammar | stated on front; km/m from 04 | ok |
| P16 14dbea81 | mixed-unit division problem | Fronts 04/13; Ch. 3 division; Ch. 8 "per piece" | ok |
| 17 871bf06e | 1.5 h diagnosis | Front 07; Ch. 7 decimals; Ch. 6 half of 60 | ok |
| 18 558503c8 | mixed-unit addition | Front 13; Ch. 2 addition | ok |
| 19 8ed87671 | different kinds cannot add | Fronts 05/06/13 | ok |
| 20 7284eb81 | missing unit critique | Fronts 01–02; everyday spatial benchmarks | ok |
| 21 295dc28d | bathtub reasonableness | Front 06 benchmark; Ch. 6 fifth | ok |
| 22 29f3e053 | false precision | Fronts 09/13; Ch. 1 estimates | ok |
| P23 4d10c895 | interval propagation | Fronts 10–11; Ch. 2 addition | repaired: EVALUATE deviation bound corrected from 8 to 10 (low side 110 − 100) |
| P24 2cfa2a2e | better buy across units | Fronts 06/14; Ch. 8 unit rate/better buy; Ch. 7 money and scaled division | ok |
| P25 f5e044d4 | percent discount, missing whole | Ch. 9 scheduled discount cards; Front 20's missing-information stance | repaired: solution originally used the untaught complement shortcut "pay 0.75 times it" — rephrased to the Ch. 9 subtract-the-discount structure |

Answer-side scan: no answer introduces a term that a later front assumes
without its own establishment. Figure alt texts were scanned; none names an
unestablished unit or leaks a graded value (arrow positions, band edges,
and the map's missing meter value are described positionally only).

## Arithmetic verification (direct derivation)

\(2 \times 60 = 120\); \(4 + 6 \times 0.1 = 4.6\); \(3 \times 100 = 300\);
\(250 \div 1000 = 0.25\) (and 250 g is a quarter of 1000 g);
\(2.5 \times 1000 = 2500\); \(3.4 \times 100 = 340\),
\(340 \div 20 = 17\) with inverse check \(17 \times 20 = 340\);
\(60 + 30 = 90\); \(120 + 45 = 165\) and 165 cm = 1.65 m;
interval endpoints 5.5/6.5 and 65/74 under the stated half-up rule
(65 → 70, 74 → 70, 75 → 80); \(35 + 65 = 100\), \(44 + 74 = 118\),
naive 110 inside with maximum deviation 10; \(2 \times 2.00 = 4.00\),
\(4.50 \div 1.5 = 45 \div 15 = 3.00\), portion check
\(4.50 \div 3 = 1.50 < 2.00\); 200 mL is one fifth of 1 L
(\(1000 \div 200 = 5\)). Unit claims (100 cm = 1 m, 1000 m = 1 km,
1000 g = 1 kg, 1000 mL = 1 L, 60 s = 1 min, 60 min = 1 h) match the SI
Brochure and NIST SP 811 entries already in the deck source register.

## Simplifications and boundaries recorded

- "How heavy" for mass is a labeled simplification; the mass–weight
  distinction is deferred to a science context (also recorded in
  `CARD_README.md` rejected examples).
- Intervals are stated in words ("at least … and less than …") because
  inequality symbols are deliberately excluded from this deck.
- The half-up tie convention is restated on every front whose graded
  answer depends on an interval endpoint (fronts 10, 11, P23).

## Result

All 25 fronts map every domain-bearing dependency to confirmed inbound
closure knowledge or an earlier scheduled establishment in this chapter.
Three defects found during the scan were repaired before this report
(fronts 04, P23, P25 above); none remain open.

cold_start_status: pass
unresolved_dependencies: 0
