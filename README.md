📘 ESG & Financial Performance Analysis of European Banks
A quantitative study linking ESG scores to profitability, efficiency, risk, and balance‑sheet structure.

📄 Project Overview
This repository contains the full analysis, dataset, and reporting for a quantitative study investigating whether Environmental, Social, and Governance (ESG) performance is a meaningful financial driver for European banks.
Despite popular assumptions that ESG improves profitability or operational efficiency, the findings show a more nuanced and long‑term relationship.
This project includes:

The full dataset used for the analysis
Complete regression outputs (12 models)
Cluster analysis comparing High‑ESG and Low‑ESG banks
A summarized Interpretation & Commentary Report
A detailed Quantitative Report


📊 Key Findings (Summary)
1. ESG is not a strong short‑term financial predictor
Across 12 regression models:

R² values remain low (≈ 0.10–0.30; maximum ≈ 0.31)
Almost all F‑tests are insignificant
Only 4 ESG sub-scores ever reach p < 0.05 — each only once
Adjusted R² is sometimes even negative

Interpretation:
Short-term banking performance (ROA, ROE, efficiency ratios, liquidity metrics) is dominated by baseline business conditions, not ESG.

2. No multicollinearity issues
All VIF values are low (typically below 2).
Meaning:
The weak regressions are genuine — not caused by overlapping ESG inputs.

3. ESG Clusters reveal structural — not financial — differences
High‑ESG banks are:

Roughly 10× larger in asset size
Less leveraged (safer capital structure)

But financially not better-performing:

ROA, ROE, Net Profit Margin → no significant difference
Liquidity, efficiency, and income structure → no meaningful difference

Interpretation:
ESG aligns with scale and maturity, not earnings power.

4. Subsample regressions confirm the same conclusion
Even when splitting banks into High‑ESG vs. Low‑ESG groups:

No consistent ESG predictor emerges
Models remain statistically weak
Significant coefficients appear only sporadically


5. The financial meaning of all this
Short term:
ESG does not reliably drive profitability or operational performance.
Long term:
ESG appears related to:

More resilient balance-sheet structure
Lower leverage
Institutional maturity
Stability-oriented business models

Conclusion:
ESG is more of a risk‑profile indicator than a short‑term “return generator”.
🧰 Methodology
The analysis includes:

12 multiple linear regressions
VIF multicollinearity diagnostics
K-means cluster analysis for ESG profiles
Comparative KPI analysis (High‑ESG vs Low‑ESG groups)
Subsample regressions by ESG tier

All calculations, metrics, and interpretations are based on the dataset included in the repository.

📌 Purpose of the Project
This repository serves as:

A transparent demonstration of quantitative ESG analysis
A portfolio piece showcasing data handling, econometrics, and interpretation skills
A foundation for future, more advanced model development (non-linear, interaction effects, panel data, causal models)
![pic](https://github.com/user-attachments/assets/4dcc40de-6983-4901-85f1-e3dfb23eccbd)
<img width="3000" height="1800" alt="r2_bar_chart" src="https://github.com/user-attachments/assets/5d100fc6-ca6d-4aee-a2d4-210458c883a1" />
<img width="935" height="414" alt="Screenshot 2026-03-19 1532044" src="https://github.com/user-attachments/assets/f2d5e985-b702-4b26-bf24-00aca0aded7d" />

