# COVID-19 Severity Prediction Using Machine Learning

This project explores machine learning (ML) techniques for early detection of COVID-19 using clinical symptoms and basic laboratory data. With testing delays, limited resources, and high infection risk in traditional testing methods, this research aims to develop a fast, accurate, and remote diagnostic tool powered by ML models. The approach uses symptom-based data to classify COVID-19 cases without requiring direct hospital visits, thus reducing exposure risks and supporting rapid diagnosis.

# Project Objectives

- Reduce the time required to test for COVID-19.
- Enable early diagnosis based on symptoms to accelerate patient care.
- Provide a machine learning-based tool that can assist in identifying potential COVID-19 cases remotely.
- Support overwhelmed healthcare systems by reducing reliance on manual testing.


##  Background & Motivation

COVID-19 has caused a massive global health crisis, affecting millions and overwhelming medical infrastructure. Traditional testing methods like RT-PCR, though accurate, are resource-intensive, time-consuming, and not always accessible.

Machine learning, already proven effective in fields like healthcare, finance, and education, can help identify COVID-19 cases by learning patterns from symptoms and lab results. This study leverages ML to create a predictive model that uses easily accessible data for faster, safer screening.


##  Methodology

###  Data Collection
- Symptom and severity-related data collected from publicly available sources such as Kaggle, IEEE Xplore, and Google Scholar.
- Included data based on clinical symptoms, simple lab test results, and COVID-19 outcomes.

###  Data Splitting
- **80%** of the dataset used for training
- **20%** used for testing

###  Machine Learning Models Used

| Algorithm      | Description                           | Key Features                                                                 |
|---------------|---------------------------------------|------------------------------------------------------------------------------|
| Decision Tree | Structured tree-based classifier      | Easy interpretation, good with categorical data                             |
| Naïve Bayes   | Probabilistic classifier              | Fast, stable performance, but struggles with missing data                   |
| Random Forest | Ensemble of decision trees            | Good with high-dimensional and imbalanced datasets, handles missing values  |
| Neural Network| Deep learning model                   | High accuracy, but complex and harder to interpret                           |

---

##  Literature Review Highlights

- **Zoabi et al.** used LightGBM and SHAP values to interpret symptom-based COVID-19 predictions.
- **Quer et al.** combined wearable sensor data and self-reported symptoms to improve COVID-19 detection.
- **Cabitza et al.** applied multiple classifiers (RF, NB, LR, SVM, KNN) using blood test data, with hyperparameter tuning and cross-validation to ensure robust performance.

These studies demonstrate that ML can successfully classify COVID-19 cases, particularly when RT-PCR or CT imaging is not viable.

---

##  Installation & Usage

### Prerequisites
- Python 3.8+
- Required packages listed in `requirements.txt`:
  - scikit-learn
  - pandas
  - numpy
  - matplotlib
  - seaborn


