
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0,1a1a2e,16213e,0f3460&height=200&section=header&text=Patience%20M.%20Fuglo&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Quantitative%20Researcher%20%C2%B7%20Systematic%20Trader%20%C2%B7%20Risk%20Modeler&descAlignY=58&descSize=16&descColor=a0aec0" width="100%"/>
</div>

<div align="center">

[![Portfolio](https://img.shields.io/badge/🌐_bullseyealpha.com-0f3460?style=for-the-badge)](https://bullseyealpha.com)&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/patience-fuglo)&nbsp;
[![Email](https://img.shields.io/badge/patfug3@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:patfug3@gmail.com)&nbsp;
[![Location](https://img.shields.io/badge/New_York,_NY-1a1a2e?style=for-the-badge)](https://bullseyealpha.com)

</div>

<br>

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════════╗
║  Cert in Quantitative Finance · M.Sc. Software Engineering · B.Sc. Computer Science              ║
║   Building systems where mathematics meets markets                        ║
╚══════════════════════════════════════════════════════════════════════════╝
```

</div>

---

## `$ whoami`

> **CQF-certified Quantitative Researcher** operating at the intersection of financial mathematics, statistical modeling, and production engineering. I build systems that extract signal from noise — from GARCH volatility models and PCA factor decompositions to event-driven trading engines and walk-forward forecasting pipelines, covering the full quant stack from raw tick data to portfolio-level risk attribution.

Currently founding **[Bullseye Alpha](https://bullseyealpha.com)** — a next-generation systematic equity research platform for alpha signal discovery across equities and ETFs.

<br>

## `$ at-a-glance`

<div align="center">

|  📁 12 Projects  |  📅 15+ Years Data  |  📈 Sharpe > 1.2 OOS  |  🔄 1,000+ Tickers  |
|:---:|:---:|:---:|:---:|
| Full quant stack covered | S&P 500 1962–2026 | Multi-factor strategies | Scalable pipelines |

</div>

<br>

## `$ experience`

**`BULLSEYE ALPHA`** — *Founder & Lead Quantitative Researcher* · Nov 2024 – Present · New York, NY

```
↳ Architecting a next-gen systematic equity research platform with modular quant engine
↳ Designed & backtested multi-factor strategies achieving Sharpe > 1.2 out-of-sample
↳ Built scalable data pipelines processing 1,000+ tickers for large-scale signal validation
↳ Modeled order book dynamics, slippage & execution — reducing backtest performance bias
↳ Identified cross-sectional return predictors with statistically significant alpha across regimes
```

**`QUANTITATIVE RESEARCH INTERN`** — *Remote* · Jan 2024 – Nov 2024

```
↳ ARIMA and LSTM models improving directional accuracy by 15–20% over baseline
↳ Reduced data ingestion latency by 25% for time-critical financial datasets
↳ Monte Carlo simulations and VaR/CVaR modeling under black-swan stress scenarios
↳ Empirical research on time-series data to identify trading signals and market inefficiencies
```

<br>

## `$ skills --all`

<table>
<tr>
<td valign="top" width="33%">

**Quantitative Finance**
```
Time-Series Analysis
Alpha Signal Generation
Factor Modeling (PCA)
Portfolio Optimization (MPT)
CAPM & Beta Estimation
VaR / CVaR / Drawdown
Volatility Forecasting (GARCH)
Stress Testing & Scenarios
Efficient Frontier
```

</td>
<td valign="top" width="33%">

**Machine Learning & Stats**
```
ARIMA / ARCH / GARCH
LSTM / XGBoost / RandomForest
Walk-Forward Validation
Feature Engineering Pipelines
Regime Detection
Model Decay Monitoring
Hypothesis Testing
Eigendecomposition
Stochastic Processes
```

</td>
<td valign="top" width="34%">

**Engineering**
```
Python · NumPy · Pandas
Scikit-learn · Statsmodels
FastAPI · Docker · C++
Redis Streams · ClickHouse
BigQuery · Vertex AI
SQL · Event-Driven Arch
Market Microstructure
Order Book Simulation
```

</td>
</tr>
</table>

<br>

## `$ projects --tier=all`

---

### ▌TIER I — Systems & Pipelines

<table>
<tr>
<td width="50%" valign="top">

#### [`smart-trade-analytics-engine`](https://github.com/patience-fuglo/smart-trade-analytics-engine)

Trade data validation and analytics engine with two implementations — modular functional pipeline **and** OOP class hierarchy (`Trade` + `TradePortfolio`). Handles dirty broker data: mixed types, `None` values, zero prices. `try/except/finally` provides audit trail on every record.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![OOP](https://img.shields.io/badge/OOP-1a1a2e?style=flat-square)
![Pipelines](https://img.shields.io/badge/Pipelines-0f3460?style=flat-square)

</td>
<td width="50%" valign="top">

#### [`smart-log-incident-detection`](https://github.com/patience-fuglo/smart-log-incident-detection)

Server log processing engine with severity classification (CRITICAL / HIGH / MEDIUM / LOW), allowlist validation, and structured incident summarization. Three distinct rejection modes with different exception types — `finally` block fires on 100% of entries for complete audit coverage.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Defensive](https://img.shields.io/badge/Defensive_Programming-1a1a2e?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [`smart-trade-analyzer`](https://github.com/patience-fuglo/smart-trade-analyzer)

Three-class OOP hierarchy: `Trade → TradeAnalyzer → StrategyAnalyzer`. Lambda-based filtering with `filter()`, `max()`/`min()` key functions, argument unpacking `(*data)`, and `if __name__ == "__main__"` entry point. Both imperative and functional approaches shown side-by-side.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Inheritance](https://img.shields.io/badge/Inheritance-0f3460?style=flat-square)
![Lambdas](https://img.shields.io/badge/Lambdas-16213e?style=flat-square)

</td>
<td width="50%" valign="top">

#### [`stock-return-feature-engineering`](https://github.com/patience-fuglo/stock-return-feature-engineering)

End-to-end ML pipeline: 10+ financial indicators, Box-Cox transforms (λ=1.007), three encoding strategies, three scalers with **RobustScaler** recommended for fat-tailed returns, and a production `sklearn Pipeline` with `ColumnTransformer`. Logistic Regression baseline: **52% accuracy** — honestly reported with class-imbalance analysis.

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![yfinance](https://img.shields.io/badge/yfinance-1a1a2e?style=flat-square)
![ML](https://img.shields.io/badge/ML_Pipeline-0f3460?style=flat-square)

</td>
</tr>
</table>

---

### ▌TIER II — Statistical Analysis & Time Series

<table>
<tr>
<td width="50%" valign="top">

#### [`stock-returns-statistical-analysis`](https://github.com/patience-fuglo/stock-returns-statistical-analysis)

Empirical investigation of classical statistical assumptions across 10 large-cap stocks. Jarque-Bera normality rejection at **p = 9.22×10⁻¹²**. Excess kurtosis up to **16.91** (AMD). AAPL vs AMZN t-test: p=0.606. Zero inside all 95% CIs — consistent with EMH. QQ plots, one/two-sample tests, Wilcoxon, Mann-Whitney.

![scipy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![seaborn](https://img.shields.io/badge/seaborn-76B7B2?style=flat-square)
![Fat Tails](https://img.shields.io/badge/Fat_Tails-0f3460?style=flat-square)

</td>
<td width="50%" valign="top">

#### [`multi-asset-timeseries-analysis`](https://github.com/patience-fuglo/multi-asset-timeseries-analysis)

10-asset engineering pipeline: `globals()` dynamic CSV loading, dollar-formatted price cleaning, NumPy broadcasting normalisation (`prices / prices[0]`), 20-day rolling stats, EWM (span=20), and equal-weight portfolio via `simple_return.dot(weights)` — no loops, pure matrix ops. 2,510 data points.

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Broadcasting](https://img.shields.io/badge/Broadcasting-16213e?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [`regime-aware-stock-forecasting`](https://github.com/patience-fuglo/regime-aware-stock-forecasting)

Full ARIMA lifecycle: ADF test (prices p=0.990 → returns p≈0.000), ACF/PACF-guided **ARIMA(1,0,1)**, quantile-based regime classification (Low / Moderate / High Volatility), model decay detection via 12-period rolling error, and walk-forward expanding-window retraining across **4,079 trading days**. Rolling vs static MSE comparison reported honestly.

![statsmodels](https://img.shields.io/badge/statsmodels-4B8BBE?style=flat-square)
![ARIMA](https://img.shields.io/badge/ARIMA-1a1a2e?style=flat-square)
![Regime](https://img.shields.io/badge/Regime_Detection-0f3460?style=flat-square)

</td>
<td width="50%" valign="top">

#### [`market-risk-stability-analysis`](https://github.com/patience-fuglo/market-risk-stability-analysis)

Log-return analysis with Shapiro-Wilk (IBM: p=**1.45×10⁻²⁸**), AAPL vs IBM t-test (p=**0.030**, reject H₀), rolling IBM–MSFT correlation regime analysis 2010–2023. Variance-threshold feature selection: only **AMD, NFLX, TSLA** pass variance > 0.0005 for high-signal modelling. 3-component PCA on filtered subspace.

![scipy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![PCA](https://img.shields.io/badge/PCA-16213e?style=flat-square)
![Feature Selection](https://img.shields.io/badge/Feature_Selection-0f3460?style=flat-square)

</td>
</tr>
</table>

---

### ▌TIER III — Factor Modeling & Volatility

<table>
<tr>
<td width="50%" valign="top">

#### [`market-risk-factor-analysis-pca`](https://github.com/patience-fuglo/market-risk-factor-analysis-pca)

PCA factor decomposition on **82,880 observations** (1962–2023, 10 tickers). **PC1 explains 46.27%** of all return variance — dominant market factor. GOOG one-sample t-test: p=**0.003** (reject H₀, 3,296 days). Eigendecomposition: λ₁ = 3× λ₂. Covariance heatmap, 95% CIs for all assets, rolling covariance and correlation stability analysis.

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![PCA](https://img.shields.io/badge/PCA-1a1a2e?style=flat-square)
![Eigendecomposition](https://img.shields.io/badge/Eigendecomposition-0f3460?style=flat-square)

</td>
<td width="50%" valign="top">

#### [`timeseries-volatility-modeling-framework`](https://github.com/patience-fuglo/timeseries-volatility-modeling-framework)

Complete AR/MA/ARMA/ARIMA/ARCH/GARCH comparison on 4,082 days of AAPL. All 4 mean models converge to **MSE = 0.000195** — quantitative EMH confirmation. GARCH(1,1) Log-Likelihood: **10,405.5**, AIC: **-20,803** (beats ARCH(5)). Ljung-Box: p=**0.000033**. Jarque-Bera: statistic=**5,983**. Five-mode failure analysis: regime change, fat tails, leverage effect, structural breaks, overfitting.

![arch](https://img.shields.io/badge/arch_library-1a1a2e?style=flat-square)
![GARCH](https://img.shields.io/badge/GARCH-0f3460?style=flat-square)
![Diagnostics](https://img.shields.io/badge/Diagnostics-16213e?style=flat-square)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### [`multi-asset-trading-strategy-analysis`](https://github.com/patience-fuglo/multi-asset-trading-strategy-analysis)

Systematic trading framework across **equities (AAPL), ETFs (SPY), crude oil futures (CL=F), and Bitcoin** via live `yfinance` data. Three strategies: mean reversion (Sharpe = **-0.0016** on a trending asset — strategy-regime mismatch documented, not hidden), momentum (**+0.0003**), volatility regime (**+0.0008**, lowest risk at 16.99% ann. vol). CL=F min return of **-306%** captures the April 2020 WTI negative price event. Bond pricing formula, call option payoff (`np.maximum(S−K, 0)`) vectorised across price range. Signal alignment: `signal[:-1]` for lookahead-free execution.

![yfinance](https://img.shields.io/badge/yfinance-3776AB?style=flat-square&logo=python&logoColor=white)
![Multi-Asset](https://img.shields.io/badge/Multi--Asset-1a1a2e?style=flat-square)
![Sharpe](https://img.shields.io/badge/Sharpe_Ratio-0f3460?style=flat-square)
![Options](https://img.shields.io/badge/Options-16213e?style=flat-square)
![Futures](https://img.shields.io/badge/Futures-0f3460?style=flat-square)

</td>
</tr>
</table>

---

### ▌TIER IV — Portfolio Construction & Risk Management

#### [`portfolio-risk-modeling-mpt-capm`](https://github.com/patience-fuglo/portfolio-risk-modeling-mpt-capm) — *Flagship Project*

<div align="center">

| Metric | Value | Context |
|:---|:---:|:---|
| Efficient Frontier Portfolios | **10,000** | Monte Carlo random weights |
| Max Sharpe (Ann. Return) | **21.02%** | AAPL 51.5%, AMZN 19.0%, GOOGL 15.4%, MSFT 14.1% |
| Max Sharpe Ratio | **0.882** | Zero risk-free rate |
| Portfolio Beta | **1.118** | vs S&P 500 benchmark |
| Historical VaR₉₅ | **-2.45%/day** | 5th percentile of daily returns |
| CVaR₉₅ (Expected Shortfall) | **-3.53%/day** | 108bps gap confirms fat tails |
| Parametric VaR₉₅ | **-2.40%/day** | μ − 1.65σ Gaussian approximation |
| Maximum Drawdown | **-41.11%** | Peak-to-trough, 2010–2026 |
| VaR Backtesting | **205 vs 204.35** | Near-perfect calibration over 4,087 days |

</div>

Full pipeline: annualised returns (AAPL 22.8%, AMZN 21.3%, GOOGL 18.2%, MSFT 17.2%) → 10×10 covariance matrix → 10,000-portfolio Monte Carlo → Max Sharpe + Min Variance identification → CAPM beta per asset → portfolio beta aggregation → Historical/Parametric VaR/CVaR → drawdown duration analysis → three stress scenarios (market crash −5%, vol spike 2×, correlation breakdown ρ=1) → cumulative return vs S&P 500 benchmark → rolling 252-day Sharpe revealing regime instability → VaR backtesting with Kupiec-style violation counting.

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Monte Carlo](https://img.shields.io/badge/Monte_Carlo-1a1a2e?style=flat-square)
![MPT](https://img.shields.io/badge/MPT-0f3460?style=flat-square)
![CAPM](https://img.shields.io/badge/CAPM-16213e?style=flat-square)
![VaR/CVaR](https://img.shields.io/badge/VaR%2FCVaR-0f3460?style=flat-square)
![Stress Testing](https://img.shields.io/badge/Stress_Testing-1a1a2e?style=flat-square)

---

## `$ principles`

```
01  No synthetic results     — every p-value, MSE, Sharpe, drawdown comes from live market data
02  Honest failures          — negative Sharpe, 52% accuracy, rolling > static MSE; all explained
03  Theory ↔ implementation  — GARCH equation → arch library → AIC comparison; always connected
04  Production patterns      — shuffle=False splits, signal[:-1] alignment, RobustScaler, walk-forward
05  Full lifecycle           — data → features → model → diagnostics → stress test → backtesting
```

---

## `$ stack`

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4B8BBE?style=for-the-badge&logoColor=white)
![arch](https://img.shields.io/badge/arch_(GARCH)-1a1a2e?style=for-the-badge&logoColor=white)

</div>

---

## `$ research-interests`

- **Volatility regime modeling** — GJR-GARCH, EGARCH, DCC, realized volatility, vol surface dynamics
- **Alternative data** — satellite imagery, NLP on earnings calls, order flow imbalance as alpha signals
- **High-frequency microstructure** — L2 order book reconstruction, optimal execution, adverse selection modeling
- **Cross-sectional factor research** — Fama-French extensions, momentum decay, factor crowding detection
- **ML for finance** — walk-forward validation, feature importance stability, regime-conditional model selection
- **Market microstructure** — price-time priority matching, slippage modeling, event-driven execution engines

---

## `$ education`

```
2024  Certificate in Quantitative Finance (CQF)
2023  M.Sc.  Software Development & Engineering
2021  B.Sc.  Computer Science
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0,0f3460,16213e,1a1a2e&height=120&section=footer&text=In%20markets%2C%20the%20data%20doesn%27t%20lie%20%E2%80%94%20but%20it%20doesn%27t%20explain%20itself%20either.&fontSize=13&fontColor=a0aec0&fontAlignY=65" width="100%"/>

</div>
