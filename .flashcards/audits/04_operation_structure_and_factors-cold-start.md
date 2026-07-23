# Cold-start audit — 04_operation_structure_and_factors

- Date: 2026-07-23
- Auditor: authoring agent (claude-fable-5), isolated fresh-agent regeneration
- Method: the chapter design ledger and concept-dependency ledger below were
  frozen before card drafting. After drafting, every scheduled front (Q: or P:
  block, including figure alt text and supplied premises) was scanned in
  intended first-learning order for domain-bearing terms, symbols,
  representations, and procedures, and each dependency was recorded before the
  answer was consulted. Each resolves to one of: **inbound** (Chapter 1, 2, or
  3 scheduled cards, per the machine-resolved closure), **earlier**
  (established by a scheduled Chapter 4 card that precedes it), or **self**
  (defined on the same front before first use, using only established
  language).
- Inbound closure: `chapter:03_multiplication_and_division`, whose own closure
  includes `chapter:02_addition_and_subtraction` and
  `chapter:01_quantities_and_whole_numbers`. No external decks, no assumed
  tools. No other chapter is inbound; explicit edges are in force.

## Inbound frontier (Chapters 1–3)

From Chapter 1: quantity and numeral; counting; zero; whole numbers; digits;
place value (ones, tens, hundreds); placeholder zero; number line with
rightward growth; comparison symbols `<` and `>`; exact value vs. estimate;
rounding with the round-half-up-at-halfway convention;
IDENTIFY/PLAN/EXECUTE/EVALUATE problem labels.

From Chapter 2: addition, `+`, `=`, sum/total; part–whole diagram; operation;
number-line jumps; column alignment; regrouping as an equal-value exchange;
subtraction, `-`, difference; removal, comparison, and unknown-part meanings;
inverse operations and inverse checks; place-by-place computation; estimate,
bound, and alignment error diagnosis; compensation.

From Chapter 3: equal groups; multiplication, `×`, "times"; factor (of a
multiplication statement) and product; groups-first reading convention;
repeated addition; arrays with rows and columns; order of factors leaves the
product unchanged; ×1 and ×0; multiplying by ten via place value; partial
products; division, `÷`, quotient; sharing and grouping meanings;
multiplication–division inverse; division by zero undefined; remainder and
"q r r" notation; remainder bound and rebuild check; one-more-group
interpretation; build-up division; addition-vs-multiplication cue; figure
grammar: counters, arrays, loops enclosing one group.

## Chapter design ledger (frozen before drafting)

Retrieval targets → card forms, in scheduled order:

| # | Form | Target | Numbers |
|---|---|---|---|
| 1 | Q | Arithmetic expression; why one string of operations needs a shared reading rule (teaching bridge; both candidate readings supplied) | 5+3×2 → 16 vs 11 |
| 2 | Q | Grouping marks (parentheses); compute inside first | (9−4)×2=10; 9−(4×2)=1 |
| 3 | Q | Convention: multiply/divide before add/subtract when no marks | 5+3×2=11; task 20−2×7=6 |
| 4 | Q | Equal-rank operations read left to right; marks override | 10−4−3=3; 10−(4−3)=9 |
| 5 | Q | Diagnose the all-left-to-right error | 8+6÷2≠7; =11 |
| 6 | Q | Translate a structure diagram into a marked expression (figure 1) | (7−2)×3=15 |
| 7 | Q | Exponent notation; base, exponent, power (teaching bridge; expansion supplied) | 3^4=81; task 2×2×2=2^3=8 |
| 8 | Q | Diagnose the base-times-exponent error | 2^5≠10; =32 |
| 9 | Q | Complete order: marks → powers → ×,÷ → +,−; powers before multiplication | 2×3^2=18, not 36 |
| 10 | P | Analyzed IPEE: evaluate a three-operation expression | 50−4×3^2=14 |
| 11 | P | Faded: choose between marked and unmarked expressions for a context | 3×(4+2)=18 vs 3×4+2=14 |
| 12 | Q | Factor of a number = divides with remainder 0 (teaching bridge from Ch. 3 factor-of-a-statement) | 4 yes, 5 no, for 12 |
| 13 | Q | Factor pairs; arrays show pairs; every number's 1-and-itself pair (figure 2) | 12: 1,2,3,4,6,12 |
| 14 | Q | Multiples; the list never ends | first five multiples of 4 |
| 15 | Q | Diagnose reversed factor/multiple statement; decisive direction cue | 3 and 12 |
| 16 | Q | Divisible by; even and odd defined by divisibility by 2 | 9 → odd (9÷2=4 r 1) |
| 17 | Q | Ones-digit divisibility rules for 2, 5, 10, and why they work | 85 → 5 only |
| 18 | Q | Prime and composite among whole numbers greater than 1 (teaching bridge) | 5 prime; 9 composite |
| 19 | Q | Why 1 is neither prime nor composite; the classification's scope | 1 has one factor |
| 20 | Q | Diagnose "no even number is prime"; the lone even prime | 2 |
| 21 | P | Independent: all factors of a number via ordered pair search with stop rule | 36 |
| 22 | P | Mixed: prime/composite decides whether an equal-teams split exists | 27 yes; 23 no |

