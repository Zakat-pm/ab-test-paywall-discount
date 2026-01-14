# A/B Test: Subscription Paywall Discount

## 📌 Project Overview

This project analyzes the results of an A/B test conducted in a mobile application to evaluate whether adding a **“50% discount”** message to a subscription paywall increases conversion to purchase.

**Test groups:**
- **Control (A):** Standard subscription offer ($4.99)
- **Variant (B):** Same price, but with a “50% discount” message

The goal was to measure the impact of pricing communication on user behavior.

---

## 🎯 Primary Metric

**Purchase Conversion Rate**  
(share of users who completed a purchase)

---

## 🧠 Hypothesis

We hypothesize that adding a “50% discount” message to the subscription paywall
will increase the purchase conversion rate.

- **H0 (Null hypothesis):**  
  The purchase conversion rate in the variant with a “50% discount” message
  is equal to or lower than in the control group.

- **H1 (Alternative hypothesis):**  
  The purchase conversion rate in the variant with a “50% discount” message
  is higher than in the control group.

---

## 🧪 Experiment Design

- Randomized A/B test  
- Independent samples  
- Significance level: **α = 0.05**  
- Statistical test: **Two-proportion z-test**

---

## 📊 Results Summary

| Group | Users | Conversions | Conversion Rate |
|------|------:|------------:|----------------:|
| A | 10,013 | 611 | 6.10% |
| B | 9,985 | 889 | 8.90% |

- **Absolute uplift:** +2.8 pp  
- **p-value:** < 0.0001  
- **Result:** statistically significant

---

## 📈 Visualizations

- Conversion comparison with **95% confidence intervals**
- Conversion trend over time  

(see `/visuals` folder)

---

## ✅ Conclusion & Product Decision

The variant with the **“50% discount”** message shows a statistically significant increase in purchase conversion.

**Recommended action:**
- Roll out **Variant B**
- Continue monitoring downstream metrics (**ARPU**, **retention**)

---

## 🛠 Tools Used

- Python  
- Pandas, NumPy  
- SciPy  
- Matplotlib, Seaborn

