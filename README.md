# Principal-Component-Analysis-PCA-
## Wine Classification using PCA and Logistic Regression
## 📌 Project Overview
This notebook addresses the business problem of classifying wines into different categories or types based on their chemical and physical characteristics. By applying Principal Component Analysis (PCA) for dimensionality reduction and then a Logistic Regression model to predict the wine categories, a system can be developed to automatically identify and categorize wines. This could be valuable for wine producers for quality control, for distributors to verify product authenticity, or for retailers to ensure accurate product placement, ultimately streamlining operations and ensuring product consistency.

## 📊 Dataset
The dataset used is the Wine Dataset, which contains the results of a chemical analysis of wines grown in a specific region in Italy. It includes 13 different chemical constituents (features) for 3 types of wine cultivars.

## ⚙️ Methodology
Data Preprocessing: Loading data and splitting it into training (80%) and testing (20%) sets.
Feature Scaling: Standardizing features using StandardScaler to ensure PCA and Logistic Regression perform optimally.
Dimensionality Reduction: Implementing PCA to reduce the feature space from 13 dimensions to 2 Principal Components. This allows for noise reduction and 2D visualization.
Classification: Training a Logistic Regression model on the principal components.
Visualization: Generating decision boundary plots to visualize how the model separates the three classes in a 2D space.

## 🏆 Results
<img width="565" height="455" alt="image" src="https://github.com/user-attachments/assets/79aef4b6-e6ea-45e2-805a-d3007f6d5f0b" />
<img width="565" height="455" alt="image" src="https://github.com/user-attachments/assets/72388eb1-7280-4696-9704-c2021d4c3e75" />

Accuracy: 

The model achieved an impressive 97.22% accuracy on the test set.

Key Insight: 

Even with a significant reduction in features (from 13 to 2), the model maintained high predictive power, proving the effectiveness of PCA in capturing the dataset's variance.

## 🛠️ Tech Stack
Language: Python

Libraries: Scikit-Learn, Pandas, NumPy, Matplotlib

Environment: Google Colab / Jupyter Notebook
