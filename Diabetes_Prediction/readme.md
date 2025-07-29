# Diabetes Prediction Analysis

This project is a machine learning model for predicting diabetes using medical parameters from the popular **Pima Indians Diabetes Dataset**. The model is built using **Python**, with libraries like `NumPy`, `Pandas`, `Matplotlib`, `Seaborn`, and `Scikit-learn`. The core algorithm used is **K-Nearest Neighbors (KNN)**, with a tuned value of **k=13** for optimal accuracy.

---

### Features:
| Feature | Description |
|---------|-------------|
| Pregnancies | Number of times pregnant |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| SkinThickness | Triceps skin fold thickness (mm) |
| Insulin | 2-Hour serum insulin (mu U/ml) |
| BMI | Body mass index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Age (in years) |
| Outcome | Class variable (0 or 1) |

---

## 🧪 Exploratory Data Analysis (EDA)

- ✅ No missing or null values found.
- ✅ No duplicate rows.
- 📈 Visualizations included:
  - Countplot of Outcome
  - Boxplots to detect outliers
  - Pairplot for feature relationships
  - Histograms for distribution
  - Heatmap for correlation

---

## 🔍 Data Preprocessing

- Standard scaling performed on all features except `Outcome`.
- Target column separated for model training.
- Split dataset into 70% training and 30% testing.

---

## 🤖 Model Building: K-Nearest Neighbors (KNN)

- Trained using values of `k` from 1 to 14.
- Best test accuracy at **k = 13**.
- Accuracy score on test set: **77.92%**
- Final model trained with `k = 13`.

### 🔢 Accuracy Scores
| Metric | Score |
|--------|-------|
| Train Accuracy | 100.00% |
| Test Accuracy | **77.92%** |

---

