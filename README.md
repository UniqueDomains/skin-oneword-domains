# Available .SKIN One-Word Domains (12,355)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C355%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .skin one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,355 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,355 domains

**Last updated:** 2026-05-01  
**Canonical page:** `https://unique.domains/domains/tld/skin`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/skin?utm_source=github&utm_medium=referral&utm_campaign=repo_skin_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./skin.csv">CSV</a> / <a href="./skin.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_skin_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_skin_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SKIN search](https://unique.domains/domains/tld/skin?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_skin_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SKIN search](https://unique.domains/domains/tld/skin?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_skin_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_skin_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SKIN one-word domain catalog.

### Files

- `skin.csv` — public CSV extract (1,000 rows)
- `skin.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/skin-oneword-domains/main/skin.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar             |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------- |
| makers.skin        | available | $1.65     | $15.75        | 62             | 67     | 6      | namesilo              |
| research.skin      | resell    | —         | —             | 78             | 39     | 8      | Dynadot LLC           |
| CocaCola.skin      | premium   | $2,800    | $2,800        | 92             | 82     | 9      | namecheap             |
| keepthechange.skin | available | $1.99     | —             | 46             | 59     | 15     | name.com              |
| reflex.skin        | resell    | —         | —             | 76             | 22     | 6      | Go Daddy, LLC         |
| insight.skin       | premium   | $2,500    | —             | 76             | 69     | 8      | name.com              |
| whynot.skin        | available | $1.99     | —             | 74             | 39     | 7      | name.com              |
| styling.skin       | resell    | —         | —             | 78             | 11     | 7      | 101domain GRS Limited |
| donuts.skin        | premium   | $2,500    | —             | 54             | 62     | 6      | name.com              |
| prompts.skin       | available | $1.65     | $15.75        | 54             | 39     | 7      | namesilo              |
| aloevera.skin      | resell    | —         | —             | 80             | 10     | 9      | Dynadot LLC           |
| regions.skin       | premium   | $2,500    | —             | 64             | 59     | 7      | name.com              |
| neuroscience.skin  | available | $1.99     | —             | 80             | 37     | 12     | name.com              |
| cars.skin          | premium   | $2,500    | —             | 66             | 47     | 4      | name.com              |
| notes.skin         | available | $1.99     | —             | 73             | 37     | 5      | name.com              |
| jobs.skin          | premium   | $2,500    | —             | 79             | 42     | 4      | name.com              |
| popup.skin         | available | $1.99     | —             | 84             | 29     | 6      | name.com              |
| events.skin        | premium   | $812.50   | —             | 68             | 37     | 6      | name.com              |
| blocks.skin        | available | $1.99     | —             | 53             | 29     | 6      | name.com              |
| stories.skin       | premium   | $2,500    | —             | 58             | 36     | 7      | name.com              |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 1,000-row public sample | 12,355 live domains                              |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/skin?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_skin_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/skin?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_skin_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_skin_oneword_domains&utm_content=related_pricing)

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
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SKIN One-Word Domains*. Version 2026-05-01. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SKIN page](https://unique.domains/domains/tld/skin?utm_source=github&utm_medium=referral&utm_campaign=repo_skin_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_skin_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_skin_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_skin_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
