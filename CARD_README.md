# Quantitative Reasoning And Arithmetic card blueprint

This file records retrieval decisions specific to this deck. Do not copy the
universal standard, playbook, subject brief, roadmap, or research literature
here; link to a justified exception when one is necessary.

## Learner model

- Level: foundational
- Confirmed mathematical/tool prerequisites: none
- Confirmed subject prerequisites: none unless explicitly listed
- Capabilities this deck should produce: understand, calculate, estimate,
  represent, compare, and check whole, signed, rational, decimal, percent, and
  proportional quantities in short authentic situations.
- Important exclusions: formal algebra, geometry as a deductive subject,
  probability and statistics, calculator-specific keystrokes, and long-form
  problem sets.

Unconfirmed subject knowledge is not mastered. A target level describes the
destination, not permission to assume its vocabulary.

## Curriculum and prerequisite graph

Define prerequisite decks and assumed tools in `deck.toml`; define chapter
edges and provided concepts in each chapter's TOML frontmatter. Inspect the
resolved, human-readable graph with `flashcards deck prerequisites .`. Do not
duplicate that graph here. Use this section only to explain important design
decisions, boundaries, or rejected edges that the metadata cannot express.

The ten chapters form a strict local learning progression. Later chapters will
declare explicit `chapter:` edges when authored; their position in the chapter
map alone grants no inbound knowledge. Chapter 1 has no inbound concepts.

## Concept-dependency ledger

