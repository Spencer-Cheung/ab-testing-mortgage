# AB Testing Mortgage

Evaluating how pricing vs. rate adjustments impact mortgage lock behavior using a simulated A/B testing framework.

##  Overview
This project explores how pricing and rate adjustments impact mortgage lock behavior using an A/B testing framework built on simulated loan data.

The goal is to understand the trade-off between **conversion (lock volume)** and **profitability (margin / revenue)** — a key decision problem in mortgage secondary marketing and capital markets.

---

##  Problem Statement
Mortgage pricing decisions directly affect:
- Borrower lock behavior  
- Loan volume  
- Revenue and margins  

However, determining whether to adjust **price vs. rate** is not always straightforward.

This project builds a structured approach to evaluate these trade-offs through simulation and (later) modeling.

---

##  Approach

### Notebook 1 — Data Generation
- Generate synthetic loan-level data  
- Simulate borrower and loan characteristics  

### Notebook 2 — Scenario Simulation
- Apply pricing and rate adjustments  
- Evaluate impact on:
  - Lock rate  
  - Lock volume  
  - Revenue  

### Notebook 3 — Experimental Validation *(in progress)*
- Introduce statistical / ML-based modeling  
- Move toward a true A/B testing framework  

---

## 🔍 Key Insight (So Far)

Initial simulations suggest:

- **Price reductions** increase volume but reduce revenue due to margin compression  
- **Rate reductions** significantly improve both volume and total revenue  

> This highlights the asymmetric impact of pricing vs. rate strategies in mortgage markets.

---

##  Data
- All data is **synthetic and generated within the project**
- No real borrower or loan data is used
- Datasets are not stored in the repository and are reproducible via code

---

##  Purpose
This project is designed to:
- Demonstrate applied data science in a financial / mortgage context  
- Explore A/B testing and causal thinking in pricing strategy  
- Bridge business intuition with analytical modeling  

---

##  Disclaimer
This is a simulation-based project for educational and exploratory purposes.  
Results should not be interpreted as real-world pricing recommendations.
