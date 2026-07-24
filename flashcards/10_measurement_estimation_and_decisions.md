+++
order = 10
subject = "mathematics"
authoring_model = "claude-fable-5"
authoring_reasoning_effort = "high"
tags = ["quantitative-reasoning", "measurement", "units", "estimation"]
prerequisites = ["chapter:09_percents"]
provides = ["measurement", "measurement-unit", "unit-conversion", "measurement-precision", "rounded-value-interval", "quantitative-reasonableness"]
+++

# Measurement, estimation, and decisions

## Measuring versus counting

<!-- card-id: f6f33461-c3d2-4d4f-b3aa-dd3bc3ded893 -->
Q: To **measure** a quantity is to find how much of it there is by
lining up a repeated **unit** — a chosen fixed amount — against it
and counting the copies: lay same-size paper clips end to end along
a pencil, count 6 clips, and the pencil is "6 clips long."
Counting answers *how many separate things*; measuring answers
*how much of something*. Which statement reports a count, and
which reports a measurement: "the shelf holds 12 books" or "the
shelf is 9 pencils long"?

A: "12 books" is a count of separate things; "9 pencils long" is a
measurement — the shelf's length compared with a repeated
pencil-length unit.

<!-- card-id: d4bee79f-b797-4723-8ccb-91a29c57ff2d -->
Q: Two cooks measure the same table's length in their own hand
widths: one counts 12 hands, the other counts 15. The table did not
change. Why do their numbers disagree, and what kind of unit would
make everyone's numbers agree?

A: Their units differ in size — a wider hand covers the table in
fewer copies — so the two counts describe different units, not
different tables. Numbers agree only when everyone measures with
the same agreed-on unit of fixed size.

<!-- card-id: 36eee8dc-f130-4e3a-be95-69d48deddd2c -->
Q: A carton's eggs can be counted exactly: 12, not "about 12." A
pencil measured in paper clips comes out "6 clips and a bit," and
a smaller unit would reveal still finer detail past the 6. Why can
a count be exact while a measurement is always approximate?

A: Separate whole things can be matched one by one, so a count
ends exactly. A measured amount can fall *between* any two unit
marks, so a measurement is a nearest-unit report, never a
guaranteed exact value.

## Standard units

<!-- card-id: c5515974-10bf-4961-ae6e-8a90b6d458e7 -->
Q: The **meter** (written m) is the worldwide agreed unit of
length — about the height of a door handle above the floor. Two
relatives rename it with prefixes: **centi-** means one hundredth,
so 1 **centimeter** (cm) is \(\frac{1}{100}\) of a meter and
100 cm = 1 m (a fingernail is about 1 cm across); **kilo-** means
one thousand, so 1 **kilometer** (km) is 1000 m (roughly the
length of ten city blocks). Which of these units best suits the distance
between two towns, and why?

A: The kilometer — town-to-town distances span many thousands of
meters, so km keeps the number small enough to grasp.

<!-- card-id: 0a088403-4337-4dbc-80ee-7838da0f17a8 -->
Q: The **gram** (g) and **kilogram** (kg) are the agreed units of
**mass** — how heavy an object is when picked up. As with length,
kilo- means one thousand: 1 kg = 1000 g. A paper clip weighs about
1 g; a thick textbook weighs about 1 kg. Which unit — g or kg —
best suits the mass of one apple, and what benchmark decides it?

A: Grams — an apple is far lighter than the textbook's 1 kg but
far heavier than a 1-g paper clip, so a count of grams (a couple
hundred) fits it naturally.

<!-- card-id: 3546f4b7-c32a-480f-bd39-6b001686ab4e -->
Q: The **liter** (L) is the agreed unit of **capacity** — how much
liquid a container can hold. **Milli-** means one thousandth, so
1 **milliliter** (mL) is \(\frac{1}{1000}\) of a liter and
1000 mL = 1 L. A large water bottle holds about 1 L; a small spoon
holds about 5 mL. Which unit — mL or L — best suits a single dose
of cough medicine, and why?

A: Milliliters — one dose is a spoonful or two, around 5 mL to
10 mL, a tiny fraction of one liter.