| Concept or representation | Front(s) requiring it | Confirmed inbound source or first explanation | First supported retrieval | Later application | Status |
|---|---|---|---|---|---|
| Quantity/amount and numeral | 01–02 | Front 01 defines both in a labeled pantry-shelf situation before asking anything. | Front 01 asks for the label-to-jars relationship; Front 02 classifies a painted symbol versus a stack of boxes with less support. | Every later numerical context. | established |
| Counting procedure: fixed word order, count each item once, final word is the quantity | 03 | Front 03 states the word sequence “one, two, three, four, five,” the touch-once rule, and the final-word meaning before the question. | Front 03 diagnoses a count that skipped a shell. | Exact counts, estimates, and every authentic count later. | established |
| Zero and whole number | 04–05 | Front 04 lists the numerals 0, 1, 2, 3, 4, 5, and so on as counts of complete items and maps 0 to “none.” | Front 04 retrieves zero for an empty bowl; Front 05 retrieves the category name with less support. | Place value, number line, and all whole-number arithmetic. | established |
| Digit, group of ten, ones place, tens place | 06–07 | Front 06 lists the ten digits, defines the ones and tens places, and states the figure grammar (each loop holds exactly ten counters). | Front 06 translates the grouped-counter figure into a two-digit numeral; Front 07 retrieves the value of the 7 in 73. | Multi-digit numerals here and arithmetic in Chapters 2–4. | established |
| Hundreds place and placeholder zero | 08–09 | Front 08 states the right-to-left ones–tens–hundreds sequence, defines a hundred as ten tens, and explains a 0 digit as “no groups of that size.” | Front 08 retrieves the zero's role in 507; Front 09 diagnoses a place-ignoring claim about 380. | Larger whole numbers, decimals, and written algorithms. | established |
| Whole-number line, marked dot, rightward growth | 10 | Front 10 defines the evenly spaced line starting at 0 and the larger-to-the-right rule; the original figure labels every mark from 0 to 10. | Front 10 asks which labeled dot marks the larger quantity. | Comparison, rounding, and later signed, fraction, and decimal lines. | established |
| Comparison symbols `<` and `>` | 11 | Front 11 gives both readings and the open-side-faces-the-larger rule before asking the learner to choose between two complete comparisons. | Front 11 chooses the true comparison for 9 and 4. | Inequalities and quantitative checks throughout. | established |
| Exact quantity and estimate | 12–13 | Front 12 defines an exact quantity as a careful complete count and an estimate as a close-but-rough value signaled by words like “about.” | Front 12 classifies an “about 30” report; Front 13 explains when an estimate is the appropriate report. | Rounding and error-aware decisions throughout. | established |
| Rounding, nearest ten, halfway value, higher-halfway convention, ones-digit rule | 14–16 | Front 14 defines rounding, the two neighboring tens, the halfway value ending in 5, and the deck's round-halfway-higher convention, supported by a 30–40 number-line figure; Front 16 states the complete ones-digit shortcut before its diagnosis question. | Front 14 reads the figure to round 38; Problem 15 executes an analyzed nearest-ten rounding. | Front 16 diagnoses wrong-direction rounding of 84; Chapters 2, 3, 7, 9, and 10. | established |
| IPEE problem structure | 15 | Solution 15 names and demonstrates IDENTIFY, PLAN, EXECUTE, and EVALUATE; the front itself needs only the already-taught rounding skill. | Front/Solution 15 is the analyzed model. | Faded Solution 18 and later chapters' problem cards. | established |
| Nearest hundred | 17–18 | Front 17 transfers the nearest-place idea to hundreds and states the halfway value ending in 50 before its supported choice about 452. | Front 17 makes the supported choice. | Problem 18 independently rounds an authentic 649 count. | established |
| Addition, `+`, `=`, total, and sum | Ch. 2 fronts 01–04 | Ch. 2 Front 01 defines joining, both symbols, and the result word on a supported small count; whole numbers come from Ch. 1. | Front 01 completes a joining statement; Front 02 translates a part–whole figure. | Operation choice and all later whole-number sums. | established |
| Part–whole diagram grammar | Ch. 2 front 02 | Front 02 explains that the two upper boxes are parts and the lower box is the whole before asking for the total. | Front 02 translates the diagram into a sum. | Unknown-part subtraction on Front 12. | established |
| Place-value decomposition and aligned addition | Ch. 2 fronts 05–08 | Ch. 1 established tens and ones; Front 05 explains jump labels on an open number line, and Front 06 explains aligning equal places. | Fronts 05–06 retrieve the matching computation; Front 08 completes regrouped addition. | Efficient whole-number addition and later decimal alignment. | established |
| Regrouping as an equal-value exchange | Ch. 2 fronts 07–08, 15, and 17 | Front 07 defines regrouping and shows that ten ones can be exchanged for one ten without changing the quantity. Front 15 reverses that exchange for subtraction. | Front 07 explains the addition exchange; Front 15 chooses the subtraction exchange. | Multi-digit arithmetic in Chapters 2–4 and decimal computation in Chapter 7. | established |
| Subtraction, `-`, remaining amount, comparison, and difference | Ch. 2 fronts 09–12 | Front 09 defines removal and the minus symbol; Front 11 explicitly establishes comparison as a second subtraction meaning. | Fronts 09–11 retrieve remaining and comparison differences. | Unknown-part choice, inverse checks, and later quantitative change. | established |
| Addition and subtraction as inverse operations | Ch. 2 fronts 13 and 16 | Front 13 defines inverse operations as operations that undo one another and models a sum/subtraction pair. | Front 13 checks a sum; Front 16 checks a difference before Problem 17 applies the check independently. | Error checking throughout the deck. | established |
| Estimate, magnitude bound, alignment, and regrouping checks | Ch. 2 fronts 18–21 | Rounding, comparison, and place value are inbound from Ch. 1; each front states the applicable check or shows the written work being diagnosed. | Fronts 18–21 each diagnose one distinct error signal. | Reasonableness checks for later operations. | established |
| Compensation for an easier sum | Ch. 2 front 22 | Front 22 defines compensation as moving the same amount from one joined part to the other so the total stays unchanged. | Front 22 selects the equivalent easier sum. | Flexible mental addition and later estimation. | established |
| Equal groups, arrays, multiplication, factors, product | Ch. 3 fronts 01–07 | Ch. 3 Front 01 defines equal groups and `x`; an original array establishes rows/columns on its own front. | Translation among words, array, and notation. | Products, powers, factors, fraction/decimal scaling, proportions. | planned |
| Sharing/grouping division, quotient, remainder | Ch. 3 fronts 08–16 | Separate scheduled fronts define both division meanings and establish `÷`; remainder is introduced with an incomplete final group. | Meaning contrast and quotient/remainder retrieval. | Factors, fraction division, unit rates, conversions. | planned |
| Expression, grouping marks, operation order, exponent/power | Ch. 4 fronts 01–11 | Ch. 4 Front 01 defines an expression; later fronts teach grouping, left-to-right rules, and powers before mixed evaluation. | Supported interpretation before independent evaluation. | Fraction/decimal computations and percent expressions. | established |
| Factor, multiple, divisibility, prime, composite | Ch. 4 fronts 12–22 | Multiplication/division are inbound from Ch. 3; each term is defined with a concrete factor-pair example before retrieval. | Factor/multiple contrast, divisibility diagnosis, classification. | Simplifying fractions and building common denominators. | established |
| Signed number, positive/negative sign, zero, opposite, absolute distance | Ch. 5 fronts 01–08 | Ch. 5 Front 01 defines signed numbers on a counted floors-from-street-level context; Front 02 extends the Ch. 1 line left of zero with an original figure; distance from zero and opposite follow on scheduled fronts. | Position, comparison, opposite, and distance retrieval, including the sign-versus-subtraction discrimination. | Signed addition/subtraction and later quantitative changes. | established |
| Signed addition and subtraction as directed movement | Ch. 5 fronts 09–19 | Front 09 derives the leftward jump for a negative addend on an original line figure and bridges grouping-mark packaging; subtraction crossing zero and the add-the-opposite identity are demonstrated before independent problems. | Prediction and diagnosis precede independent movement problems. | Decimal change, percent change, and measurement error. | established |
| Fraction, equal parts, numerator/denominator, unit fraction, quotient meaning | Ch. 6 fronts 01–08 (basics 01–07, Problem 01) | Front 01 defines equal parts, fraction notation, numerator, denominator, and unit fraction on an original shaded-strip figure; Front 05 extends the Ch. 1 line with an original sixths figure; analyzed Problem 01 derives 3 ÷ 4 = 3/4 from equal sharing. | Translate among picture, words, and notation; Front 07 reuses Ch. 5 opposites on a fraction. | Equivalence, comparison, operations, and fractions of quantities. | established |
| Equivalent fractions, mixed numbers, common denominator | Ch. 6 fronts 09–20 (basics 09–18, Problems 02–03 among them) | Mixed↔improper conversion is bridged through Ch. 3 division-with-remainder; equivalence is derived on the original strips figure and tied to Ch. 3 multiplication; “common factor” and “common multiple” each get a one-clause bridge at first use. | Visual equivalence, simplest form, and four comparison strategies precede computation; the add-1-to-both misconception is diagnosed after common denominators exist. | Fraction operations and decimal/percent translation. | established |
| Fraction addition/subtraction, multiplication/division, reciprocal | Ch. 6 fronts 19–34 | Same-denominator addition counts unit fractions; unlike denominators reuse renaming; “of” selects a fraction of a counted set on an original figure; division is first modeled as counting fractional groups on an original figure before the reciprocal rule. | Analyzed and faded models precede independent “of,” multiplication, and division problems and the mixed comparison. | Rates, proportions, percent, and unit conversion. | established |
| Decimal, decimal point, tenths, hundredths, thousandths | Ch. 7 fronts 01–12 | Ch. 7 Front 01 extends Ch. 1 place value rightward past the ones place; Fronts 02 and 04 cut a tenth and a hundredth into ten equal parts using Ch. 6 fraction multiplication. | Front 01 reads 2.7; Front 02 counts hundredths; Problem 03 translates the hundred grid; Front 04 values a thousandths digit. | Comparison, conversion, money, all decimal operations, and rounding. | established |
| Trailing zeros and placeholder zeros in decimals | Ch. 7 fronts 06–07, 09–10, 13–14, 17 | Front 06 explains the placeholder zero in 0.07; Front 07 derives 0.5 = 0.50 from equivalent fractions. | Fronts 06–07. | Between-tenths density (09), comparison diagnosis (10), money notation (13–14), and subtracting from a whole number (17). | established |
| Decimal number line and between-tenths density | Ch. 7 fronts 08–09 | Front 08 extends the Ch. 6 fraction-line grammar: the gap between neighboring whole numbers cut into ten equal steps. | Front 08 reads the dot; Front 09 names a hundredth between two tenths. | Comparison, rounding distance reasoning, and Chapter 10 scale reading. | established |
| Fraction↔decimal conversion and its finite boundary | Ch. 7 fronts 05, 11–12 | Front 05 names the denominator from the last-used place; Front 11 renames a fraction to denominator 10/100/1000 with Ch. 6 equivalence; Front 12 shows why no ending decimal equals 1/3 using division remainders. | Fronts 05 and 11. | Percent conversion in Chapter 9 and measurement in Chapter 10. | established |
| Money notation: dollar, cent, dollar sign, two decimal places | Ch. 7 fronts 13–14, 27 | Front 13 defines one cent as one hundredth of a dollar and the two-place dollar notation. | Front 13 writes 7 dollars and 8 cents. | Front 14 display diagnosis, Problem 27 mixed money change; percent-of-money contexts in Chapter 9. | established |
| Decimal addition/subtraction alignment and regrouping | Ch. 7 fronts 15–17, 27 | Front 15 contrasts point-aligned and last-digit-aligned column layouts on an original figure; regrouping itself is inbound from Ch. 2. | Front 15 chooses the layout; Problem 16 completes an addition. | Front 17 whole-minus-decimal, Problem 27 money change, Chapter 10 measurement arithmetic. | established |
| Decimal multiplication and the tenfold place shift | Ch. 7 fronts 18–20 | Front 18 explains the place shift for ×10/×100; Front 19 derives tenths × tenths = hundredths from Ch. 6 fraction multiplication. | Fronts 18–19. | Problem 20 independent product; unit rates and percent computation later. | established |
| Decimal division: tenths counting and scaling both numbers by 10 | Ch. 7 fronts 21–23, 27 | Front 21 shares tenths among a whole number of groups; Front 22 rewrites the division as a fraction (Ch. 6) and scales top and bottom by 10 (equivalent fractions). | Fronts 21–22. | Problem 23 independent quotient; unit rates in Chapter 8. | established |
| Decimal rounding and the restated round-half-up convention | Ch. 7 fronts 24–27 | Front 24 transfers Ch. 1 nearest-value rounding to decimal places and restates the deck's ties-round-up convention. | Fronts 24–25. | Front 26 chain-rounding diagnosis; Problem 27 estimate check; precision in Chapters 9–10. | established |
| Ratio, colon notation, order of mention, part-to-part versus part-of-whole | Ch. 8 fronts 01–05 | Front 01 bridges Ch. 2 difference and Ch. 3 times-as-many comparison; Front 02 defines the "for every" relationship and colon notation on a counted mixture; Front 03 states the order rule; Front 05 links a part-to-part ratio to the Ch. 6 fraction of the whole. | Front 02 writes a ratio; Front 04 reads one from the original collection figure; Front 05 converts to a fraction of the whole. | Equivalence, tables, rates, proportions, and percent. | established |
| Equivalent ratio, scale factor, simplest form, ratio comparison | Ch. 8 fronts 06–12 | Front 06 defines equivalent ratios and the scale factor through a doubled batch and Ch. 6 equivalent fractions; Front 07 reverses with division by a shared factor (Ch. 4); Front 08 compares two ratios by scaling to a common part. | Fronts 06–08 scale, simplify, and compare with the method stated; Front 09 fills a ratio-table entry after the table grammar is defined on the same front. | Double number lines, proportion problems, and percent. | established |
| Ratio table and double number line grammars | Ch. 8 fronts 09–12 | Front 09 defines each table column as one scaled ratio before asking for an entry; Front 10 defines aligned zeros and dashed pairing guides on the original mixture figure. | Front 09 completes a column; Front 10 interprets an aligned pair; analyzed Problem 11 and completion Problem 12 apply both grammars. | Proportional-table test and Chapter 10 conversion maps. | established |
| Rate, unit rate, "per," better-buy comparison | Ch. 8 fronts 13–15 | Front 13 defines a rate as a ratio of two different kinds of quantities and the unit rate as the per-one amount found by division; money is the only different-kind context, bridged in Ch. 7. | Front 13 finds a whole-dollar unit price; Front 14 a decimal one using Ch. 7 tenths-counting division. | Independent Problem 15 compares unit prices; percent rates and Chapter 10 conversion factors. | established |
| Proportional relationship and additive-versus-multiplicative comparison | Ch. 8 fronts 01, 16–20 | Front 16 defines a proportional relationship as all pairs forming the same ratio (constant per-one amount); Front 17 states the same-amount-per-one table test; Front 18 works a constant-difference non-example including the 0-pairs-with-0 boundary. | Fronts 16–18 classify with the test stated; no graph grammar is assumed. | Independent Problem 19 scales a tile pattern; mixed Problem 20 rejects the add-the-same-amount shortcut; percent and unit conversions. | established |
| Percent, per hundred, \% symbol, conversions among forms | Ch. 9 fronts 01–08 | Front 01 defines the comparison-to-100 and the symbol, bridging Ch. 8's "per"; Front 02 states the hundred-grid grammar on its own front; Fronts 03–06 teach each conversion direction from Ch. 7 hundredths and Ch. 6 equivalence; Front 08 sets the 100%-and-beyond boundary. | Front 01 writes 61 per 100 as a percent; Front 02 counts and names 27%; Fronts 03–06 convert one value each. | Cross-form comparison (Front 07), every part-whole-rate and consumer front, and Chapter 10 precision decisions. | established |
| Percent of a quantity, 10% anchor, part/whole/percent-rate roles, find-the-rate, find-the-whole | Ch. 9 fronts 09–16 | Front 09 bridges Ch. 6 "of" multiplication; Front 10 derives the 10% anchor from 1/10; Front 11 names the three roles via Ch. 8's unit-rate "per one"; Fronts 12–13 teach the rate and whole methods (part-over-whole fraction; Ch. 8 ratio-table scaling). | Analyzed Problem 14 (find the part) precedes completion Problem 15 (find the whole) and independent Problem 16 (find the rate). | Consumer fronts 17–22 and percent-change fronts 23–27. | established |
| Discount, sale price, sales tax, tip, percent change, percentage point, successive change | Ch. 9 fronts 17–27 | Fronts 17–18 define the take-off and add-on structures with worked money examples (money inbound from Ch. 7); Front 19's original price-breakdown bar states its grammar on the front; Front 23 defines percent change against the start on original before/after bars; Front 25 defines percentage points; Front 26 computes both successive steps. | Fronts 17–18 compute one sale price and one total; Front 19 reads the rate from the bar; Fronts 23–25 retrieve one change each. | Independent Problems 21–22 (discount, tip), diagnosis Front 20, mixed Problem 27 (points versus change), and Chapter 10 decisions. | established |
| Measurement, unit, scale reading, precision, unit identities | Ch. 10 fronts 01–11 | Front 01 defines measure/unit via the paper-clip example; Front 02 the agreed-unit rationale; Front 03 the approximate nature of measuring; Fronts 04–07 establish length, mass, capacity, and time identities with benchmarks; Front 08 states the ruler-scale grammar on its own front; Front 09 defines precision. | Fronts 01–09 each make one supported decision; faded Problem 12 reads between marks. | Conversions (13–19), critiques (20–22), mixed Problems 23–25. | established |
| Conversion, conversion map, rounded-value interval, reasonableness | Ch. 10 fronts 10–25 | Front 13 defines conversion as a "per" rate (multiply to a smaller unit) and Front 14 the divide direction; Front 15's map states its aligned-lines grammar on the front; Front 10 defines the rounded-value interval on the band figure with the half-up rule restated; Front 11 extends it to counts. | Fronts 10–11 and 13–15 retrieve one value each; analyzed Problem 16 executes a full conversion. | Diagnoses 17–19, critiques 20–22, interval-propagation Problem 23, better-buy Problem 24, insufficient-information Problem 25 (reusing the Ch. 9 discount structure). | established |

