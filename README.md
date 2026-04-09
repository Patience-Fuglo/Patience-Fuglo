<div align="center">

```
██████╗  █████╗ ████████╗██╗███████╗███╗   ██╗ ██████╗███████╗
██╔══██╗██╔══██╗╚══██╔══╝██║██╔════╝████╗  ██║██╔════╝██╔════╝
██████╔╝███████║   ██║   ██║█████╗  ██╔██╗ ██║██║     █████╗  
██╔═══╝ ██╔══██║   ██║   ██║██╔══╝  ██║╚██╗██║██║     ██╔══╝  
██║     ██║  ██║   ██║   ██║███████╗██║ ╚████║╚██████╗███████╗
╚═╝     ╚═╝  ╚═╝   ╚═╝   ╚═╝╚══════╝╚═╝  ╚═══╝ ╚═════╝╚══════╝
                  FUGLO  ·  QUANTITATIVE RESEARCHER
```

</div>

<div align="center">

[![Portfolio](https://img.shields.io/badge/🌐_bullseyealpha.com-000000?style=for-the-badge&logoColor=white)](https://bullseyealpha.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/patience-fuglo)
[![Email](https://img.shields.io/badge/patfug3@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:patfug3@gmail.com)
[![Location](https://img.shields.io/badge/New_York,_NY-FF6B35?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

<div align="center">

### `[ QUANTITATIVE RESEARCHER · SYSTEMATIC TRADER · RISK MODELER ]`

*Building the infrastructure where mathematics meets markets.*

</div>

---

## ◈ WHO I AM

> **CQF-certified Quantitative Researcher** with an M.Sc. in Software Development & Engineering and a B.Sc. in Computer Science — operating at the intersection of financial mathematics, statistical modeling, and production engineering.

I build systems that **extract signal from noise**: from GARCH volatility models and PCA factor decompositions to event-driven trading engines and walk-forward forecasting pipelines. My work covers the full quant stack — from raw tick data to portfolio-level risk attribution — with a relentless focus on correctness, reproducibility, and real-world applicability.

Currently building **[Bullseye Alpha](https://bullseyealpha.com)** — a next-generation systematic equity research platform for alpha signal discovery across equities and ETFs.

---

## ◈ CORE COMPETENCIES

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  QUANTITATIVE FINANCE          │  MACHINE LEARNING & STATS                  │
│  ─────────────────────────     │  ─────────────────────────────             │
│  • Time-Series Analysis        │  • ARIMA / GARCH / ARCH Modeling           │
│  • Alpha Signal Generation     │  • LSTM / XGBoost / Random Forest          │
│  • Factor Modeling (PCA)       │  • Walk-Forward Validation                 │
│  • Portfolio Optimization      │  • Feature Engineering Pipelines           │
│  • VaR / CVaR / Drawdown      │  • Regime Detection & Model Decay          │
│  • Volatility Forecasting      │  • Hypothesis Testing & Inference          │
│                                │                                            │
│  MARKET MICROSTRUCTURE         │  ENGINEERING                               │
│  ─────────────────────────     │  ─────────────────────────────             │
│  • Order Book Dynamics         │  • Python: NumPy · Pandas · Scikit-learn   │
│  • Price-Time Priority         │  • Statsmodels · Arch · SciPy              │
│  • Slippage Modeling           │  • FastAPI · Docker · Redis Streams        │
│  • Execution Logic             │  • ClickHouse · BigQuery · Vertex AI       │
│  • Multi-Asset Strategies      │  • SQL · C++ · Event-Driven Architecture   │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## ◈ EXPERIENCE

**`BULLSEYE ALPHA`** — Founder & Lead Quantitative Researcher | *Nov 2024 – Present · New York, NY*

- Architecting a next-gen systematic equity research platform with a modular quant engine focused on low-latency backtesting and signal generation
- Designed and backtested multi-factor strategies (momentum + mean reversion) achieving **Sharpe > 1.2** in out-of-sample testing
- Built scalable data pipelines processing **1,000+ tickers** for large-scale empirical research and signal validation
- Modeled order book dynamics, slippage, and execution behavior — improving backtest realism and reducing performance bias
- Identified cross-sectional return predictors with **statistically significant alpha** across multiple market regimes

**`QUANTITATIVE RESEARCH INTERN`** — Remote | *Jan 2024 – Nov 2024*

- Engineered ARIMA and LSTM forecasting models improving directional prediction accuracy by **15–20%** over baseline
- Reduced data ingestion latency by **25%** for time-critical financial datasets
- Conducted Monte Carlo simulations and risk modeling (VaR/CVaR) to stress-test portfolio resilience under black-swan events

---

## ◈ PROJECT PORTFOLIO

> *12 production-quality projects spanning the complete quantitative finance stack — from defensive data pipelines to GARCH volatility models and MPT portfolio optimization.*

---

### ▸ TIER I — SYSTEMS & PIPELINES

<table>
<tr>
<td width="50%" valign="top">

**[`smart-trade-analytics-engine`](https://github.com/patience-fuglo/smart-trade-analytics-engine)**

Trade data validation and analytics pipeline with two implementations — a modular functional pipeline and an OOP class hierarchy (`Trade` + `TradePortfolio`). Handles dirty broker data: mixed types, `None` values, negative quantities, zero prices.

`Python` `OOP` `Error Handling` `Financial Pipelines`

</td>
<td width="50%" valign="top">

**[`smart-log-incident-detection`](https://github.com/patience-fuglo/smart-log-incident-detection)**

Server log processing engine with severity classification, allowlist validation, and incident summarization. Three rejection modes with distinct exception types (`TypeError`, `ValueError`) — `finally` block provides audit trail for every entry.

`Python` `Defensive Programming` `Incident Detection`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[`smart-trade-analyzer`](https://github.com/patience-fuglo/smart-trade-analyzer)**

Console-based trade analyzer with a three-class OOP hierarchy: `Trade` → `TradeAnalyzer` → `StrategyAnalyzer`. Lambda-based filtering with `filter()`, `max()`/`min()` with key functions, `if __name__ == "__main__"` entry point.

`Python` `Inheritance` `Lambdas` `OOP`

</td>
<td width="50%" valign="top">

**[`stock-return-feature-engineering`](https://github.com/patience-fuglo/stock-return-feature-engineering)**

End-to-end ML feature engineering pipeline on AAPL data. Financial indicators, Box-Cox transforms (λ=1.007), three encoding strategies, RobustScaler comparison, and a production `sklearn` Pipeline with `ColumnTransformer`. Logistic Regression baseline: **52% accuracy** (honestly reported).

`Python` `scikit-learn` `Feature Engineering` `Pipeline`

</td>
</tr>
</table>

---

### ▸ TIER II — STATISTICAL ANALYSIS & TIME SERIES

<table>
<tr>
<td width="50%" valign="top">

**[`stock-returns-statistical-analysis`](https://github.com/patience-fuglo/stock-returns-statistical-analysis)**

Empirical investigation of classical statistical assumptions across 10 large-cap stocks (250 trading days). Jarque-Bera normality rejection at **p = 9.22×10⁻¹²**, excess kurtosis up to 16.91. AAPL vs AMZN t-test: p=0.606 (indistinguishable). Zero inside all 95% CIs — consistent with EMH.

`scipy` `Hypothesis Testing` `Fat Tails` `seaborn`

</td>
<td width="50%" valign="top">

**[`multi-asset-timeseries-analysis`](https://github.com/patience-fuglo/multi-asset-timeseries-analysis)**

10-asset time series engineering pipeline: `globals()` dynamic CSV loading, dollar-formatted price cleaning, NumPy broadcasting normalisation (`prices / prices[0]`), 20-day rolling statistics, EWM, and equal-weight portfolio construction via `simple_return.dot(weights)` matrix operation.

`pandas` `NumPy` `Broadcasting` `Portfolio Construction`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[`regime-aware-stock-forecasting`](https://github.com/patience-fuglo/regime-aware-stock-forecasting)**

Production-grade ARIMA forecasting lifecycle: ADF stationarity test (raw: p=0.99 → returns: p≈0), ACF/PACF-guided ARIMA(1,0,1), quantile-based regime classification, model decay detection via rolling error tracking, and walk-forward expanding-window retraining across 4,079 trading days.

`statsmodels` `ARIMA` `Regime Detection` `Model Decay`

</td>
<td width="50%" valign="top">

**[`market-risk-stability-analysis`](https://github.com/patience-fuglo/market-risk-stability-analysis)**

Log-return analysis with Shapiro-Wilk normality testing (IBM: p=1.45×10⁻²⁸), AAPL vs IBM t-test (p=0.030, reject H₀), rolling IBM–MSFT correlation regime analysis, and variance-threshold feature selection. Only AMD, NFLX, TSLA (variance > 0.0005) pass for a high-signal factor model.

`scipy` `PCA` `Feature Selection` `Regime Analysis`

</td>
</tr>
</table>

---

### ▸ TIER III — FACTOR MODELING & VOLATILITY

<table>
<tr>
<td width="50%" valign="top">

**[`market-risk-factor-analysis-pca`](https://github.com/patience-fuglo/market-risk-factor-analysis-pca)**

PCA factor decomposition on 13 years of S&P 500 returns (82,880 observations). **PC1 explains 46.27%** of all return variance — the dominant market factor. GOOG one-sample t-test: p=0.003 (reject H₀ over 3,296 days). Eigendecomposition of 10×10 covariance matrix; λ₁ = 3× λ₂.

`PCA` `scikit-learn` `Eigendecomposition` `Factor Analysis`

</td>
<td width="50%" valign="top">

**[`timeseries-volatility-modeling-framework`](https://github.com/patience-fuglo/timeseries-volatility-modeling-framework)**

Complete AR/MA/ARMA/ARIMA/ARCH/GARCH model comparison. All four mean models converge to **MSE = 0.000195** — quantitative confirmation of EMH. GARCH(1,1) achieves Log-Likelihood 10,405.5 vs ARCH(5) at 10,377.9. Ljung-Box p=0.000033; Jarque-Bera statistic=5,983 on residuals.

`arch` `statsmodels` `GARCH` `Model Diagnostics`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

**[`multi-asset-trading-strategy-analysis`](https://github.com/patience-fuglo/multi-asset-trading-strategy-analysis)**

Systematic trading framework across equities (AAPL), ETFs (SPY), crude oil futures (CL=F), and Bitcoin — via live `yfinance` data. Three strategies implemented and compared: mean reversion (Sharpe = **−0.0016**, applied to a trending asset — intentional), momentum (**+0.0003**), and volatility regime filtering (**+0.0008**, lowest risk at 16.99% ann. vol). CL=F min return of −306% captures the April 2020 WTI negative price event.

`yfinance` `Algorithmic Trading` `Sharpe Ratio` `Multi-Asset`

</td>
</tr>
</table>

---

### ▸ TIER IV — PORTFOLIO CONSTRUCTION & RISK MANAGEMENT

<table>
<tr>
<td width="50%" valign="top">

**[`portfolio-risk-modeling-mpt-capm`](https://github.com/patience-fuglo/portfolio-risk-modeling-mpt-capm)**

Full MPT pipeline: 10,000-portfolio Monte Carlo efficient frontier, Max Sharpe portfolio (Sharpe=**0.882**, AAPL 51.5%), Min Variance portfolio (MSFT 41.2%). Portfolio beta = **1.118**. Historical VaR₉₅ = −2.45%, CVaR₉₅ = −3.53% (108bps gap confirms fat tails). Max drawdown = **−41.11%**. Three stress scenarios. VaR backtesting: **205 violations vs 204.35 expected** — near-perfect calibration over 4,087 days.

`NumPy` `Monte Carlo` `VaR/CVaR` `MPT` `CAPM` `Stress Testing`

</td>
<td width="50%" valign="top">

**[`stock-return-feature-engineering`](https://github.com/patience-fuglo/stock-return-feature-engineering)**

*See Tier I entry above.*

---

**CREDENTIAL SNAPSHOT**

```
CQF  Certificate in Quantitative Finance   2024
MSc  Software Development & Engineering    2023
BSc  Computer Science                      2021
```

Building: **Bullseye Alpha** — systematic equity  
research platform for alpha signal discovery.

🌐 [bullseyealpha.com](https://bullseyealpha.com)

</td>
</tr>
</table>

---

## ◈ TECHNOLOGY STACK

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-4B8BBE?style=flat-square&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-76B7B2?style=flat-square&logoColor=white)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

</div>

---

## ◈ WHAT SEPARATES THIS WORK

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                                                                             │
│  ✦  NO SYNTHETIC RESULTS — every metric (p-values, MSE, Sharpe ratios,    │
│     drawdowns, VaR violations) comes directly from live market data        │
│                                                                             │
│  ✦  HONEST FAILURES DOCUMENTED — 52% classifier accuracy, negative        │
│     Sharpe on mean reversion, rolling ARIMA MSE > static — all explained  │
│                                                                             │
│  ✦  THEORY ↔ IMPLEMENTATION — every model tied to its mathematical        │
│     foundation: GARCH(1,1) equation → arch library → AIC comparison       │
│                                                                             │
│  ✦  PRODUCTION PATTERNS — shuffle=False splits, signal[:-1] alignment,   │
│     RobustScaler for fat tails, walk-forward retraining, VaR backtesting  │
│                                                                             │
│  ✦  FULL LIFECYCLE — data → features → model → diagnostics → stress test  │
│     → backtesting → failure analysis. Not just fitting, but validating.   │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## ◈ RESEARCH INTERESTS

- **Volatility regime modeling** — GARCH extensions (GJR-GARCH, EGARCH, DCC), realized volatility, vol surface dynamics
- **Alternative data** — satellite imagery, NLP on earnings calls, order flow imbalance as alpha signals  
- **High-frequency microstructure** — L2 order book reconstruction, optimal execution, adverse selection modeling
- **Cross-sectional factor research** — Fama-French extensions, momentum decay, factor crowding detection
- **ML for finance** — Walk-forward validation, feature importance stability, regime-conditional model selection

---

<div align="center">

---

*"In markets, the data doesn't lie — but it doesn't explain itself either."*

**Patience M. Fuglo** | [bullseyealpha.com](https://bullseyealpha.com) | [linkedin.com/in/patience-fuglo](https://linkedin.com/in/patience-fuglo) | New York, NY

---

</div>
