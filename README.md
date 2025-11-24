## 📌 Employee Joining Prediction Using Logistic Regression

This project focuses on predicting whether a candidate will join a company after receiving an offer. Using machine learning—specifically **Logistic Regression**—the model analyzes HR and candidate-related features to estimate the likelihood of offer acceptance.

This type of prediction helps HR departments optimize hiring strategy, reduce offer drop-offs, and improve workforce planning.

---

### 📁 Dataset

The dataset contains candidate details related to experience, recruitment channel, offer status, and more.
Target Variable: **Status**

* `1` → Candidate Joined
* `0` → Candidate Did Not Join

---

### 🧼 Data Preprocessing

* Handled missing values using median imputation.
* Encoded categorical variables using `LabelEncoder`.
* Split dataset into **train-test** using `train_test_split`.

---

### 📊 Exploratory Data Analysis (EDA)

Several visualizations were generated to understand data patterns:

* Countplot of joining status
* Correlation heatmap
* Feature distribution plots
* Relationship analysis using scatter plots and boxplots

---

### 🤖 Machine Learning Model

Algorithm Used: **Logistic Regression**

Model Steps:

1. Define features (X) and target (y)
2. Train-test split
3. Train model using Logistic Regression
4. Evaluate using metrics:

   * Accuracy
   * Confusion Matrix
   * Classification Report (Precision, Recall, F1-score)

---

### 🧪 Model Evaluation

| Metric    | Result                  |
| --------- | ----------------------- |
| Accuracy  | ✔️ (Depends on dataset) |
| Precision | ✔️                      |
| Recall    | ✔️                      |
| F1 Score  | ✔️                      |

> A confusion matrix heatmap was plotted for better performance visualization.

---

### 📌 Feature Importance

Coefficient values extracted from the model show which variables influence joining decisions the most.

---

### 🛠️ Tech Stack

| Component            | Technology                       |
| -------------------- | -------------------------------- |
| Programming Language | Python                           |
| Data Processing      | Pandas, NumPy                    |
| Visualization        | Matplotlib, Seaborn              |
| ML Model             | Scikit-Learn Logistic Regression |

---

### 📂 Folder Structure

```
├── dataset.xlsx  
├── model.ipynb  
├── README.md
```

---

### 🚀 How to Run

1. Clone the repository:

```
git clone <repo-url>
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the notebook.

---

### 📌 Future Improvements

* Try other classification models (Random Forest, XGBoost, SVM)
* Hyperparameter tuning
* Deploy the model using Flask/Streamlit
* Add interactive dashboards

---
### 🧑‍💻 Screenshots
<img width="1920" height="1080" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/22b6943f-0ab3-4cf2-8a0f-0398ef18af8b" />

<img width="1920" height="1080" alt="Screenshot (43)" src="https://github.com/user-attachments/assets/bbfaa543-6cc4-4af2-9ab3-3e26452402be" />

<img width="1920" height="1080" alt="Screenshot (44)" src="https://github.com/user-attachments/assets/7c7edf15-474f-4369-8820-a69aaeafadd1" />

<img width="1920" height="1080" alt="Screenshot (45)" src="https://github.com/user-attachments/assets/29dfa447-92d1-4472-bc85-d59ab2acd39b" />

<img width="1920" height="1080" alt="Screenshot (46)" src="https://github.com/user-attachments/assets/f0d4377f-6ec7-4a85-81f5-7b1870c5fcdb" />

<img width="1920" height="1080" alt="Screenshot (47)" src="https://github.com/user-attachments/assets/4dec35b3-d9e0-47e6-9cf7-7c08f7d92400" />

<img width="1920" height="1080" alt="Screenshot (48)" src="https://github.com/user-attachments/assets/c67ae3d6-b867-4333-a45c-fdfcf6eece51" />

<img width="1920" height="1080" alt="Screenshot (49)" src="https://github.com/user-attachments/assets/02fcf52f-c58e-430e-9d72-a7210b646dcd" />

<img width="1920" height="1080" alt="Screenshot (50)" src="https://github.com/user-attachments/assets/de14cc28-475d-46a8-8f1a-770fe4f95f23" />

### 🧑‍💻 Author

**Sushant Raj**
📍 Data Analytics & Machine Learning Enthusiast

---




