# Sampling
**Sampling Assignment**

**About the Dataset:**
The dataset comprises 772 entries with two classes: class 0 and class 1. However, it is imbalanced, with 763 entries for class 0 and only 9 for class 1. To address this imbalance, SMOTE (Synthetic Minority Oversampling Technique) is employed, which involves generating synthetic samples for the minority class by considering the k-nearest neighbors of each point.

**Sample Size Calculation:**
The sample size (n) is calculated using the formula: n = Z^2 * p * (1-p) / E^2, where n is the sample size, p is the standard deviation, Z is the z-score, and E is the margin of error.

**Sampling Techniques Used:**
1. **Simple Random Sampling**
2. **Systematic Random Sampling**
3. **Cluster Sampling**
4. **Bootstrap Sampling**

**Models Used for Evaluation:**
1. Logistic Regression (Model 1)
2. Support Vector Classifier (Model 2)
3. XGBoost Classifier (Model 3)
4. Random Forest (Model 4)
5. Gaussian Naive Bayes (Model 5)

**Accuracy Scores:**
| Sample/Model | Logistic Regression | SVC | XGBoost | Random Forest | Gaussian Naive Bayes |
|--------------|---------------------|-----|---------|---------------|-----------------------|
| Simple Random | 0.87                | 0.93| 0.94    | 0.99          | 0.78                  |
| Systematic Random | 0.89             | 0.94| 0.97    | 0.97          | 0.81                  |
| Cluster Sampling | 0.93              | 0.97| 0.99    | 1 (Overfit)    | 0.83                  |
| Bootstrap Sampling | 0.95            | 0.95| 0.96    | 1 (Overfit)    | 0.87                  |

**Result:**
Among the sampling techniques, Bootstrap Sampling proves to be the most effective in this scenario.


Saanvi Sharma (102103699)
3CO25
