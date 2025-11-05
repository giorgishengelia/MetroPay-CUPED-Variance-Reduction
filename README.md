# MetroPay A/B Testing — CUPED Variance Reduction

**Author:** Giorgi Shengelia  
**Date:** November 2025  

This repository contains a complete A/B testing analysis using **CUPED (Controlled Experiment Using Pre-Experiment Data)**  
to reduce variance and uncover small, meaningful treatment effects in a real-world-style dataset.

---

### 🔗 View the full analysis:
➡️ [**Open the Jupyter Notebook**](MetroPay_CUPED_AB_Test.ipynb)

---

### Contents
| File | Description |
|------|--------------|
| `MetroPay_CUPED_AB_Test.ipynb` | Full Jupyter Notebook (code, plots, and explanations) |
| `metropay_ab.csv` | Experiment dataset |
| `graph.png` | Visualization output |
| `README.md` | Project summary |

---

### Highlights
- Cleaned and analyzed 10K+ user sessions from a checkout experiment.  
- Computed weekly **Conversion Rate (CR)** and **Average Revenue Per User (ARPU)**.  
- Applied **CUPED variance reduction**, revealing a **+0.4 pp lift** in conversion that became statistically significant (p ≈ 0.045).  
- Built reusable code blocks for A/B testing, Z-tests, and bootstrapped ARPU confidence intervals.  