Problem progression: analyzed (10) → faded choice (11) → independent (21) →
mixed discrimination (22), per the deck blueprint. Clozes: none — every
target here is either newly built meaning or a decision procedure, and no
exact, compact, already-understood formulation precedes the cards that would
test it (consistent with the deck-wide zero-cloze plan).

Figure opportunities (assessed by retrieval role):

- **Included — `expression_structure`**: an expression's grouping is a
  genuinely structural fact; a boxes-and-arrows diagram shows which result
  feeds which operation, and translating that structure into a correctly
  marked expression is the retrieval decision (the front shows the structure,
  not the expression or its value).
- **Included — `factor_pair_arrays`**: a factor pair is exactly a rectangular
  arrangement; two arrays of the same 12 counters make pair-ness inspectable,
  and compiling the complete factor list from them is the decision. The alt
  text describes the structure without stating the array dimensions, because
  the dimensions are the answer.
- **Omitted — order-of-operations pyramid/staircase chart**: the rank list is
  short verbal knowledge; a decorated chart adds no structural content and
  risks becoming a memorized picture instead of a reading procedure.
- **Omitted — factor rainbow for 36**: the ordered-pair search in problem 21
  is itself the target procedure; a rainbow diagram would reveal the pair
  list the learner must produce.
- **Omitted — prime spiral / sieve grid**: pattern-gazing over many numbers
  is outside this chapter's smallest sufficient set; classification here
  rests on the two-factor definition, not on sieve patterns (recorded in the
  deck blueprint as the intentional omission for this chapter).
- **Omitted — number-line skip picture for multiples**: Chapter 2's
  number-line jump grammar already covers equal rightward jumps; words
  suffice and a figure would add no new retrieval decision.

## Concept-dependency ledger

