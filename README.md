# Available .LEASE One-Word Domains (12,673)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C673%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .lease one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,673 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,673 domains · **Median ask:** $24.23 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-09  
**Canonical page:** `https://unique.domains/domains/tld/lease`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/lease?utm_source=github&utm_medium=referral&utm_campaign=repo_lease_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./lease.csv">CSV</a> / <a href="./lease.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_lease_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_lease_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .LEASE search](https://unique.domains/domains/tld/lease?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_lease_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .LEASE search](https://unique.domains/domains/tld/lease?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_lease_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_lease_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LEASE one-word domain catalog.

### Files

- `lease.csv` — public CSV extract (1,000 rows)
- `lease.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/lease-oneword-domains/main/lease.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| girls.lease       | available | $14.99    | —             | 83             | 23     | 5      | name.com  |
| barup.lease       | available | $14.99    | —             | 82             | 2      | 6      | name.com  |
| matcha.lease      | available | $14.99    | —             | 86             | 39     | 6      | name.com  |
| dogsit.lease      | available | $14.99    | —             | 96             | 2      | 6      | name.com  |
| QandA.lease       | available | $73.98    | —             | 80             | 10     | 7      | namecheap |
| toneup.lease      | available | $14.99    | —             | 80             | 5      | 7      | name.com  |
| dogsick.lease     | available | $14.99    | —             | 90             | 1      | 7      | name.com  |
| skills.lease      | available | $14.99    | —             | 58             | 47     | 6      | name.com  |
| homes.lease       | premium   | $500      | —             | 86             | 34     | 5      | name.com  |
| Ryan.lease        | available | $73.98    | —             | 60             | 44     | 4      | namecheap |
| partners.lease    | premium   | $123.75   | —             | 61             | 32     | 8      | name.com  |
| reports.lease     | premium   | $123.75   | —             | 58             | 24     | 7      | name.com  |
| whynot.lease      | available | $14.99    | —             | 74             | 39     | 7      | name.com  |
| apartments.lease  | premium   | $242      | $242          | 60             | 21     | 10     | namesilo  |
| teams.lease       | available | $14.99    | —             | 62             | 32     | 5      | name.com  |
| studios.lease     | premium   | $250      | —             | 54             | 21     | 7      | name.com  |
| trends.lease      | available | $14.99    | —             | 60             | 32     | 6      | name.com  |
| dont.lease        | premium   | $250      | —             | 42             | 18     | 4      | name.com  |
| letsgo.lease      | available | $14.99    | —             | 57             | 31     | 7      | name.com  |
| Automobiles.lease | premium   | $280      | $280          | 62             | 17     | 11     | namecheap |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,673 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/lease?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_lease_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/lease?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_lease_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_lease_oneword_domains&utm_content=related_pricing)

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

This selection is focused entirely on one-word .lease domains. That makes the main question straightforward: does the word pair naturally with leasing activity, or does the extension feel forced? Strong candidates tend to be simple, memorable words that can plausibly support equipment, vehicle, property, or niche leasing use. Examples like Acup.lease and jewels.lease are specific, while names like getup.lease or forces.lease are broader and may need more interpretation. The median ask is 24.23, so price may not be the main filter. Instead, compare commercial relevance, clarity when spoken, and whether the exact word creates avoidable trademark or positioning risk.

- Prioritize words that fit leasing use without explanation
- Check if the word stays clear when paired with .lease
- Low ask can help, but renewal fit still matters
- Screen exact-match brands before treating a name as ownable

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LEASE One-Word Domains*. Version 2026-05-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LEASE page](https://unique.domains/domains/tld/lease?utm_source=github&utm_medium=referral&utm_campaign=repo_lease_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_lease_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_lease_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_lease_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
