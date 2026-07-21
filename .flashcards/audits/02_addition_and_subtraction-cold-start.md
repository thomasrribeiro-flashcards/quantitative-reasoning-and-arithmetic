# Chapter 2 cold-start audit: addition and subtraction

Audit date: 2026-07-20

Target: `flashcards/02_addition_and_subtraction.md`

## Chapter-boundary contract

The machine-resolved graph was checked with
`flashcards deck prerequisites . --chapter 2`.

- Edge mode: explicit.
- Allowed local inbound chapter:
  `chapter:01_quantities_and_whole_numbers`.
- Allowed scheduled inbound knowledge: quantities and numerals; reliable
  counting; zero and whole numbers; digits; ones, tens, and hundreds place
  value; placeholder zero; the whole-number line and rightward increase;
  whole-number comparison; exact amounts and estimates; nearest-ten and
  nearest-hundred rounding; and the already demonstrated IPEE problem labels.
- External deck closure: none.
- Assumed tools: none.
- Excluded as unseen: multiplication, division, operation-order conventions,
  signed quantities, fractions, decimals, ratios, percents, measurement units,
  money conventions, formal algebra, and letter placeholders.

## Chapter concept-dependency ledger

| New concept, symbol, procedure, or representation | First explanation or analyzed example | First supported retrieval | Later faded or independent use | Status |
|---|---|---|---|---|
| Addition; \(+\); \(=\); total; sum | Front 01 defines every term and symbol while joining two small counted amounts. | Front 01 completes a supported sum. | Fronts 03–08, 13, 17, 20, 22–23. | established |
| Part–whole diagram | Front 02 explains the upper parts, lower whole, labels, and unknown mark; the front SVG and alt text contain only setup information. | Front 02 finds the whole from two parts. | Front 12 finds an unknown part without requiring a letter variable. | established |
| Operation as a mathematical action | Front 03 defines the term before asking for operation choice. | Front 03 chooses addition from a joining situation. | Fronts 10 and 23. | established |
| Place-value decomposition for addition | Front 04 explicitly directs tens-with-tens and ones-with-ones and is a fully analyzed problem. | Front 04 computes a supported sum. | Fronts 05–08 and 22. | established |
| Decomposed number-line jumps | Front 05 defines the start, rightward jump labels, tens jump, ones jump, and unknown endpoint on the scheduled front. | Front 05 translates the line to an endpoint and sum. | Flexible addition and later number-line reasoning. | established |
| Vertical calculation and column alignment | Front 06 defines a column and explains equal-place alignment beside the written layout. | Front 06 explains why the ones digits align. | Fronts 08, 14, 20–21. | established |
| Regrouping as an equal-value exchange | Front 07 defines regrouping, states both exchange directions, and supplies an original reversible tens/ones figure. | Front 07 records twelve ones as one ten and two ones. | Fronts 08, 15–16, 21, and 23. | established |
| Subtraction; \(-\); difference; remaining amount | Front 09 defines the operation, symbol, result word, and removal meaning on a small counted amount. | Front 09 completes supported removal. | Fronts 10–21 and 23. | established |
| Subtraction as comparison | Front 11 explicitly defines the comparison meaning before asking for a difference. | Front 11 finds how many more. | Magnitude and reasonableness checks. | established |
| Subtraction as unknown-part finding | Part–whole grammar is established on Front 02; Front 12 supplies the whole and known part in words. | Front 12 chooses subtraction and finds the missing part. | Inverse-operation reasoning. | established |
| Inverse operations and inverse checks | Front 13 defines “inverse” as undoing and supplies a complete sum before asking for the checking subtraction. | Front 13 checks addition. | Fronts 16–17 and 23 check subtraction or a final addition. | established |
| Subtraction regrouping | Front 15 states why two ones cannot supply eight ones while staying in whole-number arithmetic and reuses the already explained exchange figure. | Front 15 selects three tens and twelve ones. | Fronts 16, 21, and 23. | established |
| Estimate check | Exact/estimate and nearest-hundred rounding are inbound; Front 18 supplies the rounded values and asks only for the diagnostic judgment. | Front 18 rejects a result with the wrong approximate size. | Later arithmetic reasonableness checks. | established |
| Subtraction magnitude bound | Whole-number comparison is inbound; Front 19 states the applicable zero-to-starting-amount bound before asking for diagnosis. | Front 19 rejects a difference larger than the starting amount. | Later quantitative reasonableness checks. | established |
| Compensation | Front 22 defines moving the same amount between joined parts and states that the total is unchanged. | Front 22 selects the equivalent easier sum. | Flexible mental computation. | established |

## Front-by-front cold-start scan

