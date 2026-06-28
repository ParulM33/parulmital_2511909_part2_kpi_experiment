# parulmital_2511909_part2_kpi_experiment
# Part 2: KPI Framework and Experiment Analysis

 

## 1. Business Context

 

This project analyzes an A/B experiment for a new onboarding and activation campaign.

 

Two groups were tested:

- Control group: Existing onboarding experience

- Treatment group: New onboarding flow

 

The goal is to decide whether the new experience should be launched based on performance and impact.

 

---

 

## 2. North Star Metric

 

The selected North Star metric is:

 

Paid Conversion Rate (paid users / total users)

 

This metric is chosen because it directly reflects the business objective of converting users into paying customers.

 

---

 

## 3. KPI Framework

 

The KPI Tree is divided into three main areas:

 

### Activation Funnel

- Landing page visit rate

- Trial start rate

- Onboarding completion rate

- Paid conversion rate

 

### Revenue Quality

- Average revenue per user

- Revenue per converted user

 

### User Experience

- Engagement score

- Days to convert

- Support ticket rate

 

### Guardrail Metrics

- Refund rate

- Support ticket rate

- Engagement score

 

---

 

## 4. Summary of Results

 

The Treatment group showed improvement across most key metrics:

 

- Paid conversion rate increased from 3.19% to 7.04%

- Trial start rate and onboarding completion rate improved

- Engagement score increased

- Users converted faster (fewer days)

 

However, some risks were observed:

- Support ticket rate increased

- Refund rate slightly increased

- Revenue per converted user decreased

 

---

 

## 5. Hypothesis Testing

 

### Hypothesis

 

Null hypothesis (H0): Treatment conversion rate is less than or equal to Control 

Alternative hypothesis (H1): Treatment conversion rate is greater than Control 

 

### Test Details

 

- Test type: One-tailed two-proportion z-test

- Significance level: 0.05

 

### Results

 

- Control conversion rate: 3.19%

- Treatment conversion rate: 7.04%

- Lift: 3.85 percentage points

- Z statistic: 3.26

- P-value: 0.000549

 

Since p-value is less than 0.05, we reject the null hypothesis.

 

This means the improvement is statistically significant.

 

---

 

## 6. Interpretation

 

The new onboarding experience significantly increases paid conversion rate.

 

Users in the Treatment group:

- Move faster through the funnel

- Show higher engagement

- Convert at a higher rate

 

However, there are trade-offs:

- Increase in support tickets suggests usability issues

- Refund rate slightly increased

- Revenue quality needs monitoring

 

---

 

## 7. Final Recommendation

 

Launch with monitoring

 

The Treatment experience should be launched because it significantly improves conversion.

 

However, the company should monitor:

- Support ticket rate

- Refund rate

- Revenue quality

 

A phased rollout can also be considered to reduce risk.

 

---

 

## 8. Files Included

 

- experiment_analysis.xlsx

- summary_metrics.png

- hypothesis_test_output.png

- kpi_tree.png

