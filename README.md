# Mushroom Classification using Support Vector Machine

## Overview

This project focuses on classifying mushrooms as either edible or poisonous based on their properties and habitat using a Support Vector Machine (SVM). The implementation is done in Python, leveraging popular libraries such as Scikit-learn, Pandas, Matplotlib, and Seaborn.

## Project Steps

### 1. Dataset Splitting
The dataset is divided into training and test sets, with 80% of the data used for training the model and 20% for evaluating its performance.

### 2. Encoding
Ordinal encoding is applied to input variables, and label encoding is used for the target variable to prepare the data for SVM modeling.

### 3. Rescaling
To ensure the SVM model works optimally, input variables are rescaled to the range (-1, 1).

### 4. SVM Model Fitting
The SVM model is fitted to the training data, utilizing various kernels and hyperparameters.

### 5. Model Evaluation
The model's performance is evaluated on the test dataset using metrics such as confusion matrix and classification report.

### 6. Hyperparameter Tuning
Grid search algorithm is employed to fine-tune hyperparameters like kernel type, gamma, and cost function, optimizing the model for accuracy.

## Results and Conclusion

After thorough experimentation and analysis, the following key findings were observed:

- Achieved an impressive accuracy of 95% using a linear kernel and a C value of 1.0.
- Identified the SVM model with a polynomial kernel and a C value of 1 as the best-fit model for this dataset, boasting a remarkable accuracy of 100%.

This project demonstrates the effectiveness of SVM in classifying mushrooms based on their properties, offering insights into the optimal model configuration for accurate predictions. Feel free to explore the code, dataset, and results in this repository.

## How to Use

1. Clone this repository to your local machine.
2. Install the required Python libraries: Scikit-learn, Pandas, Matplotlib, and Seaborn.
3. Run the Jupyter notebook or Python script to reproduce the analysis and results.

Feel free to contribute, report issues, or provide feedback. Happy coding!
