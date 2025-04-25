# ARPS Scalp Short Indicator
**Originally created: July 27, 2020**
*(Note: This script was created in 2020 but is being shared on GitHub on 2025-04-25)*

---

# ARPS Scalp Short Indicator

## Overview

The **ARPS Scalp Short Indicator** is designed to identify short-selling opportunities for scalping within intraday and swing trading scenarios. This indicator leverages a combination of technical signals, including candlestick patterns, RSI crossover analysis, Ichimoku Cloud techniques, trend continuation factors, and the Parabolic SAR.

This tool provides traders with highly customizable and advanced features to aid in precise trade decisions under bearish market conditions. The indicator generates alerts when predefined conditions for a short sell signal are met, reducing the guesswork of identifying entry points.

---

## Features

### 1. **Oscillators and Moving Averages**
- **Awesome Oscillator (AO):** Measures market momentum. Used primarily to confirm bearish setups.
- **RSI Cross:** Uses smoothing with Weighted Moving Average (WMA) for refined RSI crossover signals.
- **Stochastic Oscillator:** Highlights overbought and oversold conditions, combined with WMA smoothing for precision.
- **Multi-Length WMA:** Tracks market trends over short- and long-term periods.

### 2. **Candlestick Patterns**
The indicator identifies various bearish reversal patterns:
- **Doji Variations:** Standard, Fly Dragon Doji, Gravestone Doji.
- **Bearish Reversal Patterns:** Evening Star, Shooting Star, Bearish Harami, Bearish Engulfing, and Dark Cloud Cover.
- **Continuation and Previous Candle Metrics:** Includes previous bearish patterns for historical context.

### 3. **Ichimoku Cloud Analysis**
- **Full Ichimoku Integration:** Supports Tenkan-sen, Kijun-sen, Senkou Span A/B, and Cloud analysis.
- **Double Ichimoku Clouds:** Offers an adjusted cloud configuration for enhanced reliability to gauge market dynamics.

### 4. **Trend Continuation Factor (TCF)**
Tracks price movement consistency:
- **Positive TCF:** Measures upward trends before reversal.
- **Negative TCF:** Measures downward trends for bearish setups.

### 5. **Parabolic SAR**
Built-in Parabolic SAR plotting helps traders track price reversals and identify bearish momentum transitions.

### 6. **Signal Generation**
The indicator combines multiple conditions (candlestick patterns, oscillators, clouds, and TCF) to generate highly reliable **Short Position sell signals** — displayed as labels above candles and configured for alert conditions.

---

## Signal Conditions

Sell signals are generated based on the following criteria:
1. **Bearish Momentum Confirmations:**
   - RSI and Stochastic crossovers indicate bearish market sentiment.
   - Awesome Oscillator turns negative or weakens further in a downward setup.
2. **Candlestick Reversal Patterns:**
   - The emergence of bearish reversal candlestick formations.
3. **Cloud Positioning (Ichimoku):**
   - Price consistently trading below adjusted Ichimoku Cloud levels.
4. **SAR Confirmation:**
   - Price trading below Parabolic SAR levels.
5. **Trend Continuation Validations:**
   - Bearish changes confirmed with trend continuation factor comparisons.

---

## Alerts

The indicator supports **custom alerts** triggered whenever a short-sell signal is activated:
- **Title:** Signal
- **Message:** Signal  
These alerts streamline trading by integrating with trading terminals for real-time execution.

---

## Input Parameters

### 1. **Core Settings**
- `Length`: Default value is 20, defines the period for trend continuation factor calculations.
- `Source`: Default is set to close price for all calculations.

### 2. **Candlestick Parameters**
- Define sensitivity for Doji patterns (`DojiSize`).
- Enable bearish candlestick pattern recognition.

### 3. **Ichimoku Cloud**
- Adjustable parameters for Tenkan-sen, Kijun-sen, and Senkou Span periods.
- Option to activate standard or adjusted Ichimoku configurations.

### 4. **Stochastic Oscillator**
- Periods for `%K` and `%D` with smoothing factor.

### 5. **Display Options**
- Enables selection of plotted shapes and cloud fills to customize visuals.

---

## How to Use

1. **Apply to Chart:**
   Add the indicator to the trading view chart. Ensure it's applied to a timeframe suitable for scalping or short selling (e.g., 5-minute, 15-minute charts).

2. **Signal Scaling:**
   Configure inputs according to the trading strategy and asset's volatility.

3. **Watch for Alerts:**
   Set up notifications to avoid excessive monitoring and respond to signals promptly.

4. **Risk Management:**
   Use signals in conjunction with stop-loss and take-profit strategies.

---

## Proposed Indicator Name

`ARPS Scalp Short Indicator v1.0`

The name emphasizes the tool's robust short-selling capabilities and precision for scalping under bearish setups, using Ali Rajabpour Sanati's specialized pattern indicators.

---

## Disclaimer

This indicator is intended for educational purposes. Use in live trading must be accompanied by proper risk management. Results may vary based on asset class, market conditions, and timeframe selection. Always backtest and validate the indicator before deployment in live market scenarios.