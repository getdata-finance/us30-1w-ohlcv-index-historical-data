# US30 1w OHLCV Stock index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_948_rows-blue)](https://getdata.finance/datasets/us30) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/us30)

### -> [**Download the full US30 dataset on getdata.finance**](https://getdata.finance/datasets/us30)

**US30 1w OHLCV stock index historical data** — ultra high-quality 1w OHLCV for **Dow Jones 30**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1w OHLCV** for **Dow Jones 30** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/us30) · **2,948** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `US30_1w.csv` (105 rows, `2024-08-01` -> `2026-07-30`). **Full archive on [getdata.finance](https://getdata.finance/datasets/us30)** — **2,948** `1m` rows (~0.22 MB), **11 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W), `1970-02-05` -> `2026-07-30`.

## Download sample

**[US30_1w.csv](https://github.com/getdata-finance/us30-1w-ohlcv-index-historical-data/blob/main/US30_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/us30-1w-ohlcv-index-historical-data/main/US30_1w.csv)) · [GitHub Releases](https://github.com/getdata-finance/us30-1w-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/us30-1w-ohlcv-index-historical-data/](https://getdata-finance.github.io/us30-1w-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/us30](https://getdata.finance/datasets/us30)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/us30))** |
|---|--:|---|
| Instrument | Dow Jones 30 · Stock index | Dow Jones 30 · Stock index |
| Timeframes | `1w` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 105 | **2,948** |
| Size | 0.01 MB | ~0.22 MB |
| Period | `2024-08-01` -> `2026-07-30` | `1970-02-05` -> `2026-07-30` |
| File | `US30_1w.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/us30) |
| Coverage report | — | [US30 coverage](https://getdata.finance/coverage/us30) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1w` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/us30)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

GitHub = `1w` sample · [getdata.finance](https://getdata.finance/datasets/us30) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1w` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`US30_1w.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-08-01T00:00:00+00:00 | 40986.341 | 41213.061 | 38484.221 | 38739.841 | 2921247 |
| 2024-08-08T00:00:00+00:00 | 38739.841 | 40167.701 | 38654.121 | 40145.101 | 2283396 |
| 2024-08-15T00:00:00+00:00 | 40145.101 | 41069.731 | 40087.941 | 40985.131 | 1368474 |
| 2024-08-22T00:00:00+00:00 | 40985.131 | 41519.311 | 40662.401 | 41256.431 | 1795470 |
| 2024-08-29T00:00:00+00:00 | 41256.431 | 41674.311 | 40839.591 | 41021.731 | 1629473 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-02T00:00:00+00:00 | 52349.391 | 53435.551 | 52132.901 | 52346.801 | 2508875 |
| 2026-07-09T00:00:00+00:00 | 52346.801 | 53164.551 | 52301.551 | 52970.951 | 2176019 |
| 2026-07-16T00:00:00+00:00 | 52970.951 | 53189.551 | 52109.751 | 52600.151 | 2445618 |
| 2026-07-23T00:00:00+00:00 | 52600.151 | 53259.421 | 51786.681 | 51887.931 | 3530786 |
| 2026-07-30T00:00:00+00:00 | 51887.931 | 52868.731 | 51887.931 | 52830.231 | 726906 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('US30_1w.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('US30_1w.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('US30_1w.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **US30** archive on **[getdata.finance](https://getdata.finance/datasets/us30)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **2,948** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full US30 dataset on getdata.finance](https://getdata.finance/datasets/us30)**

---
*GetData · US30 1w OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/us30) · 2026-08-05 UTC*
