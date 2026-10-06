<!-- ELUCENIA technical documentation · escala-de-lawton · en · no clinical/professional/rights approval -->

# Lawton–Brody Scale (IADL)

[conditions, sources and permissions](https://elucenia.org/en/tools/escala-de-lawton)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Telephone

`tel`

- `a` — Uses the telephone independently (looks up and dials numbers)
- `b` — Dials some familiar numbers
- `c` — Answers but does not dial
- `d` — Does not use the telephone

### Shopping

`compras`

- `a` — Does all shopping independently
- `b` — Does only small purchases independently
- `c` — Needs someone to accompany them for any shopping
- `d` — Unable to shop

### Meal preparation

`comida`

- `a` — Plans, prepares and serves adequate meals independently
- `b` — Prepares meals if provided with ingredients
- `c` — Heats and serves prepared meals, but does not maintain an adequate diet
- `d` — Needs meals to be prepared and served by others

### Household tasks

`casa`

- `a` — Manages the home independently or with occasional help for heavy tasks
- `b` — Does light tasks (washing dishes, making the bed)
- `c` — Does light tasks but does not maintain adequate cleanliness
- `d` — Needs help with all tasks
- `e` — Does not perform any household tasks

### Laundry

`roupa`

- `a` — Washes all personal clothing
- `b` — Washes small items of clothing
- `c` — All clothing is washed by others

### Transport

`transp`

- `a` — Uses public transport or drives independently
- `b` — Takes a taxi or ride-hailing service alone but does not use public transport
- `c` — Uses public transport when accompanied
- `d` — Travels only by taxi or car with another person’s assistance
- `e` — Does not leave home

### Medication

`remedio`

- `a` — Takes medication independently at the correct dose and time
- `b` — Takes medication if someone prepares the doses beforehand
- `c` — Unable to take medication independently

### Finances

`dinheiro`

- `a` — Manages finances independently
- `b` — Makes everyday purchases but needs help with banking and major purchases
- `c` — Unable to manage money

## Method edition

Lawton–Brody 1969: local 8-domain adaptation 0–1, total 0–8 for both sexes; not the original sex-specific version

## Documented formula

Each activity scores 1 (independent) or 0 (dependent) by the described level:

Telephone: 1 for the first three levels.

Shopping and meal preparation: 1 only for the first level.

Housework: 1 for every level except “does not participate”.

Laundry: 1 for the first two levels.

Transport: 1 for the first three levels.

Medicines: 1 only for the first level.

Finances: 1 for the first two levels.

Total 0 (dependent) to 8 (independent).

## Limits and population

This version of Lawton assesses eight instrumental activities and uses a total from 0 to 8 for all genders, following the 2019 HIGN guidance; it does not apply the former five-item male scoring system. The guidance consulted does not recommend the instrument for institutionalized older adults. Answers from the person or an informant describe perceived function and do not demonstrate actual performance of each task; they may overestimate or underestimate ability and fail to capture small changes. Record who answered and the assessment context.

## References

- [Lawton MP, Brody EM. Assessment of older people: self-maintaining and instrumental activities of daily living. Gerontologist, 1969.](https://doi.org/10.1093/geront/9.3_Part_1.179)

- [HIGN,TryThis23,revised2019](https://hign.org/sites/default/files/2020-06/Try_This_General_Assessment_23.pdf)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Independent in instrumental activities


### 2

Dependency in 3 activities: shopping, medications, finances


### 3

Dependency in 6 activities: shopping, meal preparation, housework, laundry, transportation, medications

