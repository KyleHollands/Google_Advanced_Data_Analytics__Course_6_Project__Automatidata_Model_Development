# Google_Advanced_Data_Analytics__Course_6_Project__Automatidata_Model_Development

The initial goal of this project phase was to create a machine learning model predicting whether a customer would tip at all. However, this was deemed unethical and potentially harmful to the company long-term. The focus shifted to predicting if a customer would be a generous tipper.

The resulting Random Forest model, while not perfect, successfully predicts generous tippers based on specific variables. It achieved an f1 score of 0.75 and an accuracy of 0.71, which were deemed sufficient given the data's imbalance.

Key predictors include VendorID_2, predicted_fare, passenger_count, mean_distance, and mean_duration. Further analysis of VendorID_2 is needed to understand its significance.

Next steps involve testing the model with a small group of drivers to assess its real-world performance. Additionally, fine-tuning hyperparameters, exploring other models, and acquiring more relevant data could potentially enhance the model's accuracy.