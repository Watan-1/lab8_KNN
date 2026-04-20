# lab8_KNN

This Lab implements the **K-Nearest Neighbors (KNN)** algorithm to classify data points based on their features.The goal is to build a model that predicts the **TARGET CLASS** using distance-based learning.

---

## 📂 Dataset

* Dataset used: **KNN_Project_Data.csv**
* The dataset contains multiple numerical features and a target column:
  * **TARGET CLASS** (0 or 1)

---

## ⚙️ Steps Performed

### 1. Data Loading

* Loaded the dataset using pandas

### 2. Exploratory Data Analysis (EDA)

* Used seaborn pairplot to visualize relationships between features

### 3. Data Preprocessing

* Applied **StandardScaler** to normalize feature values
* This step is important because KNN depends on distance

### 4. Train-Test Split

* Split the data into:

  * 70% training
  * 30% testing

### 5. Model Training

* Trained KNN model using:

  * Initial value: **K = 1**

### 6. Evaluation

* Used:

  * Confusion Matrix
  * Classification Report (Precision, Recall, F1-score)

### 7. Choosing Optimal K

* Tested K values from 1 to 40
* Plotted **Error Rate vs K Value**
* Selected the best K based on lowest error

### 8. Final Model

* Retrained the model using the optimal K value
* Achieved improved performance




---
