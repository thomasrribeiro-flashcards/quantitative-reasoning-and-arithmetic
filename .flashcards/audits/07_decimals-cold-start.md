# Cold-start audit — Chapter 7: Decimals (`flashcards/07_decimals.md`)

- Audit date: 2026-07-23 (isolated regeneration run)
- Auditor: authoring agent, same session as authoring, separate first-use scan per D8
- Chapter under audit: 27 scheduled cards (22 Q/A basics, 5 P/S problems, 0 clozes)

## Method

Per CARD_STANDARD D7/D8 and the cold-start workflow: every front was scanned
in scheduled (linear) order. For each front, every concept, term, notation,
and skill the front invokes was recorded and resolved against the inbound
closure or an earlier point in the chapter **before** the answer/solution
was read. Only `Q:/A:`, `P:/S:` blocks count as establishing material
(this chapter has no `C:` blocks); section headings, prose, and figure alt
text were treated as non-establishing. A concept counts as established
in-chapter only if a strictly earlier scheduled card taught it, or the
current front itself teaches it before asking (teach-then-ask fronts are
marked "taught on this front").

## Inbound closure (fixed at sandbox resolution — no additions made)

Direct prerequisite (full scheduled cards read): **06_fractions** —
`fraction`, `fraction-number-line`, `equivalent-fraction`, `mixed-number`,
`fraction-operations` (all four operations, common denominator, reciprocal,
simplest form, benchmark 1/2), `fraction-of-quantity`.

Transitive prerequisites (validator-resolved capability summaries only):

| Chapter | Capabilities relied on below |
|---|---|
| 01 quantities and whole numbers | `place-value`, `whole-number`, `whole-number-line`, `whole-number-comparison`, `rounding-whole-numbers` (incl. round-half-up tie convention, restated on Front 24 before any use) |
| 02 addition and subtraction | `whole-number-addition`, `whole-number-subtraction`, `whole-number-regrouping`, `inverse-operation-check` |
| 03 multiplication and division | `whole-number-multiplication`, `whole-number-division`, `division-remainder` |
| 04 operation structure and factors | `factor-and-multiple` |
| 05 signed quantities | none invoked by this chapter |

External decks: none. Assumed tools: none.

## In-chapter concept frontier (first-establishment ledger)

| # | Concept | Established on front |
|---|---|---|
| 1 | decimal point; tenths place; decimal number; "point" reading | 01 |
| 2 | hundredths place | 02 |
| 3 | hundred grid as a picture of hundredths | 03 (P) |
| 4 | thousandths place; digit value fixed by position | 04 |
| 5 | last-used place names the fraction denominator | 05 |
| 6 | placeholder zero (between point and digit) | 06 |
| 7 | trailing-zero equivalence (0.5 = 0.50) | 07 |
| 8 | decimals on the number line; tenths marks between wholes | 08 |
| 9 | hundredths between neighboring tenths (density) | 09 |
| 10 | place-by-place decimal comparison | 10 |
| 11 | fraction → decimal via equivalent 10/100/1000-denominator fraction | 11 |
| 12 | not every fraction has a terminating decimal (1/3 boundary) | 12 |
| 13 | money notation: dollars, cents, two decimal places | 13 |
| 14 | decimal-point alignment for column addition/subtraction | 15 |
| 15 | whole number written with decimal places (5 = 5.00) | 17 |
| 16 | ×10 / ×100 place shift | 18 |
| 17 | decimal-places count rule for multiplication | 19 |
| 18 | dividing a decimal by a whole number (tenths counting) | 21 |
| 19 | dividing by a decimal via scaling both numbers (equivalent fraction) | 22 |
| 20 | rounding a decimal (nearest whole; tie convention restated) | 24 |
| 21 | rounding to a decimal place (nearest tenth) | 25 |
| 22 | round from the original number, never in stages | 26 |

## Front-by-front audit

Status legend: **OK** = every dependency resolved to the inbound closure
or an earlier front (or taught on the front itself before the ask).

**Front 01** (`fdefe6bb`, Q/A) — invokes: whole-number place value,
ten-times/one-tenth place pattern (Ch01 `place-value`), fraction notation
\(\frac{1}{10}\), whole-plus-fraction sums (Ch06 `fraction`,
`mixed-number`). Teaches on this front: decimal point, tenths, decimal,
"point" reading. No earlier in-chapter dependencies. **OK**

**Front 02** (`e6945501`, Q/A) — invokes: tenths/decimal point (Front 01),
fraction multiplication \(\frac{1}{10}\times\frac{1}{10}\) (Ch06
`fraction-operations`), equivalent fractions \(\frac{3}{10}=\frac{30}{100}\)
(Ch06 `equivalent-fraction`). Teaches: hundredths place. **OK**

