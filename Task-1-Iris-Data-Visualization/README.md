# Task 1: Exploring and Visualizing the Iris Dataset

## Objective

The objective of this task is to learn how to load, inspect, analyze, and visualize a dataset using Python data science libraries. The Iris dataset was used to understand data distributions, relationships between features, and potential outliers.

---

## Dataset

Dataset Name: Iris Dataset

Source: Seaborn Built-in Dataset

The dataset contains measurements of iris flowers from three different species:

* Setosa
* Versicolor
* Virginica

### Features

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width
* Species

---

## Tools and Libraries Used

* Python
* Google Colab
* Pandas
* Matplotlib
* Seaborn

---

## Tasks Performed

### 1. Data Loading

The Iris dataset was loaded using Seaborn and stored in a Pandas DataFrame.

### 2. Data Inspection

The following methods were used:

* shape
* columns
* head()
* info()
* describe()

### 3. Data Cleaning

The dataset was checked for missing values using:

* isnull().sum()

No missing values were found.

### 4. Data Visualization

The following visualizations were created:

#### Scatter Plot

Used to analyze relationships between sepal length and petal length.

#### Histograms

Used to examine the distribution of numerical features.

#### Box Plots

Used to detect potential outliers.

#### Correlation Heatmap

Used to identify relationships between numerical variables.

#### Pair Plot

Used to visualize all feature relationships simultaneously.

---

## Results and Findings

* The dataset contains 150 observations and 5 columns.
* No missing values were present.
* Three flower species were identified.
* Petal measurements provided better separation of species than sepal measurements.
* Strong positive correlation was observed between petal length and petal width.
* Box plots highlighted potential outliers in some measurements.

---

## Conclusion

The Iris dataset was successfully explored and visualized using Pandas, Matplotlib, and Seaborn. Through exploratory data analysis, meaningful patterns and relationships between flower measurements were identified. This task provided hands-on experience in data loading, inspection, statistical analysis, and visualization techniques commonly used in machine learning workflows.
