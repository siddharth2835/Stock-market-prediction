## Project Overview
This project aims to develop a **machine learning-based framework** for predicting the future return, price direction, and volatility of selected Indian small- and mid-cap stocks. 

The system combines multiple sources of information:
* Historical price and trading data
* Technical indicators
* Company fundamentals
* Market and sector-level factors
* Macroeconomic indicators
* Financial news sentiment

---

## Data Collection & Processing
Since small- and mid-cap companies often have limited company-specific news coverage, the proposed system incorporates **company-level, sector-level, and market-level news** to capture both stock-specific and broader market effects. 

* **Source:** News data is collected using the **MarketAux API**.
* **Processing:** Data is processed for entity relevance and sentiment, then aggregated into time-aligned features.

---

## Methodology & Objectives
* **Rigorous Evaluation:** The project uses **time-series-based training and evaluation** to prevent data leakage.
* **Comparative Analysis:** Different machine learning approaches are compared to understand how specific feature groups contribute to prediction performance.
* **Probabilistic Outputs:** Rather than generating direct buy/sell recommendations, the system delivers actionable predictions, including:
  * Expected future return
  * Probability of upward/downward movement
  * Expected volatility

---

## Future Extensibility
The framework is designed to be fully extensible, paving the way for future research and enhancements such as:
* Advanced NLP models and Deep Learning
* Explainable AI (XAI)
* Alternative data sources
* Sophisticated portfolio-level analysis
