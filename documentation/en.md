<!-- ELUCENIA technical documentation · indice-de-tobin · en · no clinical/professional/rights approval -->

# Tobin index (rapid shallow breathing index)

[conditions, sources and permissions](https://elucenia.org/en/tools/indice-de-tobin)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Spontaneous respiratory rate

`fr`

breaths/min · range: 1–80

### Spontaneous tidal volume

`vt`

mL · range: 50–1500

## Method edition

RSBI/Yang–Tobin 1991: f/VT, VT in litres; do not confuse with VT in mL

## Documented formula

f/VT = respiratory rate (breaths/min) ÷ tidal volume (litres).

## Limits and population

RSBI was studied as a predictor of the outcome of ventilator-weaning attempts. The result depends on measurement conditions and technique and does not alone confirm airway-protection ability or extubation safety. A favorable index does not guarantee success.

## References

- [Yang KL, Tobin MJ. A prospective study of indexes predicting the outcome of trials of weaning from mechanical ventilation. N Engl J Med, 1991.](https://doi.org/10.1056/NEJM199105233242101)

- [Boles JM et al. Weaning from mechanical ventilation. Eur Respir J, 2007.](https://doi.org/10.1183/09031936.00010206)

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
