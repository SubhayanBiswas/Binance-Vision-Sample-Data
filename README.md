# BTC/USDT 1-Hour OHLCV Data

## Dataset Overview
This dataset contains cleaned historical 1-hour candlestick data for Bitcoin (BTC) quoted in Tether (USDT). It covers a continuous two-year period from the start of 2024 to the end of 2025.

**File Name:** `BTCUSDT_1h_Cleaned.csv`

## Temporal Coverage
- **Start Date:** January 01, 2024, 00:00
- **End Date:** December 31, 2025, 23:00
- **Total Duration:** 2 Years (731 Days)
- **Time Zone:** UTC (Assumed based on standard crypto data formats, usually starts 00:00)

## Data Structure
- **Format:** CSV (Comma Separated Values)
- **Rows:** 17,544
- **Columns:** 6
- **Frequency:** Hourly (1h)

### Column Descriptions
| Column Name | Data Type | Description |
|:------------|:----------|:------------|
| `Date`      | String    | Timestamp of the candle open (Format: `DD-MM-YYYY HH:MM`) |
| `Open`      | Float     | The price at the beginning of the 1-hour interval |
| `High`      | Float     | The highest price reached during the 1-hour interval |
| `Low`       | Float     | The lowest price reached during the 1-hour interval |
| `Close`     | Float     | The price at the end of the 1-hour interval |
| `Volume`    | Float     | The amount of the asset traded during the 1-hour interval |

## Summary Statistics
*(Based on data inspection)*
- **Price Range:** ~38,768 to ~126,208 USDT
- **Volume Range:** 0 to ~231,253
- **Missing Values:** No missing timestamps or null values detected.

## Usage
This dataset is suitable for:
- Backtesting trading strategies on hourly timeframes.
- Analyzing price trends and market volatility.
- Training machine learning models for time-series forecasting.

**Data Source**: https://data.binance.vision/?prefix=data/futures/um/monthly/klines/BTCUSDT/1h/
