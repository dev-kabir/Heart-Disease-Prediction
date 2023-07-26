# Heart-Disease-Prediction

Question:
I wanted to predict heart disease using a dataset. The dataset had information about 13 different features related to the patients' health, like age, blood pressure, cholesterol levels, etc. The target variable (what we want to predict) was whether the patient had heart disease or not, represented by 1 for "Disease" and 0 for "Normal." My goal was to use a logistic regression model to predict if a patient has heart disease based on their health features.

Results:
I applied the logistic regression model to the dataset and got some promising results. The model's accuracy was around 88.5%, which means it correctly predicted heart disease or normal cases 88.5% of the time. The precision, which measures the accuracy of the model's "Disease" predictions, was about 87.9%. This indicates that when the model predicts someone has heart disease, it's correct about 87.9% of the time. The recall, which measures the model's ability to identify actual positive cases, was approximately 90.6%. It means the model can successfully detect about 90.6% of the patients who actually have heart disease. The F1 score, a balanced measure considering both precision and recall, was around 89.2%, which is quite good.

Looking at the confusion matrix, we see that the model made some mistakes. It correctly identified 25 patients with heart disease and 29 healthy patients. However, it misclassified 4 healthy patients as having heart disease and missed 3 actual cases of heart disease. These misclassifications suggest there's still room for improvement, but overall, the model is doing a good job in predicting heart disease.

It's important to keep in mind that the results might not be perfect, and the model's performance could vary depending on the data and features used. However, the model shows promise, and we could further explore ways to enhance its performance or consider other algorithms if needed.

In summary, the logistic regression model seems to be a good starting point for predicting heart disease, and we can use these results to guide further analysis or potential real-world predictions.
