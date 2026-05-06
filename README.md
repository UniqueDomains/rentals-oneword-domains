# Available .RENTALS One-Word Domains (12,124)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C124%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .rentals one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,124 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,124 domains · **Median ask:** $25.83 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/rentals`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/rentals?utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./rentals.csv">CSV</a> / <a href="./rentals.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .RENTALS search](https://unique.domains/domains/tld/rentals?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .RENTALS search](https://unique.domains/domains/tld/rentals?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .RENTALS one-word domain catalog.

### Files

- `rentals.csv` — public CSV extract (1,000 rows)
- `rentals.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/rentals-oneword-domains/main/rentals.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| finals.rentals      | available | $14.99    | —             | 80             | 7      | 6      | name.com         |
| jewels.rentals      | available | $14.99    | —             | 80             | 15     | 6      | name.com         |
| geton.rentals       | available | $14.99    | —             | 82             | 10     | 6      | name.com         |
| Apples.rentals      | available | $56.98    | —             | 90             | 16     | 6      | namecheap        |
| playon.rentals      | available | $14.99    | —             | 80             | 14     | 7      | name.com         |
| toneup.rentals      | available | $14.99    | —             | 80             | 5      | 7      | name.com         |
| getlife.rentals     | available | $14.99    | —             | 80             | 5      | 8      | name.com         |
| FabFour.rentals     | available | $14.99    | —             | 82             | 3      | 8      | name.com         |
| skills.rentals      | available | $14.99    | —             | 58             | 47     | 6      | name.com         |
| WiFi.rentals        | resell    | —         | —             | 83             | 37     | 5      | GoDaddy.com, LLC |
| jobs.rentals        | premium   | $250      | —             | 79             | 42     | 4      | name.com         |
| tokens.rentals      | available | $14.99    | —             | 51             | 36     | 6      | name.com         |
| circular.rentals    | resell    | —         | —             | 78             | 30     | 8      | GoDaddy.com, LLC |
| solutions.rentals   | premium   | $250      | —             | 56             | 31     | 9      | name.com         |
| William.rentals     | available | $56.98    | —             | 74             | 31     | 7      | namecheap        |
| videos.rentals      | resell    | —         | —             | 52             | 30     | 6      | NameCheap, Inc.  |
| Jim.rentals         | premium   | $280      | $280          | 78             | 28     | 3      | namecheap        |
| maps.rentals        | available | $14.99    | —             | 56             | 31     | 4      | name.com         |
| instruments.rentals | resell    | —         | —             | 62             | 11     | 11     | GoDaddy.com, LLC |
| pages.rentals       | premium   | $82.50    | —             | 52             | 28     | 5      | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,124 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

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

This selection is entirely made up of one-word domains on the .rentals extension. The names range from direct commercial terms to broader words such as Acup.rentals, jewels.rentals, ladies.rentals, matcha.rentals, and finals.rentals. For founders, the best choices are the ones that clearly match a rental use case and still sound credible as a brand. For investors, the key test is narrower: does the word have obvious rental-market applicability, buyer clarity, and enough specificity to support resale interest? The median ask is 25.83, but low entry price should not outweigh weak fit. In this extension, clarity of use and renewal discipline matter more than novelty alone.

- Favor words with clear rental intent over abstract terms
- Check renewal economics before treating a low ask as a deal
- Exact-match commercial terms usually read stronger in .rentals
- Avoid words with weak rental relevance or possible trademark issues

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .RENTALS One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .RENTALS page](https://unique.domains/domains/tld/rentals?utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rentals_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
