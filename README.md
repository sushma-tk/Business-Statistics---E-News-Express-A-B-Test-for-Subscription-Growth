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


# Key Findings & Conclusions
| Metric | Business Question | Control Group (Old Page) | Treatment Group (New Page) | Statistical Test & Conclusion |
| :--- | :--- | :--- | :--- | :--- |
| **Time Spent** | Do users spend more time on the new page? | **4.53 minutes** (Mean) | **6.22 minutes** (Mean) | **Two Sample T-Test:** New page time is significantly higher (P-value = 0.0001). |
| **Conversion Rate** | Is the conversion rate for the new page higher? | **42%** (21/50 users) | **66%** (33/50 users) | **Two Proportion Z-Test:** New page conversion is significantly higher (P-value = 0.008). |

Other Finding : 
- **Language Independence**: There is no significant relationship between a user's preferred language (English, French, or Spanish) and their likelihood of converting.
- **Uniform Engagement**: The mean time spent on the new page is statistically the same across all language groups, suggesting the new design is universally engaging.

# Recommendations 
- Implement the new landing page to enhance user engagement and increase subscriptions.
- Prioritize a seamless user experience by ensuring content is easily accessible and navigation is intuitive.
- Utilize feedbacks to understand user behavior and identify areas for improvement.
- Incorporate high-quality visuals, videos, and infographics to make content more engaging and easily digestible.
- Allow users to share articles on social media platforms to increase visibility and drive traffic.

# Technical Stack
- Programming: Python
- Libraries:
  - Pandas & NumPy (Data Manipulation and Preparation)
  - Matplotlib & Seaborn (Exploratory Data Analysis and Visualization)
  - SciPy (Statistical Hypothesis Testing: T-Test, Z-Test, Chi-Square, ANOVA)
- Concepts: A/B Testing, Business Statistics, Inferential Statistics.
