# Breast-Cancer

--------------

![image](https://github.com/user-attachments/assets/42aedfe6-f6a9-464a-8e0c-c1198160801d)


--------------

**Binary Classification Prediction for type of Breast Cancer**

--------

**About Dataset**

**Description:**

Breast cancer is the most common cancer amongst women in the world. It accounts for 25% of all cancer cases, and affected over 2.1 Million people in 2015 alone. It starts when cells in the breast begin to grow out of control. These cells usually form tumors that can be seen via X-ray or felt as lumps in the breast area.

The key challenges against it’s detection is how to classify tumors into malignant (cancerous) or benign(non cancerous). We ask you to complete the analysis of classifying these tumors using machine learning (with SVMs) and the Breast Cancer Wisconsin (Diagnostic) Dataset.

**Acknowledgements:**

This dataset has been referred from **Kaggle**.

**Objective:**

Understand the Dataset & cleanup (if required).
Build classification models to predict whether the cancer type is Malignant or Benign.
Also fine-tune the hyperparameters & compare the evaluation metrics of various classification algorithms.

--------
**Conclusion**

In this analysis, we built a k-Nearest Neighbors (k-NN) classifier to predict breast cancer diagnosis based on various features from a dataset. 
 
Data Preprocessing: 
 
We encoded the 'diagnosis' column (Malignant/Benign) into numerical values. 
We standardized the features to ensure they had similar scales, improving the performance of the k-NN algorithm. 
Model Building and Evaluation: 
 
We split the data into training and testing sets. 
 
We trained a k-NN classifier with an initial k value of 5. 
 
We evaluated the model using various metrics: 
 
Jaccard Index: Measures the similarity between the predicted and actual labels. 
Confusion Matrix: Provides a detailed breakdown of true positive, true negative, false positive, and false negative predictions. 
Classification Report: Displays precision, recall, F1-score, and support for each class. 
Cross-Validation: We used cross-validation to assess the model's performance on different subsets of the data, providing a more robust evaluation. 
Optimizing the Model: 
 
We explored different values of 'k' to find the optimal value that maximizes the F1 score. 
We visualized the F1 score for various 'k' values to identify the best performing 'k'. 
We utilized Grid Search to systematically search for the best 'k' value through cross-validation. 


Results: 
 
The analysis revealed that the k-NN classifier can effectively predict breast cancer diagnosis. 
The optimal value of 'k' was determined through the exploration of different 'k' values and Grid Search. 
The model's performance was evaluated using various metrics, providing insights into its accuracy and effectiveness. 
Overall, the k-NN model, along with the optimization techniques employed, demonstrates its potential for accurate breast cancer diagnosis prediction based on the provided features. However, it's crucial to consider that this is a specific analysis based on a particular dataset, and the model's generalization ability to other datasets may vary. Further investigation and refinement may be necessary to achieve higher accuracy and robustness in real-world applications.

--------
![image](https://github.com/user-attachments/assets/610623a2-4266-424a-9353-7426334fe18f)
--------
☘️LinkTree: https://linktr.ee/azimjaantech
