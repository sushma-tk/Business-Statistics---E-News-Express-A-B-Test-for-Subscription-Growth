# E-News Express: A/B Test for Subscription Growth

# Project Goal
To statistically determine the effectiveness of a new landing page design for E-news Express, an online news portal, in increasing user engagement and subscriber conversion rates through a controlled A/B testing experiment.

# Context & Business Problem
E-news Express was experiencing a decline in new monthly subscriptions. The executive team hypothesized that the existing landing page lacked sufficient design and content to keep visitors engaged long enough to subscribe.
This project utilized A/B testing to compare the performance of the existing page (Control Group) against a newly designed page (Treatment Group).

# Methodology: A/B Testing
An experiment was conducted using a randomly selected sample of 100 users, split equally:
- Control Group (50 users): Served the Old landing page.
- Treatment Group (50 users): Served the New landing page.
  
A statistical analysis was performed at a 5% significance level ($\alpha$ = 0.05) to evaluate the new page's impact on key user metrics.

# Key Questions and Statistical Tests Used
| Business Question | Statistical Test Applied |
| :--- | :--- |
| Do users spend more time on the new page? | Two Sample T-Test (One-Tailed) |
| Is the conversion rate for the new page higher? | Two Proportion Z-Test (One-Tailed) |
| Does conversion depend on the user's preferred language? | Chi-Square Test of Independence |
| Is time spent on the new page consistent across different language users? | One-Way ANOVA |

# Technical Stack
- Programming: Python
- Libraries:
  - Pandas & NumPy (Data Manipulation and Preparation)
  - Matplotlib & Seaborn (Exploratory Data Analysis and Visualization)
  - SciPy (Statistical Hypothesis Testing: T-Test, Z-Test, Chi-Square, ANOVA)
- Concepts: A/B Testing, Business Statistics, Inferential Statistics.
