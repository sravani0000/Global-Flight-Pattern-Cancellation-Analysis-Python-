**Global Flight Pattern & Cancellation Analysis**


✈️ Project Overview
This project investigates global airline flight patterns to understand why and when cancellations occur. By leveraging Python's data science ecosystem, I analyzed historical flight data and built a predictive model to identify flights at high risk of being grounded.



📊 Performance Summary
The machine learning model (Random Forest) performed exceptionally well, achieving near-perfect prediction scores. This suggests that flight cancellations follow highly predictable patterns based on scheduling and timing.

Project Accuracy Score: 99.92%

Recall (Cancellations): 0.97 (Successfully identified 97% of all actual cancellations).

F1-Score: 0.98 (Excellent balance between precision and recall).



🛠️ Technical Implementation

Following the methodologies used in advanced data analysis, this project includes:

Data Cleaning: Handling missing values and formatting cancellation codes.
Exploratory Analysis: Identifying correlations between flight distance, departure time, and cancellation status.
Feature Scaling: Using StandardScaler to normalize data for the machine learning model.
Classification: Training a Random Forest Classifier to distinguish between successful flights and cancellations.



📈 Model Classification Report

              precision    recall  f1-score   support

           0       1.00      1.00      1.00    203718
           1       1.00      0.97      0.98      4722

    accuracy                           1.00    208440


    
🚀 Key Insights

Predictability: Despite the complexity of global travel, cancellations are not random and can be predicted using temporal features (Month, Day, Time).

Reliability: The model rarely produces "false alarms," meaning if it predicts a cancellation, it is almost certainly correct (1.00 Precision).



📂 Requirements

To run this project, you need the following Python libraries:

pandas
numpy
seaborn

matplotlib

scikit-learn
