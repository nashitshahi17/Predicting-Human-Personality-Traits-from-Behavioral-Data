# 🧠 Predicting Human Personality Traits from Behavioral Data

An interactive, AI-powered personality profiling project built using Python, Scikit-learn, and Power BI — leveraging classification models to predict human personality types (Introvert, Ambivert, Extrovert) from behavioral and survey-style data. Designed with clarity and cognitive insight, the project brings psychology and data science together under a unified analytical flow.

---

## 🧩 1. Project Workflow Overview

This project follows a modular, interpretable ML workflow:

- **Python (Pandas, Scikit-learn)**: Data cleaning, encoding, preprocessing, classification modeling, and export preparation.
- **Power BI**: Built an interactive visual dashboard for personality insights and trait-level analysis.

---

## 🧹 2. Data Cleaning & Preparation (Python)

### ✅ Dataset Used:
- `personality_synthetic_dataset.csv` – a synthetic dataset simulating behavioral survey data for 20,000 individuals.

### 🔧 Cleaning Steps:
- Verified data quality: No missing values or duplicates.
- Scaled features using `StandardScaler` for ML modeling.
- Label-encoded target variable `personality_type` into numerical form.
- Split the dataset into:
  - Features (X): 29 behavioral and psychological indicators
  - Target (y): Encoded personality type (0 = Introvert, 1 = Ambivert, 2 = Extrovert)
- 80/20 train-test split for model validation

---

## 🤖 3. Model Building & Evaluation (Python - Scikit-learn)

### 🔷 Models Used:
- Logistic Regression  
- Random Forest Classifier  
- Support Vector Machine (SVM)

### 🎯 Objective:
Predict one of three personality types using numerical indicators.

### 📈 Performance:
- All three models achieved **~100% accuracy** on test data due to the clean, synthetic structure.
- Evaluated using precision, recall, F1-score, and confusion matrix.

---

## 📊 4. Power BI Dashboard

### 🎨 Theme:
Clean dark-mode layout with contrasting color visuals, designed for high readability and visual clarity.

### 🔷 Dashboard Elements Included:

✅ **KPI Cards**
- Total Individuals
- Personality Breakdown (Introverts, Ambiverts, Extroverts)
- Average Trait Scores 

✅ **Visuals Created**

| Visual Type           | Description                                         |
|------------------------|-----------------------------------------------------|
| 📊 Bar Chart           | Distribution of Personality Types (Introvert, etc.) |
| 📶 Stacked Column Chart| Average trait values per personality group          |
| 🍩 Doughnut Chart      | Sum of leadership by personality type               |
| 🌲 TreeMap             | Sum of Social Energy by personality type            |
| 📆 Slicers             | Personality Type Filter, Trait Range Selector       |

✅ **Advanced Features**
- Interactive trait comparison using slicers and filters
- Prediction comparison (if predicted personality labels were added)

---

## 📦 5. Data Export & Integration

- Used `to_csv()` in Python to export cleaned + labeled data for Power BI
- Enabled smooth interaction between ML outputs and dashboard insights

---

## 🧠 6. Machine Learning Outcome

### 🎯 Goal:
Predict psychological orientation (Introvert, Ambivert, Extrovert) using quantifiable behavior data.

### 💡 Interpretation:
- Decision boundaries and confusion matrix indicated clear separability
- Model outputs integrated into Power BI to analyze predicted vs actual types

---

## 📁 7. Dataset Details

**Source**: Synthetic personality behavior dataset

**Features Included**:
- Behavioral traits (e.g., `talkativeness`, `risk_taking`, `party_liking`)
- Cognitive and psychological markers (e.g., `creativity`, `discipline`, `empathy`)
- Survey-style preferences (e.g., `routine_preference`, `reading_habit`, `travel_desire`)

**Target**:
- `personality_type`: Introvert, Ambivert, Extrovert

---

## 📌 8. Final Thoughts & Future Scope

✅ Clean integration of machine learning and business intelligence  
✅ Psychology-informed features paired with ML for explainability  
✅ Correlation insights reveal hidden trait interactions  

### 🔮 Next Steps:
- Apply deep learning (e.g., MLPClassifier or ANN)
- Extend project to real-world datasets or conduct a survey for primary data
- Deploy interactive web-based quiz for real-time personality prediction
- Integrate with HR or EdTech platforms for use in profiling and personalization

---

## 🙌 Built With:
- Python (Pandas, Scikit-learn, Seaborn, Matplotlib)  
- Power BI (Matrix, DAX, Unpivoting, Custom visuals)  
- Curiosity, creativity, and data-driven psychological exploration 🧠✨
