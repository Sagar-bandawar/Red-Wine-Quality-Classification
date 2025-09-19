🍷 Wine Quality Exploratory Data Analysis

This repository contains a starter Kaggle kernel for performing Exploratory Data Analysis (EDA) on the Wine Quality (Red Wine) dataset. The notebook demonstrates how to read, explore, and visualize the dataset using Python, Pandas, Matplotlib, and Scikit-learn.

📂 Dataset

The dataset used: winequality-red.csv

It contains 1599 rows and 12 columns describing various physicochemical properties of red wine, along with a quality score (0–10).

Columns:

fixed acidity

volatile acidity

citric acid

residual sugar

chlorides

free sulfur dioxide

total sulfur dioxide

density

pH

sulphates

alcohol

quality (target variable)

⚙️ Workflow

Import libraries

Pandas for data handling

Matplotlib for visualization

NumPy for numerical operations

Scikit-learn for preprocessing

Read the dataset

df = pd.read_csv('/kaggle/input/winequality-red.csv')


Data exploration

Preview data using df.head()

Check dataset shape (#rows & #columns)

Visualization

Histograms for feature distributions

Correlation matrix to check feature relationships

Scatter and density plots for pairwise relationships

📊 Example Outputs

Distribution Graphs – Histograms of sampled features

Correlation Matrix – Heatmap showing correlations between variables

Scatter Matrix – Scatter plots with density plots for numerical features

🚀 How to Use

Open the notebook in Kaggle.

Click "Edit Notebook" or "Fork Notebook" to start experimenting.

Modify or extend the analysis as needed:

Perform feature engineering

Apply machine learning models

Evaluate classification performance

✅ Conclusion

This kernel provides a basic exploratory analysis of the Wine Quality dataset.
From here, you can:

Extend the EDA

Train ML models (e.g., Logistic Regression, Random Forest, XGBoost)

Optimize hyperparameters and evaluate model performance
