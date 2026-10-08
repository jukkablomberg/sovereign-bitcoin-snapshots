# State of Sovereign Bitcoin — snapshots

Government Bitcoin holdings by country, frozen as dated, immutable snapshots by [CoinBucha](https://coinbucha.com/sovereign-bitcoin/snapshots?utm_source=github&utm_medium=dataset&utm_campaign=cb-sovereign-github). Every row carries its sources and a provenance grade. This repository mirrors the files CoinBucha serves; the canonical record for each snapshot is its page on coinbucha.com.

## Snapshot 2026-10-01

Frozen 2026-10-01: **11 states tracked, 7 holding 630,180 BTC** in reserves or seized coins (3.1747% of a 19,850,000 BTC supply, at $83,467/BTC). 1 of 11 rows cite a primary source. Methodology v0.1.0. Never revised after 2026-10-01. **Every holdings figure equals the 2026-09-04 snapshot; only the BTC price moved** — the newest `as_of` date on any row is 2026-08-10.

- Canonical page: https://coinbucha.com/sovereign-bitcoin/snapshots/2026-10-01
- DOI (archived copy on Zenodo): [10.5281/zenodo.23092782](https://doi.org/10.5281/zenodo.23092782)
- Files: `data/2026-10-01.csv` and `data/2026-10-01.json` — byte-identical to https://coinbucha.com/sovereign-snapshots/2026-10-01.csv and `.json`.

## Snapshot 2026-09-04

Frozen 2026-09-04: **11 states tracked, 7 holding 630,180 BTC** in reserves or seized coins (3.1747% of a 19,850,000 BTC supply, at $77,736/BTC). 1 of 11 rows cite a primary source. Methodology v0.1.0. Never revised after 2026-09-04.

- Canonical page: https://coinbucha.com/sovereign-bitcoin/snapshots/2026-09-04
- DOI (archived copy on Zenodo): [10.5281/zenodo.23004345](https://doi.org/10.5281/zenodo.23004345)
- Files: `data/2026-09-04.csv` (one row per state, sources pipe-separated) and `data/2026-09-04.json` (full record incl. each state's framework note and labelled sources) — byte-identical to https://coinbucha.com/sovereign-snapshots/2026-09-04.csv and `.json`.
- Live monitor (refreshed daily): https://coinbucha.com/sovereign-bitcoin?utm_source=github&utm_medium=dataset&utm_campaign=cb-sovereign-github

| Country | BTC | Status | Tier | As of | Source grade |
|---|---:|---|---:|---|---|
| United States | 325,000 | strategic_reserve | 1 | 2026-04-30 | secondary |
| El Salvador | 7,739 | strategic_reserve | 2 | 2026-08-10 | primary |
| Bhutan | 3,654 | divested | 3 | 2026-04-30 | secondary |
| Finland | 90 | seized_held | 4 | 2026-05-15 | secondary |
| Pakistan | 0 | announced_not_yet_held | 5 | 2026-05-01 | secondary |
| Brazil | 0 | legislation_proposed | 5 | 2026-02-15 | secondary |
| Czech Republic | 0 | exploring | 5 | 2025-12-31 | secondary |
| Germany | 0 | divested | 5 | 2024-07-15 | secondary |
| Ukraine | 46,351 | seized_held | 2 | 2024-12-31 | secondary |
| United Kingdom | 61,000 | seized_held | 2 | 2024-10-30 | secondary |
| China | 190,000 | seized_held | 1 | 2024-12-31 | secondary |

## Columns (CSV)

`snapshot_date` · `country_code` · `country_name` · `holdings_btc` · `status` (strategic_reserve, seized_held, divested, legislation_proposed, exploring, announced_not_yet_held) · `tier` · `as_of` (the date the figure refers to) · `source_quality` (primary / secondary) · `usd_value` · `pct_of_supply` · `primary_sources` · `sources`.

## Provenance and limits

A `primary` grade means the figure is confirmed by the holding government's own publication; `secondary` means press or tracker reporting. Most rows are secondary — the grade is printed so you can weigh each figure. Holdings are as of the `as_of` date on each row, not the snapshot date. Figures are third-party: they are compiled from the sources named on each row, and those sources keep their own rights.

## Terms and citation

Free to access; reuse with attribution — attribute as "CoinBucha (coinbucha.com)" and carry the `as_of` date with any figure ([terms](https://coinbucha.com/methodology#terms)). Information, not financial advice.

> CoinBucha (2026). Sovereign Bitcoin reserves by country — snapshot 2026-10-01. https://coinbucha.com/sovereign-bitcoin/snapshots/2026-10-01 · doi:10.5281/zenodo.23092782
>
> CoinBucha (2026). Sovereign Bitcoin reserves by country — snapshot 2026-09-04. https://coinbucha.com/sovereign-bitcoin/snapshots/2026-09-04 · doi:10.5281/zenodo.23004345

Also on [Hugging Face](https://huggingface.co/datasets/jukkab/sovereign-bitcoin-snapshots) and archived on [Zenodo](https://doi.org/10.5281/zenodo.23092782). `CITATION.cff` in this repository gives GitHub's "Cite this repository" button the same citation.

*Mirrored to GitHub by an AI agent on CoinBucha's behalf; new snapshots are added as CoinBucha freezes them.*
