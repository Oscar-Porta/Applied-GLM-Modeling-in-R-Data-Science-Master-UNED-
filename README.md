# Applied Regression Models with R (Freeny Dataset)

This repository contains the final assessment for the Regression Models module, part of the Master’s in Big Data and Data Science Applied to Economics and Business at UNED (2024–2025).

## 🎯 Objective

To solve a set of regression modeling exercises using R and RMarkdown, with full commentary, diagnostics, and interpretation. The analysis is based on the **Freeny** dataset included in the `memisc` package, which contains quarterly toy sales and economic indicators.

## 🧪 Exam Structure

### 1. Simple Linear Regression
- Reading and summarizing the Freeny dataset.
- Estimating a linear model of price vs. sales.
- Confidence intervals and residual diagnostics.
- Significance test of negative relationship (one-sided test, α = 0.05).

### 2. Multiple Regression
- Selecting the best explanatory model for toy sales.
- Comparison of GLM models using AIC and pseudo R².
- Bayesian regression and comparison with classical methods.
- Cook’s distance and robust estimation (if needed).
- Evaluation of OLS vs. Ridge regression when multicollinearity is present.

### 3. Polynomial Regression
- Modeling nonlinear relationships between price and sales.

### 4. ANOVA and ANCOVA
- Creating temporal variables (year and quarter).
- Fitting an ANOVA model with time-based factors.
- Fitting an ANCOVA model including price as covariate.
- Interpretation of results.

## ⚙️ Tools and Libraries

- R  
- `memisc`, `ggplot2`, `broom`, `car`, `arm`, `MASS`  
- `rstanarm` or `brms` (optional Bayesian)  
- RMarkdown for structured reporting

## 📁 Files Included

- `Examen 2025 Modulo 3.html` – Final rendered HTML  
- `Examen 2025 Modulo 3.Rmd` – Full RMarkdown source code

## 👨‍💻 Author

Óscar Porta  
Master’s Student in Big Data & Data Science – UNED  
GitHub: [Oscar-Porta](https://github.com/Oscar-Porta)
