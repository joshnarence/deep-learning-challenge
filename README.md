# deep-learning-challenge
# Deep Learning Challenge - Module 21 Performance Report for Alphabet Soup

## Overview

## Results

### Data Preprocessing
- The dataset has a single target variable, IS_SUCCESSFUL.
- The features used for analysis are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
- EIN and NAME, which are business identifiers, are not relevant to the funding success prediction and are neither target variables nor features.

### Model Compilation, Training, and Evaluation
- The successful model was constructed with three hidden layers. The first layer had 12 neurons, the second layer had 12 neurons, and the third layer had 8 neurons. ReLU activation functions were used for all hidden layers, while the output layer utilized a sigmoid activation function.
- The model achieved the target accuracy of 75%, with the highest accuracy reaching 76.08% in the final attempt.
- Attempts were made to enhance model performance by adding an extra layer and increasing the number of neurons.

In summary, achieving the target model performance required multiple iterations and adjustments, including the addition of layers and neurons. Varying the training epochs helped reduce bias and improved overall accuracy. Binning the classification values also contributed to better accuracy. Exploring alternative classification methods, such as Random Forest, may further capture complex data interactions and potentially lead to even better model performance.
