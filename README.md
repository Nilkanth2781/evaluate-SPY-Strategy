
---

# 📊 Project 1 – Risk & Return Analysis of Investment Strategies

## Overview

This project, completed as part of **FINA 6333 – Spring 2024**, evaluates the performance of multiple trading strategies using descriptive statistics, risk-adjusted return metrics, and tail-risk measures.

We assess four base strategies (S1, S2, S3, and a composite S4 with 3-day variations) to determine their relative performance, stability, and risk-return tradeoffs.

## 🔑 Key Questions

* Which strategies generate the highest **average returns**?
* Which strategies offer the best **risk-adjusted performance** (Sharpe ratio)?
* How do strategies differ in terms of **Value at Risk (VaR)** and **Conditional VaR (CVaR)**?
* What strategies balance **return potential and downside risk**?

## 📂 Project Structure

```
.
├── Team36_project1.ipynb    # Jupyter notebook with analysis & plots
├── project team 36.docx     # Written report
├── Team36_project1.pptx     # Presentation slides
└── README.md                # Documentation
```

## ⚙️ Methodology

### Data & Models

* Daily returns generated for multiple strategies (S1–S4).
* Statistical measures: mean, variance, standard deviation, skewness, kurtosis.
* Risk metrics: **Sharpe Ratio, VaR, CVaR**.
* Visualization: cumulative returns, kernel density plots, scatter risk-return maps.

### Evaluation Metrics

1. **Descriptive Statistics**

   * **S1**: highest mean return but also highest volatility.
   * **S3**: lowest variance (most stable) but lowest average returns.

2. **Sharpe Ratio**

   * **S4\_days3** has the **highest Sharpe ratio**, suggesting the best risk-adjusted return.

3. **Risk Measures (VaR & CVaR)**

   * **S3** consistently has the lowest expected losses in adverse conditions.

4. **Kernel Density & Cumulative Returns**

   * **S3** and **S4\_days3** show tighter distributions (preferred by risk-averse investors).
   * **S1** and **S4** show steeper cumulative returns (higher growth but riskier).

## 📊 Results (Summary)

* **Best Risk-Adjusted Strategy**: **S4\_days3**

  * Strong mean returns
  * Best Sharpe ratio
  * Balanced VaR & CVaR
* **Most Conservative Strategy**: **S3**

  * Lowest volatility
  * Lowest downside risk
* **Most Aggressive Strategy**: **S1**

  * Highest returns
  * Highest volatility

➡ Investors should weigh **risk tolerance** vs. **return goals**. S4\_days3 offers the most balanced profile.


## 📚 References

* Hull, J. (2018). *Options, Futures, and Other Derivatives*.
* Jorion, P. (2007). *Value at Risk: The New Benchmark for Managing Financial Risk*.
* Class notes and statistical risk analysis references.



---

👉 Would you like me to also add **example plots (Sharpe ratios, KDE, cumulative returns)** directly into the README so that it looks visually polished on GitHub?
