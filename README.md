Some methods used in making this model.

Model Training

A Logistic Regression model is instantiated with a random_state of 1 for reproducibility.
The model is trained using the training dataset (X_train, y_train).

Model Predictions & Evaluation

The trained model predicts loan status using X_test.
A confusion matrix and classification report assess model performance.
Results indicate 100% precision and recall for predicting healthy loans (0) and 87% precision with 95% recall for high-risk loans (1), achieving an overall 99% accuracy.
