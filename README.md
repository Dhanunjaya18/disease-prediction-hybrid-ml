# disease-prediction-hybrid-ml
"Hybrid ML project for predicting diseases using fuzzy logic and genetic algorithms."
# 🧠 Disease Prediction Using Hybrid Machine Learning Models

A smart health diagnostic system that predicts diseases like Diabetes using a **hybrid AI approach** combining Machine Learning with Fuzzy Logic and Genetic Algorithms.

## 🚀 Project Highlights
- Predicts disease risk using real medical data
- Hybrid model using:
  - Classical ML (Logistic Regression, Random Forest)
  - Fuzzy Logic for interpretability
  - Genetic Algorithm for rule optimization
- Interactive web app built with Streamlit
- Deployed online for real-time use

---

## 📊 Technologies & Tools
- Python
- Scikit-learn
- Pandas, NumPy
- DEAP / geneticalgorithm
- scikit-fuzzy
- Streamlit
- Matplotlib/Seaborn

---

## 📁 Dataset
- **Diabetes Dataset**  
  [🔗 Kaggle Link](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)

Attributes include:
- Glucose, BMI, Insulin, Age, Pregnancies, BloodPressure, etc.

---

## 🔍 How It Works

### Step 1: Preprocessing
- Cleaning, normalizing, and splitting the data

### Step 2: Base ML Models
- Logistic Regression, Decision Tree, Random Forest

### Step 3: Hybrid Intelligence
- Fuzzy logic layer classifies user inputs (Low/Medium/High)
- Genetic algorithm tunes fuzzy rules and thresholds

### Step 4: Web App
- User inputs health data
- Model predicts risk level and provides explanation
- Generates report with visual risk chart

---

## 🌐 Live Demo
> [Will update after deployment]

---

## 🧪 Run Locally
```bash
git clone https://github.com/yourusername/disease-prediction-hybrid-ml.git
cd disease-prediction-hybrid-ml
pip install -r requirements.txt
streamlit run app.py
