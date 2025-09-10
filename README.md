# 🟢 Semiconductor Wafer Defect Classification

This project explores how **machine learning** can be applied to classify defect patterns on semiconductor wafers using real wafer map image data.  
The aim is to improve defect detection accuracy and reduce manual inspection in semiconductor manufacturing.  

---

## 📑 Table of Contents
- [Objective](#-objective)
- [Dataset](#-dataset)
- [Workflow](#-workflow)
- [Technologies](#-technologies)
- [Repository Structure](#-repository-structure)
- [Installation & Usage](#-installation--usage)
- [Results](#-results)
- [Acknowledgments](#-acknowledgments)

---

## 📌 Objective
Automatically recognize defect types in wafer maps using three supervised learning models:

- Support Vector Machine (SVM)  
- Logistic Regression (LR)  
- Random Forest Classifier (RF)  

Each model is trained to classify different wafer defect types, enabling **early detection** and **process optimization**.  

---

## 📊 Dataset
- **Source:** [WM-811K Dataset (Kaggle)](https://www.kaggle.com/qingyi/wm811k-wafer-map)  
- **Provider:** Multimedia Information Retrieval Lab ([mirlab.org](http://mirlab.org))  
- **Description:** Contains wafer map images with labeled defect categories.  

---

## ⚙️ Workflow

1. **Data Loading**  
   - Load wafer map images from `.npy` files.  

2. **Preprocessing**  
   - Remove null/undetermined categories.  
   - Reshape wafer maps into uniform inputs for classifiers.  

3. **Model Training**  
   - Train SVM, Logistic Regression, and Random Forest.  
   - Split data into training and testing sets.  

4. **Evaluation**  
   - Accuracy, confusion matrices, and classification reports.  
   - Visualization of model performance.  

---

## 🧪 Technologies

- Python 3.x  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Seaborn  
- Jupyter Notebook  

---

## 📁 Repository Structure