**Front 03** (`64fd2d62`, P/S, figure `decimal_grid.svg`) — invokes:
part-of-whole fraction of a subdivided square (Ch06 `fraction`, area-model
grammar from Ch06 figures), hundredths and two-place decimals (Fronts
01–02), counting by rows of ten (Ch03 `whole-number-multiplication`).
Teaches: hundred grid as hundredths picture. Figure sits on the front;
alt text describes only the visible shading (two rows plus seven squares)
and does not state the fraction or decimal — same disclosure level as the
Ch06 grid/strip figures. **OK**

**Front 04** (`1ea2d651`, Q/A) — invokes: tenths/hundredths pattern
(Fronts 01–02), place-position determines digit value (Ch01
`place-value`). Teaches: thousandths, third decimal place. **OK**

**Front 05** (`f900fd2d`, Q/A) — invokes: tenths, hundredths, thousandths
places (Fronts 01–04), fraction notation (Ch06). Teaches: last-used place
names the denominator. Worked examples 0.7 and 0.43 precede the ask on
0.209. **OK**

**Front 06** (`4b44305b`, Q/A) — invokes: decimal notation and hundredths
(Fronts 01–02), fraction comparison via same denominator (Ch06
`equivalent-fraction`), comparison language (Ch01
`whole-number-comparison`). Teaches: placeholder zero. The front asks the
comparison directly; no unestablished term appears. **OK**

**Front 07** (`59ab4a66`, Q/A) — invokes: decimal notation (Fronts 01–02),
equivalent fractions by multiplying top and bottom (Ch06). Teaches:
trailing-zero equivalence, and contrasts with placeholder zero (Front 06).
**OK**

**Front 08** (`34dc4437`, Q/A, figure `decimal_line.svg`) — invokes:
number line with labeled whole numbers (Ch01 `whole-number-line`, Ch06
`fraction-number-line` for subdividing a unit interval into equal steps),
tenths (Front 01). Teaches: decimals take number-line positions at tenths
marks — stated on the front before the ask. Alt text and SVG desc say only
"a dot on one of the marks," matching the Ch06 `fraction_line` disclosure
convention (position not leaked). **OK**

**Front 09** (`c03bf132`, Q/A) — invokes: tenths marks on the number line
(Front 08), two-place decimals (Front 02), trailing-zero renaming for the
required justification (Front 07). Teaches: density of hundredths between
tenths. **OK**

**Front 10** (`667cb201`, Q/A) — invokes: decimal notation (Fronts 01–02),
whole-number comparison of 48 vs 6 (Ch01), renaming with trailing zeros
(Front 07). Teaches: place-by-place comparison; misconception diagnosis
form (R-form for a classic error). **OK**

**Front 11** (`585240c9`, Q/A) — invokes: equivalent fractions (Ch06),
decimals from fractions with denominator 10/100 (Fronts 01–02, 05).
Teaches: the general fraction→decimal route, with \(\frac{1}{2}=0.5\)
worked before the \(\frac{3}{4}\) ask. **OK**

**Front 12** (`b252f0e2`, Q/A) — invokes: fraction→decimal route
(Front 11), last-place-names-denominator (Front 05), equivalent-fraction
comparison \(\frac{99}{300}\) vs \(\frac{100}{300}\) (Ch06),
division with remainder (Ch03 `division-remainder`), factor language
(Ch04 `factor-and-multiple`). Teaches: terminating-decimal boundary
without repeating-decimal notation (deliberately excluded — see rejected
list in CARD_README.md). **OK**

**Front 13** (`21bbb638`, Q/A) — invokes: hundredths (Front 02),
placeholder zero (Front 06), two-place decimals. Teaches on this front,
before the ask: the money bridge (1 dollar = 100 cents, cent =
\(\frac{1}{100}\) dollar, two-decimal-place convention, \(\$\) notation).
Money is in-scope for Chapter 7 per the deck chapter map; this is its
first use anywhere in the deck, so the front establishes it explicitly
rather than assuming it. **OK**

**Front 14** (`0b4d0cc1`, Q/A) — invokes: money notation (Front 13),
trailing-zero equivalence (Front 07), placeholder zero (Front 06).
Calculator display behavior is explained in the answer, not assumed on
the front. **OK**

**Front 15** (`cf24de38`, Q/A, figure `decimal_alignment.svg`) — invokes:
column-form addition with digit columns (Ch02 `whole-number-addition`),
tenths/hundredths places (Fronts 01–02), adding unlike fractions requires
renaming (Ch06 `fraction-operations`, used as analogy in the answer).
Teaches: align the decimal points. The figure shows both setups on the
front; alt text names the layouts' visible difference without saying which
is correct. **OK**

