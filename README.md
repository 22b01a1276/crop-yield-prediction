Crop Yield Prediction Using Machine Learning

Project Overview :
This project focuses on building a machine learning model to predict crop yield based on various agricultural and environmental factors such as rainfall, fertilizer usage, pesticide usage, crop type, season, and cultivation area. The objective is to help farmers and agricultural planners make data-driven decisions to improve productivity.

Problem Statement :
To develop a predictive model using real-world agricultural data that can estimate crop yield accurately and explain the influence of different factors on crop production.

Dataset Description :
The dataset contains agricultural records from multiple states in India between 1997 and 2020. It includes the following features:
Crop,
Year,
Season,
State,
Area,
Production,
Annual Rainfall,
Fertilizer,
Pesticide,
Yield (Target Variable).


Methodology :
The project follows a complete machine learning pipeline:
Data Collection and Understanding,
Data Cleaning and Preprocessing,
Handling Missing Values,
Encoding Categorical Variables,
Feature Scaling,
Train-Test Split,
Model Training,
Model Evaluation,
Performance Analysis.

Models Used :
Linear Regression,
Random Forest Regressor,
Decision Tree Regressor,
The best-performing model was selected based on evaluation metrics.

Evaluation Metrics : 
The model performance was evaluated using:
Mean Squared Error (MSE),
R² Score.
Final Results:
R² Score: ~0.90,
MSE: ~72,571.
These results indicate strong predictive performance.


Key Learnings :
Practical experience in data preprocessing,
Understanding feature importance,
Model selection and tuning,
Performance evaluation,
Handling real-world datasets.


Technologies Used :
Python,
Pandas,
NumPy,
Scikit-learn,
Matplotlib,
Google Colab.


Future Enhancements :
Deployment using Streamlit/FastAPI,
Integration with live weather APIs,
Addition of advanced models like XGBoost,
Building a web dashboard.
