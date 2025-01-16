# Parkinson's Disease Detection Using Machine Learning  

## Description  
This project is designed to detect Parkinson's Disease using machine learning techniques. It utilizes a dataset containing biomedical voice measurements to classify individuals as having Parkinson's Disease or not. The primary goal is to build a model with high accuracy to assist in the early detection of Parkinson's Disease, which is critical for effective treatment and management.  

### Key Features:  
- Dataset includes 24 features related to vocal attributes.  
- Evaluated multiple models: Logistic Regression, Support Vector Classifier (SVC), and Random Forest Classifier.  
- Optimized the Random Forest Classifier using GridSearchCV for hyperparameter tuning.  
- Achieved a maximum accuracy of **93.88%** with the Random Forest Classifier.  

**Dataset Reference:** [Parkinson's Disease Dataset](https://archive.ics.uci.edu/ml/datasets/parkinsons)  

---

## Badges  
![Python](https://img.shields.io/badge/python-v3.8%2B-blue)  
![License](https://img.shields.io/badge/license-MIT-green)  
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)  
![Issues](https://img.shields.io/github/issues/your-username/parkinsons-detection)  

---

## Visuals  
### Correlation Heatmap of Features:  
![Heatmap](https://via.placeholder.com/800x400.png?text=Feature+Correlation+Heatmap)  

### Model Accuracy Comparison:  
| Model                           | Accuracy|  
|---------------------------------|---------|  
| Logistic Regression             | 87.76%  |  
| Support Vector Classifier (SVC) | 83.67%  |  
| Random Forest Classifier (Best) | 93.88%  |  

---

## Installation  
Follow these steps to set up and run the project locally:  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/parkinsons-detection.git  
   cd parkinsons-detection  
