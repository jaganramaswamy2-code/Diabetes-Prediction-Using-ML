# Diabetes Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting whether a patient is diabetic based on various medical attributes using Machine Learning algorithms. The dataset used is the **Pima Indians Diabetes Dataset**, and the project includes data preprocessing, exploratory data analysis (EDA), model training, and performance evaluation.

The implementation is done in **Python** using **Jupyter Notebook**.

---

## 📂 Project Structure

```
Diabetes-Prediction/
│
├── Diabetes_Prediction.ipynb    # Main notebook
├── diabetes.csv                 # Dataset
└── README.md                    # Project documentation
```

---

## 📊 Dataset

The dataset contains medical records of female patients and includes the following features:

| Feature | Description |
|---------|-------------|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Triceps skin fold thickness |
| Insulin | 2-Hour serum insulin |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Age of patient |
| Outcome | Target Variable (0 = Non-Diabetic, 1 = Diabetic) |

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📈 Project Workflow

### 1. Data Loading
- Load the dataset using Pandas.
- Display dataset information and statistics.

### 2. Data Preprocessing
- Check for missing values.
- Replace invalid zero values in medical features with suitable mean/median values.
- Separate input and target variables.

### 3. Exploratory Data Analysis (EDA)
- Correlation Heatmap
- KDE Plots
- Violin Plots
- Distribution Analysis

### 4. Data Splitting
- Train-Test Split
- Training Set: 67%
- Testing Set: 33%

### 5. Model Building

The following machine learning models were implemented:

- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Multi-Layer Perceptron (Neural Network)

### 6. Feature Scaling

Standardization was performed using:

- StandardScaler

The neural network model was trained both before and after feature scaling for comparison.

### 7. Model Evaluation

Models were evaluated using:

- Training Accuracy
- Testing Accuracy

The KNN model was also tested with different values of **K (1–10)** to determine the optimal number of neighbors.

---

## 📉 Visualizations

The notebook includes:

- Correlation Heatmap
- KDE Plots
- Violin Plots
- KNN Accuracy vs Number of Neighbors Graph

These visualizations help understand feature relationships and model behavior.

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Diabetes-Prediction.git
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook
```

3. Launch Jupyter Notebook

```bash
jupyter notebook
```

4. Open

```
Diabetes_Prediction.ipynb
```

5. Run all cells sequentially.

---

## 📌 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost
- Model deployment using Flask or Streamlit
- Web interface for diabetes prediction

---

## 🎯 Learning Outcomes

Through this project, the following concepts were implemented:

- Data Cleaning
- Data Visualization
- Feature Engineering
- Machine Learning Classification
- Model Evaluation
- Data Standardization
- Exploratory Data Analysis

---

## 👨‍💻 Author

**Jagan Rama Swamy**

B.Tech Mechanical Engineering  
Indian Institute of Technology Kharagpur (IIT KGP)

---

## 📜 License

This project is developed for educational and learning purposes.