<!-- card-id: 00f2d833-0adc-41c7-ab41-a4bd0ec55dba -->
Q: Time has its own agreed units, and they do *not* follow the
tens pattern: 60 **seconds** (s) make 1 **minute** (min), and 60
minutes make 1 **hour** (h). How many minutes are in 2 hours?

A: 120 minutes — each hour contributes 60 minutes, and
\(2 \times 60 = 120\).

## Reading scales, precision, and rounded reports

<!-- card-id: 834d7c5a-1324-4c5e-947e-9570b31055ed -->
Q: A measuring tool carries a **scale**: a number line drawn on
the tool, with labeled marks at whole units and equal small steps
between them. On the ruler scale below, the labeled marks are
whole centimeters, and ten equal small steps split each centimeter
into tenths. A reading is the value where a pointer meets the
scale. What value does arrow A point to?

![A horizontal measuring scale from zero to six with a longer labeled mark at every whole centimeter and ten equal small steps between neighboring labeled marks; two arrows above the scale, labeled A and B, each point down at the scale — A at one of the labeled marks and B between two labeled marks](../figures/10_measurement_estimation_and_decisions/instrument_scale.svg)

A: 3 cm — arrow A meets the scale right at the labeled 3 mark.

<!-- card-id: 75dba8aa-2a2c-4f72-8803-392d41e0db28 -->
Q: A written measurement claims its own **precision** — how finely
the object was measured — through its last written place. As
*numbers*, 4.3 = 4.30; as *measurement reports*, 4.3 cm says
"measured to the nearest tenth of a centimeter," while 4.30 cm
says "measured to the nearest hundredth." Do the reports 4.3 cm
and 4.30 cm tell the reader the same thing?

A: No — they name the same number but claim different precision:
4.30 cm promises a measurement ten times finer than 4.3 cm. On a
measurement report, a trailing zero is a claim, not decoration.

<!-- card-id: 735cdd77-82d9-49c9-b402-61aef597b298 -->
Q: A stick is measured on a whole-centimeter scale and reported as
6 cm — meaning 6 was the nearest labeled mark, using the rule that
a value exactly halfway between marks is reported at the higher
one. The shaded band below covers every true position that would
be reported as 6 cm; that band is the report's **rounded-value
interval**. Reading the band's edges in tenths, what are the
shortest and longest true lengths the stick could have?

![A number line from five to seven with a longer labeled mark at each whole centimeter and small steps at tenths between them; a dot sits on the mark at six, and a shaded band along the line surrounds the dot, stretching partway toward five on the left and partway toward seven on the right](../figures/10_measurement_estimation_and_decisions/rounded_interval.svg)

A: At least 5.5 cm, and anything up to but not including 6.5 cm —
5.5 is halfway and reports upward to 6, while 6.5 would report
upward to 7. A reported value stands for a whole band of true
values, not a single point.

<!-- card-id: 04d508cc-a0da-4716-bf02-dd851128b6c1 -->
Q: Rounded-value intervals also apply to rounded *counts*. A
concert crowd was counted exactly, then reported rounded to the
nearest ten: "70 people." Using the halfway-rounds-up rule, what
are the smallest and largest true counts the report allows?

A: Smallest 65, largest 74 — 65 rounds up to 70, 74 rounds down to
70, and 75 would round up to 80. Because people come in whole
numbers, the interval holds only the whole counts 65 through 74.

<!-- card-id: 3ccc72bf-879f-4579-9105-b16c098375ae -->
P: On the ruler scale below, the labeled marks are whole
centimeters and each small step is one tenth of a centimeter. The
plan is fixed: name the last labeled mark before arrow B, count
the small steps past it, and combine the two as a decimal. Carry
it out: what is arrow B's reading?

![A horizontal measuring scale from zero to six with a longer labeled mark at every whole centimeter and ten equal small steps between neighboring labeled marks; two arrows above the scale, labeled A and B, each point down at the scale — A at one of the labeled marks and B between two labeled marks](../figures/10_measurement_estimation_and_decisions/instrument_scale.svg)

S: 4.6 cm — arrow B sits 6 small steps past the 4 mark, and
\(4 + 6 \times 0.1 = 4.6\).

