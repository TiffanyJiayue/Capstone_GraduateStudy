# Capstone Project: Pittsburgh Technology Council Member Renewal Analysis

## Project Overview
This capstone project supports the Pittsburgh Technology Council in understanding factors driving member renewals. It explores:

### Scorecard Usage: Which scorecards are most heavily used by renewing members?
### Engagement Levers: What types of engagement strategies most effectively secure renewals?
### Event Participation: How participation correlates with membership retention.

The project utilizes advanced statistical analyses, including survival modeling, to uncover actionable insights and develop strategies for member retention.

Repository Contents
1. Capstone_1.Rmd: Introduction and Data Overview
Introduces the dataset and project objectives.
Performs exploratory data analysis (EDA) to summarize key trends and features.
2. Capstone_2.Rmd: Scorecard Usage Analysis
Explores scorecard usage patterns among renewing members.
Visualizes usage trends from 2018 to 2023.
3. Capstone_3.Rmd: Scorecard Categorization and Trends
Categorizes scorecards into main types.
Converts SC Date and Paid Through Date into month numbers for temporal analysis.
Visualizes scorecard usage trends for all members and specific categories over time.
4. Capstone_4.Rmd: Event Participation Analysis
Examines how event participation correlates with membership renewals.
Focuses on metrics like event frequency and participation trends.
5. Capstone_5.Rmd: Panel Dataset Preparation and Visualization
Builds a panel dataset to support survival modeling in Capstone_6.
Prepares data and creates comprehensive visualizations to analyze member behavior:
Binary Conversion: Converts Event_Frequency and scorecard columns to binary variables.
Company Categorization: Adds company categories to member data for detailed segmentation.
Current Member Analysis: Plots the distribution of current members across company categories.
Behavioral Analysis:
Compares behaviors in the first six months vs. the second six months of membership.
Adds confidence intervals to visualizations for statistical robustness.
Examines member usage before leaving PTC, focusing on participation in events and scorecards (e.g., "Event_Participation," "SC.Outreach").
Temporal Comparison:
Compares event participation in the first year vs. the last year of membership.
Visualization Experiments: Tests different plotting approaches to identify the most effective visualizations.
Concludes by running a preliminary survival model to evaluate membership trends, with a plan to refine it in Capstone_6.
6. Capstone_6.Rmd: Membership Survival Analysis
Cox Proportional Hazards Model:
Explores time-dependent factors influencing membership duration.
Key Findings:
Event Participation: A one-unit increase reduces the risk of ending membership by 16.5%.
Scorecard Outreach (SC.Outreach): A one-unit increase reduces the risk of ending membership by 20.3%.
Strategies for Membership Enhancement:
Retention Strategies: Encourage consistent engagement and diverse activity participation.
Event Diversification: Expand topics, formats, and categories to appeal to varied interests.
Feedback Integration: Use insights to tailor event offerings and enhance member experiences.
How to Use This Repository
Clone or download the repository to your local machine.
Ensure you have R and necessary libraries installed (e.g., survival, ggplot2, caret).
Run the .Rmd files sequentially for a comprehensive understanding:
Start with Capstone_1.Rmd for an overview.
Progress through Capstone_2 to Capstone_5 for detailed analyses and visualizations.
Conclude with Capstone_6 for survival modeling insights.
Render the .Rmd files into HTML/PDF for a polished report.
Findings and Implications
This project delivers key insights into member retention:

High-Impact Engagement Levers: Scorecard outreach and event participation significantly enhance retention.
Behavioral Trends: Detailed analyses reveal how member behavior changes over time.
Predictive Insights: A survival model identifies time-dependent risks and opportunities for retention strategies.
Recommendations
Retention Strategies: Maintain member engagement through targeted communications and activities.
Event Diversification: Offer diverse events to cater to different interests and needs.
Feedback Integration: Use data-driven insights to refine services and enhance member satisfaction.
Contact
For questions or further details, please reach out via GitHub.

