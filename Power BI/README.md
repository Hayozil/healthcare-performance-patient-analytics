# Healthcare Performance & Patient Analytics Dashboard

# Project Overview

The Healthcare Performance & Patient Analytics Dashboard is an interactive Business Intelligence project developed using Microsoft Power BI to analyze the operational, financial, and patient-experience performance of a healthcare organization operating across multiple states in Nigeria.

Healthcare organizations generate large amounts of data from patient visits, medical departments, diagnoses, revenue, costs, waiting times, satisfaction scores, and patient outcomes. However, raw data can make it difficult for management to quickly understand overall performance and identify areas that require attention.

This project transforms raw healthcare data into an interactive analytical solution that provides management with a centralized view of organizational performance.

The dashboard combines financial analysis, patient analytics, operational performance, and patient experience analysis into a single Power BI report.

The solution allows users to:

* Monitor the number of patients and visits.
* Track revenue, costs, and profitability.
* Compare revenue against state-level targets.
* Analyze patient demographics.
* Identify common diagnoses.
* Evaluate department performance.
* Monitor patient waiting times.
* Analyze patient satisfaction.
* Compare performance across states and branches.
* Examine patient outcomes.
* Identify areas of operational and financial concern.

The central business question guiding the project is:

### How is our healthcare organization performing, what are our patients experiencing, and where are the major areas that require attention?

The project also demonstrates the application of a complete Power BI workflow, including data preparation, data modeling, DAX development, interactive visualization, dashboard design, drill-through analysis, tooltips, bookmarks, page navigation, dynamic insights, and Row-Level Security.

# Business Problem

The healthcare organization operates across multiple states and generates data from different areas of its operations.

Management needs to understand whether the organization is performing effectively and where improvements should be made.

However, without a centralized analytical solution, answering these questions can be difficult.

The organization faces several analytical challenges.

## Financial Performance

Management needs visibility into:

* Total revenue generated.
* Total operational costs.
* Total profit.
* Profit margins.
* Revenue performance by state.
* Revenue performance by department and service.
* Revenue targets.
* Variance between actual revenue and targets.
* Target achievement.

Without this analysis, management may not easily identify which locations or departments are financially strong or underperforming.

## Patient Volume and Demographics

The organization also needs to understand its patient population.

Important questions include:

* How many patients are being served?
* How many healthcare visits are recorded?
* Which states have the highest patient volume?
* Which age groups are most represented?
* What are the most common diagnoses?
* What are the patient outcomes?
* What proportion of patients are categorized as new or returning?
  
## Operational Performance

Healthcare operations directly influence the quality of service delivered to patients.

Management needs to identify:

* Which departments handle the highest patient volumes?
* Which departments have the longest waiting times?
* Which branches perform well operationally?
* Which branches may require improvement?
* How does waiting time vary across departments and branches?
  
## Patient Experience

Patient satisfaction is another important performance indicator.

The organization needs to understand:

* Average patient satisfaction.
* Satisfaction by department.
* Satisfaction by branch.
* Waiting time across departments.
* Whether areas with longer waiting times also experience lower satisfaction.
* Patient outcomes across the organization.

## The Business Challenge

The main challenge is therefore to transform raw healthcare data into clear, actionable insights that management can use to improve:
* Financial performance.
* Operational efficiency.
* Patient experience.
* Resource allocation.
* Service delivery.


# Project Objectives

The main objective of this project is to develop an interactive Power BI dashboard that provides a comprehensive view of healthcare performance.
The specific objectives are to:

1. Measure overall healthcare performance using key performance indicators.
2. Analyze patient volume and demographics.
3. Identify common diagnoses and patient outcomes.
4. Evaluate hospital department performance.
5. Analyze waiting times and patient satisfaction.
6. Evaluate revenue, cost, profit, and profit margins.
7. Compare actual revenue with state-level revenue targets.
8. Identify high-performing and underperforming states and branches.
9. Provide interactive filtering and drill-through capabilities.
10. Create dynamic insights that help management interpret the data.
11. Implement Row-Level Security for controlled access to state-level information.
12. Build a professional, user-friendly dashboard suitable for management reporting.


# Key Business Questions
The dashboard was designed to answer the following business questions.

