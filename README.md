# Kokou Hugues Minasseh

**MSc Artificial Intelligence and Data Science, University of Hull.** I build and validate models for financial markets, with a focus on model risk, market risk, and model reliability. I am aiming for a career in quantitative risk and model validation.

My background is in engineering, and I came to data science through statistical modelling and machine learning. What interests me most is not just building a model, but proving it is sound: the independent, sceptical checking that must be done before a model is trusted.

---

## Quant portfolio

A set of projects built around one idea, the discipline of model validation. Each one builds a model and then checks it honestly: benchmarks it against a known answer, tests where it holds and where it breaks, and reports the results.

**[Volatility Forecasting and Strategy Backtesting](https://github.com/Hugues-hash/volatility-strategy-backtesting)** (Python)

Six volatility models (rolling, EWMA, GARCH, GJR, EGARCH, Random Forest) compared out of sample on 21 years of S&P 500 data, turned into a volatility-targeting strategy, and validated as one-day VaR models with the Kupiec and Christoffersen tests. The main finding: the most accurate forecaster, the best trading signal, and the best risk model turn out to be three different things, which is the whole point of validating a model for the job it will actually do.

**[Regime and Drift Detection in Financial Time Series](https://github.com/Hugues-hash/drift_detection)** (Python)

A two-state Hidden Markov Model labels calm and stressed regimes on the S&P 500, and three drift metrics (PSI, the KS test, and KL divergence) are shown to move with a live model's rising error. It demonstrates that distribution drift is a measurable early warning for model decay, which is the basis of monitoring a model in production.

**[Monte Carlo Option Pricer](https://github.com/Hugues-hash/monte-carlo-option-pricer)** (C++)

A pricing engine written in C++ and validated the way a model risk team validates a pricing model: the Monte Carlo price is benchmarked against the exact Black-Scholes formula, checked for convergence at the theoretical rate, sharpened with antithetic and control-variate variance reduction, and cross-checked on the Greeks using finite differences with common random numbers. An optional pybind11 binding exposes the fast C++ core to Python.

---

## MSc coursework

Coursework projects from the MSc at Hull. These are kept separate from the quant portfolio above and will be added here as their own repositories (prefixed `msc-`).

- Traffic Accident Data Mining and Time-Series Forecasting: spatiotemporal analysis, association rule mining, clustering, and weekly forecasting on UK road accident data.
- NLP Classification with Deep Learning: traditional models (Naive Bayes, SVM) compared with LSTM and Transformer architectures for text classification.
- Predictive Modelling and Customer Behaviour Analysis: regression and classification on structured data, evaluated with AUC-ROC and F1.
- Census Data Analysis and Statistical Decision-Making: hypothesis testing, imputation, and statistical inference on population data.

---

## Technical toolkit

**Languages:** Python, C++, SQL
**Machine learning:** supervised and unsupervised methods, time-series modelling, deep learning (LSTM, Transformer), NLP, model evaluation and selection
**Quant and risk methods:** GARCH / GJR / EGARCH, Hidden Markov Models, Monte Carlo simulation, Value at Risk with Kupiec and Christoffersen backtests, PSI / KS / KL drift monitoring, backtesting with Sharpe and drawdown
**Libraries and tools:** pandas, NumPy, scikit-learn, TensorFlow, arch, hmmlearn, Matplotlib, CMake, pybind11, Git, Jupyter, Power BI

---

## Contact

- Email: mink_hugues@outlook.com
- GitHub: [github.com/Hugues-hash](https://github.com/Hugues-hash)
- LinkedIn: www.linkedin.com/in/kokou-hugues-minasseh-b426591b8
- Based in Hull, UK
