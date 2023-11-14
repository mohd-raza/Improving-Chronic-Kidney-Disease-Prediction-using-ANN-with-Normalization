# Chronic Kidney Disease Prediction
This work aims to accurately predict Chronic Kidney Disease (CKD) using a robust Artificial Neural Network model and compares its performance to various machine learning algorithms, ultimately achieving an impressive accuracy of 98%, making it a promising tool for CKD diagnosis.

## Motivation
The motivation for advancing the predictive accuracy of Chronic Kidney Disease (CKD) prediction is underscored by compelling statistics. Globally, CKD affects approximately 10% of the population, with an alarming 90% of cases remaining undiagnosed until reaching advanced stages. Improved accuracy in prediction models holds the potential to address this concerning trend by enabling early detection in a substantial number of cases, potentially reducing the incidence of CKD-related complications by a significant percentage.

Furthermore, the economic impact is substantial, with CKD management accounting for an estimated 2% to 3% of total healthcare expenditures globally. By optimizing resource allocation through accurate predictions, healthcare providers can make substantial cost savings, potentially resulting in millions of dollars redirected towards other critical healthcare needs.

Moreover, considering that CKD is a leading cause of morbidity and mortality worldwide, refining predictive models not only holds the potential to improve individual patient outcomes but also contributes to broader public health goals, aligning with global efforts to tackle the growing burden of non-communicable diseases. This pursuit of accuracy is essential for shaping effective healthcare strategies and research initiatives, ultimately enhancing the quality of life for millions affected by CKD.

## Proposed Methodology
<img src="https://github.com/mohd-raza/Improving-Chronic-Kidney-Disease-Prediction-using-ANN-with-Normalization/assets/91888013/a0961fdb-2271-46a1-9fb0-52ab7038abfe" alt="image" width="600" height="300">

## ANN Architechture
<img src="https://github.com/mohd-raza/Improving-Chronic-Kidney-Disease-Prediction-using-ANN-with-Normalization/assets/91888013/8c2d4729-b221-4210-af2f-407385dbb088" alt="image" width="350" height="450"><br>


The Artificial Neural Network (ANN) architecture employs Rectified Linear Unit (ReLu) activation functions in both the input and hidden layers, with a sigmoid activation function in the output layer to predict the binary outcome of Chronic Kidney Disease (CKD) prediction. The model utilizes binary cross-entropy as the loss function and the Adaptive Moment Estimation (Adam) optimizer, tailored for binary data, to optimize its parameters. After rigorous testing of various classification algorithms, the ANN demonstrated the highest accuracy. The custom ANN architecture includes three hidden layers with respective unit configurations of {32, 16, 8}. It operates with a learning rate of 0.01 and a batch size of 8 during training, with a total of 50 epochs to fine-tune the model's performance. This architecture is designed to effectively predict the presence or absence of CKD with the provided hyperparameters and configurations.
## Conference, Presentation and Publication
Our research work titled **Improving Chronic Kidney Disease Prediction using ANN with Normalization** has been presented at the ***4th International Conference on Data Science and Applications, 2023*** and accepted for publication in the ***Springer Book Series, “Lecture Notes in Networks and Systems 2024.*** 

## Authors
Neel Kothari, Mohammed Raza Syed, Praniket Walavalkar, Dr. Pratik Kanani & Dr. Nilesh Patil
