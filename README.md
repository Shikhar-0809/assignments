Sampling Assignment – Credit Card Fraud Detection Methodology

Dataset Description
In this assignment, we used a credit card transaction dataset. The dataset is highly imbalanced, which means:

Most transactions are normal (Class = 0)

Very few transactions are fraudulent (Class = 1)

This situation is common in real life. If we train models directly on such data, they may become biased and predict only the majority class.

Data Preprocessing
The dataset was loaded and analyzed.

No missing values were found.

Features (X) and target column (y) were separated.

Models were not trained directly on the imbalanced data.

Balancing the Dataset
To handle the imbalance problem, sampling techniques were applied to create a balanced dataset. Balancing ensures that:

Both classes get equal importance

The model can learn fraud patterns better

Prediction performance improves

Creation of Five Samples
After balancing the data, five different samples were created. Each sample represents a different way of handling class imbalance.

Sampling Techniques Used
The following sampling techniques were applied:

Sampling1 – Random Under Sampling

Sampling2 – Random Over Sampling

Sampling3 – SMOTE (Synthetic Minority Over-sampling Technique)

Sampling4 – Stratified / Cluster-based Sampling

Sampling5 – Hybrid Sampling (Combination of Over & Under Sampling)

Machine Learning Models Used
Five different machine learning models were used:

M1 – Logistic Regression

M2 – Decision Tree

M3 – Random Forest

M4 – Support Vector Machine (SVM)

M5 – K-Nearest Neighbors (KNN)

Model Training and Evaluation
Each model was trained on each sampled dataset.

Model performance was evaluated using accuracy.

The results were recorded and compared.

Result Table Model Sampling1 Sampling2 Sampling3 Sampling4 Sampling5 
M1 50.10 52.24 63.18 69.23 70.12 M2 59.25 65.27 68.72 28.36 30.25 M3 90.45 72.41 32.17 42.58 41.85 M4 78.25 56.24 47.23 33.44 40.12 M5 81.25 12.85 57.36 32.25 52.74 Analysis and Discussion

M1 (Logistic Regression) performs best with Sampling5.

M2 (Decision Tree) gives highest accuracy with Sampling3.

M3 (Random Forest) performs best with Sampling1.

M4 (SVM) achieves highest accuracy with Sampling1.

M5 (KNN) also performs best with Sampling1.

Conclusion

Different sampling techniques affect models differently.

There is no single best sampling method for all models.

Choosing the correct sampling technique depends on the model.

Sampling plays a very important role in handling imbalanced datasets.

Author

Shikhar kumar Sanjay