## Overall Performance
* How many patients does the organization serve?
* How many total visits were recorded?
* How much revenue was generated?
* How much did the organization spend?
* What is the total profit?
* What is the overall profit margin?
  
## Patient Analytics
* Which age group represents the largest patient population?
* Which diagnoses are most common?
* Which states have the highest patient volumes?
* How many patients are classified as new or returning?
* What are the most common patient outcomes?
* Operational Analytics
* Which departments handle the most visits?
* Which departments have the longest waiting times?
* Which branches have the highest patient volume?
* Which departments have the highest satisfaction scores?
* Are there departments or branches requiring operational attention?
  
## Financial Analytics
* Which states generate the most revenue?
* Which departments generate the most revenue?
* Which services generate the most revenue?
* Which departments generate the highest profit?
* How does actual revenue compare with the target?
* Which states are closest to or furthest from their targets?
  
## Patient Experience
* What is the average patient satisfaction score?
* What is the average waiting time?
* Which departments have the lowest satisfaction?
* Which branches have longer waiting times?
* Is there an observable relationship between waiting time and satisfaction?

 # Tools and Technologies
 The following tools and technologies were used throughout the project.

## Tool/Technology -	Purpose
* Microsoft Power BI -	Data modeling, DAX, visualization, dashboard development
* Power Query -	Data cleaning and transformation
* DAX -	Measures, calculated columns, KPIs and dynamic insights
* Microsoft Excel -	Source dataset
* GitHub -	Project documentation and portfolio presentation
  
## Power BI
Power BI was the primary tool used to develop the analytical solution.
It was used for:
* Data modeling.
* DAX calculations.
* Interactive dashboards.
* KPI cards.
* Charts and tables.
* Slicers.
* Drill-through.
* Report-page tooltips.
* Bookmarks.
* Page navigation.
* Conditional formatting.
* Dynamic titles.
* Dynamic insights.
* Row-Level Security.
  
  ## Power Query

Power Query was used to prepare the raw dataset before analysis.
It was used for:

* Data type correction.
* Data validation.
* Missing-value checks.
* Duplicate checks.
* Data consistency checks.
* Data transformation.
  
  ## DAX
DAX was used to create business metrics and analytical calculations.
Examples include:

* Total Patients.
* Total Visits.
* Total Revenue.
* Total Cost.
* Total Profit.
* Profit Margin.
* Average Revenue Per Patient.
* Average Waiting Time.
* Average Satisfaction.
* Previous Month Revenue.
* MoM Revenue Growth.
* Revenue Target.
* Revenue Variance.
* Achievement Percentage.
  
## GitHub
GitHub serves as the project's documentation and portfolio repository.
It provides a structured location for:

* Project documentation.
* Dashboard screenshots.
* Dataset files.
* Power BI files.
* DAX documentation.
* Project insights.
* Recommendations.

## Dataset
The project uses an Excel workbook containing three primary datasets:

## 1. Patient Visits

The Patient_Visits table contains 1,200 patient records and serves as the primary analytical dataset.
It contains information relating to:

* Patients.
* Visits.
* States.
* Branches.
* Departments.
* Services.
* Diagnoses.
* Revenue.
* Costs.
* Waiting times.
* Satisfaction.
* Outcomes.

## Dataset Fields
## Column  - Description
* Patient_ID -	Unique patient identifier
* Visit_Date -	Date of healthcare visit
* State -	State where service was provided
* Branch -	Healthcare branch
* Department -	Department handling the patient
* Service -	Service provided
* Age -	Patient age
* Gender -	Patient gender
* Diagnosis -	Patient diagnosis
* Payment_Method -	Patient payment method
* Insurance_Type -	Insurance category
* Visit_Count-	Number of visits
* Revenue_NGN -	Revenue generated
* Cost_NGN -	Cost incurred
* Waiting_Time_Min -	Waiting time in minutes
* Satisfaction_Score -	Patient satisfaction rating
* Outcome -	Patient visit outcome


## 2. State Targets
The State_Targets table contains state-level annual revenue targets.
This table allows the dashboard to calculate:

* Revenue Target.
* Revenue Variance.
* Achievement Percentage.
  
