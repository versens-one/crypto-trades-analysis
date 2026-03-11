# BTC Trade Analysis

This project analyzes Bitcoin trading activity using trade-level data from Binance.

The analysis explores price dynamics, trading volume, and the distribution of trade sizes using Python.

---

## Dataset

The dataset contains individual BTC/USDT trades and includes the following fields:

- trade_id
- price
- quantity
- quote_qty (trade size in USDT)
- timestamp
- trade direction

Total trades analyzed: **5,176,064**

---

## Tools Used

- Python
- pandas
- matplotlib
- Jupyter Notebook

---

## Analysis

### 1. BTC Price Over Time

The first analysis examines how the price of BTC evolves throughout the day.

This helps identify periods of higher volatility and major price movements.

---

### 2. Trading Volume Over Time

The second analysis looks at trading volume aggregated by minute.

Volume spikes often correspond to periods of increased market activity.

---

### 3. Distribution of Trade Sizes

The third analysis studies the distribution of trade sizes.

Key findings:

- Median trade size ≈ **5.6 USDT**
- Average trade size ≈ **443 USDT**
- Only about **1% of trades exceed 10,000 USDT**

This indicates that most trades are small retail transactions, while occasional large trades suggest participation from larger market participants.

---

## Conclusions

The BTC trading dataset reveals several key patterns:

- Price exhibits intraday volatility.
- Trading volume spikes often coincide with price movements.
- The majority of trades are small.
- A small number of very large trades contribute significantly to market activity.

---

## Project Structure

```
crypto-trades-analysis
│
├── btc_trade_analysis.ipynb
├── README.md
└── data/
    └── BTCUSDT-trades-2026-03-10.csv
```

---

## Future Work

Possible extensions of this analysis include:

- buy vs sell pressure analysis
- exchange flow analysis
- whale activity detection