| Concept, symbol, or representation | Required on front(s) | Inbound source or first establishment | First supported retrieval | Later application | Status |
|---|---|---|---|---|---|
| Arithmetic expression (a string of numbers and operation signs naming one value) | 1 onward | Front 1 defines it on the 5+3×2 example with both candidate readings supplied | Front 1 states why a shared rule is needed | Every later evaluation | established |
| Grouping marks (parentheses); compute inside first | 2, 4, 6, 9–11, 22 | Front 2 defines the marks on two fully marked expressions | Front 2 evaluates both | Fronts 4, 6, 9; problems 10–11 | established |
| Multiply/divide before add/subtract (no-marks convention) | 3, 5, 9–11 | Front 3 states the convention and resolves the front-1 ambiguity | Front 3 evaluates 20−2×7 | Diagnosis 5; order 9; problems 10–11 | established |
| Equal-rank left-to-right reading | 4, 5, 9 | Front 4 states the tie rule on 10−4−3 | Front 4 contrasts the marked version | Diagnosis 5; complete order 9 | established |
| Structure diagram grammar (boxes and arrows; result feeds next operation) | 6 | Self: bridged on front 6 using established part–whole-diagram language | Front 6 translates the diagram | none (single-use representation, noted) | established |
| Exponent notation; base; exponent; power | 7–10 | Front 7 defines the notation with the expansion of 3^4 supplied | Front 7 writes 2×2×2 as a power | Diagnosis 8; order 9; problem 10 | established |
| Complete order: marks → powers → ×,÷ → +,− | 9–11, 22 | Front 9 assembles the full list from fronts 2–4 and 7 | Front 9 evaluates 2×3^2 | Problems 10–11; expression checks in 22 | established |
| Factor of a number (divides with remainder 0) | 12 onward | Front 12 defines it against the Ch. 3 factor-of-a-statement meaning | Front 12 decides 4 and 5 for 12 | Pairs 13; direction 15; divisibility 16–17; prime 18–20; problems 21–22 | established |
| Factor pair; arrays display pairs; 1-and-itself pair | 13, 21 | Front 13 defines pairs on the two-array figure; the 1-and-itself pair is stated on the front | Front 13 compiles the factors of 12 | Ordered pair search in problem 21 | established |
| Multiple of a number | 14, 15 | Front 14 defines multiples as products with the counting numbers 1, 2, 3, … | Front 14 lists the first five multiples of 4 | Direction diagnosis 15 | established |
| Factor/multiple direction (smaller divides; larger is built) | 15 | Front 15 poses the reversed statement for repair | Front 15 states the decisive cue | Correct usage throughout 16–22 | established |
| Divisible by (division leaves remainder 0) | 16, 17, 18, 22 | Front 16 defines it from the front-12 factor test | Front 16 classifies 9 | Ones-digit rules 17; prime work 18–22 | established |
| Even and odd | 16, 17, 20 | Front 16 defines both by divisibility by 2 | Front 16 | Rule 17; even-prime diagnosis 20 | established |
| Ones-digit divisibility rules for 2, 5, 10 | 17, 21–22 | Front 17 derives the rules from each ten splitting evenly | Front 17 tests 85 | Quick eliminations in problems 21–22 | established |
| Prime; composite (whole numbers greater than 1) | 18–20, 22 | Front 18 defines both by counting factors | Front 18 classifies 9 | Scope 19; diagnosis 20; problem 22 | established |
| 1 is neither prime nor composite | 19 | Front 19 derives it from 1's single factor | Front 19 | Correct scoping in problem 22 | established |
| Ordered pair search with stop rule | 21, 22 | Problem 21's PLAN names the search: test 1, 2, 3, … and stop when pairs repeat | Problem 21 executes it for 36 | Prime testing in problem 22 | established |
| Trial-division stop rule for primality (stop when trial×trial passes the number) | 22 | Problem 22's PLAN derives the stop from repeating pairs (front-21 rule) | Problem 22 tests 23 | none (chapter end) | established |

## Front-by-front audit

Cards listed in scheduled order. Dependencies were recorded from each front
(including supplied premises and figure alt text) before the answer was
consulted.

1. `cc3d1361` — Q, arithmetic-expression bridge (5+3×2 read two ways).
   Dependencies: single-operation statements, `+`, `×`, `=` (inbound,
   Ch. 2–3); **arithmetic expression** (self: defined on this front before
   the question); both candidate readings are supplied as separate
   established-form equations (5+3=8, 8×2=16; 3×2=6, 5+6=11), so no reading
   convention is needed to follow them. The target — why a shared rule is
   needed — uses no unestablished idea.
2. `c16d691d` — Q, grouping marks.
   Dependencies: expression (earlier: card 1); **grouping marks/parentheses**
   and compute-inside-first (self: defined before the task); both task
   expressions are fully marked, so no precedence convention is required;
   subtraction and multiplication arithmetic (inbound).
3. `51a46017` — Q, multiply/divide-before-add/subtract convention.
   Dependencies: expression and the card-1 ambiguity (earlier: card 1); the
   convention (self: stated on front, with the worked 5+3×2 resolution
   supplied); task 20−2×7 uses established subtraction and multiplication.
4. `9e541a38` — Q, equal-rank left-to-right.
   Dependencies: rank language ("multiplication and division above addition
   and subtraction") (earlier: card 3); the tie rule (self: stated on
   front); grouping marks for the contrast expression (earlier: card 2).
5. `2f517395` — Q, diagnosis of the all-left-to-right error.
   Dependencies: precedence convention (earlier: card 3); left-to-right tie
   rule and "rank" (earlier: card 4); division arithmetic 6÷2 (inbound,
   Ch. 3); the flawed reasoning is quoted as the object of diagnosis (self).
6. `aa4ea559` — Q, structure-diagram figure translation.
   Dependencies: part–whole diagram analogy (inbound, Ch. 2); diagram
   grammar — circles hold numbers, boxes hold operations, arrows feed
   results (self: stated on front before the figure); `?` as unknown
   (inbound, deck convention from Ch. 2); grouping marks for the answer
   expression (earlier: card 2); precedence for the unmarked contrast in
   the answer (earlier: card 3). Figure alt text names only the structure —
   neither the marked expression nor any value appears in the figure or
   alt text.