EVALUATE: The picture agrees: B lies between the 4 and 5 marks and
a little past the middle, and 4.6 is indeed just past the halfway
value 4.5.

## Converting units

<!-- card-id: 1003ac79-fe84-4f0f-ade6-5e321ec0180c -->
Q: **Converting** a measurement rewrites it in a different unit of
the same kind: the amount stays the same while the number and unit
change together. Going to a *smaller* unit means more copies fit,
so the number grows: each meter holds 100 cm — a "100 cm per 1 m"
rate — so meters become centimeters by multiplying by 100. Convert
3 m to centimeters.

A: 300 cm — \(3 \times 100 = 300\). Same length, smaller unit,
bigger number.

<!-- card-id: 1f414364-c968-4bf0-bffc-e6e3c67deb33 -->
Q: Converting to a *bigger* unit divides, because many small units
bundle into one big one: every 1000 g bundles into 1 kg, so grams
become kilograms by dividing by 1000. Convert 250 g to kilograms.

A: 0.25 kg — \(250 \div 1000 = 0.25\), each digit shifting three
places smaller. That is a quarter of a kilogram, and 250 g is
indeed a quarter of 1000 g.

<!-- card-id: 46ff9e28-ead1-4751-8585-df00e7b9d034 -->
Q: A **conversion map** lines up the same distances in two units:
the two lines below start at the same zero, and each dashed guide
joins a distance on the kilometer line to that same distance on
the meter line directly below it — 1 km above 1000 m, 2 km above
2000 m. A dot marks 2.5 km. What meter value belongs at the
question mark?

![Two horizontal lines with zeros aligned at the left: the upper line has labeled marks at zero, one, two, and three kilometers, and the lower line has labeled marks at zero, one thousand, two thousand, and three thousand meters; dashed vertical guides join each kilometer mark to the meter mark directly below it, and a dot on the upper line between the two and three kilometer marks has a dashed guide leading down to a question mark on the lower line](../figures/10_measurement_estimation_and_decisions/conversion_map.svg)

A: 2500 m — 2.5 km sits halfway between 2 km and 3 km, so its
partner sits halfway between 2000 m and 3000 m; equally,
\(2.5 \times 1000 = 2500\).

<!-- card-id: 14dbea81-b4f9-40d3-9e6b-71f376893a71 -->
P: A ribbon is 3.4 m long. How many whole 20-cm pieces can be cut
from it?

S: 17 pieces.

IDENTIFY: A measurement division problem whose two lengths use
different units — the ribbon in meters, the piece size in
centimeters — so they cannot be combined as given.

PLAN: Convert the ribbon to centimeters (multiply by 100, since
the meter is being traded for a smaller unit), then divide the
ribbon length by the piece length to count pieces.

EXECUTE: \(3.4 \times 100 = 340\), so the ribbon is 340 cm, and
\(340 \div 20 = 17\).

EVALUATE: The units check out: centimeters divided by centimeters
per piece leaves a plain count of pieces. An estimate agrees: 3 m
is 300 cm, giving 15 pieces, so 17 pieces from 3.4 m is
reasonable.

<!-- card-id: 871bf06e-e310-4a48-9827-75ef29d10098 -->
Q: Nora converts 1.5 h to minutes and writes "1 h 50 min — so 110
minutes." Diagnose the error and give the correct number of
minutes.

A: She read the .5 as 50 minutes, as if an hour held 100 minutes.
Hours are built on 60: 0.5 h is half of 60 min, which is 30 min,
so 1.5 h is \(60 + 30 = 90\) minutes.

<!-- card-id: 558503c8-34b2-40ee-aec6-a52f918f7f34 -->
Q: A hallway is measured in two pieces: 1.2 m and 45 cm. Why is
\(1.2 + 45\) not the hallway's length, and what is the true total?

A: Those numbers count different-size units — meters and
centimeters — so their sum counts nothing. Convert to one unit
first: 1.2 m is 120 cm, and \(120 + 45 = 165\) cm total, which is
1.65 m.

