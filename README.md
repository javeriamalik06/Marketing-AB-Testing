# Marketing-AB-Testing

#### Business Problem
Marketing teams aim to optimize advertisement strategies to maximize user conversions. This project evaluates the effectiveness of two types of ads—commercial ads (Ad) and public service announcements (PSA)—to determine which leads to higher conversion rates. By identifying statistically significant differences in user engagement, businesses can allocate their advertising budgets more effectively.

#### Technical Details
* [Data](https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing) consists of **588,101** records with variables including user ID, test group (Ad or PSA), conversion status, total ads shown, most active ad day, and most active ad hour.
* Exploratory Data Analysis (EDA) was performed to understand data distribution and key patterns.
* Statistical tests were conducted:
  - **Chi-Square Test**: Used to analyze categorical variables (test group, ad day, ad hour) and their impact on conversion.
  - **Mann-Whitney U Test**: Applied to assess the difference in total ads shown for converted vs. non-converted users due to non-normal distribution.
* Key findings:
  - The test group significantly affects conversion rates.
  - Conversion rates vary significantly based on the day and hour of ad exposure. They also vary based on the total ads shown.
  - Users in the Ad group had a higher conversion rate than those exposed to PSA.

#### Recommendation
Marketing teams should prioritize **commercial ads** over public service announcements for driving conversions. Additionally, optimizing ad placements based on high-performing days and hours can further enhance campaign effectiveness. 
