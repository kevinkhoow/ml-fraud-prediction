# **Predicting Fraud in Electricity and Gas Consumption** 

## **Overview**

This project aims to investigate the effectiveness of the following machine learning algorithms in predicting fraud in electricity and gas consumption.
* **Logistic Regression** (LR), implemented via scikit-learn
* **Support Vector Machine** (SVM), implemented via scikit-learn
* **Extreme Gradient Boosting** (XGB), implemented via xgboost

Fraudulent consumption of electricity and gas results in financial losses that are not only borne by distribution companies, but are also passed onto consumers in most cases. Additionally, illicit tampering with distribution networks compromises the reliability of the power grid and poses a risk to public safety (Plummer 2025).

The project is structured into the following key phases:
* **Exploratory Data Analysis** (EDA)
* **Train-test Split**
* **Data Pre-processing**
  * **Feature Engineering**, using one-hot encoding (OHE) and data aggregation
  * **Feature Scaling**
  * **Feature Selection**, using Sequential Forward Selection (SFS) implemented via MLxtend
  * **Oversampling to handle Class Imbalance**, using the Synthetic Minority Oversampling Technique (SMOTE) implemented via imbalanced-learn
* **Results and Discussion**

This project is developed as part of the NUS course IT1244 Artificial Intelligence: Technology and Impact.

## **Project Structure**

```
ml-fraud-prediction  
├── README.md  
├── dataset  
│   ├── clients.csv  
│   ├── invoice.csv  
├── code.ipynb  
└── report.pdf
``` 

## **Setup**

#### Clone the Repository
```
git clone https://github.com/kevinkhoow/ml-fraud-prediction.git
cd ml-fraud-prediction
```

####  Set Up and Activate Virtual Environment
```
python3 -m venv venv
source venv/bin/activate
```

#### Install Dependencies
```
pip install -r requirements.txt
```

You may now run the code in `code.ipynb`, as well as view the detailed report in `report.pdf`.
