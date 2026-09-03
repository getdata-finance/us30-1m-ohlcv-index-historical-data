# US30 1m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-6_024_308_rows-blue)](https://getdata.finance/datasets/us30) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/us30)

### -> [**Download the full US30 dataset on getdata.finance**](https://getdata.finance/datasets/us30)

**US30 1m OHLCV index historical data** — ultra high-quality 1m OHLCV for **Dow Jones 30**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Dow Jones 30** (Index)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/us30) · **6,024,308** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `US30_1m.csv` (55,440 rows, `2026-07-07` -> `2026-09-02`). **Full archive on [getdata.finance](https://getdata.finance/datasets/us30)** — **6,024,308** `1m` rows, **11 timeframes**, `2009-03-11` -> `2026-09-02`.

## Download sample

**[US30_1m.csv](https://github.com/getdata-finance/us30-1m-ohlcv-index-historical-data/blob/main/US30_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/us30-1m-ohlcv-index-historical-data/main/US30_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/us30))** |
|---|--:|---|
| Instrument | Dow Jones 30 · Index | Dow Jones 30 · Index |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **6,024,308** |
| Period | `2026-07-07` -> `2026-09-02` | `2009-03-11` -> `2026-09-02` |
| File | `US30_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/us30) |
| Coverage report | — | [US30 coverage](https://getdata.finance/coverage/us30) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/us30)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`US30_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-07T18:58:00+00:00 | 53025.06 | 53029.56 | 53016.06 | 53017.06 | 452 |
| 2026-07-07T18:59:00+00:00 | 53017.06 | 53020.56 | 53008.06 | 53013.56 | 482 |
| 2026-07-07T19:00:00+00:00 | 53013.56 | 53023.06 | 52997.06 | 53005.06 | 961 |
| 2026-07-07T19:01:00+00:00 | 53005.06 | 53006.06 | 52968.56 | 52981.06 | 915 |
| 2026-07-07T19:02:00+00:00 | 52981.06 | 52996.06 | 52980.56 | 52988.06 | 679 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:56:00+00:00 | 52735.04 | 52737.04 | 52731.54 | 52732.04 | 92 |
| 2026-09-02T01:57:00+00:00 | 52732.04 | 52732.54 | 52729.04 | 52729.04 | 75 |
| 2026-09-02T01:58:00+00:00 | 52729.04 | 52739.04 | 52729.04 | 52738.54 | 117 |
| 2026-09-02T01:59:00+00:00 | 52738.54 | 52741.04 | 52734.04 | 52740.04 | 83 |
| 2026-09-02T02:00:00+00:00 | 52740.04 | 52744.04 | 52739.04 | 52744.04 | 25 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full US30 archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full US30 dataset on getdata.finance](https://getdata.finance/datasets/us30)**
