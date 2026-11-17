# Airline compensation claim forms

Where each airline takes compensation claims for delayed and cancelled flights: its own claim form, or the page that leads to it, with what the link opens. Every link was opened on the airline's own website, and each row gives the date it was checked.

- 13 airlines that fly to and from the UK, from British Airways and easyJet to KLM and Air Canada
- Checked on 8 and 9 November 2026

Maintained by [Flight Compensation Check](https://flightcompensationcheck.com), a free check of whether a delayed or cancelled flight is owed compensation under UK261 or EU261. Each airline has a page there with how to claim from it, for example [easyJet](https://flightcompensationcheck.com/easyjet-compensation-claim) and [British Airways](https://flightcompensationcheck.com/british-airways-compensation).

## Files

- `airline-claim-forms.csv`: one row per airline
- `airline-claim-forms.json`: the same rows as JSON

| Column | Meaning |
|---|---|
| `id` | Short name |
| `airline` | The airline |
| `claim_url` | The airline's claim form, or its page that leads to it |
| `opens` | What the link opens, and what to choose there |
| `checked` | The date the link was opened and checked, as YYYY-MM-DD |
| `details` | The airline's page on Flight Compensation Check |

## Things to know

- You can claim direct from the airline using these links. Claims companies chase the airline for you and usually keep a share of the compensation.
- Airlines move these pages without notice. If a link breaks, start from the airline's help pages.
- This is guidance, not legal advice.

## Corrections

If a link has moved, open an issue with the new one.

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You can reuse the data, including commercially, if you credit Flight Compensation Check with a link to https://flightcompensationcheck.com.
