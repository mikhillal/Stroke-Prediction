# Stroke-Prediction

This repository contains code for predicting the likelihood of an individual having a stroke based on various health-related factors.

*Data*

The dataset used for this project is the Stroke Prediction Dataset, which is publicly available on Kaggle. It contains data on over 5000 patients and their various health attributes, such as age, gender, hypertension, heart disease, smoking status, etc.

The code for this project is written in Python. The main file is stroke_prediction.ipynb, which contains the code for loading the dataset, preprocessing it, and training machine learning models on it.

In addition, there is a templates directory that contains HTML templates for a web application. The app.py file contains the Flask web application code that serves these templates and uses the trained model to predict stroke likelihood.

*How to Use*

To use this project, you will need to install Python and several Python packages. You can do this by running the following command:

pip install -r requirements.txt

After installing the necessary packages, you can run the Flask web application by running the following command:

python app.py

This will start the web application on your local machine, and you can access it by visiting http://localhost:5000 in your web browser.
