# PBSS V2 System Architecture

## Core Philosophy

PBSS V2 focuses on:

* Simple
* Testable
* Measurable
* Smart Money Oriented

Avoid:

* Indicator Overload
* Duplicate Logic
* Unnecessary Filters

---

# Core Signal Flow

H4 Trend Bias

↓

Liquidity Sweep

↓

Delta Proxy

↓

Absorption

↓

CHoCH

↓

M5 Trigger

↓

Signal

---

# Engine 1: H4 Trend Bias

Purpose:

Determine higher timeframe directional bias.

Inputs:

* EMA200
* Market Structure
* Swing High
* Swing Low

Output:

* Bullish
* Bearish
* Neutral

---

# Engine 2: Liquidity Sweep

Purpose:

Detect stop hunt and liquidity grab events.

Inputs:

* Equal High
* Equal Low
* Previous Day High
* Previous Day Low

Output:

* Buy-side Sweep
* Sell-side Sweep

---

# Engine 3: Delta Proxy

Purpose:

Estimate order flow behavior using TradingView-accessible data.

Inputs:

* Candle Body %
* Volume Spike
* Relative Volume
* Wick Analysis

Output:

* Bullish Delta Proxy
* Bearish Delta Proxy

---

# Engine 4: Absorption

Purpose:

Detect rejection and absorption behavior.

Inputs:

* Upper Wick
* Lower Wick
* Volume
* Candle Close Position

Output:

* Bullish Absorption
* Bearish Absorption

---

# Engine 5: CHoCH

Purpose:

Detect Change of Character.

Output:

* Bullish CHoCH
* Bearish CHoCH

---

# Engine 6: M5 Trigger

Purpose:

Entry confirmation.

Inputs:

* Break Structure
* Candle Confirmation

Output:

* Buy Setup
* Sell Setup

---

# Engine 7: Signal Generator

Purpose:

Generate final trade signal.

Output:

* Buy
* Sell
* Stop Loss
* Take Profit
* Risk %