Rejected pilot examples (2026-07-22 regeneration):

- Money, prices, lengths, weights, temperatures, times, debts, fractions of
  objects, and arithmetic totals were rejected because they would borrow units,
  signed numbers, fractions, or operations from later chapters.
- A comma-separated numeral such as `12,450` was rejected because the comma
  convention has not earned a separate bridge.
- Rounding-error bounds written with inequalities were rejected because they
  would make symbol manipulation, rather than estimation, the hidden target.
- Spoken number-word names for multi-digit numerals (such as “seventy”) were
  rejected on answers; digit strings like `70` are used instead, because
  English number-name grammar is never established on a scheduled front.
- A rounding example ending in 5 was rejected for the analyzed problem because
  the tie convention deserves a stated rule before it decides a graded answer;
  the convention is stated on Fronts 14, 16, and 17 instead.

Rejected Chapter 2 examples:

- Prices, lengths, temperatures, debts, and fractional quantities were rejected
  because money, measurement units, signed quantities, and fractions are not in
  the resolved inbound closure.
- Letter placeholders for unknown parts were rejected because formal algebra is
  outside this deck and a question mark can express the bounded missing amount.
- A copied receipt, worksheet, or base-ten-block image was rejected; all
  contexts and technical figures are original, and the diagrams define their
  own grammar on scheduled fronts.

