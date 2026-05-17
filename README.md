# Available .CENTER One-Word Domains (11,001)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C001%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .center one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,001 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,001 domains · **Median ask:** $12.39 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-17  
**Canonical page:** `https://unique.domains/domains/tld/center`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/center?utm_source=github&utm_medium=referral&utm_campaign=repo_center_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./center.csv">CSV</a> / <a href="./center.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_center_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_center_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CENTER search](https://unique.domains/domains/tld/center?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_center_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CENTER search](https://unique.domains/domains/tld/center?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_center_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_center_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CENTER one-word domain catalog.

### Files

- `center.csv` — public CSV extract (1,000 rows)
- `center.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/center-oneword-domains/main/center.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| etc.center          | available | $7.99     | —             | 58             | 34     | 3      | name.com          |
| marketing.center    | resell    | —         | —             | 78             | 48     | 9      | Porkbun LLC       |
| photos.center       | premium   | $28       | $28           | 54             | 28     | 6      | namecheap         |
| Trex.center         | available | $42.98    | —             | 80             | 24     | 5      | namecheap         |
| prompts.center      | resell    | —         | —             | 54             | 39     | 7      | Sav.com, LLC - 40 |
| girls.center        | premium   | $250      | —             | 83             | 23     | 5      | name.com          |
| deeplearning.center | available | $7.99     | —             | 74             | 23     | 13     | name.com          |
| tokens.center       | resell    | —         | —             | 51             | 36     | 6      | Automattic Inc.   |
| veterans.center     | premium   | $250      | —             | 56             | 23     | 8      | name.com          |
| products.center     | available | $7.99     | —             | 60             | 23     | 8      | name.com          |
| trading.center      | resell    | —         | —             | 78             | 35     | 7      | Porkbun LLC       |
| apartments.center   | premium   | $242      | $242          | 60             | 21     | 10     | namesilo          |
| investors.center    | available | $7.99     | —             | 60             | 23     | 9      | name.com          |
| teams.center        | resell    | —         | —             | 62             | 32     | 5      | Spaceship, Inc.   |
| resources.center    | premium   | $28       | $28           | 58             | 20     | 9      | namecheap         |
| beans.center        | available | $7.99     | —             | 74             | 21     | 5      | name.com          |
| holidays.center     | resell    | —         | —             | 78             | 23     | 8      | DNSPod, Inc.      |
| properties.center   | premium   | $23.60    | $23.60        | 58             | 18     | 10     | namesilo          |
| Mikey.center        | available | $42.98    | —             | 70             | 21     | 5      | namecheap         |
| solarpower.center   | resell    | —         | —             | 84             | 15     | 11     | GoDaddy.com, LLC  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,001 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/center?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_center_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/center?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_center_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_center_oneword_domains&utm_content=related_pricing)

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

This set is entirely made up of .center domains, with a wide mix of dictionary words, descriptive terms, and longer exact-match phrases such as key.center, crucial.center, slot.center, and ChineseNewYear.center. The median ask is 12.39, which signals a low entry point across the broader selection. For founders, the main question is whether the word pairs naturally with .center and still feels credible when spoken aloud. For investors, the focus is narrower: whether the term is commercially legible, category-relevant, and easy to justify at resale. In this extension, clarity usually matters more than novelty.

- The full selection is .center only.
- Median ask across this set is 12.39.
- Short words like key.center are easier to recall.
- Check whether the word fits the .center ending.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CENTER One-Word Domains*. Version 2026-05-17. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CENTER page](https://unique.domains/domains/tld/center?utm_source=github&utm_medium=referral&utm_campaign=repo_center_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_center_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_center_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_center_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
