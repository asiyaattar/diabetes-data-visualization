# diabetes-data-visualization

# READ.ME

## Project Description
This project provides data visualization and exploratory data analysis on a diabetes dataset using Python libraries Pandas, Seaborn, and Matplotlib. The dataset contains medical predictor variables and a binary outcome indicating the presence of diabetes.

The goal is to understand patterns and relationships within the dataset through various plots such as bar plots, box plots, violin plots, KDE plots, and swarm plots.

## Dataset
- The dataset is sourced from the kaggle :  
  `diabetes.csv`
- It includes features like Glucose, BMI, Age, Blood Pressure, and Outcome (0 = no diabetes, 1 = diabetes).

## Visualizations and Insights

### 1. Outcome Counts (Bar Plot)  
![Outcome Count](images/outcome<img width="741" height="695" alt="Screenshot 2025-09-16 175740" src="https://github.com/user-attachments/assets/3ddff88e-2b46-4555-94c5-b4cbedc910c4" />
_count.png)  
The dataset is imbalanced, with more non-diabetic cases (Outcome=0) than diabetic ones (Outcome=1).


### 2. Glucose Levels by Outcome (Box Plot)  
![Glucose Boxplot](images/glucose_boxplot.png)  
Diabetic individuals tend to have higher glucose levels compared to non-diabetic individuals.

### 3. BMI Distribution by Outcome (Violin Plot)  
![BMI Violin Plot](images/bmi_violin.png)  
A higher BMI is associated with a higher probability of diabetes.

### 4. Age Distribution by Outcome (KDE Plot)  
![Age KDE Plot](images/age_kde.png)  
Diabetic cases are more frequent among older individuals whereas non-diabetic cases peak at a younger age.

### 5. Blood Pressure by Outcome (Swarm Plot)  
![Blood Pressure Swarm](images/bp_swarm.png)  
Blood pressure distribution is similar across outcomes, but extreme values appear more in the diabetic group.

## How to Run the Project

1. Clone this repository.
2. Ensure you have Python installed (version 3.6+ recommended).
3. Install required libraries (if not already installed):
