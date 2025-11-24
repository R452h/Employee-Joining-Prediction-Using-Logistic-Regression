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

### 🧑‍💻 Author

**Sushant Raj**
📍 Data Analytics & Machine Learning Enthusiast

---



🙂