## 3. Date Table
The Date_Table contains dates covering the reporting period.
It supports:

* Monthly analysis.
* Revenue trends.
* Patient visit trends.
* Previous-month calculations.
* Time intelligence.
  
## Important Data Consideration
A key modeling decision was made regarding patients versus visits.
There are 1,200 unique patients, while the Visit_Count field sums to 2,920 visits.

Therefore:
## Total Patients ≠ Total Visits

The project uses DISTINCTCOUNT(Patient_ID) for patients and SUM(Visit_Count) for visits.

This prevents the dashboard from incorrectly treating each patient record as a single healthcare visit.

# Data Preparation

Data preparation was performed using Power Query before building the analytical model.

The goal was to ensure that the data was clean, consistent, correctly typed, and ready for analysis.

## Step 1 — Data Import
The Excel workbook was imported into Power BI.
The following tables were loaded:

* Patient_Visits
* State_Targets
* Date_Table

  
## Step 2 — Data Type Validation
Data types were reviewed and corrected where necessary.
Examples:

* Patient_ID → Text
* Visit_Date → Date
* State → Text
* Branch → Text
* Department → Text
* Age → Whole Number
* Visit_Count → Whole Number
* Revenue_NGN → Decimal Number
* Cost_NGN → Decimal Number
* Waiting_Time_Min → Whole Number
* Satisfaction_Score → Decimal Number

  
## Step 3 — Missing Value Checks
Important fields were checked for blanks and missing values.
The review focused on:

* Patient IDs.
* Dates.
* States.
* Departments.
* Revenue.
* Costs.
* Waiting times.
* Satisfaction scores.
* Outcomes.
  
## Step 4 — Duplicate Checks
The dataset was checked for duplicate records.
Patient IDs were also reviewed to understand patient uniqueness.

## Step 5 — Category Consistency
Categorical fields were reviewed for consistency.
Examples include:

* State.
* Branch.
* Department.
* Diagnosis.
* Gender.
* Payment Method.
* Insurance Type.
* Outcome.
  
## Step 6 — Derived Fields
Additional fields were created to support deeper analysis.
For example, an Age Group field was created to categorize patients into:

* 0–17
* 18–35
* 36–50
* 51–65
* 66+

A Patient Type classification was also created based on Visit_Count.

## Step 7 — Data Validation
After preparation, the transformed data was reviewed to ensure:

* Correct data types.
* Consistent categories.
* Accurate numerical values.
* Correct date interpretation.
* Reliable relationships.
* Correct DAX calculations.

The prepared data was then loaded into the Power BI data model.

# Data Model
The project uses a structured relational data model designed to support reliable filtering, calculations, and analysis.

The model follows a star-schema-oriented approach, with Patient_Visits functioning as the main fact table and supporting tables providing dimensions and reference information.

* Main Tables
* Patient_Visits
* Date_Table
* State_Targets
* Dim_State
* UserState

# Row-Level Security
The project also includes a UserState mapping table.
The purpose is to control which states individual users can access.
Example:

## User -	Authorized State
* Manager A	- Lagos
* Manager A	- Rivers
* Manager B	- Abuja
* Manager C	- Anambra
This enables dynamic access based on the logged-in user's identity.

## Why the Data Model Is Important
A well-designed data model ensures that:

* Filters propagate correctly.
* DAX measures calculate accurately.
* Time intelligence works correctly.
* State analysis remains consistent.
* Targets can be compared with actual performance.
* Drill-through functionality works properly.
* Row-Level Security can be implemented.
* The dashboard remains scalable and easier to maintain.


# DAX Measures and Calculations
DAX (Data Analysis Expressions) was used in Power BI to create the key calculations and performance indicators required for the dashboard.
The main measures created include:

* Total Patients
* Total Visits
* Total Revenue
* Total Cost
* Total Profit
* Profit Margin %
* Average Revenue per Patient
* Average Waiting Time
* Average Satisfaction
* Previous Month Revenue
* MoM Revenue Growth %
* Revenue Target
* Revenue Variance
* Achievement %
* New Patients
* Returning Patients
* Average Visits per Patient

Calculated fields were also created for Age Group and Patient Type to support patient segmentation and analysis.

