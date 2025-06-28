# Customer-Booking-Prediction-for-British-Airways
This project focuses on building a machine learning model to predict whether a customer will complete a holiday booking with British Airways (BA) based on historical booking data. The goal is to help the airline take proactive business decisions, improve marketing strategies, and increase customer acquisition by identifying patterns in booking behavior.

Problem Statement

With thousands of customers interacting with BA daily, understanding who is likely to book a holiday is critical. The task is to:

1)Explore and clean the raw booking data

2)Train a predictive model to identify potential bookers

3)Interpret results to find key influencing factors

4)Present findings visually for business stakeholders

Steps Performed

1. Data Exploration & Cleaning
  1)Loaded the dataset using pandas

  2)Removed duplicates and handled missing values

  3)Conducted initial data analysis and visualizations

2. Feature Engineering
  1)Applied One-Hot Encoding to categorical variables such as:

  2)sales_channel, trip_type, flight_day, route, booking_origin

  3)Created a fully numerical dataset ready for machine learning

3. Model Training
 1)Split the data into training and test sets (80/20)

 2)Used RandomForestClassifier from scikit-learn

 3)Handled class imbalance using class_weight='balanced'

 4)Achieved ~84% accuracy via 5-fold cross-validation

4. Evaluation
  1)Evaluated performance using:

  2)Accuracy, Precision, Recall, F1-score

  3)Confusion matrix

  4)Observed high precision for non-bookers, low recall for actual bookings due to imbalance

5. Feature Importance
  1)Visualized top predictors of booking:

  2)Route, Booking Origin, Trip Type, Flight Day, and Sales Channel

6. Business Presentation
  1)Created a clean PowerPoint slide summarizing:

  2)Key model metrics

  3)Visual feature importance chart

  4)Insights & recommendations for stakeholders

7.📈 Model Performance
  Metric	Value
  Accuracy	84.29%
  Precision (1)	37%
  Recall (1)	4%
  F1-score (1)	8%
  CV Accuracy	~84%

8.Technologies Used
  1)Python

  2)Pandas, NumPy – Data manipulation

  3)Matplotlib, Seaborn – Visualization

  4)scikit-learn – ML algorithms and evaluation

  5)PowerPoint – Business-friendly presentation




