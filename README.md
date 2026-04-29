# SMC Pro for MetaTrader 4

A multi-module **Smart Money Concepts (SMC)** trading and market analysis workstation for **MetaTrader 4**, developed in **MQL4**.

This project combines **multi-timeframe market structure analysis**, **currency strength modeling**, **timing and session tools**, **risk and position management**, and **Python-connected research workflows** in a unified chart-based environment.

![Main Dashboard](images/main-dashboard.png)

## Overview
This project translates discretionary trading concepts into structured, rule-based workflows for analysis, research, dataset generation, and execution support.

The system is organized around three connected layers:
- **Analysis Layer:** market structure, liquidity, order blocks, timing, and strength analytics
- **Research Layer:** feature extraction, dataset generation, and model development
- **Execution Layer:** live market processing and decision-support workflows

The framework processes market data across multiple timeframes and summarizes the results through compact dashboards that support both discretionary analysis and semi-automated research workflows.

## Core Capabilities

### Multi-Timeframe Market Structure Analysis
The platform analyzes market structure across lower and higher timeframes and presents the results through compact summary panels and chart annotations.

Main capabilities:
- multi-timeframe structure detection
- internal and external structure interpretation
- change of character (ChoCh) and market structure shift detection
- displacement and continuation context
- structure summaries across monitored timeframes
- rule-based visual annotations for analysis and execution support

### Smart Money Concepts Toolset
The system calculates and visualizes key SMC components directly on the chart.

Included concepts:
- internal and external liquidity
- multiple order block variations
- breaker blocks
- fair value gaps (FVG)
- liquidity sweeps
- premium and discount zones
- displacement and structure shifts
- refine and no-refine structural modes

### Currency Strength Analysis
The framework includes pure and relative currency strength analysis across multiple timeframes.

This module is used for:
- directional bias estimation
- cross-symbol filtering
- instrument comparison and ranking
- trade selection support

### Timing and Session Models
The project includes timing tools inspired by ICT-oriented workflows and session-based market context.

Supported concepts include:
- ICT kill zones
- Asian, London, and New York session timing
- CLS timing references
- quarterly timing references
- daily, weekly, and monthly cycle context
- intraday timing windows

### Money Management and Position Control
The platform includes dedicated panels for structured risk and trade management.

Included functions:
- risk-based lot sizing
- dynamic and fixed sizing modes
- daily and total P&L tracking
- margin monitoring
- time-based and condition-based close logic
- position monitoring utilities

### Position Management and Trade Execution Support
The system includes tools for active trade handling and chart-based execution support.

Features include:
- manual buy/sell controls
- multi-target take-profit handling
- break-even and risk-free management logic
- regular and step trailing stop workflows
- position add-on logic
- symbol-level and account-level close functions

### Dataset Generation and Research Workflow
A major purpose of this project is structured feature engineering for quantitative trading research.

The framework has been used to generate datasets across multiple instruments and timeframes using features derived from:
- market structure states
- liquidity behavior
- order block logic
- timing models
- currency strength
- session context
- multi-timeframe alignment

These datasets have been used in:
- classical machine learning workflows
- deep learning workflows
- time series forecasting experiments

### Python Integration
The platform is connected to Python-based research and inference workflows through structured data export.

General workflow:
1. MetaTrader 4 processes market data and computes structured analytical features
2. selected live features are transferred to external Python pipelines
3. external models estimate directional bias or movement expectations
4. outputs are used in trade decision-support workflows

## Technology Stack
- **Language:** MQL4
- **Platform:** MetaTrader 4
- **Research Environment:** Python
- **Data Interface:** CSV-based structured feature export
- **Version Control:** Git, GitHub

## Screenshots

| Main Panel | Currency Strength | Money Management |
|---|---|---|
| ![](images/main-dashboard.png) | ![](images/currency-strength.png) | ![](images/money-management.png) |

| Timing Tools | Position Manager | ML Parameters |
|---|---|---|
| ![](images/timing-tools.png) | ![](images/position-manager.png) | ![](images/ml-parameters.png) |

## Project Scope
This repository is shared for **portfolio and documentation purposes**.

Some proprietary source components, execution modules, dataset pipelines, and model logic are not publicly included.

## Getting Started
1. Place the compiled components in the appropriate MetaTrader 4 directories
2. Attach the tool to a chart
3. Configure the required inputs and workflow settings
4. Use the platform for analysis, execution support, and research workflows

## Status
Actively developed as part of a broader trading systems research environment.

## Author
Hamid Haddadian
