# Task 1: Exploring and Visualizing the Iris Dataset

## Objective
Load, inspect, and visualize the Iris dataset to understand feature trends, distributions, and potential outliers.

## Dataset
- Iris dataset (loaded from CSV using pandas)
- Source used in notebook:
  - `https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv`

## Skills Practiced
- Data loading and inspection with `pandas`
- Descriptive statistics and exploratory analysis
- Data visualization with `matplotlib` and `seaborn`

## Notebook
- File: `task1.ipynb`
- Main steps performed:
  1. Import libraries (`pandas`, `seaborn`, `matplotlib`)
  2. Load dataset with `pd.read_csv(...)`
  3. Print shape, column names, and first 5 rows
  4. Use `.info()` and `.describe()` for summary statistics
  5. Create and save required visualizations

## Visualizations Generated
- Scatter plot: `iris_scatter.png`
  - `petal_length` vs `petal_width`, colored by species
- Histograms: `iris_histograms.png`
  - Distribution of all numeric features
- Box plots: `iris_boxplots.png`
  - Outlier and spread comparison across species

## How To Run
1. Open `task1.ipynb` in VS Code.
2. Select a Python kernel.
3. Run Cell 1.

## Expected Output
- Printed dataset inspection details in notebook output
- Three saved image files in the workspace root:
  - `iris_scatter.png`
  - `iris_histograms.png`
  - `iris_boxplots.png`

## Status
Task 1 is completed and verified successfully.
