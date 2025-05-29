# Advanced Prediction of Student Performance Using Machine Learning

This project aims to predict the academic performance of university students using various machine learning techniques. By analyzing student-related data such as demographics, attendance, academic history, and socio-economic factors, the model can help identify students at risk and support personalized learning strategies.

## 🔍 Objective

To develop a machine learning model that can accurately predict a student’s academic performance based on multiple input features. The goal is to help educators and institutions improve academic outcomes through data-driven insights.

----

## 🧠 Techniques Used

* Data Preprocessing and Feature Engineering
* Machine Learning Algorithms:

  * Linear Regression
  * Decision Trees
  * Random Forest
  * Support Vector Machine (SVM)
  * K-Nearest Neighbors (KNN)
* Model Evaluation: Accuracy, Precision, Recall, F1-Score
* Data Visualization for Insights and Interpretation

------

## 📁 Project Structure

```
student-performance-prediction/
│
├── data/                     # Raw and processed data files
├── notebooks/                # Jupyter notebooks for EDA and model training
├── models/                   # Trained machine learning models
├── src/                      # Source code for preprocessing and training
│   ├── preprocess.py
│   └── train_model.py
├── results/                  # Output results, graphs, and reports
└── README.md                 # Project overview and guide
```

## 🛠️ Requirements

* Python
* Django 
* Windows 8 
* SQlite
* Pentium IV or higher 
* HTML,CSS,javascript

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/Shashimpally/student-performance-prediction-ml.git
cd student-performance-prediction-ml
```

2. Run the preprocessing script:

```bash
python src/preprocess.py
```

3. Train the model:

```bash
python src/train_model.py
```

4. View results and analysis in the `results/` folder or open the notebooks for visual exploration.

## 📊 Dataset

The dataset includes information such as:

* Gender, Age
* Attendance and Study Hours
* Previous Grades and Exam Scores
* Family Background and Financial Status
* Participation in Extracurricular Activities

> **Note:** Dataset is either collected manually or sourced from publicly available educational datasets.

## 📈 Outcome

* Predictive accuracy of student performance
* Early identification of at-risk students
* Insightful reports to support decision-making for educators
