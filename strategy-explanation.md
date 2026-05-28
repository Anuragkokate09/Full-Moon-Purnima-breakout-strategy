# Strategy Explanation

## Concept

This strategy explores whether market behavior around Full Moon (Purnima) days shows repeatable intraday breakout or reversal characteristics.

The system combines:

* Astronomical lunar-cycle timing
* Intraday Opening Range logic
* Momentum confirmation

---

# Opening Range Logic

The strategy captures:

* High of the 9:15–9:30 candle
* Low of the 9:15–9:30 candle

These levels become the key intraday decision zones.

---

# Trade Conditions

## BUY Setup

A BUY signal is generated when:

* Price closes below the Opening Range Low
* During the 9:30–9:45 window
* On a Full Moon day

This assumes a possible reversal after downside expansion.

---

## SELL Setup

A SELL signal is generated when:

* Price closes above the Opening Range High
* During the 9:30–9:45 window
* On a Full Moon day

This assumes a possible reversal after upside expansion.

---

# Risk Management

The strategy optionally uses:

* Stop Loss = Opposite OR level
* Target = OR Range Size

---

# Why This Project Is Interesting

This project demonstrates:

* Pine Script development
* Quantitative thinking
* Time-cycle experimentation
* Automated strategy design
* Intraday trading research

It is intended as a research-oriented strategy rather than a predictive financial model.