Rejected Chapter 6 examples (2026-07-23 regeneration):

- Measurement units, money, and time contexts (half a cup, three-quarters of a
  dollar, half an hour) were rejected because units and money belong to later
  chapters; all contexts use counted objects such as bars, panes, games, and
  game pieces.
- Decimal names and percent phrasing for fractions were rejected as
  later-chapter vocabulary.
- Letter placeholders in equivalence completions were rejected; a question
  mark expresses the bounded missing numerator without algebra.
- A benchmark-½ comparison with an odd denominator (such as 5/9) was rejected
  because locating half of an odd count of parts would smuggle in fraction
  multiplication before it is taught; even denominators carry that card.
- Unequal decorative “pizza slice” art was rejected per the design ledger; the
  equal-parts requirement is carried by an original strip figure whose grammar
  is stated on its own front.

Rejected Chapter 7 examples (2026-07-23 isolated regeneration):

- Measurement contexts (lengths, masses, litres, temperatures) were rejected
  because measurement units are reserved for Chapter 10; money is the only
  unit-like context and it receives its own bridge front before use.
- Percent phrasing for hundredths ("43 percent") was rejected as Chapter 9
  vocabulary; hundredths are named through fractions and the hundred grid.
- Repeating-decimal notation such as a bar over a digit was rejected; the 1/3
  boundary card states only that no decimal that ends equals 1/3, argued with
  division remainders and fraction comparison already established.
