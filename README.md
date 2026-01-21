
<h1>Crop Recommendation Using Machine Learning</h1>

👉Summary

A machine learning model that recommends the most suitable crop based on soil nutrients and environmental conditions.

👉 Overview

This project uses supervised machine learning to help farmers or agricultural planners decide which crop to grow given soil and climate parameters. 

Goal: Build a model that recommends the optimal crop using measurable factors like nitrogen, phosphorus, potassium, temperature, humidity, pH, and rainfall.

📊 Dataset

Dataset :<a href="https://github.com/rajan-kumar-mu1439/crop-recommendation-system/blob/main/Crop_recommendation.csv"> Crop Recommendation Dataset</a>

Features:

N – Nitrogen content in soil

P – Phosphorus content in soil

K – Potassium content in soil

temperature – Temperature in °C

humidity – Relative humidity (%)

ph – Soil pH value

rainfall – Rainfall in mm

Target: label – Recommended crop (rice, wheat, maize, cotton, etc.)

👉Tools & Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook

👉 Methods Used

 Data Cleaning & Validation

 Exploratory Data Analysis (EDA)

 Feature Scaling (if required)

 Model Training (e.g., Random Forest / Decision Tree / KNN)

 Train-Test Split (80% train / 20% test)

 Model Evaluation (Accuracy, Confusion Matrix)

👉 Key Insights

Soil nutrients (N, P, K) are strong predictors of crop type

Rainfall and temperature significantly affect model confidence

Tree-based models outperform simple linear models

If accuracy is high but logic is weak, the model is still useless — this one is both.

👉 Dashboard / Model Output

 Crop prediction based on user input

 Accuracy score displayed

 Confusion matrix / classification report

✅ Results & Conclusion

 Model achieves high accuracy on unseen data

 Helps reduce crop selection risk

 Can be extended for real-world deployment

👉 Future Work

 Add location-based recommendations

 Deploy as a web or mobile app

 Integrate real-time weather API

 Try ensemble or deep learning models

👤 Author & Contact

Name: Rajan Kumar

Role: Machine Learning Enthusiast 

Email: rajankumarmu1439@gmail.com

LinkedIn: https://www.linkedin.com/in/rajan-kumar-mu1439/
