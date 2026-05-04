# Time Series Field Guide

An interactive 4-page teaching tool covering ETS, ARMA, ARIMA, and SARIMA(X), built for the Cambridge PACE 2026 cohort and anyone learning forecasting from scratch.

Each page lets a learner pair a data scenario with a model, see the fit live in a chart, and read a verdict that classifies the combination as Textbook, Workable, or Wrong tool, with reasoning grounded in real-world datasets.

- **ETS** ([ets.html](ets.html)): nine Holt-Winters variants on nine datasets, with a verdict-coloured 3 by 3 matrix
- **ARMA** ([arma.html](arma.html)): ACF, PACF, AIC and BIC selection, stationarity gate
- **ARIMA** ([arima.html](arima.html)): differencing, ADF test, the AIC-across-d trap
- **SARIMAX** ([sarimax.html](sarimax.html)): seasonal differencing, exogenous regressors, rolling-origin cross-validation

Vanilla HTML, CSS, and JS. No build step. KaTeX for maths, Google Fonts for typography.

By Pierre Sutherland.
