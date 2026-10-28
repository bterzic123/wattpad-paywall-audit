# Paywall Audit — Wattpad

**Live:** https://bterzic123.github.io/wattpad-paywall-audit/

Prepared for the Wattpad team by Adapty. Four ideas for the Wattpad Premium paywall, each backed by a number from [State of Paywalls 2026](https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=wattpad). There's also a clickable rebuild of the paywall and of what happens when it is closed, in Wattpad's own design. Flip **Today / Proposed** above the phone to compare.

## The four ideas

| # | Idea | Report anchor | Potential outcome |
| :-- | :-- | :-- | :-- |
| 1 | Give a cheaper way in when they close: Premium at 5,99 € a month | Only 4% of apps show a second paywall on close; it converts at 0.88× the main one and beats it in 45% of apps | ARPU +10–15% · based on Adapty data |
| 2 | Put the trial on the annual plan, and say what it saves | Trial on annual, emphasized: conversion +15–30% in winning A/B tests | CR +15–30% · observed in winning A/B tests |
| 3 | Show how the 7 days work, with real dates | 24% of top trial paywalls show a timeline; a trial explainer lifted ARPU 12–36%; 39.8% of US trials are cancelled within 24 hours | ARPU +12–36% · observed in winning A/B tests |
| 4 | Put your 4.7 and Editors’ Choice on the paywall | 27% of top paywalls show social proof; it lifted conversion 10–30% in winning tests | CR +10–30% · observed in winning A/B tests |

**Benchmark slice:** all categories, US (App Store data, Oct 2025–Sep 2026). The report has no Books category, and the US is Wattpad's largest App Store market by ratings.

## Grounding

Prices, plan names, feature lines and legal copy come from Wattpad's live iOS paywall (EUR storefront). The rating (4.7 from 706K ratings) and Editors’ Choice come from Wattpad's US App Store listing. Savings (26% on Premium+, 16% on Premium) are computed from those same prices. Nothing else is invented.

Impact ranges are observed lifts from winning A/B tests in State of Paywalls 2026 and Adapty's own data, not measured results for Wattpad.

## Run locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000.
