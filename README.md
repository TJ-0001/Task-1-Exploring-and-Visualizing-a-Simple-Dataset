# Task — Iris Dataset Exploration & Visualization

## Objective
The objective of this task is to load the Iris dataset and perform basic data exploration and visualization to understand the distribution of features and differences between Iris species.

## Dataset Used

* Dataset: Iris.csv
* Features included:
  * SepalLengthCm
  * SepalWidthCm
  * PetalLengthCm
  * PetalWidthCm
  * Species

## Steps Performed in Code
### 1. Dataset Loading
* Loaded the dataset using `pandas.read_csv()`.
* Displayed the first few rows using `df.head()`.
* Printed:
  * Dataset shape
  * Column names
* Checked dataset information using `df.info()`.
* Displayed basic statistical summary using `df.describe()`.

## Data Visualization
The following visualizations were created using Matplotlib and Seaborn:
### 1. Scatter Plot
* Plotted SepalLengthCm vs SepalWidthCm and PetalLengthCm vs PetalWidthCm.
* Colored by Species using Seaborn’s `scatterplot`.
* Purpose: Visualize the relationship between sepal length/width across species.

### 2. Histograms
* Created histograms for all numerical features using `df.hist()`.
* Purpose: Understand the distribution of each feature.

### 3. Box Plot
* Boxplot created for:
  `SepalLengthCm`, `SepalWidthCm`, `PetalLengthCm`, `PetalWidthCm`
* Purpose: Detect outliers and compare feature distributions.

##  Key Findings

* The dataset loads correctly with no missing values (as shown in `df.info()`).
* Scatter plot shows clear separation of species based on sepal measurements.
* Histograms reveal the spread and distribution of each feature.
* Boxplots show slight variations and potential outliers in sepal width.

## Files Included
- **Iris_Analysis_Notebook.ipynb** — Jupyter Notebook containing all code, visualizations, and outputs.
- **Iris.csv** — Dataset used for analysis and visual exploration.

