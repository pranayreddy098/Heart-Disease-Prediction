# Heart-Disease-Prediction
Cardiovascular diseases are a significant public health challenge, accounting for a substantial portion of deaths. Early detection of heart disease is very important for effective treatment. Traditional diagnostic methods can be time-consuming and expensive, so we need an efficient predictive tool. In this project, we utilize a dataset containing clinical attributes associated with heart disease to train a logistic regression model to predicts the likelihood of a patient developing heart disease within ten years.
This approach uses data science techniques with machine learning to provide insights and can be used for effective treatment of the patients with heart disease. In this approach Logistic Regression and Confusion Matrix methods for prediction of heart diseases.
3.Data Collection
Data is collected from google datasets
Data consists of Age, Gender, and other health information which is useful in our model building
4.Data Preprocessing
Removing unwanted fields like patient id, location to reduce the amount of data to be processed. And standardising data for an efficient model
5.Meachine Learning Model
For this Model Logistic Regression is used for statical analysis and model creation.
Model evaluation:
Accuracy: To determine the proportion of correctly predicted instances.
Confusion Matrix: To provide a detailed breakdown of true and false predictions.
Classification Report: To evaluate precision, recall, and F1-score.
6.Model Implementation
Data Splitting: Split dataset into 80% training and 20% testing sets using `train_test_split` from Scikit-Learn.
Using logistic Regression for model creation and training data set.
Visualizing the result using a ROC curve and confusion matrix heatmap.
Finally, the detailed breakdown of the confusion matrix and classification report was printed for an in-depth analysis of the model’s predictive capabilities.

7. Results and Evaluation
The results from the heart disease prediction model indicate that logistic regression can effectively classify individuals at risk of heart disease based on clinical attributes. The performance metrics and visual evaluations highlight of the model's strengths.
Based on the metrics and visualization, the model's performance can be summarized as:
• The accuracy of the model indicates how well it predicts heart disease.
• The ROC AUC score demonstrates the model's ability to distinguish between classes effectively.
• The confusion matrix and classification report provide insights into specific areas of success and failure, such as identifying false positives and false negatives.

9. Conclusion and Future Work
This project shows the development and implementation of a logistic regression model to predict heart disease risk, inspired by Sustainable Development Goal 3 Good Health and Well-being. By analyzing clinical data and using machine learning techniques, to created a predictive tool that can to identifying individuals at risk of heart disease. Through performance metrics such as accuracy, ROC AUC score, and a detailed confusion matrix, the model showed results in correctly classifying patients at risk, contributing toward early discovery.
Future Work we can use more advanced models and a bigger data set to get a model trained on large amount of data for identifying new symptoms and increase accuracy of a model. Feature Engineering, Cross-Validation, Hyperparameter Tuning and many other techniques can be used in feature.
