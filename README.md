# Social Media Impact on Student Life - Exploratory Data Analysis

## Project Overview
This project performs an Exploratory Data Analysis (EDA) on a dataset evaluating the impact of social media on student life[cite: 1]. The analysis involves data loading, inspection, cleaning, and preliminary data visualization to understand the relationships between social media usage, academic performance, and mental health metrics[cite: 1].

## Dataset Description
The dataset `Social_media_impact_on_life.csv` contains 4,500 entries and 16 distinct features[cite: 1]. 

Key columns analyzed include:
* **Demographics**: `Student_ID`, `Age`, `Gender`, `Academic_Level`[cite: 1].
* **Usage Metrics**: `Primary_Platform`, `Daily_Usage_Hours`, `Weekend_Extra_Hours`, `Device_Type`, `Late_Night_Usage`, `Social_Comparison_Frequency`[cite: 1].
* **Wellbeing & Performance**: `Sleep_Duration_Hours`, `Sleep_Quality_Score`, `Perceived_Stress_Score`, `Mental_Health_Index`, `Academic_Performance_GPA`, `Overall_Impact`[cite: 1].

## Technologies Used
* **Python**[cite: 1]
* **Pandas**: For data manipulation and missing value imputation[cite: 1].
* **NumPy**: For numerical operations[cite: 1].
* **Matplotlib & Seaborn**: For creating static data visualizations[cite: 1].

## Data Cleaning & Preprocessing
To ensure data integrity, missing values were handled using the following strategies:
* Identified 85 missing values in the `Academic_Performance_GPA` column and filled them using the column's mean value[cite: 1].
* Identified 46 missing values in the `Perceived_Stress_Score` column and filled them using the column's median value[cite: 1].

## Visualizations
The analysis includes basic graphical representations to uncover trends:
* Scatter plots assessing the relationship between average daily usage and weekend extra hours[cite: 1].
* Line and box plots mapping the relationship between a student's age and their daily social media usage hours[cite: 1].
* Distribution checks across genders and ages using value counts[cite: 1].

## How to Run
1. Clone this repository.
2. Ensure you have the required libraries installed (`pip install pandas numpy matplotlib seaborn`).
3. Update the file path in the `pd.read_csv()` function to point to your local dataset location.
4. Run the Jupyter Notebook cell by cell to reproduce the analysis.