**Front 16** (`7fcc23df`, P/S completion problem) — invokes: aligned
setup (Front 15), trailing-zero padding 2.7 → 2.70 (Front 07, and the
setup is handed to the learner on the front per the completion-problem
form: IDENTIFY/PLAN faded), regrouping ten tenths as one (Ch02
`whole-number-regrouping`), estimation check with benchmark-friendly 0.5
(Ch06 benchmark). **OK**

**Front 17** (`4c0bc978`, Q/A) — invokes: trailing zeros (Front 07),
alignment (Front 15), subtraction with regrouping (Ch02), inverse-check
(Ch02 `inverse-operation-check`). Teaches: whole numbers take decimal
places (5 = 5.00), stated on the front before the ask. **OK**

**Front 18** (`e674c05e`, Q/A) — invokes: place values ten times
larger/smaller (Ch01 `place-value`, Front 01), decimal places (Fronts
01–02). Teaches: ×10/×100 digit shift, with the ×10 case worked on the
front before the ×100 ask. **OK**

**Front 19** (`a74f7946`, Q/A) — invokes: fraction multiplication
\(\frac{3}{10}\times\frac{2}{10}=\frac{6}{100}\) (Ch06), tenths/hundredths
(Fronts 01–02). Teaches: decimal-places count rule, derived on the front
before the ask. **OK**

**Front 20** (`cf88202c`, P/S) — invokes: decimal-places rule (Front 19),
whole-number multiplication 15 × 24 (Ch03), trailing-zero drop 3.60 = 3.6
(Front 07), bounding estimate (Ch03 multiplication, Ch01 comparison).
**OK**

**Front 21** (`ff013b3f`, Q/A) — invokes: reading a decimal as a count of
tenths (Fronts 01, 05), whole-number division (Ch03), multiplication
check (Ch02/Ch03 inverse relationship). Teaches: divide a decimal by a
whole number via tenths counting, with 3.6 ÷ 3 worked before the
6.4 ÷ 4 ask. **OK**

**Front 22** (`d7c1c378`, Q/A) — invokes: division written as a fraction
and scaled top-and-bottom (Ch06 `equivalent-fraction`; fraction-as-
division reading established in Ch06), whole-number division (Ch03).
Teaches: scale both numbers by 10 so the divisor becomes whole, worked on
1.2 ÷ 0.4 before the 2.4 ÷ 0.6 ask. **OK**

**Front 23** (`04bca0d7`, P/S) — invokes: scaling method (Front 22),
whole-number division 45 ÷ 9 (Ch03), multiply-back check, dividing by a
number smaller than 1 gives a larger quotient (reasoned out in EVALUATE
from group-counting meaning, Ch03). **OK**

**Front 24** (`938c1358`, Q/A) — invokes: rounding whole numbers —
nearest-candidates procedure (Ch01 `rounding-whole-numbers`), decimal
comparison (Front 10). Teaches: rounding decimals; **restates the
round-half-up tie convention on the front** (required since the
summarized Ch01 cards are not readable in this run), though 6.48 itself
is not a tie. **OK**

**Front 25** (`159a587c`, Q/A) — invokes: rounding procedure with
neighboring candidates (Front 24), tenths marks (Front 08), decimal
subtraction distances 0.076/0.024 (Front 17). Teaches: rounding to the
nearest tenth. **OK**

**Front 26** (`281b3db3`, Q/A) — invokes: rounding to tenths and
hundredths (Fronts 24–25), halfway value comparison (Front 24).
Teaches: one-step rounding from the original number; misconception
diagnosis of chained rounding. **OK**

**Front 27** (`07137d38`, P/S) — invokes: money notation \(\$4.68\),
\(\$2.79\), \(\$10\) (Front 13), decimal addition and subtraction with
alignment and regrouping (Fronts 15–17, Ch02), rounding to the nearest
tenth for the estimate (Front 25), inverse check (Ch02). Multi-step
mixed application; full IPEE retained. **OK**

## Answer-side check

After the front scan, each answer/solution was re-read against the
frontier at its card's position. No answer introduces a term, notation,
or method beyond its front's recorded dependencies plus material the same
card teaches; no future-facing examples (U11 firewall): no percent, no
measurement units, no repeating-decimal notation, no long-division
algorithm, no ratio/proportion language anywhere in the chapter.

## Reconciliation

- Fronts audited: 27 of 27.
- Dependencies resolved to inbound closure: Ch01 (place value, number
  line, comparison, rounding), Ch02 (add/subtract, regrouping, inverse
  check), Ch03 (multiply/divide, remainder), Ch04 (factor), Ch06 (all
  listed capabilities). Ch05 signed quantities: unused, as planned.
- Dependencies resolved in-chapter: 22 frontier entries, each established
  strictly before (or on) first use; sequence verified linear.
- Unexplained or forward references found: none.

cold_start_status: pass
unresolved_dependencies: 0
