Semiconductor Wafer Defect Classification
This project demonstrates how machine learning can be used to identify defect patterns on semiconductor wafers using real wafer map image data. The goal is to improve defect detection and reduce manual analysis effort in semiconductor manufacturing.

📌 Project Objective
To automatically recognize defect types in wafer maps using three supervised machine learning models:

Support Vector Machine (SVM)

Logistic Regression (LR)

Random Forest Classifier

Each model is trained to classify different types of defects on wafer dies, enabling early detection and process optimization.

📊 Dataset
The dataset used is WM-811K, available on Kaggle.
It contains wafer map images with labeled defect types.

Dataset source:
Multimedia Information Retrieval Lab: mirlab.org

⚙️ Key Steps
Data Loading
The dataset is loaded from .npy files.

Preprocessing

Wafer maps are extracted and filtered to remove null/undetermined categories.

Each wafer map is reshaped to uniform input for classification.

Model Training

Three models (SVM, Logistic Regression, Random Forest) are trained.

Accuracy and performance are compared for each model.

Data is split into training and test sets.

Evaluation

Confusion matrix and classification reports are used to assess model performance.

Visualization is provided for model comparison.

🧪 Technologies Used
Python

NumPy

Matplotlib

Scikit-learn

Seaborn

📁 Files
semiconductor-wafer-defect-classificatio (1).ipynb: Main Jupyter notebook containing code, analysis, and model training

Wafer image dataset from Kaggle

📈 Results
The three models are compared on classification performance. Results show which algorithm performs best on the wafer defect recognition task.

📬 Acknowledgments
Dataset provided by the Multimedia Information Retrieval Lab and hosted on Kaggle.
