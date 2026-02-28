⛏️ Data Mining Techniques and Preprocessing
📖 Overview
This repository contains a collection of Jupyter Notebooks demonstrating fundamental data mining and data preprocessing techniques. It serves as a practical guide to preparing, cleaning, and transforming data for machine learning and analytical modeling.

📂 Repository Contents
Data Aggregation (Data_Aggregation.ipynb)

Demonstrates time aggregation by grouping data over different time periods, such as monthly, quarterly, and yearly.

Implements spatial aggregation by summarizing data across spatial attributes like region and city using pandas.

Handling Imbalanced Classes (Handle Imbalanced Classes.ipynb)

Shows how to handle datasets with uneven class distributions (e.g., an 80:20 split).

Implements over-sampling of minority classes and under-sampling of majority classes using the imblearn and sklearn.utils libraries.

Feature Selection (Feature Selection Data Mining.ipynb)

Explores Filter Methods, including Information Gain, Chi-square tests, Correlation Coefficients, Variance Thresholds, and Mean Absolute Difference (MAD).

Covers Wrapper Methods such as Forward Selection, Backward Elimination, and Recursive Feature Elimination (RFE).

Demonstrates Embedded Methods using Lasso Regularization and Tree-based methods (Random Forest).

Feature Transformation (Feature Transformation Techniques in Data Mining.ipynb)

Applies mathematical transformations to data using numpy and sklearn's FunctionTransformer.

Includes Logarithmic (log1p), Square, Reciprocal, Trigonometric (Sin, Cos, Tan), and Square Root transformations.

Principal Component Analysis (PCA) (PCA in Data Minining.ipynb)

Demonstrates dimensionality reduction using the Breast Cancer dataset.

Calculates the covariance matrix, eigenvalues, and eigenvectors manually before applying Scikit-Learn's PCA implementation to extract principal components.

Data Integration and Transformation (Data Integration and Data Transformation for Data Mining.ipynb)

Shows Tight Coupling (joining datasets on a common key) and Loose Coupling (concatenating datasets).

Implements data transformation techniques such as Smoothing (Moving Average), Aggregation, Discretization (Binning), Attribute Construction, and Generalization.

Covers Normalization techniques including Min-Max Normalization, Z-Score Normalization, and Decimal Scaling.

🛠️ Tools & Technologies Used
Language: Python 3

Core Libraries: pandas, numpy, matplotlib, seaborn

Machine Learning & Preprocessing: scikit-learn, imblearn (Imbalanced-learn), mlxtend
