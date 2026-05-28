# 🌕 Full Moon (Purnima) Reversal Breakout Strategy

An experimental intraday trading strategy built using TradingView Pine Script v5 for NSE/BSE markets.

This project combines:

* 🌕 Full Moon lunar-cycle detection
* 📈 Opening Range breakout logic
* ⚡ Intraday momentum analysis
* 🤖 Automated TradingView alerts
* 📊 Strategy backtesting

---

# 🚀 Strategy Overview

The strategy works only on **Full Moon (Purnima) days**.

It captures the:

* **9:15 AM – 9:30 AM Opening Range**
* Uses the OR High and OR Low as key breakout levels

## Signal Logic

### BUY Signal

Triggered when:

* Price closes BELOW the Opening Range Low
* During the 9:30–9:45 AM window

### SELL Signal

Triggered when:

* Price closes ABOVE the Opening Range High
* During the 9:30–9:45 AM window

---

# 📌 Features

✅ Automatic Full Moon detection
✅ Opening Range breakout visualization
✅ BUY / SELL labels
✅ Dynamic OR High & OR Low levels
✅ Stop Loss & Target logic
✅ TradingView alerts
✅ Backtesting support

---

# 🛠 Technologies Used

* Pine Script v5
* TradingView
* Quantitative Trading Concepts
* Time-Series Analysis
* Intraday Market Structure

---

# 📷 Example Chart

![Strategy Screenshot](screenshots/nifty-fullmoon-example.png)

---

# ⚠ Disclaimer

This strategy is created for educational and research purposes only.

It is an experimental market analysis project and should not be considered financial advice.

Always perform your own backtesting and risk management before live trading.

---

# 👨‍💻 Author

Anurag Kokate

* Data Analytics & AI Enthusiast
* Python | SQL | Power BI | TradingView Pine Script
