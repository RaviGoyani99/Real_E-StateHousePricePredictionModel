# Real_E-StateHousePricePredictionModel

### Technologies and Tools
**This project leverages a variety of tools and technologies to achieve its goals:**

1. Python
2. NumPy and Pandas: Used for data cleaning, manipulation, and analysis.
3. Matplotlib: Utilized for data visualization, creating plots and graphs to understand data distributions and model performance.
4. Data Cleaning, Feature Engineering, and Outlier Removal: Techniques used to prepare and enhance data quality for model building.
5. Dimensionality Reduction: Applied to reduce the complexity of data while preserving important information.
6. One-Hot Encoding and Data Processing Pipeline: Techniques for handling categorical data and streamlining data processing workflows.
7. Scikit-Learn: The primary machine learning library used for model building, evaluation, and hyperparameter tuning with GridSearchCV.
8. Git BASH: A command-line tool used for version control and managing code.
9. Flask: A lightweight web framework used to build the backend server for the application.
10. Amazon Web Services (AWS) - EC2 and Nginx: Used for deploying the application to the cloud and managing server configurations.

## ML Model Deploy to production using aws Ec2 & NGINX Web server
<img width="959" alt="Screenshot 2024-08-28 161520" src="https://github.com/user-attachments/assets/708dd003-15dd-48b1-8c6d-01e82cca53ad">

### Objectives
* To develop a machine learning model capable of predicting real estate prices based on specific features.
* To create an end-to-end pipeline that includes data collection, preprocessing, model training, and deployment.
* To build a user-friendly web interface where users can input property details and receive real-time price predictions.

### Project Overview
The Real Estate Price Prediction project is a data science and machine learning initiative designed to predict real estate prices based on various features such as area, number of bedrooms, bathrooms, and location. This project aims to provide a comprehensive learning experience by walking through each step of building a machine learning model, from data collection and preprocessing to model training and deployment through a web-based interface.

**The project is organized into several key components:**

**Model:** Includes Python notebooks for data preprocessing, model building, and evaluation. This is where the core machine learning tasks are executed, including linear regression and hyperparameter tuning.

**Server:** The backend server is developed using Python Flask, which handles requests from the front end and communicates with the trained model to provide predictions.
UI: Contains the code for the web-based user interface. Built with HTML, CSS, and JavaScript, this front-end provides a simple way for users to enter property details and receive predicted prices.

**Data Collection and Preprocessing:** The project starts with collecting the real estate dataset, specifically the Bangalore home prices dataset from Kaggle. The data is then cleaned using Numpy and Pandas, involving tasks such as handling missing values, outlier detection, and feature engineering to make the data suitable for model training.

**Model Training:** The cleaned dataset is used to train a linear regression model using Scikit-Learn. This phase involves splitting the data into training and test sets, applying feature scaling, and tuning hyperparameters using techniques like GridSearchCV and K-Fold Cross Validation to optimize model performance.

**Web Interface Development:** A user-friendly web interface is developed using HTML, CSS, and JavaScript. This interface allows users to input property details such as square footage, number of bedrooms, and location, which are then sent to the server for prediction.

**Deployment:** The trained model is deployed using Flask, allowing it to handle real-time prediction requests. The server processes the input details, runs them through the model, and returns the predicted price to the user interface.

**User Interaction:** Users interact with the application by entering property details into the web interface. The application processes this input, predicts the price, and displays it on the web page.

### Installation Guide

1. Clone the Repository: git clone https://github.com/your-username/real-estate-price-prediction.git
   
2. Install Dependencies: Navigate to the project directory and run pip install -r requirements.txt to install all necessary Python packages.

3. Run the Server: Start the Flask server by navigating to the server directory and running python app.py.

4. Access the Web Interface: Open your browser and go to http://localhost:5000 to access the prediction interface.

### Conclusion
This project demonstrates the application of various data science, machine learning, and web development tools to build a functional and practical real estate price prediction tool. It provides a comprehensive learning experience, covering all major aspects of building and deploying a machine learning model, from data preprocessing to user interface development.
