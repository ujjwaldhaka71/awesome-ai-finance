<!--lint disable awesome-heading awesome-github awesome-toc -->

<div align="center">

<!-- LOGO PLACEHOLDER — replace with actual banner -->
<img src="assets/banner.png" alt="awesome-ai-finance banner" width="800">

# Awesome AI Finance

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![Stars](https://img.shields.io/github/stars/ujjwaldhaka/awesome-ai-finance?style=flat-square&color=yellow)](https://github.com/ujjwaldhaka/awesome-ai-finance/stargazers)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/ujjwaldhaka/awesome-ai-finance/pulls)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg?style=flat-square)](http://creativecommons.org/publicdomain/zero/1.0/)
[![Last Updated](https://img.shields.io/badge/updated-March_2026-blue?style=flat-square)]()

**The definitive resource for using AI in finance — LLMs, agents, ML, and beyond.**

[Why This List?](#-why-this-list) · [Start Here](#-start-here) · [Contribute](#-contributing)

</div>

---

> **2026 is the year AI became infrastructure in finance.** From LLM-powered equity research to autonomous trading agents, the tooling landscape is evolving faster than any single person can track. This list exists to fix that — opinionated, practitioner-focused, and ruthlessly curated.

---

## Contents

- [🔥 Start Here](#-start-here)
- [🤖 AI Agents for Finance](#-ai-agents-for-finance)
- [🧠 LLMs & Foundation Models](#-llms--foundation-models)
- [📊 Quantitative Trading & Backtesting](#-quantitative-trading--backtesting)
- [🔍 AI-Powered Research & Analysis](#-ai-powered-research--analysis)
- [📈 Portfolio Optimization & Risk](#-portfolio-optimization--risk)
- [📰 Sentiment Analysis & Alternative Data](#-sentiment-analysis--alternative-data)
- [🗃️ Financial Datasets & Benchmarks](#-financial-datasets--benchmarks)
- [🔧 Infrastructure & Data Pipelines](#-infrastructure--data-pipelines)
- [🏦 Banking, Payments & InsurTech AI](#-banking-payments--insurtech-ai)
- [🇮🇳 India-Specific Tools & APIs](#-india-specific-tools--apis)
- [📚 Learning Resources](#-learning-resources)
- [📄 Research Papers](#-research-papers)
- [🎙️ Communities & Newsletters](#-communities--newsletters)
- [Contributing](#-contributing)

---

## 🔥 Start Here

**New to AI in Finance?** Start with these — they're the highest-impact, most accessible resources.

| What you want to do | Start with |
|---|---|
| Build an AI trading agent | [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) — open-source agent platform for financial analysis using LLMs |
| Backtest ML strategies in Python | [Qlib](https://github.com/microsoft/qlib) — Microsoft's AI-oriented quant investment platform |
| Use LLMs for equity research | [OpenBB](https://github.com/OpenBB-finance/OpenBB) — AI-powered open-source research workspace |
| Get free financial data | [yfinance](https://github.com/ranaroussi/yfinance) — Yahoo Finance market data downloader |
| Understand the field | [ML for Trading](https://github.com/stefan-jansen/machine-learning-for-trading) — comprehensive book + code (6.6k ⭐) |
| Fine-tune an LLM on finance | [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) — open-source financial LLM framework |

---

## 🤖 AI Agents for Finance

Multi-agent systems and autonomous AI for trading, research, and financial workflows.

- [TradingAgents](https://github.com/TauricResearch/TradingAgents) — Multi-agent LLM trading framework mirroring real trading firm dynamics. Supports GPT, Gemini, Claude, Grok. ⭐
- [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) — Open-source AI agent platform for equity research and valuation using LLMs.
- [AI Hedge Fund](https://github.com/virattt/ai-hedge-fund) — Explore AI-driven trading decisions with a simulated multi-agent hedge fund.
- [ATLAS](https://github.com/) — Self-improving trading system with 25 agents, Darwinian selection, and autonomous agent spawning. _(verify link)_
- [OpenFinClaw](https://github.com/) — AI-native one-person hedge fund platform. Natural language → strategy → backtest → execution in 60s. _(verify link)_
- [FinSight AI](https://github.com/) — Multi-agent financial research platform with 7 specialized agents, RAG, and smart charts. _(verify link)_

### MCP Servers for Finance

- [edgartools](https://github.com/dgunning/edgartools) — SEC EDGAR data for quant strategies — fundamentals, 13F holdings, insider transactions. Includes MCP server for AI workflows.
- [XVARY Stock Research](https://github.com/) — Claude Code skill for SEC EDGAR + market data: `/analyze`, `/score`, `/compare`. _(verify link)_

---

## 🧠 LLMs & Foundation Models

Finance-specific language models, fine-tuning frameworks, and LLM applications.

### Finance-Tuned LLMs

- [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) — Open-source financial LLM. Data-centric approach with full fine-tuning pipeline.
- [BloombergGPT](https://arxiv.org/abs/2303.17564) — 50B parameter LLM trained on Bloomberg's financial data. _(paper only, proprietary)_
- [FinMA](https://github.com/) — Financial LLM with instruction tuning on diverse financial tasks. _(verify link)_
- [Fino1](https://github.com/) — Reasoning-enhanced LLMs transferred to finance. _(verify link)_

### LLM Applications in Finance

- [Hands-on LLMs: Financial Advisor](https://github.com/) — Train and deploy a real-time financial advisor chatbot with Falcon 7B. _(verify link)_
- [ChatGPT Strategy by OctoBot](https://github.com/) — Use ChatGPT to determine crypto trades based on technical indicators. _(verify link)_
- [Finance-LLMs](https://github.com/kennethleungty/Finance-LLMs) — Comprehensive compilation of real-world LLM implementations in financial services.

---

## 📊 Quantitative Trading & Backtesting

Frameworks, engines, and libraries for building and testing trading strategies.

### Backtesting Frameworks

- [Qlib](https://github.com/microsoft/qlib) — Microsoft's AI-oriented quant investment platform. Full ML pipeline. 10k+ ⭐
- [zipline](https://github.com/quantopian/zipline) — Pythonic algorithmic trading library. The OG backtester.
- [backtrader](https://github.com/mementum/backtrader) — Python backtesting library for trading strategies.
- [nautilus_trader](https://github.com/nautechsystems/nautilus_trader) — High-performance algorithmic trading platform and event-driven backtester.
- [vectorbt](https://github.com/polakowo/vectorbt) — Blazing-fast backtesting and analysis using vectorized operations.
- [fastquant](https://github.com/enzoampil/fastquant) — Backtest investment strategies with as few as 3 lines of Python.
- [Lean](https://github.com/QuantConnect/Lean) — QuantConnect's open-source algorithmic trading engine. C#/Python.
- [vnpy](https://github.com/vnpy/vnpy) — Python-based open-source quantitative trading framework. Strong Asia markets support.

### Execution & Live Trading

- [the0](https://github.com/) — Self-hosted execution engine for algo bots. Supports Python, TypeScript, Rust, C++, C#, Scala, Haskell. _(verify link)_
- [ccxt](https://github.com/ccxt/ccxt) — Crypto trading API with 100+ exchange support. JavaScript/Python/PHP.
- [Kelp](https://github.com/) — Open-source Golang algorithmic crypto trading bot. _(verify link)_

### Technical Analysis

- [TA-Lib](https://github.com/TA-Lib/ta-lib-python) — Technical analysis library. The industry standard.
- [pandas-ta](https://github.com/twopirllc/pandas-ta) — 130+ technical indicators as Pandas extensions.
- [finta](https://github.com/peerchemist/finta) — Common financial technical indicators in Pandas.

---

## 🔍 AI-Powered Research & Analysis

Tools that use AI to accelerate financial research, document analysis, and due diligence.

- [OpenBB](https://github.com/OpenBB-finance/OpenBB) — AI-powered open-source research and analytics workspace. The open-source Bloomberg alternative. ⭐
- [Fincept Terminal](https://github.com/) — Open-source Bloomberg alternative with AI-driven research, multi-asset analytics. _(verify link)_
- [edgartools](https://github.com/dgunning/edgartools) — SEC EDGAR data extraction — fundamentals, 13F, insider transactions, 8-K events.
- [ValueRay](https://github.com/) — Technical, quantitative, and sentiment data for stocks/ETFs. Optimized for AI/LLM agents. _(verify link)_

---

## 📈 Portfolio Optimization & Risk

- [PyPortfolioOpt](https://github.com/robertmartin8/PyPortfolioOpt) — Financial portfolio optimization. Efficient frontier, Black-Litterman, HRP.
- [skfolio](https://github.com/skfolio/skfolio) — Portfolio optimization built on scikit-learn's API.
- [Riskfolio-Lib](https://github.com/dcajasn/Riskfolio-Lib) — Portfolio optimization and risk management in Python.
- [FinRL](https://github.com/AI4Finance-Foundation/FinRL) — Deep reinforcement learning for financial portfolio management. First open-source DRL-in-finance project.
- [MarS](https://github.com/) — Financial market simulation engine powered by a generative foundation model. _(verify link)_

---

## 📰 Sentiment Analysis & Alternative Data

NLP and alternative data for market signals.

- [FinBERT](https://github.com/ProsusAI/finBERT) — Pre-trained NLP model for financial sentiment analysis. The standard.
- [stockpredictionai](https://github.com/) — GAN with LSTM for predicting stock price movements. _(verify link)_
- [Nof1](https://github.com/) — Benchmark for AI investing. Each model gets $10k of real money in real markets. ⭐ _(verify link)_
- [CoinPaprika API](https://api.coinpaprika.com/) — Free crypto market data — prices, volume, market cap, OHLCV for 7,000+ coins.

---

## 🗃️ Financial Datasets & Benchmarks

Datasets, APIs, and benchmarks for training and evaluating financial AI models.

### Datasets & Data Sources

- [yfinance](https://github.com/ranaroussi/yfinance) — Yahoo Finance data downloader. The go-to for free market data.
- [ArcticDB](https://github.com/man-group/ArcticDB) — Man Group's high-performance time series datastore.
- [fredapi](https://github.com/mortada/fredapi) — Python API for Federal Reserve Economic Data (FRED).
- [FinanceDatabase](https://github.com/JerBouma/FinanceDatabase) — Database of 300k+ symbols — equities, ETFs, funds, indices, crypto.
- [CryptoInscriber](https://github.com/) — Live crypto historical trade data blotter. _(verify link)_

### Benchmarks & Evaluation

- [FLARE](https://github.com/) — Financial Language Understanding and Evaluation benchmark. _(verify link)_
- [FinBen](https://github.com/) — Comprehensive financial NLP benchmark. _(verify link)_
- [Open FinLLM Leaderboard](https://github.com/) — Leaderboard for evaluating LLMs on financial tasks. _(verify link)_

---

## 🔧 Infrastructure & Data Pipelines

Tools for building production financial data systems.

- [gs-quant](https://github.com/goldmansachs/gs-quant) — Goldman Sachs' Python toolkit for quantitative finance.
- [QuantLib](https://github.com/lballabio/QuantLib) — Comprehensive framework for quantitative finance. C++ with Python/R bindings.
- [tf-quant-finance](https://github.com/google/tf-quant-finance) — Google's TensorFlow library for quantitative finance — pricing, risk, derivatives.
- [modelx](https://github.com/) — Python library for building complex financial models. _(verify link)_

---

## 🏦 Banking, Payments & InsurTech AI

AI applications in banking infrastructure, payments, and insurance.

- [Hyperledger Fabric](https://github.com/hyperledger/fabric) — Distributed ledger framework for enterprise financial solutions.
- [Moov](https://github.com/moov-io) — Open-source financial services infrastructure. ISO 8583, ACH, wire transfers.
- [Ghostfolio](https://github.com/ghostfolio/ghostfolio) — Open-source wealth management software. Portfolio tracking, analytics.

---

## 🇮🇳 India-Specific Tools & APIs

Tools, APIs, and resources specifically for Indian financial markets.

- [awesome-fintech-india](https://github.com/gitcommitshow/awesome-fintech-india) — Curated list of financial services APIs for Indian developers.
- [Kite Connect](https://kite.trade/) — Zerodha's trading APIs for Indian markets (NSE, BSE, MCX).
- [Jugaad Data](https://github.com/) — NSE/BSE historical data scraper for Indian equities. _(verify link)_
- [NSEpy](https://github.com/) — Python library for NSE data. _(verify link)_

---

## 📚 Learning Resources

### Books

- [Machine Learning for Trading](https://github.com/stefan-jansen/machine-learning-for-trading) — Comprehensive book + code. The gold standard. 6.6k ⭐
- [Advances in Financial Machine Learning](https://www.wiley.com/en-us/Advances+in+Financial+Machine+Learning-p-9781119482086) — Marcos López de Prado. Essential reading for serious quants.
- [Build Financial Software with Generative AI](https://github.com/) — Hands-on with ChatGPT and Copilot for finance. _(verify link)_
- [Financial AI in Practice](https://github.com/) — Creating profitable, regulation-compliant financial AI applications. _(verify link)_

### Courses

- [NYU: ML in Finance](https://github.com/) — Machine Learning in Finance course materials, NYU Tandon. _(verify link)_
- [AI in Finance](https://github.com/) — Learn Fintech Online.
- [DeepLearning.AI Agent Courses](https://www.deeplearning.ai/) — Free courses with LangChain, CrewAI, AutoGen.

---

## 📄 Research Papers

Curated selection of high-impact papers at the intersection of AI and finance. For comprehensive paper lists, see [awesome-finance-ai-papers](https://github.com/junhua/awesome-finance-ai-papers) and [Awesome-AI-in-Finance (papers)](https://github.com/ihobbang250/Awesome-AI-in-Finance).

### LLM Agents in Finance

- [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://arxiv.org/) (2025)
- [FinRobot: AI Agent for Equity Research and Valuation with LLMs](https://arxiv.org/) (2024)
- [FINCON: Synthesized LLM Multi-Agent System for Financial Decision Making](https://arxiv.org/) — NeurIPS 2024
- [A Survey of LLMs for Financial Applications](https://arxiv.org/) (2024)

### Foundational

- [The Theory of Speculation — L. Bachelier](https://en.wikipedia.org/wiki/Louis_Bachelier) (1900)
- [Brownian Motion in the Stock Market — Osborne](https://en.wikipedia.org/wiki/Geometric_Brownian_motion) (1959)
- [A Deep Reinforcement Learning Framework for Financial Portfolio Management](https://arxiv.org/) (2017)

---

## 🎙️ Communities & Newsletters

- [Tauric Research](https://github.com/TauricResearch) — Open-source financial AI research community.
- [AI4Finance Foundation](https://github.com/AI4Finance-Foundation) — Open-source community for AI in finance.
- [QuantConnect Community](https://www.quantconnect.com/forum) — Algorithmic trading community with free data and backtesting.
- [r/algotrading](https://www.reddit.com/r/algotrading/) — Reddit community for algorithmic trading.
- [r/quant](https://www.reddit.com/r/quant/) — Reddit community for quantitative finance.

---

## 🤝 Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

**Quality bar:** We don't list everything. To be included, a project should be:
- Actively maintained (commits within the last 6 months)
- Documented (README with clear usage instructions)
- Genuinely useful (solves a real problem, not a toy/demo)

**How to contribute:**
1. Fork this repo
2. Add your resource to the appropriate category
3. Include a one-line description explaining what it does and why it matters
4. Submit a PR

If you're unsure where something belongs, open an issue and we'll figure it out together.

---

<div align="center">

**Built and maintained by [Ujjwal Dhaka](https://ujjwaldhaka.com)**

*Finance × AI × Strategy*

If this list helped you, consider giving it a ⭐ — it helps others find it too.

</div>
