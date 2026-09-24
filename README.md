# ❤️ Heart Disease Detection Using Machine Learning

A machine learning-based heart disease detection system built with Python and Flask. The system analyzes patient health data and uses machine learning models to predict the possibility of heart disease.

---

## ✨ Features

* **Heart Disease Detection** — Enter patient health information and receive a heart disease prediction
* **Multiple Machine Learning Models** — Uses Decision Tree, KNN, Random Forest, and SVM for classification
* **Data Preprocessing** — Prepares and scales patient data before model prediction
* **Model Comparison** — Compares different machine learning algorithms based on their prediction performance
* **Web-Based Interface** — Simple interface for entering patient information and viewing predictions
* **Prediction Results** — Displays the predicted heart disease result through the application
* **Patient Data Management** — Allows users to enter and manage patient information

---

## 🛠️ Tech Stack

| **Layer**        | **Technology**                         |
| ---------------- | -------------------------------------- |
| Backend          | Python, Flask                          |
| Machine Learning | Scikit-learn                           |
| Models           | Decision Tree, KNN, Random Forest, SVM |
| Data Processing  | Pandas, NumPy, Feature Scaling         |
| Frontend         | HTML, CSS                              |
| Database         | MySQL                                  |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/heart-disease-detection.git
cd heart-disease-detection
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

Or install the main dependencies manually:

```bash
pip install flask pandas numpy scikit-learn mysql-connector-python
```

### 3. Configure the database

Configure the MySQL database connection in the Flask application using your database credentials.

### 4. Add the dataset

Place the heart disease dataset in the required project directory.

### 5. Run the app

```bash
python app.py
```

### 6. Open in browser

```text
http://127.0.0.1:5000
```

---

## 🧠 How It Works

1. **Enter Patient Data** — Enter relevant patient health information through the web application
2. **Data Preprocessing** — The input data is cleaned and scaled before prediction
3. **Model Prediction** — Machine learning models analyze the patient data
4. **Classification** — The models classify whether the patient is likely to have heart disease
5. **Display Prediction** — The prediction result is displayed through the web application

---

## 🔬 Models Used

| **Model**                        | **Purpose**                                               |
| -------------------------------- | --------------------------------------------------------- |
| **Decision Tree**                | Uses decision-based rules to classify heart disease cases |
| **K-Nearest Neighbors (KNN)**    | Classifies patients based on similar data points          |
| **Random Forest**                | Uses multiple decision trees to improve classification    |
| **Support Vector Machine (SVM)** | Finds a decision boundary between different classes       |

---

## 📊 Model Development

The heart disease dataset is divided into training and testing sets.

```text
Dataset
   │
   ├── Training Data
   │       ↓
   │   Data Preprocessing
   │       ↓
   │   Model Training
   │       ↓
   │   Trained Models
   │
   └── Testing Data
           ↓
      Model Evaluation
```

Different machine learning models are trained and evaluated to compare their classification performance.

---

## 📈 Model Evaluation

The models can be evaluated using classification metrics such as:

* **Accuracy**
* **Confusion Matrix**
* **ROC-AUC**
* **Precision**
* **Recall**

These metrics help evaluate how effectively the models classify heart disease cases.

---

## 📸 Usage

1. **Login/Register** — Create an account or log in to the application
2. **Enter Patient Data** — Enter the required health information
3. **Run Prediction** — Submit the patient information for analysis
4. **View Result** — View the predicted heart disease result
5. **View Data** — Manage and review submitted patient information

---

> **Note:** This project is intended for educational and research purposes and is not a substitute for professional medical diagnosis.