- Long division producing decimal digits was rejected as a method; decimal
  division is carried by tenths counting and by scaling both numbers by 10,
  both reachable from the inbound closure.
- Graded rounding retrievals whose deciding digit is 5 were rejected; the tie
  convention is restated on Front 24, but no graded answer in this chapter
  turns on the tie.

Rejected Chapter 8 examples (2026-07-23 isolated regeneration):

- Speed and every per-hour, per-day, or per-week rate were rejected because
  duration and measurement units are reserved for Chapter 10; the only
  different-kind rate context is money per counted item, since dollar-and-cent
  notation earned its bridge in Chapter 7.
- Recipe amounts in cups, litres, or grams were rejected for the same reason;
  mixtures use counted spoonfuls and counted drops instead.
- Percent phrasing for ratios was rejected as Chapter 9 vocabulary.
- Coordinate graphs of proportional relationships were rejected because axis
  grammar is deferred to the algebra deck; ratio tables and double number
  lines carry the representation work, as planned in the design ledger.
- Cross-multiplication and a letter constant of proportionality were rejected
  as algebraic machinery; missing values are found with scale factors,
  equivalent ratios, and unit rates only.
- The term "greatest common factor" was avoided; simplest form is reached by
  dividing both numbers by shared factors, matching the Ch. 6 bridge.
- An enlarged-photo width/height example for the additive-shortcut error was
  rejected because photo dimensions are length measurements; counted paint
  drops carry the same target.

Rejected Chapter 9 examples (2026-07-23 isolated regeneration):

- Interest rates, loans, and savings accounts were rejected because financial
  growth mechanisms exceed the consumer bridge the closure supports;
  discount, tax, and tip carry the consumer decisions.
- Measurement contexts (percent of a length, mass, or duration; battery
  percentage) were rejected because units are reserved for Chapter 10; all
  contexts use money and counted objects.
- Poll margins, charts, and other data-reporting contexts were rejected
  because statistics is excluded from this deck; the survey wording on Front
  01 carries no statistical machinery, only counting.
- Pie charts and percent-bar charts were rejected because their graph grammar
  is not established; the hundred grid and labeled original bar figures carry
  the visual work.
- An algebraic setup (letter for the unknown part or whole) was rejected;
  parts, wholes, and rates are found with decimal/fraction multiplication,
  part-over-whole fractions, and 10%-scaling only.
- Conversions producing repeating decimals (such as 1/3 as a percent) were
  rejected because repeating-decimal notation was deliberately excluded in
  Chapter 7; every conversion uses a denominator that reaches 100 exactly.
- Prices whose percent computations land on half a cent were rejected so no
  graded answer turns on the rounding tie convention.

Rejected Chapter 10 examples (2026-07-23 isolated regeneration):

- Customary units (inch, foot, mile, pound, ounce, cup) were rejected because
  a second parallel unit system would double the identity load without adding
  a new retrieval decision; the deck's SI-default convention carries length,
  mass, and capacity, and money plus time already supply familiar non-metric
  structure.
- A speed card (kilometers per hour) was rejected: no Chapter 10 target needs
  a compound distance-per-time reading, and money-per-liter unit price carries
  the Ch. 8 rate reuse.
- The millimeter was rejected as a named unit; ruler small steps are read as
  tenths of a centimeter with Ch. 7 decimals, avoiding a fourth length
  identity.
- Temperature scales were rejected: no target needs a degree identity, and
  authentic winter examples would pull signed quantities into unit work.
- Area and volume units (square meters, cubic centimeters) were rejected as
  geometry-deck territory.
- Significant-figures terminology was rejected; precision is expressed as the
  place of the last written digit, reachable from Ch. 7 place value.
- Inequality symbols for rounded-value intervals were rejected (consistent
  with the Chapter 1 decision); intervals are stated in words as "at least …
  and less than …," with the half-up tie convention restated wherever an
  interval endpoint depends on it.
- The gram is described as measuring "how heavy" an object is; the mass–weight
  distinction is a labeled simplification deferred to a science context.

Record rejected examples that depended on future chapters. The answer revealed
after an uninformed failure is not a first explanation.

## Retrieval portfolio

Across the deck, basic cards carry bounded explanation, translation,
comparison, and diagnosis. Problem cards carry method selection and execution
through analyzed, faded, independent, and mixed progression. Clozes are not
planned by default; they will be used only if an already-understood exact symbol
or phrase benefits from compact recall.

