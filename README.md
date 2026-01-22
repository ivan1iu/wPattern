# wPattern

A Python project for detecting **W (double-bottom) stock price patterns** using rule-based technical analysis, with optional machine learning experiments.

This repo is focused on **research and experimentation**, not live trading.

---

## Overview

The goal of this project is to:

* Systematically define and detect W patterns in historical stock data
* Scan large universes (e.g. S&P 500, Nasdaq)
* Study pattern frequency and post-pattern outcomes
* Experiment with ML models on top of rule-based detection

---

## Key Features

* Rule-based W pattern detection
* Batch scans across stock universes
* Multiple experiment phases (formation-only, outcome-labeled, stricter rules)
* CSV exports and chart visualizations
* Optional ML workflows (feature engineering, classification)

---

## Repository Structure (Simplified)

```text
wPattern/
├── rules1.py              # Core W-pattern rules
├── phase1_formation_only/
├── phase2_with_outcomes/
├── strict_w_patterns/
├── sp500_scans/
├── training_data/
├── yfML/
└── plots / csv exports
```

---

## Data

* Historical OHLCV data pulled via **yfinance**
* Typical lookback window: ~60–120 trading days

---

## Disclaimer

For educational and research purposes only.
Not financial advice.

---

## Author

**Ivan Liu**
Economics & Data Science @ USC
