## Mental Health Classification Project

Project Description
This project aims to classify mental health conditions using both supervised learning (Logistic Regression) and unsupervised learning (DBSCAN Clustering). The dataset includes various mental health statuses, and both approaches were applied to evaluate their performance.

Objectives:
Use Logistic Regression with SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance and improve classification performance.
Apply DBSCAN Clustering for unsupervised learning, optimizing parameters to identify meaningful clusters within the dataset.

Algorithms Used:
1. Logistic Regression (Supervised Learning):
Technique: SMOTE was applied to the training data to balance the classes and improve the model’s ability to classify underrepresented mental health conditions.
Performance: Achieved an accuracy of 76% after applying SMOTE, with improvements in the classification of underrepresented classes such as Personality Disorder (F1-score increased from 45% to 63%) and Stress (F1-score increased to 62%).
Use Case: Logistic Regression showed strong performance in distinguishing between labeled mental health statuses after balancing the dataset using SMOTE.
2. DBSCAN Clustering (Unsupervised Learning):
Technique: Dimensionality reduction with PCA was performed to reduce the feature space, followed by DBSCAN clustering with optimized parameters (eps=0.6, min_samples=9).
Performance: DBSCAN achieved a Silhouette Score of 0.4176, successfully forming clusters that reflected some structure in the data. This performance was significantly better than earlier unsupervised methods (e.g., K-means).
Use Case: DBSCAN performed well, especially after parameter tuning, making it a suitable unsupervised learning technique for this dataset.

Final Results and Comparison:
Logistic Regression: With SMOTE applied, the model achieved an accuracy of 76% and showed strong performance in distinguishing between various mental health statuses, including underrepresented classes.
DBSCAN: Provided meaningful clusters with a Silhouette Score of 0.4176 after parameter tuning. This clustering method identified latent groupings within the data, outperforming previous unsupervised methods like K-means.

Overall, Logistic Regression remained the most effective model for this dataset, while DBSCAN offered a complementary view through unsupervised clustering.

## Kaggle Notebook:
You can find the project on Kaggle: [Kaggle Notebook](https://www.kaggle.com/code/edabelge/mental-health-classification)
