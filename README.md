## California Housing Price Prediction

Project Overview

This project uses Machine Learning to predict California housing prices based on features such as median income, house age, average rooms, population, and location data.

The model is built using Python and Scikit-learn with a Random Forest Regressor algorithm.

Dataset

Dataset: California Housing Dataset

Source: Scikit-learn built-in dataset

Features:

- MedInc (Median Income)
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

Target:

- Median House Value

Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib

Machine Learning Workflow

1. Load the California Housing dataset
2. Split data into training and testing sets
3. Train a Random Forest Regressor model
4. Predict house prices on test data
5. Evaluate performance using Mean Absolute Error (MAE)

Model Used

Random Forest Regressor

Parameters:

- n_estimators = 100
- random_state = 42

Results

Mean Absolute Error (MAE): 0.327542

A lower MAE indicates better prediction accuracy. The model achieved good performance on the test dataset.

Project Structure

California_Housing_Price_Prediction/
│
├── California_Housing_Price_Prediction.ipynb
├── README.md
└── screenshots/
├── model_output.png
└── actual_vs_predicted.png

Future Improvements

- Hyperparameter tuning
- Feature engineering
- Cross-validation
- Compare multiple regression algorithms
- Deploy the model as a web application

Learning Outcomes

Through this project, I learned:

- Data preprocessing
- Train-test splitting
- Regression modeling
- Model evaluation
- Random Forest algorithms
- Machine Learning workflow using Scikit-learn

Author

Siddi Kiranmayi

B.Tech CSE (AI & ML)

Mother Teresa College of Engineering and Technology
