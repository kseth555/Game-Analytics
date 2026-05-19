# Mobile Game Analytics: Retention & Engagement Optimization

An end-to-end product analytics project focused on analyzing player behavior, retention, engagement, and monetization patterns in a casual mobile game environment using SQL, cohort analysis, funnel analytics, and A/B testing concepts.

This project simulates how real gaming analytics teams evaluate gameplay friction, retention drop-offs, feature experiments, and player monetization strategies to improve long-term user engagement and business performance.

---

# Project Objective

The goal of this project was to analyze player gameplay behavior and identify:

* Why users churn early
* Which gameplay stages create friction
* How retention changes over time
* Which engagement features improve player activity
* How reward systems can impact monetization and retention

The project combines:

* Product analytics
* Funnel analysis
* Cohort analysis
* A/B testing
* Statistical significance testing
* Dashboard-driven business insights

---

# Dataset

### Synthetic Mobile Gaming Dataset

A realistic synthetic dataset was generated to simulate:

* 100,000 mobile game users
* 25,000+ gameplay sessions
* Daily install cohorts
* Retention activity
* Gameplay progression
* Revenue and payer behavior

### Simulated Player Events

The dataset includes:

* User installs
* Daily sessions
* Level progression
* Login streaks
* Reward collection
* In-app purchases
* Retention activity (D1/D7/D30)

### Install Date Range

* April 2023 → October 2025

---

# Core Analytics Areas

## 1. Retention Analysis

Measured:

* D1 retention
* D7 retention
* D30 retention

Used cohort-based analysis to understand:

* early churn
* player stickiness
* long-term engagement patterns

---

## 2. Funnel Analysis

Built gameplay funnels to identify:

* onboarding drop-offs
* level progression friction
* points where players abandon sessions

Example Funnel:

```text
Install → Tutorial Complete → Level 1 → Level 5 → Level 10 → Purchase
```

Insights helped identify gameplay difficulty spikes and onboarding inefficiencies.

---

## 3. Engagement Analytics

Tracked:

* average sessions per user
* gameplay progression
* session frequency
* streak behavior

Analyzed how reward systems influenced:

* repeat engagement
* gameplay consistency
* session depth

---

## 4. Monetization Analytics

Measured:

* Average Revenue Per User (ARPU)
* payer conversion
* revenue uplift
* monetization efficiency

Studied how engagement features impacted:

* purchase probability
* paying user growth
* long-term player value

---

# A/B Testing Experiment

## Experiment Overview

A simulated A/B test was conducted to evaluate the effectiveness of a new streak multiplier reward system.

### Variant A — Control

Standard daily login rewards

### Variant B — Treatment

Streak multiplier rewards designed to encourage repeated daily engagement

---

# Experiment Metrics

The following KPIs were evaluated:

* D7 Retention
* D30 Retention
* Average Revenue Per User
* Payer Conversion
* Sessions Per User
* Levels Completed

---

# Key Results

| KPI                  | Variant A | Variant B | Relative Uplift |
| -------------------- | --------- | --------- | --------------- |
| D7 Retention         | 24.49%    | 31.95%    | +30.5%          |
| D30 Retention        | 10.29%    | 16.27%    | +58.1%          |
| Avg Revenue Per User | $0.49     | $0.58     | +18.4%          |
| Payer Conversion     | 3.09%     | 5.20%     | +68.3%          |
| Sessions D1          | 2.68      | 3.11      | +16.2%          |
| Levels D7            | 14.99     | 18.58     | +24.0%          |

---

# Statistical Significance Testing

Performed statistical testing to verify whether observed uplifts were caused by actual behavioral improvements rather than random variation.

### Methods Used

* Cohort-level comparisons

### Result

All major KPIs showed extremely strong statistical significance:

```text
p-value < 0.001
```

This indicates that the improvements observed in Variant B were highly unlikely to occur due to random chance.

---

# Cohort Insights

Daily cohort analysis revealed:

* D7 retention uplift remained consistently positive across most cohorts
* Daily significance fluctuated because of smaller cohort sizes
* Pooled overall analysis provided strong experimental confidence

Key observation:

```text
The streak reward system consistently improved medium-term engagement.
```

---

# Business Insights & Recommendations

## Key Findings

* Reward multipliers significantly increased player retention
* Higher engagement translated into stronger monetization
* Improved session consistency increased gameplay depth
* Payer conversion improved substantially

## Recommended Product Actions

* Roll out streak multiplier rewards globally
* Optimize onboarding flow to reduce early churn
* Improve gameplay balancing at high-drop-off levels
* Introduce retention-driven live events

---

# Expected Business Impact

Estimated impact from rollout:

* +25–35% improvement in D7 retention
* +15–20% increase in revenue per user
* +50–70% improvement in payer conversion
* Higher long-term player lifetime value (LTV)

---

# Tech Stack

## Languages & Tools

* Python
* SQL
* Pandas
* NumPy
* SciPy
* Matplotlib / Seaborn
* Jupyter Notebook

---

# Skills Demonstrated

* Product Analytics
* Game Analytics
* Funnel Analysis
* Cohort Analysis
* A/B Testing
* Hypothesis Testing
* Statistical Significance
* KPI Analysis
* Retention Analytics
* Monetization Analytics
* Data Visualization
* Business Decision Making

---

# Real-World Relevance

This project mirrors workflows commonly performed by:

* Product Analysts
* Data Analysts
* Gaming Analytics Teams
* Growth Analysts
* Monetization Analysts

Typical use cases include:

* feature experimentation
* retention optimization
* live-ops analysis
* gameplay balancing
* monetization improvement

---

# Future Improvements

Potential future enhancements:

* Real-time analytics dashboards
* Player segmentation models
* Churn prediction using machine learning
* LTV forecasting
* Event-based telemetry pipelines
* Live experiment monitoring

---

# Conclusion

This project demonstrates how data-driven experimentation and analytics can improve mobile gaming engagement, retention, and monetization.

By combining:

* SQL analytics
* cohort analysis
* funnel analysis
* A/B testing
* statistical significance testing

the project simulates a realistic gaming product analytics workflow used in modern gaming companies.