The scan was performed in scheduled order from a front-only extraction. For
each row, the listed dependencies were recorded before the corresponding answer
or solution was inspected.

| Front | Dependencies needed to parse and attempt the front | Allowed source or earlier establishment | Finding |
|---:|---|---|---|
| 01 | Counted whole-number amounts | Chapter 1; all addition words and symbols are defined on this front | ready |
| 02 | Whole numbers; addition; new diagram grammar | Chapter 1; Front 01; diagram grammar is explained before the image | ready |
| 03 | Whole-number quantities; “operation”; addition | Chapter 1; “operation” is defined on this front; Front 01 | ready |
| 04 | Tens and ones; addition; IPEE response form | Chapter 1; Front 01; front supplies the place-value plan; IPEE is inbound | ready |
| 05 | Whole-number line, rightward increase, tens and ones, addition | Chapter 1; Front 01; jump grammar is explained on this front | ready |
| 06 | Digits and place value; addition; vertical column | Chapter 1; Front 01; “column” and alignment are defined on this front | ready |
| 07 | Place-value equivalence; addition; regrouping; exchange figure | Chapter 1; Front 01; regrouping and the full figure grammar are defined on this front | ready |
| 08 | Addition and addition regrouping | Fronts 01 and 07; the meaningful ones step is supplied for completion | ready |
| 09 | Counted whole-number amounts | Chapter 1; subtraction, minus, difference, and removal are defined on this front | ready |
| 10 | Operation choice; subtraction removal meaning | Fronts 03 and 09 | ready |
| 11 | Whole-number comparison; subtraction | Chapter 1; Front 09; comparison meaning is explained on this front | ready |
| 12 | Part–whole structure; subtraction | Fronts 02 and 09 | ready |
| 13 | Addition, subtraction, parts and total; inverse | Fronts 01, 02, and 09; inverse is defined on this front | ready |
| 14 | Vertical alignment; place value; subtraction | Chapter 1; Fronts 06 and 09 | ready |
| 15 | Subtraction; regrouping; reversible exchange figure | Fronts 07 and 09; the whole-number boundary and needed exchange are stated on this front | ready |
| 16 | Subtraction, place value, regrouping | Chapter 1; Fronts 09 and 15 | ready |
| 17 | Addition, subtraction, difference, inverse check | Fronts 01, 09, and 13 | ready |
| 18 | Estimate, nearest-hundred rounding, subtraction, difference | Chapter 1; Front 09; rounded comparison values are supplied | ready |
| 19 | Zero, whole-number comparison, subtraction, difference | Chapter 1; Front 09; the applicable bound is stated on this front | ready |
| 20 | Digit place value, addition, vertical alignment | Chapter 1; Fronts 01 and 06 | ready |
| 21 | Subtraction, columns, regrouping | Fronts 06, 09, and 15 | ready |
| 22 | Addition, joined parts, unchanged total; compensation | Fronts 01–02; compensation is defined on this front | ready |
| 23 | Counted amounts; removal versus joining; regrouping | Chapter 1; Fronts 03, 09, and 15; temporal words specify the two steps | ready |

## Answer-side and figure audit

- Back 04 uses the IPEE labels already demonstrated in Chapter 1; it introduces
  no later front dependency.
- Back 08 uses Chapter 1 rounding only after the supported regrouping front.
- Back 16 uses the inverse relationship established on Front 13.
- Back 19 names the already stated diagnostic rule a “size bound”; no later
  front requires that phrase.
- Back 23 writes the rounded two-step check as two separate equations, so no
  later operation-order convention is assumed.
- The part–whole SVG has a responsive `viewBox`, title, description, redundant
  labels, and an unknown whole; it does not reveal the requested sum.
- The decomposed-addition SVG has a responsive `viewBox`, title, description,
  numeric start and intermediate point, labeled rightward jumps, and an unknown
  endpoint; its scale and direction agree with the arithmetic.
- The regrouping SVG has a responsive `viewBox`, title, description, text
  labels, outlined tens and ones, and a two-headed same-quantity cue; meaning
  does not depend on color.
- Every Markdown alt text describes setup information without revealing the
  requested result.
- No front, back, figure, or alt text borrows an unavailable later-chapter
  concept.

## Repairs made during the scan

- Front 03 gained a minimal scheduled definition of “operation.”
- Front 06 gained a minimal scheduled definition of “column.”
- Inline math delimiters stripped during the initial patch were restored before
  parser validation.
- The regrouping figure's hidden exchange arrow and crowded one-counters were
  repaired and visually reinspected.
- The mixed problem's estimated check was split into two explicit equations to
  avoid assuming a later operation-order convention.

cold_start_status: pass
unresolved_dependencies: 0
