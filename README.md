# Capstone Project: Pittsburgh Technology Council Member Renewal Analysis

## Project Overview
This capstone project supports the Pittsburgh Technology Council by analyzing key factors that influence member renewals. The primary objectives are:
- **Scorecard Usage**: Determine which scorecards are most heavily used by renewing members.
- **Engagement Levers**: Identify engagement strategies that effectively secure renewals.
- **Event Participation**: Analyze the link between event participation and member retention.

The project employs advanced statistical analyses and visualizations, culminating in survival modeling to understand membership duration.

---

## Repository Contents

### **1. `Capstone_1.Rmd`: Introduction and Data Overview**
- **Summary**: Provides an overview of the dataset and outlines the objectives.
- **Key Features**:
  - Initial exploratory data analysis (EDA).
  - Descriptive statistics to summarize data characteristics.

### **2. `Capstone_2.Rmd`: Scorecard Usage Analysis**
- **Summary**: Investigates scorecard usage patterns among renewing members.
- **Key Features**:
  - Analysis of scorecards most frequently used.
  - Visualizations to identify trends from 2018–2023.

### **3. `Capstone_3.Rmd`: Scorecard Categorization and Trends**
- **Summary**: Categorizes scorecards and visualizes their trends.
- **Key Features**:
  1. Groups scorecard types into main categories.
  2. Converts `SC Date` and `Paid Through Date` columns into month numbers.
  3. Graphs scorecard usage from 2018–2023:
     - For all members.
     - For specific categories of scorecards.

### **4. `Capstone_4.Rmd`: Event Participation Analysis**
- **Summary**: Examines the impact of event participation on member renewals.
- **Key Features**:
  - Analyzes metrics like event frequency, participation rates, and engagement patterns.
  - Identifies how events influence member retention.

### **5. `Capstone_5.Rmd`: Panel Dataset Preparation and Visualization**
- **Summary**: Builds a panel dataset for survival modeling and produces detailed visualizations.
- **Key Features**:
  1. Checks and converts `Event_Frequency` into a binary variable.
  2. Adds binary columns for scorecard categories.
  3. Categorizes companies in the dataset.
  4. Creates visualizations:
     - Number of current members in each category.
     - Behavioral comparisons (e.g., first six months vs. second six months).
     - Member usage before leaving (e.g., "Event_Participation," "SC.Outreach").
     - Event participation comparison (first year vs. last year).
  5. Experiments with different plotting methods to identify the most effective visualizations.
  6. Runs a preliminary survival model to support analysis in `Capstone_6`.

### **6. `Capstone_6.Rmd`: Membership Survival Analysis**
- **Summary**: Uses survival analysis to study membership duration and identify renewal risks.
- **Key Features**:
  - Cox Proportional Hazards Model:
    - **Event Participation**: A one-unit increase reduces the risk of ending membership by **16.5%**.
    - **Scorecard Outreach**: A one-unit increase reduces the risk of ending membership by **20.3%**.
  - Generates survival curves and evaluates time-dependent factors.
- **Strategic Recommendations**:
  - Retention strategies to sustain engagement.
  - Event diversification to meet diverse member needs.
  - Feedback integration to improve services.

---

## How to Use This Repository

1. **Clone the repository**:
   ```bash
   git clone https://github.com/TiffanyJiayue/Capstone_GraduateStudy.git

2. **Set up the environment:
- Ensure you have R installed along with the following libraries:
  - `ggplot2`
  - `survival`
  - `caret`
  - And other dependencies mentioned in the `.Rmd` files.

3. **Run the `.Rmd` files sequentially:
1. Start with `Capstone_1.Rmd` for data overview.
2. Progress through `Capstone_2.Rmd` to `Capstone_5.Rmd` for analysis and dataset preparation.
3. Conclude with `Capstone_6.Rmd` for survival modeling.

4. **Render outputs:
- Render the `.Rmd` files into HTML or PDF for polished reports using the following R command:
   ```R
   rmarkdown::render("Capstone_1.Rmd")

## Findings and Implications
This project provides actionable insights into member renewals:

### High-Impact Engagement Levers
- Scorecard outreach and event participation significantly enhance retention.

### Behavioral Insights
- Members show distinct patterns during different stages of their membership.

### Survival Analysis
- Time-dependent risks and opportunities for retention are revealed, offering a clear roadmap for improvement.

---

## Recommendations
1. **Retention Strategies**: Encourage consistent engagement through tailored communication and activities.
2. **Event Diversification**: Expand event offerings to cater to diverse member interests.
3. **Feedback Integration**: Use member feedback to refine services and ensure satisfaction.

---

## Contact
For any questions or further details, please reach out via GitHub.


