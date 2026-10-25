# AI Powered Quantitative Trading Fundamentals

A hands-on, low-code course on quant and algorithmic stock trading: turn trading ideas into testable hypotheses, model them with machine learning, backtest them with realistic costs and run them as an automated paper-trading pipeline on Alpaca and TradingView - with no coding required.

| Course detail | Information |
|---|---|
| Course code | `C728` |
| Programme | Non-WSQ |
| Duration | 2 days, 15 hours (9:30am - 5:30pm daily) |
| Registration | [View course details and register](https://www.tertiarycourses.com.sg/ai-powered-quantitative-trading-fundamentals.html) |

## About the course

Algorithms place most orders in today's equity markets, and machine learning and agentic AI are changing how trading ideas are found, tested and executed. The course opens with quant success stories and the evolution of quant - from Thorp and Renaissance through statistical arbitrage to high-frequency trading - and the paradigm shift in which AI now writes the code while the quant owns the hypothesis, the algorithm, the testing and the risk. You classify and use the main trading algorithms, build indicators and strategies on TradingView, train and A/B test machine-learning signals, build a hedged pairs-trading strategy, and run an end-to-end automated pipeline that backtests with costs, forward-tests with automatic paper orders on Alpaca, diagnoses biases and reports performance. Every lab runs in the course's Trading Simulator; no real money is used.

## Learning outcomes

By the end of the course you will be able to:

- **LO1** - Develop hypotheses for data analytics and computational modelling in algorithmic trading, and identify big data applications across the forms of data in financial services.
- **LO2** - Identify appropriate statistical algorithms and data models to test trading hypotheses, and use the right analytics platforms, tools and statistical methods.
- **LO3** - Conduct statistical modelling of market data with machine learning models to derive patterns, and A/B test trading strategies based on different hypotheses.
- **LO4** - Configure an automated trading program based on selected models or algorithms, test its actions and outcomes, diagnose unintended outcomes, and report insights that support decisions.

## Topics covered

1. **Foundations of Quant and Algorithmic Trading: From Thorp to AI Agents** (Day 1, Labs 1-4) - quant success stories; the evolution of quant; the shift from machine learning to LLMs; agentic AI versus AI agents and multi-agent trading systems; forms of financial data and big data applications; developing trading hypotheses.
2. **Technical Indicators, Trading Strategies and Metrics with TradingView and Alpaca** (Day 1, Labs 5-9) - trend, momentum, volatility and volume indicators; classification of algorithmic trading strategies; TradingView versus Alpaca and Python; order placement; performance and risk metrics.
3. **Machine Learning Models, Statistical Modelling and A/B Testing for Trading Signals** (Day 2, Labs 10-14) - statistical analyses and data models; supervised learning for trading signals; clustering and PCA for market regimes; time-series modelling; A/B testing strategies; pairs trading as a hedging algorithm.
4. **Building an End-to-End Algorithmic Trading Pipeline: Backtest, Forward Test and Performance Analysis** (Day 2, Labs 15-20) - pipeline architecture; backtesting with realistic costs; forward testing with automated paper trading; diagnosing unintended outcomes; performance analysis and reporting.

## Labs

Each lab adds one stage to a single algorithmic-trading pipeline. Every lab runs in the Trading Simulator, online with an Alpaca paper account or offline on bundled demo data.

| Lab | Pipeline stage | Title | Time | Manual |
|---|---|---|---|---|
| 01 | Configuration | Pipeline Skeleton, Configuration and the Alpaca Paper Account | 20 min | [Lab manual](labs/Lab01-alpaca-setup/Lab01_Instructions.pdf) |
| 02 | Data validation | Data-Validation Stage: Cross-Check Pipeline Bars against TradingView | 20 min | [Lab manual](labs/Lab02-tradingview-charts/Lab02_Instructions.pdf) |
| 03 | Ingestion | Ingestion Stage: Multi-Timeframe Bars, Headlines and Data Quality | 20 min | [Lab manual](labs/Lab03-alpaca-market-data/Lab03_Instructions.pdf) |
| 04 | Hypothesis | Hypothesis Stage: from a Written Card to an Automated Statistical Test | 15 min | [Lab manual](labs/Lab04-trading-hypothesis/Lab04_Instructions.pdf) |
| 05 | Indicators | Indicator Stage: Pine Script v6 Indicators and their Python Twins | 25 min | [Lab manual](labs/Lab05-pine-indicators/Lab05_Instructions.pdf) |
| 06 | Strategy prototype | Strategy Prototype: TradingView Strategy Tester, Paper Trading from the Chart and Pipeline Reconciliation | 25 min | [Lab manual](labs/Lab06-pine-strategy-tester/Lab06_Instructions.pdf) |
| 07 | Signals | Signal Stage: a Library of Trend, Mean-Reversion, Momentum and Breakout Signals | 25 min | [Lab manual](labs/Lab07-technical-indicators/Lab07_Instructions.pdf) |
| 08 | Execution | Execution Stage: an Order Manager that Trades the Paper Account in Any Session | 25 min | [Lab manual](labs/Lab08-paper-orders/Lab08_Instructions.pdf) |
| 09 | Evaluation | Evaluation Stage: Performance and Risk Metrics with a Benchmark Table | 25 min | [Lab manual](labs/Lab09-performance-metrics/Lab09_Instructions.pdf) |
| 10 | Strategy search | Strategy-Search Stage: Grid Search, Out-of-Sample Ranking and Decay | 25 min | [Lab manual](labs/Lab10-strategy-grid-search/Lab10_Instructions.pdf) |
| 11 | ML signal | ML-Signal Stage: a Walk-Forward Classifier from Probability to Position | 25 min | [Lab manual](labs/Lab11-ml-signal-classifier/Lab11_Instructions.pdf) |
| 12 | Regime filter | Regime-Filter Stage: PCA and K-Means as a Gate on the Signals | 20 min | [Lab manual](labs/Lab12-market-regimes/Lab12_Instructions.pdf) |
| 13 | A/B test | A/B-Test Stage: a Statistical Decision before Capital Moves | 20 min | [Lab manual](labs/Lab13-ab-testing/Lab13_Instructions.pdf) |
| 14 | Pairs / stat-arb | Pairs Stage: a Hedged, Market-Neutral Statistical-Arbitrage Sleeve | 25 min | [Lab manual](labs/Lab14-pairs-trading/Lab14_Instructions.pdf) |
| 15 | Backtest engine | Backtest-Engine Stage: Cost Models, Execution Timing and Break-Even | 30 min | [Lab manual](labs/Lab15-trading-costs/Lab15_Instructions.pdf) |
| 16 | Automation | Automation Stage: a Scheduled, Risk-Checked Forward Test and Live Paper Trading | 30 min | [Lab manual](labs/Lab16-paper-trading-bot/Lab16_Instructions.pdf) |
| 17 | Event-driven automation | Event-Driven Automation: TradingView Webhook to Signal, Risk and Execution | 25 min | [Lab manual](labs/Lab17-tradingview-webhook/Lab17_Instructions.pdf) |
| 18 | Diagnostics | Diagnostics Stage: Automated Bias Checks before Go-Live | 25 min | [Lab manual](labs/Lab18-diagnose-bias/Lab18_Instructions.pdf) |
| 19 | Monitoring and reporting | Monitoring and Reporting Stage: Automated Tearsheet and Backtest-vs-Forward Report | 30 min | [Lab manual](labs/Lab19-performance-report/Lab19_Instructions.pdf) |
| 20 | End-to-end pipeline | Capstone: One Command Runs the Pipeline End to End, with a Multi AI Agents Workflow | 25 min | [Lab manual](labs/Lab20-agentic-capstone/Lab20_Instructions.pdf) |

An optional [Prompt Library](labs/Prompt_Library.md) ([HTML](labs/Prompt_Library.html) · [PDF](labs/Prompt_Library.pdf)) gives one AI prompt per lab for learners who want the code behind each lab generated for them.

## Multi AI agents workflow

Lab 20 demonstrates the simulator's eight-agent trading workflow: a lead agent orchestrates finance research (Twelve Data candles, Yahoo Finance, Equibles), news sentiment (Reddit and NewsAPI), a trading strategy built on trend, momentum, volatility, VWAP, RSI and MACD, a long / short / null signal, a stock trader that places the paper order, performance analysis and a strategy review that feeds the next run. To build this workflow yourself from scratch, continue with [Build a Multi AI Agents Workflow for Stock Trading (C177)](https://www.tertiarycourses.com.sg/build-a-multi-ai-agents-workflow-for-stock-trading.html).

## Course software

The labs run in the course's Trading Simulator, [alfredang/algorithmic-trader-bot](https://github.com/alfredang/algorithmic-trader-bot) - a local web app (uv or Docker Compose) for data, strategies, backtesting, paper trading, analytics and multi-agent AI. Installation steps are in the Learner Guide and the Lab 01 manual. You also need a free Alpaca paper-trading account and a free TradingView account; both are created in class.

## Public package

| Item | Files |
|---|---|
| Trainer slides | [PPTX](courseware/Slides_AI%20Powered%20Quantitative%20Trading%20Fundamentals_v2.1.pptx) · [PDF](courseware/Slides_AI%20Powered%20Quantitative%20Trading%20Fundamentals_v2.1.pdf) |
| Lesson Plan | [DOCX](courseware/LP-AI%20Powered%20Quantitative%20Trading%20Fundamentals_v2.1.docx) · [PDF](courseware/LP-AI%20Powered%20Quantitative%20Trading%20Fundamentals_v2.1.pdf) |
| Learner Guide | [DOCX](courseware/LG-AI%20Powered%20Quantitative%20Trading%20Fundamentals_v2.1.docx) · [PDF](courseware/LG-AI%20Powered%20Quantitative%20Trading%20Fundamentals_v2.1.pdf) · [Markdown](courseware/LG-AI%20Powered%20Quantitative%20Trading%20Fundamentals_v2.1.md) |
| Lab manuals | [`labs/`](labs/) - one `LabNN_Instructions.pdf` per lab |

Courseware version 2.1 (25 October 2026). Download everything with **Code > Download ZIP**.

## Distribution

This repository publishes the learner and trainer courseware only. Source references and any trainer-only material are kept out of the public repository.

All trading in this course is paper (simulated) trading. Lion City Capital and every scenario in these materials are fictitious. Nothing here is investment advice.

---

Developed and delivered by [Tertiary Infotech Academy Pte Ltd](https://www.tertiarycourses.com.sg/) (UEN 201200696W).
