# Available .DOWNLOAD One-Word Domains (9,701)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-9%2C702%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-9%2C701%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .download one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 9,702 rows · **Live catalog:** 9,701 domains

**Last updated:** 2026-04-11  
**Canonical page:** `https://unique.domains/domains/tld/download`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/download?utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./download.csv">CSV</a> / <a href="./download.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .DOWNLOAD search](https://unique.domains/domains/tld/download?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .DOWNLOAD search](https://unique.domains/domains/tld/download?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .DOWNLOAD one-word domain catalog.

### Files

- `download.csv` — public CSV extract (9,702 rows)
- `download.json` — public JSON extract (9,702 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/download-oneword-domains/main/download.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain                | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                     |
| --------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------------------- |
| construction.download | available | $9.98     | —             | 66             | 30     | 12     | namecheap                     |
| hello.download        | resell    | —         | —             | 130            | 71     | 5      | West263 International Limited |
| converse.download     | premium   | $437.50   | $62.50        | 64             | 73     | 8      | name.com                      |
| second.download       | available | $9.98     | —             | 120            | 28     | 6      | namecheap                     |
| get.download          | resell    | —         | —             | 88             | 69     | 3      | Porkbun                       |
| nationwide.download   | premium   | $437.50   | $62.50        | 76             | 66     | 10     | name.com                      |
| curative.download     | available | $9.98     | —             | 92             | 27     | 8      | namecheap                     |
| home.download         | resell    | —         | —             | 100            | 62     | 4      | Dynadot Inc                   |
| power.download        | premium   | $455      | $65           | 98             | 62     | 5      | namecheap                     |
| damn.download         | available | $9.98     | —             | 140            | 24     | 4      | namecheap                     |
| best.download         | resell    | —         | —             | 82             | 53     | 4      | Porkbun                       |
| seventeen.download    | premium   | $437.50   | $62.50        | 84             | 62     | 9      | name.com                      |
| drink.download        | available | $9.98     | —             | 100            | 24     | 5      | namecheap                     |
| tech.download         | resell    | —         | —             | 104            | 50     | 4      | Porkbun                       |
| cloud.download        | premium   | $3,250    | $130          | 70             | 59     | 5      | namecheap                     |
| remedial.download     | available | $9.98     | —             | 86             | 24     | 8      | namecheap                     |
| dream.download        | resell    | —         | —             | 116            | 45     | 5      | GoDaddy.com, LLC              |
| ace.download          | premium   | $625      | $81.25        | 88             | 57     | 3      | name.com                      |
| debate.download       | available | $9.98     | —             | 90             | 23     | 6      | namecheap                     |
| super.download        | resell    | —         | —             | 58             | 45     | 5      | 1API GmbH                     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 9,702-row public sample | 9,701 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/download?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/download?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .DOWNLOAD One-Word Domains*. Version 2026-04-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DOWNLOAD page](https://unique.domains/domains/tld/download?utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
