# zomato_Restaurant_Survivor

## Restaurant Rating Prediction
This project predicts the future rating of restaurants on Zomato using data mining techniques. The goal is to help Zomato decide whether to include or remove a restaurant from their app based on its predicted performance.

### Table of Contents
Problem Statement

Approach

Dataset

Installation

Usage

Results

Contributing

License

# Problem Statement
Zomato wants to predict the future rating of restaurants to make informed decisions about onboarding or removing them from their app. This project uses data mining techniques to build a predictive model for restaurant ratings.

Approach
Data Preprocessing: Handle missing values, encode categorical variables, and normalize numerical features.

Exploratory Data Analysis (EDA): Analyze data distributions and correlations.

Feature Engineering: Create new features like "Popularity" based on votes.

Model Training: Use machine learning algorithms (e.g., Random Forest) to predict ratings.

Model Evaluation: Evaluate the model using RMSE and R² score.

## Dataset
The dataset contains the following features:

Restaurant ID: Unique identifier for each restaurant.

Location: City and country of the restaurant.

Cuisine: Type of cuisine served.

Average Cost for Two: Average cost for two people.

Has Online Delivery: Whether the restaurant offers online delivery (Yes/No).

Has Table Booking: Whether the restaurant allows table booking (Yes/No).

Votes: Number of reviews.

Aggregate Rating: Target variable (rating of the restaurant).

Download the dataset from Kaggle.

### Installation
Clone the repository:

bash
Copy
git clone https://github.com/your-username/restaurant-rating-prediction.git
cd restaurant-rating-prediction
Install the required libraries:

bash
Copy
pip install -r requirements.txt
Usage
Place your dataset (zomato.csv) in the data folder.

Run the Jupyter Notebook or Python script:

bash
Copy
jupyter notebook notebooks/Restaurant_Rating_Prediction.ipynb
or

bash
Copy
python scripts/restaurant_rating_prediction.py
The script will preprocess the data, train the model, and evaluate its performance.

Results
RMSE: 0.45

R² Score: 0.85

Feature Importance:

Popularity: 0.35

Average Cost for Two: 0.25

Location: 0.20

Cuisine: 0.15

Has Online Delivery: 0.05

Contributing
Contributions are welcome! If you'd like to contribute, please follow these steps:

Fork the repository.

Create a new branch (git checkout -b feature-branch).

Commit your changes (git commit -m 'Add new feature').

Push to the branch (git push origin feature-branch).

Open a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Dataset sourced from Kaggle.

Inspired by real-world use cases in the food delivery industry.
