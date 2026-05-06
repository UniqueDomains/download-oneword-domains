# Available .DOWNLOAD One-Word Domains (12,645)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C645%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .download one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,645 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,645 domains · **Median ask:** $299.79 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `download.csv` — public CSV extract (1,000 rows)
- `download.json` — public JSON extract (1,000 rows)
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

| domain               | status    | ask_price | renewal_price | attractiveness | demand | length | registrar     |
| -------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------- |
| investors.download   | available | $9.98     | —             | 60             | 23     | 9      | namecheap     |
| systems.download     | resell    | —         | —             | 46             | 27     | 7      | NameSilo, LLC |
| donuts.download      | premium   | $437.50   | —             | 54             | 62     | 6      | name.com      |
| veterans.download    | available | $9.98     | —             | 56             | 23     | 8      | namecheap     |
| robots.download      | premium   | $437.50   | —             | 62             | 47     | 6      | name.com      |
| unicorns.download    | available | $9.98     | —             | 73             | 21     | 8      | namecheap     |
| jobs.download        | premium   | $625      | —             | 79             | 42     | 4      | name.com      |
| workers.download     | available | $9.98     | —             | 60             | 20     | 7      | namecheap     |
| shortcuts.download   | premium   | $437.50   | —             | 48             | 41     | 10     | name.com      |
| managed.download     | available | $9.98     | —             | 58             | 20     | 7      | namecheap     |
| justin.download      | premium   | $437.50   | —             | 58             | 38     | 7      | name.com      |
| clients.download     | available | $5.25     | $6.25         | 58             | 20     | 7      | namesilo      |
| WiFi.download        | premium   | $700      | $91           | 83             | 37     | 5      | namecheap     |
| computers.download   | available | $9.98     | —             | 68             | 19     | 9      | namecheap     |
| aliens.download      | premium   | $116      | $29.50        | 56             | 35     | 6      | namesilo      |
| communities.download | available | $9.98     | —             | 68             | 19     | 11     | namecheap     |
| solutions.download   | premium   | $437.50   | —             | 56             | 31     | 9      | name.com      |
| motors.download      | available | $5.25     | $6.25         | 50             | 18     | 6      | namesilo      |
| slots.download       | premium   | $1,107    | $116          | 49             | 31     | 5      | namesilo      |
| Containers.download  | available | $5.25     | $6.25         | 54             | 17     | 10     | namesilo      |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,645 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

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

These domains are all one-word names on the .download extension. That makes the selection highly specific: the best fits are words that pair cleanly with file delivery, software access, media, assets, guides, or content people expect to download. Names like showcase.download, onboard.download, and class.download read more naturally than words with weaker download intent. When comparing these domains, focus first on semantic fit with the extension, then on spelling accuracy, memorability, and pricing discipline. The median ask is $299.79, which keeps many options in an accessible range, but weaker word-extension matches can still be harder to justify or resell.

- Best fit: words that make sense with a download action
- Median ask is $299.79 across this .download selection
- Check spelling closely: calender.download raises clarity risk
- Stronger names read naturally, like showcase.download

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DOWNLOAD One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DOWNLOAD page](https://unique.domains/domains/tld/download?utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_download_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