These DAX calculations power the dashboard's KPI cards, charts, financial analysis, operational metrics, dynamic insights, and interactive reporting.


# Dashboard Structure
The dashboard consists of five main analytical pages.

## Page 1 — Executive Overview
Provides management with a high-level summary of organizational performance.

* KPIs
* Total Patients.
* Total Visits.
* Total Revenue.
* Total Cost.
* Total Profit.
* Average Revenue per Patient.
* Average Waiting Time.
* Average Satisfaction.
* Visuals
* Monthly Patient Visits.
* Revenue by State.
* Patients by Department.
* Revenue vs Target.
* Patient Outcome Distribution.

The page is designed to provide a quick executive-level understanding of the organization's current performance.

## Page 2 — Patient Analysis
This page focuses on patient demographics and behavior.

* Analysis includes:
* Patients by Age Group.
* Patients by Gender.
* Patients by Diagnosis.
* Patients by State.
* New vs Returning Patients.
* Average Visits per Patient.
* Patient Outcomes.

This page helps management understand who the organization is serving and what types of healthcare needs are most common.

## Page 3 — Hospital Operations
This page focuses on operational efficiency.

* KPIs
* Total Patients.
* Total Visits.
* Average Waiting Time.
* Average Satisfaction.
* Visuals
* Visits by Department.
* Average Waiting Time by Department.
* Satisfaction by Department.
* Patient Outcomes.
* Branch Performance Matrix.
* Monthly Patient Volume.
* Waiting Time vs Satisfaction analysis.

The page helps identify departments and branches that may require operational improvement.

## Page 4 — Financial Performance
This page focuses on the organization's financial performance.

* KPIs
* Total Revenue.
* Total Cost.
* Total Profit.
* Profit Margin.
* Revenue Target.
* Revenue Variance.
* Achievement Percentage.
* Average Revenue per Patient.
* Visuals
* Revenue by State.
* Revenue by Department.
* Revenue by Service.
* Profit by Department.
* Monthly Revenue.
* Revenue vs Target.
* State Financial Performance Matrix.
  
## Page 5 — Patient Experience
This page focuses specifically on patient satisfaction and service experience.

* KPIs
* Average Satisfaction.
* Average Waiting Time.
* Total Patients.
* Total Visits.
* Visuals
* Satisfaction by Department.
* Satisfaction by Branch.
* Satisfaction Distribution.
* Waiting Time by Department.
* Patient Outcomes.
* Waiting Time vs Satisfaction.
* Branch Experience Matrix.

# Interactive Features
The dashboard includes several interactive Power BI features.

## Slicers
Users can filter the report by:

* Date.
* State.
* Branch.
* Department.
* Gender.
* Page Navigation
A left-side navigation panel allows users to move between the five major dashboard pages.

## Drill-Through
A dedicated State Details page allows users to right-click a state and drill into detailed state-level performance.
The drill-through page provides:

* Patients.
* Visits.
* Revenue.
* Profit.
* Waiting time.
* Satisfaction.
* Department performance.
* Service performance.
* Patient outcomes.
* Branch performance.
* Report-Page Tooltips

Custom financial tooltips provide additional information when users hover over financial visuals.

## Bookmarks
Bookmarks are used to create interactive dashboard elements such as an executive insights panel.

## Dynamic Titles
Dynamic titles change based on the user's selected state or filter context.

## Dynamic Executive Insights
A dynamic narrative provides a text-based summary of important performance indicators.

## Conditional Formatting
Conditional formatting is applied to tables and matrices to make strong and weak performance easier to identify.

## Row-Level Security
Dynamic RLS is designed to ensure users can only access the states they are authorized to view.

# Key Insights
The analysis revealed several important patterns within the dataset.

## Patient Volume
The dataset contains 1,200 unique patients and 2,920 total visits, demonstrating that the organization handles significantly more visits than its unique patient count.

## State Revenue
Revenue varies across the four states.

Based on the analysis:
* Rivers generated the highest revenue.
* Abuja followed closely.
* Lagos and Anambra recorded lower revenue relative to the leading states.

This indicates that state-level performance is not evenly distributed.

## Department Volume
Pediatrics recorded the highest number of patient visits among the departments, followed by Outpatient and Pharmacy.

