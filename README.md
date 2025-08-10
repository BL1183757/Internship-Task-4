# Internship-Task-4

Breast Cancer Classification using Logistic Regression
Overview
This project demonstrates a complete machine learning workflow for breast cancer diagnosis prediction using the Logistic Regression algorithm.
The dataset is preprocessed, explored, and modeled to classify tumors as Malignant (M) or Benign (B) based on diagnostic features.

Dataset
Source: Breast Cancer Wisconsin Dataset (data.csv)

Target Column: diagnosis

M → Malignant (1)

B → Benign (0)

Shape: 569 rows × 33 columns

Features: Numerical measurements of cell nuclei (mean, standard error, and worst values for various parameters).

Tech Stack
Language: Python

Libraries:

pandas, numpy → Data handling

matplotlib, seaborn → Data visualization

scikit-learn → Preprocessing, model training, evaluation

Exploratory Data Analysis (EDA)
Checked for missing values.

Removed irrelevant column Unnamed: 32.

Analyzed feature distributions and correlations.

Visualized relationships using heatmaps and histograms.

Preprocessing
Label Encoding: Converted target variable (diagnosis) to binary (1 for Malignant, 0 for Benign).

Feature Scaling: Standardized numerical features using StandardScaler.

Data Split: 80% training, 20% testing.

Model
Algorithm: Logistic Regression

Pipeline:

Column transformation for scaling

Logistic Regression classifier

Evaluation Metrics
Accuracy Score

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

ROC-AUC Score

Results
Metric	Score
Accuracy	~96%
Precision (M)	~94%
Recall (M)	~94%
F1-Score (M)	~94%
ROC-AUC	~99%

Visualizations
Correlation heatmap for feature relationships.

ROC Curve for model performance.

Confusion matrix heatmap.

How to Run
1. Clone the repository:
  git clone https://github.com/BL1183757/Internship Task-4.git
  cd Internship Task-4
2.Install dependencies:
  pip install -r requirements.txt
3.Run the notebook:
  jupyter notebook "Internship Task-4.ipynb"

Future Improvements
Experiment with advanced models (Random Forest, XGBoost).

Hyperparameter tuning.

Feature selection for improved performance.