Primary interference pairs are quantity/numeral, digit/number, value/digit,
addition/multiplication, subtraction/division, factor/multiple, positive
sign/operation sign, numerator/denominator, fraction/ratio, decimal place-value
alignment/visual digit alignment, additive/multiplicative comparison,
percentage points/percent change, exact/estimated, and count/measurement.

## Chapter design ledger

Complete this before large-scale authoring and reconcile it at handoff. Add rows
or split columns when a chapter has several distinct figures or problems.

| Chapter | Retrieval targets | Basic-card roles | Cloze candidates | Problem progression | Representations and figure opportunities |
|---|---|---|---|---|---|
| 1. Quantities and whole numbers | Quantity/numeral, reliable counting, zero, whole number, digit/place value, comparison, exact/estimate, rounding to tens and hundreds. | 16 basic cards: minimal teaching bridges with supported retrieval, figure translation, comparison-symbol choice, and counting, place-value, and rounding-direction diagnoses. | None: every compact term first needs meaning and discrimination, so no exact already-understood target exists yet. | Supported classification and diagnosis → analyzed nearest-ten IPEE (Problem 15) → ones-digit-rule diagnosis → supported transfer to hundreds → independent authentic nearest-hundred rounding with a genuine distance check (Problem 18). | **Include 3:** grouped counters translating loops of ten plus singles into a two-digit numeral; ordered 0–10 number line with two labeled dots for comparison; 30–40 rounding stretch with halfway mark and a dot at 38 for distance comparison. **Omit:** counting-procedure illustration (the diagnosis targets the touch-once rule, not a spatial layout); hundreds-scale counter drawing (same grammar as the tens figure and illegible at phone width); photographed objects (decorative, licensing burden); comma-separated place-value chart (unneeded convention). |
| 2. Addition and subtraction | Join, separate, compare, find an unknown part, compute with place value, regroup, compensate, and check by inverse, estimate, and magnitude. | Planned 19 basic cards: scheduled teaching bridges, representation translation, method choice, inverse checks, and distinct error diagnoses. | None: every compact symbol or term first needs a meaningful scheduled bridge. | 4 problems: analyzed no-regrouping join → completion/regrouped addition → independent regrouped subtraction → mixed operation choice and execution. | **Include 3:** part–whole diagram for operation structure; open number line for place-value decomposition; before/after tens–ones exchange for regrouping. **Omit:** decorative shopping or stock art; copied manipulatives; a separate comparison bar because the part–whole grammar already supports the missing-part decision; a second exchange figure because the reversible diagram serves both operations. |
| 3. Multiplication and division | Equal groups, arrays, repeated scaling, sharing/grouping division, remainder meanings, inverse checks. | Planned 17 basic cards: translation, division-meaning contrast, partial products, and remainder diagnosis. | None: isolated facts do not yet justify schedules. | 4 problems: analyzed array → completion quotient/remainder → independent grouping → mixed operation choice. | **Include 3:** equal-groups array; sharing versus grouping panels; remainder grouping. **Omit:** multiplication table because it leaks facts. |
| 4. Operation structure and factors | Grouping marks, operation order, factor/multiple, divisibility, prime/composite, powers. | Planned 16 basic cards: structural cues, counterexamples, and key contrasts. | None: the convention is better retrieved through evaluation choices. | 4 problems: analyzed expression → faded order choice → independent factor/divisibility → mixed classification. | **Include 2:** expression tree; factor-pair arrays. **Omit:** prime spiral because visual pattern is not evidence. |
| 5. Signed quantities | Sign as direction/position, opposite, absolute distance, compare/add/subtract signed values. | Planned 15 basic cards: line interpretation, prediction, sign-role contrast, and diagnoses. | None: exact sign relations remain contextual. | 4 problems: analyzed movement → completion sum → independent position change → mixed sign diagnosis. | **Include 3:** signed positions; addition movement; subtraction/add-opposite comparison. **Omit:** thermometer photograph and unbridged domain units. |
| 6. Fractions | Equal parts, unit fraction, numerator/denominator, number-line magnitude, equivalence, operations, fraction of a quantity. | Planned 24 basic cards: representation translation, method rationale, and misconceptions. | None: symbolic identities are retrieved through meaningful comparisons. | 6 problems: analyzed partition → completion equivalence → faded addition → independent “of,” multiplication, and division → mixed comparison. | **Include 5:** equal-part area; fraction line; equivalence strips; set model; fraction-group division. **Omit:** unequal “pizza slices” and decorative food. |
| 7. Decimals | Decimal place value, fraction/decimal/money translation, comparison, rounding, four operations. | Planned 18 basic cards: place-value translation, alignment rationale, and display/trailing-zero diagnoses. | None: place names appear in meaningful retrieval. | 5 problems: analyzed grid → completion addition → independent multiplication/division → mixed money/rounding. | **Include 3:** hundred grid; decimal number line; aligned place-value columns. **Omit:** currency photographs and measurement contexts reserved for Chapter 10. |
| 8. Ratios, rates, and proportions | Ratio, equivalent ratios, unit rate, scale factor, proportional table, additive-versus-multiplicative distinction. | Planned 15 basic cards: representation translation, scaling prediction, and nonproportional diagnosis. | None: relations and method choices need reasoning. | 5 problems: analyzed double line → completion table → independent unit-rate/scaling → mixed shortcut rejection. | **Include 3:** two-kind collection; double number line; proportional/nonproportional table schematic. **Omit:** graphs until axis grammar is established in algebra. |
| 9. Percents | Per hundred, percent/fraction/decimal translation, part-whole-rate, discount/tax/tip, percent change and percentage points. | Refined pre-authoring (2026-07-23 isolated regeneration) to 21 basic cards: the 15-card sketch under-counted because each conversion direction (%→decimal, decimal→%, %→fraction, fraction→%), cross-form comparison, the 100%-and-beyond boundary, the 10% mental anchor, the three named roles, find-the-rate and find-the-whole methods, two consumer definitions, a consumer figure translation, a subtract-the-percent-number diagnosis, and the increase/decrease/point/successive-change contrasts are each an independent grading decision. | None: “per hundred” is used in decisions rather than isolated prose. | 6 problems: analyzed find-the-part with roles named → completion find-the-whole → independent find-the-rate → independent consumer discount → independent tip total → mixed percentage-point vs percent-change interpretation. The hundred grid anchors a basic translation card rather than the analyzed problem, because reading the grid is one bounded decision, not an IPEE-worthy method choice. | **Include 3:** hundred grid (defines per-hundred visually; count-and-name retrieval); price breakdown bar (find the discount rate from a labeled original/sale split); before/after bars (percent-increase retrieval anchored to the starting bar). **Omit:** copied ads and receipts; coordinate graphs (axis grammar deferred to the algebra deck); a second grid for percents over 100 (the times-the-whole statement carries it without a new representation). |
| 10. Measurement, estimation, and decisions | Measurement versus exact count; standard-unit rationale; length/mass/capacity/time unit identities with benchmarks; scale reading; precision claimed by a written report; rounded-value intervals for measurements and for counts; conversion in both directions; time-conversion error; mixed-unit addition; different-kind incompatibility; missing-unit and false-precision critique; benchmark reasonableness; rounding propagation; unit-price decision. | Refined pre-authoring (2026-07-23 isolated regeneration) to 20 basic cards: the 16-card sketch under-counted because each unit family (length, mass, capacity, time) needs its own identity-and-choice front, and interval reasoning splits continuous measurements from whole counts so each front stays one decision. | None: unit identities are applied inside meaningful retrievals, not memorized as isolated tokens. | 5 problems: analyzed conversion (IPEE ribbon cutting) → faded scale reading → independent rounded-total range (propagation) → independent better-buy conversion plus unit price → insufficient-information critique reusing the Ch. 9 discount structure. | **Include 3:** instrument scale (ruler with two pointers so a bridge read and a later faded read use distinct targets); conversion map (aligned km/m lines whose grammar is stated on the front); rounded-value interval band on a tenths number line. **Omit:** statistical data graphs (excluded domain); geometry-dependent scale drawings (later deck); a separate count-interval figure (verbal reasoning suffices once the continuous band figure establishes the idea); instrument photographs (original TikZ scales carry the reading skill without licensing burden). |

