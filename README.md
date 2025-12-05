# **Shark Tank India – Investment & Deal Analytics (EDA)**
This repository contains a structured exploratory analysis of the Shark Tank India dataset. The goal is to understand how industry category, founder composition, financials, and investor behavior influence deal outcomes. The analysis focuses on generating practical, data-driven insights for founders, investors, and ecosystem analysts.

---

## **📌 Objectives**

* Quantify deal and investment patterns across industries
* Evaluate how founder characteristics affect success rates
* Profile investor behavior and capital deployment
* Identify geographic concentration of funded startups
* Assess negotiation intensity through valuation cuts
---

## **📊 Methodology**

1. **Data Cleaning & Normalization**
   Monetary fields converted from lakhs to million INR, missing values handled, categories standardized.

2. **Feature Engineering**

   * `Deal_Success_Flag`
   * `Industry_Cleaned`
   * `Founder_Type` (Male / Female / Mixed)
   * `Valuation_Cut_Pct`

3. **Exploratory Analysis**
   Visual summaries, pivot tables, crosstabs, and descriptive statistics.

4. **Business Interpretation**
   Trends, founder performance, investor patterns, and negotiation outcomes.

---

## **🔍 Key Insights**

* **Industry concentration:** F&B, Tech, and Beauty/Fashion dominate both pitch volume and capital deployed.
* **Founder diversity:** Mixed-founder teams consistently show higher deal conversion.
* **Investor skew:** A few sharks account for the majority of invested capital, reflecting strong investment specializations.
* **Geographic bias:** Funded startups overwhelmingly come from major metros.
* **Valuation discipline:** Negotiation reduces founder valuation expectations in most deals.

## **📦 Requirements**

Minimal environment:

```text
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## **📈 Future Extensions**

* Deal outcome prediction using classification models
* Investor clustering by portfolio similarities
* Industry-level time-series trends across seasons
* Startup revenue vs valuation benchmarking