7. `e62778cf` — Q, exponent-notation bridge.
   Dependencies: repeated-addition-earned-multiplication analogy (inbound,
   Ch. 3); **power, base, exponent** and the notation \(3^4\) (self: defined
   with the full expansion supplied as established-form equations); "used as
   a factor" (inbound: factor of a statement, Ch. 3); task 2×2×2 uses only
   established multiplication.
8. `9058d2ea` — Q, diagnosis of the base-times-exponent error.
   Dependencies: base/exponent meaning (earlier: card 7); the flawed
   reasoning quoted (self); step-by-step doubling arithmetic (inbound).
9. `7b97cf36` — Q, complete order with powers.
   Dependencies: grouping marks (card 2), precedence (card 3), left-to-right
   (card 4), powers (card 7) — all earlier; the assembled four-step order
   (self: stated on front); task 2×3² and the 36 contrast use established
   pieces.
10. `e0367a1f` — P, analyzed evaluation of 50−4×3².
    Front dependencies: expression (card 1), power notation (card 7),
    no-marks reading (cards 3, 9). Solution uses the complete order
    (card 9), inverse addition check (inbound, Ch. 2), and a size/bound
    remark using established comparison (inbound, Ch. 1). IPEE labels
    inbound (Ch. 1).
11. `c8315878` — P, faded choice between marked and unmarked expressions.
    Front dependencies: equal groups (inbound, Ch. 3), grouping marks
    (card 2), precedence (card 3); both candidate expressions are supplied.
    Solution uses inside-first (card 2), precedence (card 3), and a
    repeated-addition check (inbound, Ch. 3).
12. `4ab60215` — Q, factor-of-a-number bridge.
    Dependencies: factor of a statement (inbound, Ch. 3, explicitly
    contrasted on the front); division with remainder and remainder-0
    exactness (inbound, Ch. 3); equal-groups language (inbound); **factor
    of a number** (self: defined before the task); rebuild check (inbound,
    Ch. 3).
13. `4dbc4e38` — Q, factor pairs on the two-array figure.
    Dependencies: factor of a number (earlier: card 12); **factor pair**
    and the 1-and-itself pair (self: stated on front); array rows/row-size
    reading (inbound, Ch. 3 array grammar); the completeness remark in the
    answer uses division-with-remainder (inbound) and turned-pair language
    (inbound: Ch. 3 order-of-factors). Figure alt text describes two
    unlabeled arrays only — the dimensions are the answer and appear
    nowhere on the front or in the alt text.
14. `d5b0904f` — Q, multiples.
    Dependencies: products (inbound, Ch. 3); counting numbers 1, 2, 3, …
    (inbound, Ch. 1); **multiple** (self: defined with the multiples-of-3
    example before the multiples-of-4 task).
15. `a5b14504` — Q, factor/multiple direction repair.
    Dependencies: factor of a number (earlier: card 12); multiple (earlier:
    card 14); the reversed statement quoted (self); division and
    multiplication rebuilds (inbound).
16. `aef1d17a` — Q, divisible/even/odd.
    Dependencies: factor test via remainder 0 (earlier: card 12);
    **divisible by**, **even**, **odd** (self: defined before the task);
    division arithmetic 9÷2 (inbound, Ch. 3).
17. `cced5563` — Q, ones-digit rules for 2, 5, 10.
    Dependencies: divisibility (earlier: card 16); place value — tens and
    ones digits (inbound, Ch. 1); each ten splitting into twos/fives/tens
    (self: derived on front from established equal-groups facts 5×2=10,
    2×5=10, 1×10=10 in prose); the rules themselves (self: stated before
    the task); rebuild 5×17 via partial products (inbound, Ch. 3).
18. `70d6d27e` — Q, prime/composite bridge.
    Dependencies: factors of a number and factor pairs (earlier: cards
    12–13); counting factors (inbound counting); **prime**, **composite**,
    and the greater-than-1 scope (self: defined with the worked example 5
    before the task on 9); trial remainders for 5 asserted and re-derived
    in this audit (5÷2=2 r 1, 5÷3=1 r 2, 5÷4=1 r 1).
19. `02fb6334` — Q, why 1 is neither.
    Dependencies: prime/composite factor counts and scope (earlier:
    card 18); 1×1=1 (inbound, Ch. 3 ×1 meaning); factor pair 1-and-itself
    (earlier: card 13).
20. `4548500e` — Q, even-prime diagnosis.
    Dependencies: even (earlier: card 16); prime/composite factor counts
    (earlier: card 18); the flawed claim quoted (self); divisibility of
    even numbers by 2 (earlier: cards 16–17).
