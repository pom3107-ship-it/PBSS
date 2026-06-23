# PBSS PROJECT CONTEXT

## Project Name

PBSS (Professional Business & Smart System)

Vision:
Build an AI-powered ecosystem consisting of:

1. PBSS V2 Trading System
2. PBSS SaaS Platform
3. AI Affiliate Command Center
4. Future AI Business Automation Products

Founder: ป้อม

---

# CURRENT PRIORITY

Priority Order:

1. Build Foundation Infrastructure
2. Complete PBSS V2 Core Logic
3. Deploy PBSS SaaS MVP
4. Build AI Affiliate Automation
5. Scale Into Full PBSS Ecosystem

---

# TECHNOLOGY STACK

Current Tools:

* GitHub
* VS Code
* Docker
* n8n
* Supabase
* TradingView
* Pine Script
* AI Agents

Hardware:

* iMac M1
* Windows PC (Secondary)

Budget Strategy:

* Start with free tools whenever possible
* Generate revenue first
* Scale infrastructure gradually

---

# PBSS V2 ARCHITECTURE

Core Design Philosophy:

Lean
Testable
Non-Redundant
Smart Money Concepts
Orderflow Inspired

Avoid over-filtering.

---

# CORE SIGNAL FLOW

H4 Trend Bias

↓

Liquidity Sweep

↓

Delta Proxy

↓

Absorption Detection

↓

CHoCH

↓

M5 Trigger

↓

Signal

---

# CORE MODULES

1. H4 Trend Bias

Purpose:
Determine higher timeframe directional bias.

Output:
Bullish / Bearish

---

2. Liquidity Sweep

Purpose:
Detect stop hunts and liquidity grabs.

Examples:

* Previous High Sweep
* Previous Low Sweep
* Session Liquidity Grab

---

3. Delta Proxy Engine

Purpose:
Approximate orderflow behavior using TradingView-accessible data.

Inputs:

* Candle Body
* Volume
* Relative Volume
* Wick Analysis

Output:

* Bullish Delta Proxy
* Bearish Delta Proxy

---

4. Absorption Detector

Purpose:
Detect absorption behavior.

Examples:

* Large wick rejection
* High volume with poor follow-through

---

5. CHoCH

Purpose:
Detect Change of Character.

Requirement:

* Market structure shift
* Momentum change

---

6. M5 Trigger

Purpose:
Precise entry timing.

Requirements:

* Confirmation after CHoCH
* Direction aligned with H4 Bias

---

# QUALITY ENGINE

These modules are score enhancers.

They are NOT hard filters.

---

## OB Quality Score

Evaluate:

* Freshness
* Reaction Quality
* Structure Context

---

## FVG Quality Score

Evaluate:

* Gap Size
* Mitigation Status
* Location Context

---

## Wick / Rejection Score

Evaluate:

* Upper Wick
* Lower Wick
* Rejection Strength
* Absorption Evidence

---

# INTELLIGENCE ENGINE

Future Enhancement

---

## SMP

Smart Money Pattern Detection

---

## Alignment Engine

Check multi-factor alignment.

---

## Conflict Engine

Detect conflicting conditions.

Reduce signal quality score.

---

# LOCATION ENGINE

Future Phase

Purpose:
Evaluate whether setup occurs in meaningful location.

Components:

* HTF Support
* HTF Resistance
* Premium Zone
* Discount Zone
* POC
* HVN
* LVN

Output:

Location Score

---

# FEATURES DEPRIORITIZED

Not part of current core build:

* Session Score
* Volatility Regime
* Excessive Filters
* Complex AI Prediction Layers

Reason:

Need faster validation.

Need more trade samples.

---

# DEVELOPMENT PHASES

Phase 1

Build and validate:

* H4 Bias
* Liquidity Sweep
* Delta Proxy
* Absorption
* CHoCH
* M5 Trigger

Target:

100–200 trade validation.

---

Phase 2

Add:

* OB Quality Score
* FVG Quality Score
* Wick/Rejection Score

---

Phase 3

Add:

* SMP
* Alignment Engine
* Conflict Engine

---

Phase 4

Add:

* Location Engine

---

# PBSS SAAS FUTURE

Goal:

Create cloud platform for traders.

Potential Features:

* Signal Dashboard
* Trade Journal
* Analytics
* Risk Management
* Strategy Builder
* AI Assistant
* Membership System

---

# AI AFFILIATE COMMAND CENTER

Future Business Unit

Purpose:

Automate affiliate marketing workflow.

Potential Components:

* Product Research
* Content Generation
* SEO
* Social Posting
* Analytics Dashboard
* Revenue Tracking

---

# IMPORTANT DESIGN RULES

Always prefer:

* Simplicity
* Testability
* Measurable Edge
* Modular Architecture

Avoid:

* Indicator Overload
* Duplicate Logic
* Unnecessary Complexity

Every new module must answer:

1. What edge does it add?
2. Is it measurable?
3. Is it already covered elsewhere?
4. Does it improve expectancy?

If not, reject the feature.
