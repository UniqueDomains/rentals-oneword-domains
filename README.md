# Available .RENTALS One-Word Domains (5,621,963)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-9%2C202%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-5%2C621%2C963%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .rentals one-word domains from Unique Domains.

> **Important:** this repository is a **public 9,202-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **5,621,963 domains** on the canonical page below.

**Public extract:** 9,202 rows · **Live catalog:** 5,621,963 domains

**Last updated:** 2026-04-09  
**Canonical page:** `https://unique.domains/domains/tld/rentals`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/rentals?utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <a href="https://unique.domains/domains/tld/rentals?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_create_radar"><b>🔔 Create Radar</b></a> ·
  <a href="https://unique.domains/domains/tld/rentals?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_start_project"><b>🚀 Start a Project</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./rentals.csv">CSV</a> / <a href="./rentals.json">JSON</a>
</p>

<p align="center">
  <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_methodology">Methodology</a> ·
  <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_api_docs">API docs</a>
</p>

---

> This repo is the sample. The live product keeps the exact search context and adds saved workflows, deeper filters, and richer price, demand, and risk context.

**Choose your next step**
- **Investors:** [Create a Radar from this exact .RENTALS search](https://unique.domains/domains/tld/rentals?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_create_radar)
- **Founders:** [Start a Project from this exact .RENTALS search](https://unique.domains/domains/tld/rentals?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_start_project)
- **Researchers / builders:** [Download CSV](./rentals.csv) or [Download JSON](./rentals.json)

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .RENTALS one-word domain catalog.

### Files

- `rentals.csv` — public CSV extract (9,202 rows)
- `rentals.json` — public JSON extract (9,202 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## Why leave GitHub?

| GitHub extract          | Live product                                     |
| ----------------------- | ------------------------------------------------ |
| 9,202-row public sample | 5,621,963 live domains                           |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, the live product is where the exact search becomes a workflow.

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/rentals-oneword-domains/main/rentals.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| track.rentals      | available | $14.99    | $58.99        | 94             | 45     | 5      | name.com          |
| temple.rentals     | resell    | —         | —             | 66             | 82     | 6      | GoDaddy.com, LLC  |
| commercial.rentals | premium   | $128.70   | $128.70       | 91             | 98     | 10     | namecheap         |
| strategy.rentals   | available | $56.98    | —             | 74             | 43     | 8      | namecheap         |
| space.rentals      | resell    | —         | —             | 80             | 61     | 5      | GoDaddy.com, LLC  |
| ace.rentals        | premium   | $123.75   | $123.75       | 88             | 57     | 3      | name.com          |
| deep.rentals       | available | $14.99    | $58.99        | 72             | 42     | 4      | name.com          |
| pay.rentals        | resell    | —         | —             | 84             | 60     | 3      | Spaceship, Inc.   |
| live.rentals       | premium   | $82.50    | $82.50        | 108            | 55     | 4      | name.com          |
| mark.rentals       | available | $14.99    | $58.99        | 66             | 42     | 4      | name.com          |
| office.rentals     | resell    | —         | —             | 100            | 58     | 6      | NameCheap, Inc.   |
| business.rentals   | premium   | $260      | $260          | 100            | 54     | 8      | namecheap         |
| shit.rentals       | available | $14.99    | —             | 54             | 42     | 4      | name.com          |
| better.rentals     | resell    | —         | —             | 110            | 56     | 6      | Dynadot Inc       |
| data.rentals       | premium   | $85.80    | $85.80        | 70             | 53     | 4      | namecheap         |
| research.rentals   | available | $56.98    | —             | 92             | 41     | 8      | namecheap         |
| future.rentals     | resell    | —         | —             | 94             | 55     | 6      | Dynadot Inc       |
| one.rentals        | premium   | $123.75   | $123.75       | 132            | 51     | 3      | name.com          |
| learning.rentals   | available | $56.98    | —             | 76             | 41     | 8      | namecheap         |
| good.rentals       | resell    | —         | —             | 82             | 55     | 4      | Sav.com, LLC - 33 |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. The live product keeps the exact search context and adds saved workflows, deeper filters, and alerting.

[Create Radar](https://unique.domains/domains/tld/rentals?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/rentals?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- The live product contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .RENTALS One-Word Domains*. Version 2026-04-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .RENTALS page](https://unique.domains/domains/tld/rentals?utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `hello@unique.domains`