Card-form diversity is not a goal by itself. Zero clozes can be correct. A
visually rich chapter may require several figures because diagrams, graphs,
before/after states, and spatial constructions serve different retrieval roles.

## Initial-learning path

Chapter 1 alternates minimal teaching bridges with supported retrieval, then
fades support. It begins with everyday amounts and written labels, establishes
counting and whole numbers, builds multi-digit notation from grouped objects,
then adds number-line and comparison grammar. Only after exact-versus-estimated
amounts are understood does it teach rounding, demonstrate IPEE, diagnose an
error, generalize to hundreds, and ask for independent application.

Each later chapter must repeat this establish → retrieve → vary → diagnose →
apply pattern using only its declared closure. Full authoring remains blocked
until `.flashcards/audits/pilot-cold-start.md` passes and a human explicitly
approves the pilot.

## Figure policy

Add a figure only when inspecting, predicting, labeling, comparing, tracing, or
translating it is part of learning. Author new technical figures in TikZ by
default, compile them to responsive SVG before handoff, and commit source and
output together under repository-root `figures/NN_chapter/`; keep the shared
style at `figures/tikz-style.tex` and never create `flashcards/figures/`. Since
rendering runs from the repository root, load it with
`\\input{figures/tikz-style.tex}` rather than a source-relative path. Put
setup figures on the front and answer-revealing
annotations on the back. Record why an authentic target requires another medium.

Do not treat one figure per chapter as a target or cap. Inventory every
plausible spatial, temporal, structural, graphical, relational, experimental,
and before/after representation, then include or explicitly omit it according
to its retrieval value.

## Sources and accuracy

Record authoritative sources, licenses, access dates, contested points,
simplifications, and boundary conditions in `README.md`.

## Planned-versus-actual inventory

