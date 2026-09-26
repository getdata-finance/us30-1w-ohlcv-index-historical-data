# US30 1w OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-917_rows-blue)](https://getdata.finance/datasets/us30) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/us30)

### -> [**Download the full US30 dataset on getdata.finance**](https://getdata.finance/datasets/us30)

**US30 1w OHLCV index historical data** — ultra high-quality 1w OHLCV for **Dow Jones 30**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1w OHLCV** for **Dow Jones 30** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/us30) · **917** `1w` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `US30_1w.csv` (106 rows, `2024-09-19` -> `2026-09-24`, 8.64 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/us30)** — **917** `1w` rows (full `1m`: 5,980,529), **11 timeframes**, `2009-03-05` -> `2026-09-24`.

## Download sample

**[US30_1w.csv](https://github.com/getdata-finance/us30-1w-ohlcv-index-historical-data/blob/main/US30_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/us30-1w-ohlcv-index-historical-data/main/US30_1w.csv)) · [GitHub Releases](https://github.com/getdata-finance/us30-1w-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/us30-1w-ohlcv-index-historical-data/](https://getdata-finance.github.io/us30-1w-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/us30](https://getdata.finance/datasets/us30)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/us30))** |
|---|--:|---|
| Instrument | Dow Jones 30 · Index | Dow Jones 30 · Index |
| Timeframes | `1w` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1w rows | 106 | **917** |
| Size | 8.64 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/us30) |
| Period | `2024-09-19` -> `2026-09-24` | `2009-03-05` -> `2026-09-24` |
| File | `US30_1w.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/us30) |
| Coverage report | — | [US30 coverage](https://getdata.finance/coverage/us30) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1w` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/us30)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

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
| 2024-09-19T00:00:00+00:00 | 41688.93 | 42384.08 | 41560.93 | 41998.55 | 1466158.03673 |
| 2024-09-26T00:00:00+00:00 | 41998.55 | 42720.64 | 41977.09 | 42281.14 | 1487113.29323 |
| 2024-10-03T00:00:00+00:00 | 42281.14 | 42622.12 | 41842.14 | 42576.55 | 1383541 |
| 2024-10-10T00:00:00+00:00 | 42576.55 | 43223.36 | 42340.3 | 43090.87 | 981274.00974 |
| 2024-10-17T00:00:00+00:00 | 43090.87 | 43371.56 | 42320.05 | 42486.95 | 1005464.61748 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-27T00:00:00+00:00 | 53713.15 | 53814.77 | 52660.04 | 53080.6 | 1603319 |
| 2026-09-03T00:00:00+00:00 | 53080.6 | 53757.45 | 52301.21 | 52462.98 | 1343882 |
| 2026-09-10T00:00:00+00:00 | 52462.98 | 52703.06 | 51173.84 | 51696.21 | 2381206 |
| 2026-09-17T00:00:00+00:00 | 51696.21 | 52416.95 | 51425.16 | 51433.16 | 1597714 |
| 2026-09-24T00:00:00+00:00 | 51433.16 | 51826.01 | 51072.01 | 51784.66 | 885423 |

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
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1W')
print(pf.stats())
```

## Download full data

The complete **US30** archive on **[getdata.finance](https://getdata.finance/datasets/us30)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **917** rows at `1w`, plus all other timeframes in the same ZIP.

**[-> Get the full US30 dataset on getdata.finance](https://getdata.finance/datasets/us30)**

---
*GetData · US30 1w OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/us30)*
