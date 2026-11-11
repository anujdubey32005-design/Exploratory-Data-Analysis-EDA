Exploratory Data Analysis (EDA) – Titanic Dataset

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The main objective is to understand the dataset, identify patterns, find relationships between variables, and discover useful insights through statistical analysis and data visualization.

## Objective
- Understand the structure of the dataset.
- Identify missing values and duplicate records.
- Perform statistical analysis.
- Analyze survival patterns among passengers.
- Visualize data using different charts.
- Identify trends, relationships, and outliers.

## Tools and Technologies Used
- **Python** – Programming language
- **Jupyter Notebook** – Running and documenting analysis
- **Pandas** – Data cleaning and data analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical charts and visualizations

## Dataset
**Dataset Name:** Titanic Dataset

The dataset contains passenger information, including:
- Passenger ID
- Passenger Class
- Name
- Sex
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Ticket
- Fare
- Cabin
- Embarked Location
- Survival Status

## Project Files

| File Name | Description |
|---|---|
| `Task_5_Titanic_EDA.ipynb` | Main Jupyter Notebook containing the analysis |
| `titanic.csv` | Dataset used for analysis |
| `Task_5_EDA_Report.pdf` | PDF report containing findings and visualizations |
| `Titanic_EDA.py` | Python script version of the analysis |

## Analysis Performed

### 1. Data Understanding
- Displayed the first few rows using `head()`.
- Checked dataset information using `info()`.
- Generated statistical summaries using `describe()`.

### 2. Data Cleaning
- Checked missing values.
- Checked duplicate records.
- Handled missing Age values using the median.
- Handled missing Embarked values using the mode.

### 3. Data Visualization
Created different visualizations:
- Survival Count Plot
- Age Distribution Histogram
- Survival by Gender
- Fare Distribution Boxplot
- Age vs Fare Scatterplot
- Correlation Heatmap
- Pairplot

## Key Findings
- Approximately 38.4% of passengers survived.
- Female passengers had a higher survival rate than male passengers.
- First-class passengers had a higher survival rate than passengers in lower classes.
- The dataset contains missing values, especially in the Cabin and Age columns.
- Visualizations helped identify patterns and relationships between passenger features.

## How to Run the Project

1. Install Python on your computer.
2. Install the required libraries:

   ```bash
   py -m pip install notebook pandas matplotlib seaborn
   ```

3. Download or clone this repository.
4. Keep the notebook and CSV dataset in the same folder.
5. Open Command Prompt in the project folder.
6. Run:

   ```bash
   py -m notebook
   ```

7. Open `Task_5_Titanic_EDA.ipynb`.
8. Select **Kernel → Restart & Run All** to execute the notebook.

## Conclusion
This project helped in understanding how Explor
