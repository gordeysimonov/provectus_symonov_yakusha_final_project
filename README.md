# Vodafone Music Binary Classification

## Business Problem
Predict probability that a customer will install and pay for Vodafone Music subscription.

## Target
1 – user installed and paid
0 – user did not install

## Business Usage
- Targeted marketing
- Budget optimization
- Increase ARPU

## Critical Errors
More critical: False Negative (missed potential subscriber)

## Metric
ROC-AUC

## Sprint 1 Status
✔ Business understanding  
✔ Initial EDA  
✔ Data cleaning baseline  

## Sprint 2 Status
✔ Feature Engineering & Scaling  
✔ Train baseline models (Logistic Regression, Random Forest, XGBoost)  
✔ Cross-validation & ROC-AUC analysis  

## Sprint 3 Status
✔ Confusion matrix & Error Analysis  
✔ Limitations & Next Steps  
✔ Prepare summary notebook / report

## Demo / How to Run

1. **Clone repository**
```bash
git clone https://github.com/yourusername/vodafone-music-classification.git
cd vodafone-music-classification
```
2. **Install requirements**
```bash
pip install -r requirements.txt
```
3. **Launch notebook**
```bash
Open notebooks/VodafoneMusic_Baseline.ipynb in Jupyter / Colab
```
All steps (EDA, preprocessing, modeling, evaluation) are ready to run

4. **Use processed data**
```bash
data/processed/train_music_processed.csv is ready for modeling
```
