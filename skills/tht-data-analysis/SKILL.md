---
name: tht-data-analysis
description: Analyze a data for THT indicators. Use when the user wants technical analysis between THT Multi Timeframe BX and THT Fair Value Bands.
---

# THT Data Analysis Workflow

You are performing THT technical analysis on a TradingView chart.

## Step 1: Set Up the Chart

1. `chart_set_symbol` — switch to the requested symbol
2. `chart_set_timeframe` — set the appropriate timeframe
3. Wait for the chart to load (the tool handles this)

## Step 2: Trade Analysis

Get latest values for bars:
1. `data_get_study_values` — get the current numeric values from THT indicators

## Step 3: Report

Provide the analysis:
- Current THT Multi Timeframe BX #1
- Current THT Multi Timeframe BX #2
- Indicator signal (bullish/bearish)
- Compare THT Multi Timeframe BX with each other
- Price compared to THT Fair Value Bands
- Overall bias (bullish/bearish/neutral) with reasoning