This suggests that these departments represent significant areas of patient demand and may require appropriate staffing and resource allocation.

## Diagnoses
The most frequently recorded diagnoses include:

* Malaria.
* Typhoid.
* Hypertension.
* Other conditions.
* Respiratory infections.
* Diabetes.

Malaria represents the largest diagnosis category within the dataset.

## Waiting Time
Waiting times vary across departments.

The analysis indicates that Laboratory has one of the highest average waiting times, while Outpatient also experiences relatively high waiting times.
This may indicate opportunities for process optimization.

## Patient Age
The largest patient age groups are:

* 18–35.
* 36–50.
This indicates that adults between 18 and 50 constitute a significant portion of the patient population.

## Revenue Target Performance
The organization's actual revenue is below the combined annual state revenue targets.

This indicates that management should investigate the factors contributing to the gap between actual revenue and expected revenue.

## Patient Experience
Patient satisfaction varies across branches and departments.

The dashboard makes it possible to identify locations where satisfaction and waiting-time performance require additional attention.

# Business Recommendations
Based on the analysis, the following recommendations can be considered.

## 1. Improve High-Waiting-Time Departments
Departments with relatively high waiting times should be investigated to identify operational bottlenecks.

Management could review:

* Patient flow.
* Staffing levels.
* Queue management.
* Service processes.
* Peak-period demands
  
## 2. Optimize Resource Allocation
High-volume departments such as Pediatrics, Outpatient, and Pharmacy should receive appropriate staffing and resources based on patient demand.

## 3. Investigate Revenue Target Gaps
States performing below their annual revenue targets should be investigated to understand the reasons behind the revenue gap.
Possible areas include:

* Patient volume.
* Service mix.
* Pricing.
* Department performance.
* Branch utilization.
  
## 4. Monitor Patient Satisfaction
Departments and branches with lower satisfaction should be monitored closely.

Management should examine whether:

* Waiting time is contributing to dissatisfaction.
* Service delivery needs improvement.
* Staffing levels are adequate.
* Patient flow needs optimization.
  
## 5. Strengthen High-Performing States
High-performing states such as Rivers can be studied to identify successful operational or revenue-generating practices that could potentially be applied to other states.

## 6. Use Data for Continuous Monitoring
The dashboard should be used as an ongoing management tool rather than a one-time report.
Regular monitoring can help management detect changes in:

* Patient volume.
* Revenue.
* Costs.
* Waiting time.
* Satisfaction.
* Department performance.

# Conclusion
The Healthcare Performance & Patient Analytics Dashboard demonstrates how Power BI can transform raw healthcare data into an interactive Business Intelligence solution.
The project brings together multiple areas of healthcare performance, including:

* Patient analytics.
* Operational performance.
* Financial performance.
* Patient experience.

Through data preparation, structured data modeling, DAX calculations, interactive visualizations, and advanced Power BI features, the dashboard provides management with a centralized view of organizational performance.
The solution makes it easier to identify:

* High-volume departments.
* Common diagnoses.
* Revenue-performing states.
* Financial target gaps.
* Operational bottlenecks.
* Waiting-time concerns.
* Patient satisfaction patterns.
Ultimately, the dashboard demonstrates how data analytics can support evidence-based decision-making, operational improvement, financial monitoring, and better patient experiences.

# Author
BADA AYOMIDE SAMUEL
 Data Analyst | Power BI | Data Analytics | Certified Chemist

This project represents part of my transition into Data Analytics, applying analytical thinking, data visualization, and Business Intelligence techniques to a real-world healthcare scenario.

* Skills Demonstrated
* Data Cleaning
* Power Query
* Data Modeling
* DAX
* Power BI
* Data Visualization
* Business Intelligence
* Dashboard Design
* Analytical Thinking
* Business Problem Solving
* Data Storytelling
# Project Summary
This project demonstrates the complete process of transforming raw healthcare data into an interactive Power BI Business Intelligence solution that helps management understand financial performance, patient behavior, hospital operations, and patient experience.

* Tools: Power BI • Power Query • DAX • Excel • GitHub
* Domain: Healthcare Analytics
* Project Type: Business Intelligence / Data Analytics
