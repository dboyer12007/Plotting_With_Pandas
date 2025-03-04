# Module_5: Data Analysis of Pymaceuticals Animal Study

## Background
You’ve joined **Pymaceuticals, Inc.**, a pharmaceutical company specializing in anti-cancer treatments. Pymaceuticals is currently screening treatments for **squamous cell carcinoma (SCC)**, a common skin cancer. 

As a senior data analyst, you are provided with the dataset from the company's recent animal study. In this study, 249 mice with SCC tumors were treated with a variety of drug regimens over a 45-day period, with tumor growth observed at various time points. The goal of this study was to compare the performance of Pymaceuticals' drug of interest, **Capomulin**, against other treatments.

The executive team has tasked you with generating various statistical analyses, visualizations, and figures to summarize the findings of the study.

---

## Instructions
This assignment is broken down into the following tasks:

### 1. **Prepare the Data**
- Import the provided data files and merge the `mouse_metadata` and `study_results` DataFrames into a single DataFrame.
- Remove duplicate mouse IDs that have multiple time points.
- Clean the data for further analysis.

### 2. **Generate Summary Statistics**
- Create a DataFrame that summarizes the following statistics for each drug regimen:
  - Mean
  - Median
  - Variance
  - Standard deviation
  - SEM (Standard Error of the Mean)

### 3. **Create Bar Charts and Pie Charts**
- Generate bar charts that show the total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study using both Pandas and Matplotlib.
- Generate pie charts showing the distribution of female versus male mice in the study.

### 4. **Calculate Quartiles, Find Outliers, and Create a Box Plot**
- Calculate the final tumor volume for each mouse treated with the following drugs: **Capomulin**, **Ramicane**, **Infubinol**, and **Ceftamin**.
- Calculate the quartiles and IQR to determine potential outliers in each treatment group.
- Create a box plot to visually represent the distribution of final tumor volumes and highlight any outliers.

### 5. **Create a Line Plot and a Scatter Plot**
- Generate a line plot for a single mouse treated with Capomulin, showing tumor volume vs. time points.
- Create a scatter plot comparing mouse weight vs. average tumor volume for all mice treated with Capomulin.

### 6. **Calculate Correlation and Regression**
- Calculate the correlation coefficient and linear regression between mouse weight and average tumor volume for the Capomulin regimen.
- Plot the linear regression model on top of the scatter plot.

---

## File Structure
- **`mouse_metadata.csv`**: Metadata for the mice used in the study.
- **`study_results.csv`**: Results from the study showing tumor volume at various time points for each mouse.
- **`SQL/`**: Folder containing SQL scripts, if necessary.
- **`Analysis/`**: Folder where results and visualizations are saved.

---

## Requirements
- **Python** (with libraries such as Pandas, NumPy, Matplotlib)
- **Jupyter Notebook** (for analysis and visualizations)
- **SQL** (if applicable for data retrieval)

---

## Analysis & Visualization
This project focuses on generating statistical summaries and visualizations to analyze the drug treatment data for the mice. We use **Pandas** for data manipulation, **Matplotlib** for generating graphs, and **SciPy** for statistical analysis to draw insights regarding tumor growth and treatment effectiveness.

