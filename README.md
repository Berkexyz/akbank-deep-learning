# Akbank Deep Learning Bootcamp

## Deep Learning Image Classification Project

This project aims to develop a deep learning model using a large image dataset. The goal is to create a model that can accurately classify images, utilizing data preprocessing, model optimization, and evaluation techniques to monitor model performance.

### Main Steps

#### 1. Data Loading and Preprocessing:
- Images from the dataset were loaded and processed.
- Specific file types (e.g., `.png` files) were filtered, and directories such as 'GT' were excluded.
- The paths and labels of the image files were stored in a pandas DataFrame.
- A portion of the images was split into training and test sets (80% training, 20% testing).

#### 2. Model Training:
- A neural network (ANN) model was built using **Keras**.
- The model included 3 `Dense` layers with 1024, 512, and 256 neurons.
- The final layer used the softmax activation function to classify the images.
- During training, the `adam` optimizer and `categorical_crossentropy` loss function were used.

#### 3. Monitoring Loss and Accuracy:
- The model's accuracy and loss were monitored during training.
- Loss and accuracy values for both training and validation sets were visualized.
- These graphs helped observe issues such as overfitting or underfitting during the training process.

#### 4. Model Performance Evaluation:
- The model's performance was evaluated on the test dataset.
- A confusion matrix was generated to analyze the classification results in detail.
- Additionally, a classification report was created to compute precision, recall, and F1-score for each class.

### Conclusion

This project demonstrates how to build, train, and evaluate a deep learning model for image classification tasks. The model is capable of predicting which class the images belong to with high accuracy.
