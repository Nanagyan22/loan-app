# Interactive Loan Default Prediction Web App Using Streamlit
*Leveraging Machine Learning to Predict Loan Default Amounts for Better Financial Decision-Making*

![Project Banner](img/banner-image.png)

---

## ⚠️ Disclaimer
This project uses **synthetic or anonymized data** for demonstration purposes. No confidential or real customer information is included. It showcases skills in building predictive analytics web apps while following ethical and privacy standards.

---

## Introduction
The Loan Default Prediction Web App is a multi-page interactive application built with Streamlit. It allows users to **analyze datasets, preprocess data, train regression models, evaluate performance, and make custom predictions**. The app simulates real-world financial risk modeling and supports decision-making for banking and loan management.

![Home Page](img/Home.png)

---

## Table of Contents
- [Description](#description)
- [Methodology](#methodology)
- [Tools and Technologies](#tools-and-technologies)
- [Deployment](#deployment)
- [Project Screenshots](#project-screenshots)
- [Future Enhancements](#future-enhancements)
- [Contact](#contact)

---

## Description
This project demonstrates a full **machine learning workflow for loan default prediction**, including:  
- Importing and exploring datasets  
- Preprocessing (handling missing values, encoding, scaling)  
- Feature selection (best subset, forward stepwise)  
- Model training and evaluation  
- Interactive prediction for custom user input  

![Data Overview](img/Overview.png)  
![Correlation Matrix](img/Correlation.png)
![Correlation Matrix](img/Overview_2.png).

---

## Methodology

### 1. Data Import and Overview
- Users can upload a CSV or load the provided Kaggle dataset.  
- Summary statistics and visualizations are generated.

### 2. Data Preprocessing
- Handle missing values  
- Encode categorical variables  
- Normalize/standardize numerical variables  

![Preprocessing](img/Preprocessing.png)
![Preprocessing](img/Boxplt.png)
![Preprocessing](img/Categorial.png)
![Preprocessing](img/Duplicates.png)

### 3. Feature Selection
- **Best Subset Selection** and **Forward Stepwise Selection** are implemented.  
- Outputs are compared to select optimal predictive features.

![Feature Selection](img/Featuremethod.png)

### 4. Model Training & Evaluation
- Train regression models using selected features  
- Evaluate using **RMSE** and **R²**  
- Visualize predicted vs actual values

![Model Evaluation](img/best.png)

### 5. Interactive Prediction
- Users input custom feature values to predict loan default amount  
- Display predicted value dynamically

![Interactive Prediction](img/user1.png)

![Interactive Prediction](img/User4.png)

![Interactive Prediction](img/user3.png)

---

## Tools and Technologies
| Tool/Library | Purpose |
|--------------|---------|
| Python | Core scripting and ML models |
| Streamlit | Frontend web app and UI |
| Scikit-learn | ML model training and evaluation |
| Pandas / NumPy | Data manipulation and preprocessing |
| Matplotlib / Seaborn | Visualization |
| GitHub | Version control and repository hosting |

---

## Deployment
The app is deployed on **Streamlit Community Cloud**:  
[Click here to access the live app](https://loan-appp.streamlit.app/)  

---

## Project Screenshots
- **Landing Page / Home Screen**  
![Home](img/Home.png)  

- **Data Overview and Visualization**  
![Data Overview](img/Overview_2.png)  

- **Preprocessing Page**  
![Preprocessing](img/Preprocessing.png)  

- **Feature Selection**  
![Feature Selection](img/Featureselection.png)  

- **Prediction Page**  
![Prediction](img/user3.png)  

---

## Conclusions & Recommendations
- The app demonstrates a complete **machine learning workflow**, providing reliable predictions of loan default amounts.  
- Key predictive features were identified using **Best Subset** and **Forward Stepwise Selection**, with strong evaluation metrics (RMSE, R²).  
- **Recommendations:** deploy in real-world lending platforms, retrain models regularly, enhance feature engineering, provide explanation for predictions, and scale the app for large datasets.  

---

## Future Enhancements
- Add **automated feature engineering** to improve model accuracy  
- Include **classification models** for default risk categories  
- Enable **multi-user support** with login and personalized predictions  
- Expand **visualizations and dashboard insights** for better interpretability  

---

## Contact
For questions or collaborations, feel free to reach out!  

[![LinkedIn](https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge)](https://https://www.linkedin.com/in/francis-afful-gyan-2b27a5153/)  


![Thank You](img/Thankyou1.jpg)

