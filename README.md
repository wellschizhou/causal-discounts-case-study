# Causal Impact of Discounts on Profit — E-commerce Case Study

**Business question:** Do onboarding discounts increase long-term **profit**?

**Complication:** Discounts were **not randomly assigned** — larger discounts went to customers with higher **sales predictions**, causing **confounding**.

**Method (plan):**
- Diagnose assignment bias.
- Estimate effect using **adjusted regression** and **Double Machine Learning (DML)**.
- Explore **heterogeneous effects** by prediction segments and simulate a **targeted policy**.
- (Optional) Validate on an **experimental** dataset later.

**How to run:**
1. Add `data/non_rand_discount.csv` (not included)  
   *or* run the notebook with a synthetic generator (to be added).
2. Open `ecommerce_discount_causal_case_study.ipynb` and run.

**Repo structure:**
├─ README.md
├─ ecommerce_discount_causal_case_study.ipynb
├─ .gitignore
└─ data/
└─ .gitkeep (placeholder; datasets are not tracked)

**Data:** The original dataset is synthetic and part of a paid course; it is **not** included.  
**License:** MIT (see `LICENSE`).
