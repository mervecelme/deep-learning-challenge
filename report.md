## Data Preprocessing:

Target Variable(s): The target variable for the model is IS_SUCCESSFUL, indicating whether a charity's funding application was successful.

Feature Variable(s): All variables except IS_SUCCESSFUL are considered features for the model.

Variables to be Removed: Columns 'EIN' and 'NAME' were removed from the input data as they are neither targets nor features.

## Compiling, Training, and Evaluating the Model:

Neurons, Layers, and Activation Functions: The model comprises three hidden layers with 7, 14, and 21 neurons respectively, using ReLU activation functions for the hidden layers and a sigmoid activation function for the output layer, chosen for their effectiveness in handling complex relationships and binary classification tasks.

Achievement of Target Model Performance: The model achieved an accuracy of approximately 73.27% on the test dataset, meeting the target model performance.

Steps to Increase Model Performance: Techniques such as feature engineering, hyperparameter tuning, regularization, exploring different architectures, ensemble methods, augmenting the dataset, and experimenting with optimization algorithms were undertaken to enhance model performance.