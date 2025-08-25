# Google_Advanced_Data_Analytics__Course_6_Project__Automatidata_Model_Development

## Project Overview
This project aimed to predict customer tipping behavior. The initial goal of predicting whether a customer would tip at all was deemed unethical, so the focus shifted to identifying generous tippers. The final Random Forest model achieved 71% accuracy and an F1 score of 0.75, effectively handling the imbalanced dataset. Key predictive features included VendorID_2, predicted_fare, passenger_count, mean_distance, and mean_duration.

## Business Understanding
The goal is to provide actionable insights for ride-sharing operations by identifying customers likely to tip generously, while avoiding potentially unethical predictions about tipping behavior.

## Data Understanding
Data included customer trips, fares, distances, durations, and vendor IDs. Imbalances in tipping behavior were considered, and preprocessing focused on ensuring model fairness and reliability.

## Modeling and Evaluation
A Random Forest model was used to predict generous tippers. 

### Feature importances:
- VendorID_2
- predicted_fare
- passenger_count
- mean_distance
- mean_duration

### Model Scoring Metrics: 
- Accuracy: 0.71
- F1: 0.75

## Conclusion
The model can inform operational strategies by highlighting likely generous tippers. Next steps include small-scale driver testing, hyperparameter tuning, exploring alternative models, and gathering additional data to improve performance.
