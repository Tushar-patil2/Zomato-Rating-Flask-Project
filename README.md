
# Zomato Rating Prediction (Flask)

This project aims to predict the rating of a restaurant on Zomato based on various factors such as location, cuisine, average cost for two, and more. The prediction model is built using machine learning algorithms and is trained on a dataset of restaurants in India. This project also includes to be deployed on a web application using Flask.



![zomato](https://user-images.githubusercontent.com/121338492/227210182-4e9e4885-5de0-4cf3-9cb5-b236e72d9b8c.png)

## Table of Contents

- Project Description

- Skills Used

- Installation

- Usage

- Data

- Model

- Flask Web Application

- Conclusion




## 🛠 Skills

This project requires knowledge of several skills, including:

- Python : Used to write the machine learning algorithms and the    Flask web application.

- Machine Learning Algorithms : Used to train the model 

- Data Cleaning and Preprocessing : Used to clean and preprocess the data before using it to train the machine learning model.

- Flask Web Development : Used to develop the web application that provides the user interface for the Rating prediction.

- HTML/CSS : Used to design the user interface for the Flask web application.
 
 Python, Machine learning algorithms , Pandas , Numpy , Matplotlib , Sklearn , HTML , CSS , Flask , Plotly .


## Installation

To use this project, you need to install some packages, including pandas, numpy, matplotlib, scikit-learn, and Flask. You can install these packages using the following command:

```bash
  pip install pandas numpy matplotlib scikit-learn Flask

```
    
## Demo

- Copy and Paste Below link -

file:///C:/Users/tusha/Desktop/Zomato%20Rating%20Project/New%20folder/Zomato-Rating-Flask-Project/my_project/templates/index.html

![Photo Collage Maker_2023_03_23_04_54_20](https://user-images.githubusercontent.com/121338492/227212594-99d27989-76d3-4fd7-801a-f815902e6c4a.png)

![famous](https://user-images.githubusercontent.com/121338492/227212676-364a800b-ae2f-4a2c-ac4f-f219544c8d11.png)
![Screenshot 2023-03-22 204628](https://user-images.githubusercontent.com/121338492/227212875-ac60770b-5cc8-41b9-9969-ea0f0340d41f.png)

## Usage

Using this project is very simple. You just need to run the 'app.py' file and Enter the required restaurant details (e.g. location, cuisine, average cost for two) and click the "Predict" button to get the predicted rating for the restaurant.


## Data 

The data for this project is collected from the Zomato website using web scraping techniques. The data is collected for restaurants in major cities in India. The collected data is cleaned and preprocessed using Python. The data is checked for missing values, outliers, and other anomalies. The data is transformed into a format suitable for training the machine learning model.


![Screenshot 2023-03-22 204524](https://user-images.githubusercontent.com/121338492/227213102-bc399720-df02-47c2-830e-02619859a451.png)

![Screenshot 2023-03-22 204644](https://user-images.githubusercontent.com/121338492/227213169-b41e853b-3dee-4cfa-87fb-90839c41efa4.png)


## Model building

The machine learning model is built using scikit-learn, a popular Python library for machine learning. The first step in building the model is selecting the relevant features for predicting the rating of restaurants on Zomato. These features include location, cuisine, cost, etc.

Several machine learning algorithms are tested on the training set to determine which one produces the best results. The algorithms that are tested include linear regression, , random forests , Extra tree regression that gives 93% accuracy .

Once the model is trained and fine-tuned, it is saved to a file so that it can be used for prediction in the web application.

Overall, the model building process involves selecting relevant features, testing several machine learning algorithms, evaluating their performance, selecting the best-performing model, and fine-tuning its parameters. The final trained model is saved for deployment in the web application.

## Flask Web Application

The Flask web application provides a user-friendly interface to enter inputs and get price predictions. I have used HTML/CSS to design the web interface and Flask to handle the back-end functionality.

The web interface is simple and easy to use. You just need to input the order online , book table , votes ,location , cuision , restaurant type , cost and Menu and press the Predict button at the end.

## Conclusion

The Zomato Rating Deployment Project is a machine learning project that predicts the rating of restaurants on the Zomato platform. The project is built using Python as the primary programming language and uses scikit-learn for building the machine learning model. The web application is deployed on GitHub and can be used as a project to showcase . The project demonstrates skills in data collection, data cleaning, feature selection, machine learning, model evaluation, web application development, and deployment on GitHub.
