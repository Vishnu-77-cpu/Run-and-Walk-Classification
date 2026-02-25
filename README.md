# 🏃‍♂️🚶 Run & Walk Classification using Machine Learning

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/0cfc2727-1e7a-4787-8763-b9047508c824" />


## 📌 Project Overview
This project focuses on **classifying human activities as Walking or Running** using **Machine Learning techniques**.  
The model learns patterns from **sensor-based motion data** and predicts whether the activity performed is **Walk** or **Run**.

This is a **binary classification problem** with real-world applications in **fitness tracking, healthcare, and activity monitoring systems**.

---

## 🎯 Problem Statement
Manual activity tracking is inaccurate and inefficient.  
The objective of this project is to **automatically identify whether a person is walking or running based on sensor data** using machine learning models.

---

## 🧠 Solution Approach
1. Load and explore the dataset  
2. Clean and preprocess the data  
3. Perform feature scaling  
4. Split data into training and testing sets  
5. Train multiple ML classification models  
6. Evaluate and compare model performance  

---

## 📊 Dataset Information
- 📂 Type: Sensor / Accelerometer data  
- 📈 Features: Numerical motion-based values  
- 🎯 Target Variable:
  - `0` → Walk  
  - `1` → Run  

---

## ⚙️ Machine Learning Workflow

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/7060def3-7635-4265-936e-b44dde6b52fa" />


### 🔹 Steps Followed
- Data Loading
- Data Cleaning
- Feature Scaling
- Train-Test Split
- Model Training
- Model Evaluation

---

## 🤖 Models Used
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Random Forest Classifier  

The best-performing model was selected based on **accuracy and evaluation metrics**.

---

## 📈 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

---

## 🛠️ Technologies & Tools
| Category | Tools |
|--------|-------|
| Programming Language | Python 🐍 |
| Libraries | NumPy, Pandas |
| Machine Learning | Scikit-learn |
| Visualization | Matplotlib, Seaborn |
| IDE | Jupyter Notebook |

---

## 📸 Sample Visualizations

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/b34c4a8f-7d2c-4924-ab58-580ddcc2c176" />


- Feature distribution plots  
- Confusion matrix  
- Model accuracy comparison  

---

## 🚀 How to Run This Project

```bash
# Clone the repository
git clone https://github.com/your-username/run-walk-classification.git

# Navigate to the project directory
cd run-walk-classification

# Install required libraries
pip install -r requirements.txt

# Open Jupyter Notebook
jupyter notebook