<!-- card-id: 8ed87671-6276-44f1-bfc7-4b6734b2b23a -->
Q: A mover's cart holds a 3-kg box and a 2-L jug. Can any unit
conversion make "\(3 + 2 = 5\)" describe a real total amount of
something? Why or why not?

A: No — kilograms measure mass and liters measure capacity, two
different *kinds* of quantity. Converting only rewrites an amount
within one kind (like g to kg), so no conversion gives these two
numbers a common unit to add in.

## Sensible reports and decisions

<!-- card-id: 7284eb81-0507-49bd-b11b-700954dfa9ee -->
Q: A note left for a carpenter says "cut the board at 80." Why is
the instruction unusable as written, and what must be added?

A: It names a number but no unit, so it names no amount: 80 cm is
about desk height, while 80 m is nearly the length of a soccer
field. A measurement is a number *together with* its unit, so the
note must state one.

<!-- card-id: 295dc28d-152e-4616-a961-1ebbc7c6a10d -->
Q: One of these is a reasonable capacity for a full bathtub:
200 mL or 200 L. Which one, and what benchmark decides it?

A: 200 L — a large water bottle holds about 1 L, and a bathtub
clearly holds a couple hundred bottles' worth. 200 mL is only a
fifth of one bottle.

<!-- card-id: 29f3e053-c9e6-4872-84eb-da8350c95914 -->
Q: A garden fence is estimated as "about 30 m." A neighbor
converts: "that's 3000 cm — now we know the length to the nearest
centimeter." What is wrong with that claim?

A: Converting rewrites units; it cannot add knowledge. The
estimate was rough — good to within a few meters at best — and the
zeros in 3000 come from multiplying by 100, not from measuring.
The fence's length is known no more finely than before.

<!-- card-id: 4d10c895-4ee6-4253-ac78-01dbcb14b9be -->
P: Two clubs counted their sign-ups exactly but reported the
counts rounded to the nearest ten: 40 and 70. Using the
halfway-rounds-up rule, find the smallest and the largest true
total the two reports allow.

S: Smallest 100, largest 118.

IDENTIFY: Each reported count stands for a rounded-value interval
of whole numbers, so the true total ranges from the sum of the two
low ends to the sum of the two high ends.

PLAN: Write each report's interval, then add the two smallest
values and add the two largest values.

EXECUTE: "40" allows 35 through 44; "70" allows 65 through 74.
Smallest total: \(35 + 65 = 100\). Largest total:
\(44 + 74 = 118\).

EVALUATE: The naive total \(40 + 70 = 110\) sits inside 100–118,
as it must — yet the true total can miss it by up to 10, which is
why rounded reports should not be added as if they were exact.

<!-- card-id: 2cfa2a2e-3e4a-4a80-8b15-abc609a46423 -->
P: Juice comes in two bottles: 500 mL for \(\$2.00\) or 1.5 L for
\(\$4.50\). Which bottle is the better buy?

S: The 1.5 L bottle.

IDENTIFY: A better-buy comparison — two prices attached to
different amounts in different capacity units, so the rates cannot
be compared as written.

PLAN: Convert both amounts to the same unit, then compare the unit
price per liter.

EXECUTE: 500 mL is 0.5 L. Small bottle: two half-liters make a
liter, so \(2 \times 2.00 = \$4.00\) per liter. Large bottle:
\(4.50 \div 1.5\) — scaling both numbers by 10 gives
\(45 \div 15 = \$3.00\) per liter.

EVALUATE: A portion check agrees: 1.5 L holds three 500-mL
portions, and \(4.50 \div 3 = \$1.50\) per portion versus
\(\$2.00\) for the small bottle — the large bottle wins both ways.

<!-- card-id: f5e044d4-cea3-42cc-bb25-13d69ac727d5 -->
P: A shop window says "\(25\%\) off every juice bottle today!" Rio
wants to compute exactly what he will pay for one bottle. Can he,
from this information alone? If not, name precisely what is
missing and how it would be used.

S: No — the original price is missing. A percent is a rate, not an
amount: \(25\%\) off means \(0.25\) times *the original price*
comes off, so without that price the discount has no dollar value.
Given the original price, Rio would compute the discount as
\(0.25\) times it and pay the original price minus that discount.
