## **Bangalore House Price Prediction**



#### **Project Overview**



This project is a machine learning-based web application that predicts house prices in Bangalore based on user inputs like area (in square feet), number of bedrooms (BHK), number of bathrooms, and location.



I have designed the complete system — starting from data preprocessing and model training, followed by backend API development with Flask, frontend development using HTML, CSS, and JavaScript, and finally, deploying it on an AWS EC2 instance.



Live Website: http://ec2-13-49-70-72.eu-north-1.compute.amazonaws.com/

Localhost URL: http://13.49.70.72/



---



#### **Dataset Used**



Name: Bengaluru House Data



Source: Kaggle - Bengaluru House Price Data



---



#### **What I Did**



Cleaned and processed the dataset with outlier removal, handling missing data, and categorical encoding.



Developed a Linear Regression model using Scikit-Learn with GridSearchCV for hyperparameter tuning.



Validated model performance with cross-validation techniques.



Built a Flask API to serve the trained model for live predictions.



Developed a simple frontend interface for user interaction and live prediction display.



Deployed the complete solution on an AWS EC2 Ubuntu server with Nginx as the web server.



---



#### **Key Performance Indicators**



KPI	Value

Model	Linear Regression

R² Score (Validation)	~0.85

Backend	Flask

Frontend	HTML, CSS, JavaScript

Deployment Platform	AWS EC2 (Ubuntu)

Web Server	Nginx



Tools and Technologies

Python, Pandas, NumPy



Scikit-Learn, Matplotlib



Jupyter Notebook



Flask (API Backend)



HTML, CSS, JavaScript (Frontend)



AWS EC2, Nginx



---



#### **Deployment Summary**



Deployed the app on an AWS EC2 instance with open HTTP access.



Flask backend serves the trained model via a REST API.



Frontend interacts with the API for real-time predictions.



Project files were transferred and managed on the server via WinSCP.



---



#### **Conclusion**



This project reflects a complete cycle of a real-world machine learning application — from data cleaning and model training to API development, frontend design, and deployment.

