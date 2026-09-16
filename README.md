## RIT Student Participation Analysis

This README presents the final submission of the RIT Student Participation Analysis project. The purpose of the project was to understand student participation patterns and build a model that could predict learner status.

## Project Overview

The project was completed in four stages:

* Week 1: Data understanding and cleaning
* Week 2: Exploratory data analysis and visualisation
* Week 3: Predictive modelling and model evaluation
* Week 4: Final report submission

The cleaned dataset contains **8,552 records and 23 columns**.

## Tools Used

* Python
* Google Colab
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

## Data Preparation

The dataset was checked for:

* Missing values
* Duplicate records
* Incorrect data types
* Inconsistent category names
* Unusual values

New columns were also created to support the analysis, including:

* Age in Years
* Application Delay in Days
* Signup Time Period
* Signup Day of Week
* Engagement Level

## Exploratory Data Analysis

Exploratory data analysis was performed to understand student participation patterns across different categories, status groups, years, countries, institutions, ages and genders.

## EDA Images

### Opportunity Category Distribution

![<img width="989" height="490" alt="image" src="https://github.com/user-attachments/assets/cbd6ef6c-e5c9-4b8b-9a8e-c8466fc07f52" />
)

*Figure 1: Distribution of learners across the five opportunity categories.*

### Status Group Distribution

![Status group distribution](sandbox:/workspace/scratch/292c1f2d89ac/RIT_Student_Participation_Project/images/status-group-distribution.png)

*Figure 2: Distribution of learners by status group.*

### Signup Trend by Year

![Signup trend by year](sandbox:/workspace/scratch/292c1f2d89ac/RIT_Student_Participation_Project/images/signup-trend-by-year.png)

*Figure 3: Number of participants who signed up in 2023 and 2024.*

### Top Five Countries

![Top five countries](sandbox:/workspace/scratch/292c1f2d89ac/RIT_Student_Participation_Project/images/top-five-countries.png)

*Figure 4: The five countries with the highest numbers of participants.*

### Top Five Institutions

![Top five institutions](sandbox:/workspace/scratch/292c1f2d89ac/RIT_Student_Participation_Project/images/top-five-institutions.png)

*Figure 5: The five institutions with the highest numbers of participants.*

### Age Distribution

![Age distribution](sandbox:/workspace/scratch/292c1f2d89ac/RIT_Student_Participation_Project/images/age-distribution.png)

*Figure 6: Age distribution of participants in the dataset.*

### Gender Distribution

![Gender distribution](sandbox:/workspace/scratch/292c1f2d89ac/RIT_Student_Participation_Project/images/gender-distribution.png)

*Figure 7: Number of participants in each gender category.*

## Predictive Modelling

Three classification models were tested to predict whether a learner’s status would be:

* In Progress
* Successful
* Unsuccessful

The models were compared using:

* Accuracy
* Confusion matrix
* Precision
* Recall
* F1-score

Logistic Regression was selected as the most suitable model because it provided the best overall performance for this project.

## Main Findings

* Internships had the highest level of participation.
* Internships also had the highest number and percentage of unsuccessful outcomes.
* Courses showed a stronger combination of in-progress and successful participation.
* Participation was higher in 2023 than in 2024.
* The United States had the highest participation, followed by India.
* Saint Louis University had the highest number of participants among the institutions.
* Most participants were between approximately 20 and 30 years old.
* Male participants formed the largest gender group, followed by female participants.

## Stakeholder Value

The analysis can help stakeholders understand participation patterns and identify learners who may require early support. Model predictions should support the review process, while final decisions should be made by the responsible stakeholders.

## Project Files

* Google Colab notebook: **[Add your Google Colab link here]**
* Stakeholder report: `RIT_Student_Participation_Stakeholder_Report.pdf`
* Main cleaned dataset: `RIT_Cleaned_Dataset_Week2`
* Model-ready dataset: `RIT_Model_Ready_Dataset_Week3`

## Author

**Asif Hossain**
image links and the required `images` folder.
