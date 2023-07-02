### Machine Learning Project ###

## Home page : http://127.0.0.1:5000/
## Prediction Page : http://127.0.0.1:5000/predict


# Diamond Price Prediction

This project focuses on predicting the price of diamonds using machine learning techniques. Several machine learning models, including Linear Regression, Ridge, Lasso, Decision Tree Regressor, and Random Forest Regressor, have been employed to develop accurate price prediction models.

## Features

- Data Collection: The project utilizes a dataset containing various features of diamonds, such as carat, depth, table, and dimensions (x, y, z), as well as categorical features like cut, color, and clarity.
- Model Training: Multiple machine learning models, including Linear Regression, Ridge, Lasso, Decision Tree Regressor, and Random Forest Regressor, have been trained on the diamond dataset to learn the relationships between the features and the diamond prices.
- Model Evaluation: The trained models have been evaluated using appropriate evaluation metrics to assess their performance and determine the most accurate model for diamond price prediction.
- Web Application: A Flask-based web application has been developed to provide a user-friendly interface for users to input diamond characteristics and receive predicted price estimates based on the trained models.

## Getting Started

To run this project on your local machine:

1. Clone or download the project repository to your local environment.
2. Install the required dependencies by running `pip install -r requirements.txt` in your terminal or command prompt.
3. Run the main Python script to train the models and generate the necessary artifacts for the web application.
4. Start the Flask web application by executing `python application.py` in your terminal or command prompt.
5. Access the web application by visiting `http://127.0.0.1:5000/` in your web browser.
6. Enter the diamond characteristics in the provided form and submit to receive price predictions based on the trained models.

## Dependencies

The project relies on the following dependencies:

- Flask: A micro web framework used for building the web application.
- Scikit-learn: A machine learning library used for training and evaluating the models.
- Pandas: A data manipulation library used for handling and preprocessing the diamond dataset.

These dependencies are listed in the `requirements.txt` file and can be installed using `pip install -r requirements.txt`.

## Contact

If you have any questions or inquiries regarding this project, please contact Shubham Yadav at shubhamyadav.2508@gmail.com