| Chapter | Planned forms/problems/figures | Actual at this gate | Reconciliation |
|---|---|---|---|
| 1 | 16 basic cards, 2 problem cards; no clozes; one analyzed and one independent IPEE application plus diagnoses; 3 TikZ figures. | 16 basic cards, 2 problem cards; no clozes; 3 TikZ figures (regenerated fresh on 2026-07-22). | Matches the design ledger. The analyzed problem models full IPEE on 73; the independent problem rounds 649 to the nearest hundred with a genuine distance check and uses no later-chapter operation or unit. |
| 2 | 19 basic, 4 problems, 0 clozes, 3 figures. | 19 basic, 4 problems, 0 clozes, 3 distinct TikZ/SVG figures used in 4 front placements. | Matches. The regrouping figure is deliberately reused for the reversible addition/subtraction exchange; the planned analyzed → completion → independent → mixed problem progression is present. |
| 3 | 17 basic, 4 problems, 0 clozes, 3 figures. | 17 basic, 4 problems, 0 clozes, 3 figures. | Matched: array, division-meaning contrast, and remainder grouping are independent visual decisions. |
| 4 | 16 basic, 4 problems, 0 clozes, 2 figures. | 18 basic, 4 problems, 0 clozes, 2 figures (regenerated fresh on 2026-07-23). | Two basics were added, not to raise volume: the equal-rank left-to-right rule was split from the precedence card because the two rules fail independently (a learner can rank operations correctly yet still misread ties), and a factor-versus-multiple direction card was added because the declared interference pair needs its own discrimination decision. Figure roles match: expression structure and factor-pair completeness need different representations. |
| 5 | 15 basic, 4 problems, 0 clozes, 3 figures. | 15 basic, 4 problems, 0 clozes, 3 figures (regenerated fresh on 2026-07-23). | Matched: signed positions, the leftward addition jump, and the subtract/add-opposite matched traces are distinct visual decisions, and the planned analyzed → completion → independent → mixed problem progression is present. |
| 6 | 24 basic, 6 problems, 0 clozes, 5 figures. | 28 basic, 6 problems, 0 clozes, 5 figures (regenerated fresh on 2026-07-23). | Four basics were added, not to raise volume: the negative-fraction card discharges the declared Ch. 5 prerequisite edge with a real retrieval; improper→mixed and mixed→improper are separate targets because each direction fails independently; same-numerator comparison was split from same-denominator because the two rules point in opposite directions and form an interference pair; and an estimation card closes the reasonableness thread the chapter map promises. Problems and figures match the plan exactly: analyzed partition → completion equivalence → faded addition → independent “of”/multiplication and division → mixed comparison, with area, line, equivalence-strip, set, and grouping-division figures. |
| 7 | 18 basic, 5 problems, 0 clozes, 3 figures. | 22 basic, 5 problems, 0 clozes, 3 figures (regenerated fresh in the 2026-07-23 isolated run). | Four basics were added, not to raise volume: the placeholder-zero contrast (0.07 vs 0.7) was split from trailing-zero equality (0.5 = 0.50) because the two zero roles fail independently and form an interference pair; a between-tenths density card was added because comparison and rounding both silently assume hundredths live between tenths marks; the whole-minus-decimal card (5 − 1.36) was separated from the completion addition because writing a whole number with decimal places is its own error site; and the 1/3 finite-decimal boundary card closes a correctness condition (U4) that conversion cards would otherwise overstate. Problems and figures match the plan exactly: analyzed grid → completion addition → independent multiplication and division → mixed money/rounding, with hundred-grid, decimal-line, and aligned-column figures. |
| 8 | 15 basic, 5 problems, 0 clozes, 3 figures. | 15 basic, 5 problems, 0 clozes, 3 figures (regenerated fresh in the 2026-07-23 isolated run). | Counts match the plan exactly. Two figure roles shifted without changing the count: the planned proportional-vs-nonproportional table schematic became inline markdown tables because the retrieval decision there is numeric, not spatial; and the planned single double-number-line figure split into a complete teaching figure (cocoa/sugar) and a query figure (beads, with the missing mark shown as a gold question mark) so the analyzed problem's answer is not printed on its own front. The shape-collection figure keeps its counting role. Planned analyzed → completion → independent → mixed problem progression is present. |
| 9 | 21 basic, 6 problems, 0 clozes, 3 figures (design refined pre-authoring on 2026-07-23 from the earlier 15-basic sketch; the design-ledger row records why each added basic is an independent grading decision). | 21 basic, 6 problems, 0 clozes, 3 figures (regenerated fresh in the 2026-07-23 isolated run). | Matches the refined design exactly. Problems run analyzed find-the-part → completion find-the-whole → independent find-the-rate → independent discount and tip → mixed points-versus-change; the hundred grid anchors a basic translation card instead of the analyzed problem, as the design ledger records. Figure roles match: per-hundred grid, price-breakdown bar, and before/after change bars are distinct visual decisions. |
| 10 | Refined pre-authoring plan: 20 basic, 5 problems, 0 clozes, 3 figures (original sketch said 16 basic). | 20 basic, 5 problems, 0 clozes, 3 TikZ figures (regenerated fresh in the 2026-07-23 isolated run). | Matches the refined plan. The +4 over the original sketch splits unit identities per quantity kind (length, mass, capacity, time) and splits interval reasoning into continuous and count fronts so each stays one grading decision. The ruler figure serves two distinct reads (bridge mark-read, faded between-marks read); the planned analyzed → faded → independent ×2 → critique problem progression is present, with the critique reusing the Ch. 9 discount structure. |
| **Complete deck** | **181 basic, 45 problems, 0 clozes, 31 figures, including the approved pilot and the refined chapter-9 and chapter-10 designs.** | **191 basic, 45 problems, 0 clozes, 31 figures; 236 cards total (chapters 9 and 10 regenerated fresh in 2026-07-23 isolated runs).** | **The chapter-4, chapter-6, chapter-7, chapter-9, and chapter-10 refinements are explained above. No planned target or figure role is missing, and no weak card was added to force a distribution.** |

## Validation gate

Before handoff:

1. Run `flashcards deck stabilize . --check`.
2. Run `flashcards deck validate .`.
3. Inspect every changed figure at phone width.
4. Reconcile planned versus actual card types, problems, and figures by chapter.
5. Run `git diff --check` and review the complete diff.
6. Summarize additions, changes, omissions, and any unresolved uncertainty.
