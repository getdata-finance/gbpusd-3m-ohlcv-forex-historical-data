# GBPUSD 3m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-3_075_732_rows-blue)](https://getdata.finance/datasets/gbpusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/gbpusd)

### -> [**Download the full GBPUSD dataset on getdata.finance**](https://getdata.finance/datasets/gbpusd)

**GBPUSD 3m OHLCV forex historical data** — ultra high-quality 3m OHLCV for **British Pound / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3m OHLCV** for **British Pound / US Dollar** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/gbpusd) · **3,075,732** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `GBPUSD_3m.csv` (62,538 rows, `2026-03-10` -> `2026-09-09`, 6.07 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/gbpusd)** — **3,075,732** `3m` rows (full `1m`: 9,171,581), **11 timeframes**, `2001-11-28` -> `2026-09-09`.

## Download sample

**[GBPUSD_3m.csv](https://github.com/getdata-finance/gbpusd-3m-ohlcv-forex-historical-data/blob/main/GBPUSD_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/gbpusd-3m-ohlcv-forex-historical-data/main/GBPUSD_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/gbpusd-3m-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/gbpusd-3m-ohlcv-forex-historical-data/](https://getdata-finance.github.io/gbpusd-3m-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/gbpusd](https://getdata.finance/datasets/gbpusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/gbpusd))** |
|---|--:|---|
| Instrument | British Pound / US Dollar · Forex | British Pound / US Dollar · Forex |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3m rows | 62,538 | **3,075,732** |
| Size | 6.07 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/gbpusd) |
| Period | `2026-03-10` -> `2026-09-09` | `2001-11-28` -> `2026-09-09` |
| File | `GBPUSD_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/gbpusd) |
| Coverage report | — | [GBPUSD coverage](https://getdata.finance/coverage/gbpusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/gbpusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/gbpusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`GBPUSD_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-10T18:33:00+00:00 | 1.35813 | 1.3583 | 1.3571 | 1.3571 | 1979 |
| 2026-03-10T18:36:00+00:00 | 1.3571 | 1.35777 | 1.35692 | 1.35705 | 2774 |
| 2026-03-10T18:39:00+00:00 | 1.35705 | 1.35717 | 1.35618 | 1.35634 | 1698 |
| 2026-03-10T18:42:00+00:00 | 1.35634 | 1.35689 | 1.35632 | 1.35643 | 1483 |
| 2026-03-10T18:45:00+00:00 | 1.35643 | 1.35733 | 1.35634 | 1.35713 | 1661 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-09T01:48:00+00:00 | 1.35433 | 1.35436 | 1.35427 | 1.35434 | 399 |
| 2026-09-09T01:51:00+00:00 | 1.35434 | 1.3544 | 1.35427 | 1.3544 | 548 |
| 2026-09-09T01:54:00+00:00 | 1.3544 | 1.35462 | 1.35437 | 1.35461 | 497 |
| 2026-09-09T01:57:00+00:00 | 1.35461 | 1.35464 | 1.35452 | 1.3546 | 578 |
| 2026-09-09T02:00:00+00:00 | 1.3546 | 1.3546 | 1.35448 | 1.35453 | 339 |

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

df = pd.read_csv('GBPUSD_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('GBPUSD_3m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('GBPUSD_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **GBPUSD** archive on **[getdata.finance](https://getdata.finance/datasets/gbpusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **3,075,732** rows at `3m`, plus all other timeframes in the same ZIP.

**[-> Get the full GBPUSD dataset on getdata.finance](https://getdata.finance/datasets/gbpusd)**

---
*GetData · GBPUSD 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/gbpusd)*
