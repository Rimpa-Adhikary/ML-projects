# Fake-News-Detection

## Overview
This project focuses on detecting **fake news** articles using supervised machine learning algorithms. It classifies news as **real or fake** by analyzing the textual content. The project is built using Python and various machine learning classification techniques.

## Algorithms Used
- **Logistic Regression**
- **Random Forest Classifier**
- **Decision Tree Classifier**

## Technologies & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- TfidfVectorizer

##  How it Works
1. Load and preprocess the dataset.
2. Convert the text data into numerical vectors using **TF-IDF Vectorization**.
3. Split the data into training and testing sets.
4. Train three ML models:
   - Logistic Regression
   - Random Forest
   - Decision Tree
5. Evaluate model performance using accuracy and classification report.

## Results
| Model               | Accuracy (%) |
|---------------------|--------------|
| Random Forest       | 98.69        |
| Decision Tree       | 99.67        |
