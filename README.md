🚢 Titanic Survival Prediction

**Overview**:
The aim of this project is to predict **Titanic passenger survival** using **machine learning models**. It leverages the **Titanic dataset**, containing details such as passenger age, class, fare, and more. The model identifies key survival factors and provides insights into what influenced survival during the disaster. 

**Features**:
1) Predicts **passenger survival** based on key features.
2) **Data preprocessing**: handling missing values, encoding categorical variables, and feature scaling.  
3) **Exploratory Data Analysis (EDA)**: visualizing survival patterns based on gender, class, and fare.  
4) Implements multiple **machine learning models** for prediction.  
5) **Hyperparameter tuning** to attempt improving model accuracy.

**Dataset**:
The project uses the **Titanic dataset**, which contains:  
1) **Survival** (0 = No, 1 = Yes)  
2) **Passenger Class** (1st, 2nd, 3rd)  
3) **Personal Information** (Name, Sex, Age, Siblings/Spouses, Parents/Children)  
4) **Ticket & Fare Details**  
5) **Cabin & Embarkation Port**

**Dataset Source**: 
This dataset was provided via Google Drive and is not publicly available. The original source is not explicitly mentioned.

**Model Implementation**::
The project applies multiple machine learning models to predict survival:  
1) **Logistic Regression**  
2) **Decision Trees & Random Forest**  
3) **Support Vector Machines (SVM)**  
4) **XGBoost**  

The model is trained using **feature engineering and hyperparameter tuning** to improve accuracy. 

**Code Structure**:
1) model(titanic-survival-prediction) (1).ipynb - Jupyter notebook containing Titanic survival prediction model implementation.
2) Titanic-Dataset (1).csv - Dataset file used for training and testing the model.

**Next Steps**:
1) Improve accuracy using feature engineering and advanced ML models.
2) Implement deep learning for more robust predictions.
3) Deploy the model as a web app using Flask/Streamlit.
4) Optimize hyperparameters further for better generalization.


