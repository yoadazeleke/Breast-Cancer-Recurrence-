# Breast Cancer Recurrence Data Analysis
## Overview
In this case study, I worked on analyzing breast cancer recurrence data to demonstrate my ability to handle real-world data analysis tasks, focusing on **data cleaning**, **assessing findings**, and **data visualization** using **Tableau**. The goal was to uncover key patterns in the dataset that could help inform clinical decisions, improve patient outcomes, and optimize healthcare strategies such as screening recommendations and treatment evaluations.

--- 

## Table of Contents
1. [Overview](#overview)
2. [1. Ask: Defining the Objective](#1-ask-defining-the-objective)
3. [2. Prepare: Understanding and Cleaning the Data](#2-prepare-understanding-and-cleaning-the-data)
4. [3. Process: Organizing the Data for Analysis](#3-process-organizing-the-data-for-analysis)
5. [4. Analyze: Exploring the Data](#4-analyze-exploring-the-data)
6. [5. Share: Communicating Insights with Visualizations](#5-share-communicating-insights-with-visualizations)
7. [6. Act: Implementing Insights into Action (Hypothetical)](#6-act-implementing-insights-into-action-hypothetical)
8. [Conclusion](#conclusion)

---

## 1. Ask: Defining the Objective
For this project, the main objectives were:
- To identify factors influencing cancer recurrence and potential high-risk demographics.
- To develop actionable insights that healthcare professionals could use for improved decision-making, particularly around screening, treatment, and follow-up care.
- To create clear and informative visualizations that make complex data accessible and usable in clinical settings.

---

## 2. Prepare: Understanding and Cleaning the Data
Before conducting any analysis, I needed to ensure the data was clean and ready for processing. For this, I used **Google Sheets** for the following tasks:

- **Handling Missing Data:** I addressed missing values by either imputing data using mean/median values or removing rows with insufficient data, depending on the context.
- **Outlier Detection:** Using conditional formatting and basic statistical methods, I identified and reviewed potential outliers that could affect the analysis.
- **Data Transformation:** I standardized categorical variables, transforming them into numerical values for analysis. This made the dataset easier to work with for the tools I used.
- **Normalization:** I normalized numerical data, ensuring that variables like tumor size, age, and other continuous features were on the same scale.

**Google Sheets Data:**
You can access the cleaned dataset here:  
[Breast Cancer Recurrence Data (Google Sheets)](https://docs.google.com/spreadsheets/d/1pGQo09Hav0yDvFeTFxRCqIf8eKqsH_p-hRI6FU7boB8/edit?usp=sharing)

---

## 3. Process: Organizing the Data for Analysis
With the data cleaned, I began organizing it into a structured format that allowed me to effectively analyze and visualize the key patterns. This included:

- **Organizing Key Variables:** I categorized data based on important features such as age, tumor size, node involvement, and recurrence status.
- **Filtering Irrelevant Data:** I removed or ignored non-relevant data to focus on the most impactful variables, making my analysis more targeted.
- **Creating Derived Features:** I created new columns to represent risk categories based on tumor size and lymph node involvement, which helped highlight trends during the analysis.

---

## 4. Analyze: Exploring the Data
Once the data was prepared, I began the analysis to uncover significant patterns and insights:

- **Exploratory Data Analysis (EDA):** I explored the dataset with summary statistics and visualizations (such as histograms and box plots) to get an initial understanding of the data.
- **Correlation Analysis:** I analyzed the relationships between continuous variables such as tumor size and recurrence rates to identify patterns.
- **Comparing Groups:** I examined differences between groups (such as age groups and treatment types) to see how various factors influenced recurrence rates and survival outcomes.

### Key Findings:
- **Age:** Younger patients had a higher recurrence rate compared to older individuals.
  ![Age and Breast Cancer Recurrence](https://github.com/user-attachments/assets/625eeba6-a129-4b88-8976-533d1419369a)

- **Tumor Size:** Larger tumors were strongly correlated with higher recurrence rates.
  ![Tumor Size and Breast Cancer Recurrence](https://github.com/user-attachments/assets/61ae704b-a9cb-4887-ad50-16c39e2c52eb)

- **Lymph Node Status:** Patients with positive lymph nodes showed higher recurrence rates.
  ![Node-caps and Breast Cancer Recurrence](https://github.com/user-attachments/assets/a82ef439-e639-4378-8814-62d1ceade174)

- **Treatment Type:** Radiation therapy was linked to lower recurrence rates, particularly in older patients.
![Radiation Treatment and Breast Cancer](https://github.com/user-attachments/assets/5739b77f-0fef-466c-8ff6-3ccb87da3e14)

---

## 5. Share: Communicating Insights with Visualizations
To effectively communicate my findings, I created **Tableau** dashboards that highlighted key insights in an easy-to-understand manner:

- **Recurrence Rate by Demographics:** A bar chart showing how recurrence rates varied by age, tumor size, and treatment type.
- **Correlation Matrix:** A heatmap to visualize correlations between different variables and their impact on recurrence.
- **Interactive Dashboards:** I built dashboards that allowed users to filter data by key variables (e.g., age, tumor size, treatment) to explore recurrence patterns across different groups.
- **Survival Curves:** Kaplan-Meier survival curves were generated to show how the risk of recurrence changed over time based on factors like age and tumor size.

These visualizations helped make the complex data more accessible to healthcare professionals, supporting data-driven decision-making.
![Breast Cancer Analysis Dashboard](https://github.com/user-attachments/assets/32dfa772-eae8-4c64-bad5-8d73f63679e9)

**Tableau Dashboard:**
You can explore the Tableau dashboard for interactive visualizations here:  
[Breast Cancer Recurrence Analysis (Tableau)](https://public.tableau.com/app/profile/yoada.zeleke/viz/BreastCancerRecurrenceAnalysis/Dashboard1)

---

## 6. Act: Implementing Insights into Action (Hypothetical)
As this project was a student exercise, I approached the **Act** phase hypothetically, focusing on how I would translate the insights gained from the analysis into actionable strategies in a real-world healthcare context. Here are some examples of how the insights could be used:

### Refining Screening Recommendations
- **Prioritizing High-Risk Groups:** Based on the findings, I would collaborate with senior healthcare professionals to develop targeted screening guidelines for high-risk groups, particularly younger patients with larger tumors and positive lymph node involvement.
- **Tailoring Screening Schedules:** Using data insights, I would recommend adjusted screening schedules for post-menopausal women and older individuals to ensure early detection of recurrence.

### Creating Data Visualizations for Decision-Making
- **Interactive Dashboards for Clinicians:** I would work with clinical teams to develop user-friendly Tableau dashboards that provide real-time insights into patient risk levels, based on factors like tumor size, lymph node involvement, and treatment type.
- **Visualization of Treatment Effectiveness:** By analyzing the impact of treatments like radiation therapy, I could help inform decision-makers about adjusting treatment protocols for more personalized patient care.

### Supporting Patient Education Initiatives
- **Developing Educational Materials:** Based on the analysis, I would help develop materials to educate patients on the significance of early detection and the role of specific treatments in reducing recurrence risk.
- **Creating Infographics:** I would design easy-to-understand infographics summarizing key findings to help patients and caregivers make informed decisions about treatment options.

### Contributing to Follow-Up Care Strategies
- **Tracking Recurrence:** I would assist in developing tools to track recurrence patterns, particularly for high-risk groups, ensuring ongoing monitoring for potential recurrences.
- **Optimizing Care Plans:** By analyzing trends in patient follow-up data, I would contribute to improving personalized care plans and treatment strategies for patients who are at higher risk of recurrence.

### Enhancing Treatment Evaluations
- **Assessing the Impact of Radiation Therapy:** I would work with the medical team to further analyze how radiation therapy impacts recurrence rates, especially across different demographics, and contribute to the refinement of treatment guidelines.
- **Identifying Optimal Treatment Protocols:** Using the analysis of recurrence data, I would collaborate in discussions to adjust treatment protocols to improve patient outcomes.

### Ensuring Data Quality and Accessibility
- **Maintaining Data Integrity:** I would work closely with healthcare teams to ensure that all patient data remains accurate and organized, supporting future analyses and continuous improvement in treatment protocols.
- **Streamlining Data Sharing:** I would support the development of methods for sharing insights and visual reports with clinical staff, making data more accessible and usable for decision-making.

---

## Conclusion
This project allowed me to demonstrate my ability to work with healthcare data and transform it into actionable insights that could improve patient care and clinical decision-making. By utilizing **data cleaning**, **data analysis**, and **data visualization**, I was able to uncover valuable patterns that informed important healthcare strategies, including screening, treatment, and follow-up care. The visualizations and insights I created were designed to make complex data more understandable, supporting better decision-making for both healthcare professionals and patients.
