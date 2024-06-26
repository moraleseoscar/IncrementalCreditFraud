# Incremental Credit Fraud

This project aims to develop a fraud detection system using machine learning techniques. The goal is to create models capable of identifying fraudulent transactions within a dataset of financial transactions. The project focuses on implementing incremental training methodologies to continuously update the models with new data, enabling them to adapt to evolving patterns of fraudulent activities.

## Features

- **Incremental Training:** The project employs incremental training techniques to update the fraud detection models with new data, ensuring their continuous adaptation to changing patterns of fraudulent behavior.
- **Data Preprocessing:** Prior to model training, the dataset undergoes preprocessing steps such as imputation of missing values, encoding of categorical variables, and feature scaling to ensure optimal model performance.
- **Model Evaluation:** The performance of the fraud detection models is evaluated using various metrics such as accuracy, precision, recall, ROC-AUC, and precision-recall AUC to assess their effectiveness in distinguishing between fraudulent and legitimate transactions.
- **Model Comparison:** The project compares the performance of different machine learning algorithms, including SGDClassifier (Random Forest) and Perceptron (ANN), to identify the most effective approach for fraud detection in the given dataset.

## Implementation

- The dataset is divided into multiple groups based on transaction states to facilitate incremental training.
- Each group undergoes preprocessing and is sequentially used to train the fraud detection models.
- The models are evaluated at each stage of incremental training to assess their performance and adaptability to new data.
- Additionally, non-incremental versions of the models are trained using the entire dataset to compare their performance with the incremental counterparts.

## Results

The SGDClassifier (Random Forest) model demonstrates high precision but limited capability in detecting fraudulent transactions, especially in classes with imbalanced data.

In contrast, the Perceptron (ANN) model exhibits superior efficiency in detecting fraudulent transactions from the outset, maintaining high precision and adaptability throughout incremental training.

## Conclusion

The project highlights the effectiveness of incremental training methodologies in developing fraud detection systems capable of adapting to evolving patterns of fraudulent activities. The Perceptron (ANN) model emerges as a more suitable option for fraud detection due to its superior performance in identifying fraudulent transactions compared to the SGDClassifier (Random Forest) model.

## References

Anowar, F., & Sadaoui, S. (2020, October). Incremental neural-network learning for big fraud data. In 2020 IEEE international conference on systems, man, and cybernetics (SMC) (pp. 3551-3557). IEEE.

Lefik, M., & Schrefler, B. A. (2003). Artificial neural network as an incremental non-linear constitutive model for a finite element code. Computer methods in applied mechanics and engineering, 192(28-30), 3265-3283.

Oraon, M., & Sharma, V. (2018). Predicting force in single point incremental forming by using artificial neural network. International Journal of Engineering, 31(1), 88-95.

Pal, K., & Patel, B. V. (2020, March). Emotion Classification with Reduced Feature Set SGDClassifier, Random Forest and Performance Tuning. In International Conference on Computing Science, Communication and Security (pp. 95-108). Singapore: Springer Singapore.