21. `b2e134fa` — P, independent factor search for 36.
    Front dependencies: factor of a number (card 12) only. Solution uses
    factor pairs (card 13), ones-digit rules for quick 2-and-5 decisions
    (card 17), partial products (inbound, Ch. 3), and the ordered search
    with stop-at-partner rule (self: stated in PLAN and derived from
    turned-pair repetition, card 13's completeness idea). IPEE inbound.
22. `656c81b9` — P, mixed equal-teams discrimination (27 vs. 23).
    Front dependencies: equal-groups split (inbound, Ch. 3); more-than-one
    comparison (inbound, Ch. 1). Solution uses factor pairs (card 13),
    prime/composite (card 18), ones-digit rules (card 17), trial division
    with remainders (inbound, Ch. 3), and the trial-times-itself stop rule
    (self: derived in PLAN from the card-21 stop-at-partner rule).

## Boundary checks

- No later-chapter material on any front or answer: no negative numbers,
  fractions, decimals, or letter variables (`?` and prose mark unknowns);
  no divisibility rules beyond 2, 5, 10 (no casting out threes or nines);
  no prime factorization, factor trees, greatest common factor, or least
  common multiple; no exponent rules (no product-of-powers laws, no zero
  exponent); no square-root language and no geometric "squared/cubed"
  names — powers are read only as "to the second/fourth power"; no long
  division.
- Deck conventions respected: groups-first multiplication reading is used
  in every array and team context; `?` marks the unknown in the structure
  figure, matching the Ch. 2 precedent; no calculator or tool assumed.
- Terminology collisions checked: "factor of a number" (card 12) is
  explicitly bridged from Ch. 3's "factor of a statement" on its first
  front; "power" is introduced only as the reading of exponent notation;
  "rank" is introduced in card 3–4 as ordinary comparative prose
  ("outranks"), not as a technical term requiring separate establishment.
- All arithmetic on cards was re-derived during the scan: 5+3=8, 8×2=16;
  3×2=6, 5+6=11; 9−4=5, 5×2=10; 4×2=8, 9−8=1; 2×7=14, 20−14=6; 20−2=18
  (rejected-structure remark); 10−4=6, 6−3=3; 4−3=1, 10−1=9; 8+6=14 (the
  flawed path), 6÷2=3, 8+3=11; 7−2=5, 5×3=15; 2×3=6, 7−6=1; 3×3=9, 9×3=27,
  27×3=81; 2×2=4, 4×2=8; 4×2=8, 8×2=16, 16×2=32; 3²=9, 2×9=18, 2×3=6
  (rejected base); 3²=9, 4×9=36, 50−36=14, check 14+36=50; 4+2=6, 3×6=18,
  3×4=12, 12+2=14, check 6+6+6=18; 12÷4=3 r 0 (4×3=12), 12÷5=2 r 2
  (5×2=10, 10+2=12); pairs of 12: 1×12, 2×6, 3×4; 4×1=4 … 4×5=20 (4, 8,
  12, 16, 20); 12÷3=4 r 0, 3×4=12; 9÷2=4 r 1 (2×4=8, 8+1=9); 85÷5=17
  (5×17: 5×10=50, 5×7=35, 50+35=85); factors of 5: 5÷2=2 r 1, 5÷3=1 r 2,
  5÷4=1 r 1; factors of 9: 1, 3, 9 (3×3=9, 9÷2=4 r 1); 1×1=1; factors of
  2: 1 and 2; 36: 1×36, 2×18 (2×18: 2×10=20, 2×8=16, 20+16=36), 3×12
  (30+6=36), 4×9=36, 5 fails (ones digit 6; 36÷5=7 r 1, 5×7=35), 6×6=36;
  27: 3×9=27; 23: 23÷3=7 r 2 (3×7=21, 21+2=23), 23÷4=5 r 3 (4×5=20,
  20+3=23), 5×5=25>23.
- Figures: two original TikZ sources compiled to SVG via
  `flashcards deck render-figures` with `viewBox`, `role='img'`,
  `<title>`, and `<desc>`; inspected at phone width (105 pt and 141 pt
  natural widths, high-contrast navy/pale palette, shape and label cues
  beyond color). Neither figure nor its alt text prints the expression,
  value, or array dimensions its card asks for.

## Result

cold_start_status: pass
unresolved_dependencies: 0
