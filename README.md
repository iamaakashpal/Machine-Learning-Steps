
# MACHINE LEARNING STEPS

# 1. Exploratory Data Analysis

## **`Youtube Link:`** https://www.youtube.com/playlistlist=PLZoTAELRMXVPQyArDHyQVjQxjj_YmEuO9

### **`STEP 1:`**  EDA { Exploratory Data Analysis }

    (i) Check Numerical Features.

    (ii) Check Categorial Feature.

    (iii) Check Missing Values.

    (iV) Check Outliers.

    (v) Data Cleaning.

# 2. Feature Engineering

## **`Youtube Link:`** https://www.youtube.com/playlist?list=PLZoTAELRMXVPwYGE2PXD3x0bfKnR0cJjN

## **`STEP 1:`** Handling the Missing Values

- ### For Numerical Value :

    `(i)` Mean / Median

    `(ii)` Random Sample Imputation

    `(iii)` Capturing NAN Value with a new feature.

    `(iv)` End of Distribution Imputation.

    `(v)` Arbitrary Value Imputation (Min / Max) value.

- ### For Categorical Value :

    `(i)` Mode (Frequent Category Imputation).

    `(ii)` Capturing NAN Value with a new feature.

## **`STEP 2:`** Handling Imbalanced Dataset

  `(i)` Under Sampling ( Best for small dataset ).

  `(ii)` Over Sampling ( Best for large dataset ).

## **`STEP 3:`** Treating the Outliers

`(i)` IQR.

## **`STEP 4:`** Scaling down the Data.

`(i)` Standardization.

`(ii)` Normalization.

`(iii)` Robust Scaler (Scaling To Median And Quantiles).

`(iV)` Gaussian Transformation.
        
    - Logarithmic Transformation.
    - Reciprocal Transformation
    - Square Root Transformation.
    - Exponential Transformation.
    - Box Cox Transformation.

## **`STEP 5:`**  Converting the Categorical Features into Numerical Features.

`(i)` One Hot Encoding {Nominal}.

`(ii)` One Hot Encoding with many category in a feature {Nominal}.

`(iii)` Count or Frequency Encoding {Nominal}.

`(iv)` Mean Encoding {Nominal}.

`(v)` Probability Ratio Encoding {Nominal}.

`(vi)` Ordinal Number Encoding {Ordinal}.

`(vii)` Target Guided {Ordinal Encoding}.

# 3. Feature Selection

`(i)` Variance Threshold ( Unsupervised )

`(ii)` Correlation

`(iii)` Chi-Square

`(iv)` Genetic Algorithm

`(v)` K Neighbour

`(vi)` Feature Importance {Extra Tree Classifier}

# 4. Model Building

# 1. Supervised Machine Learning

## **`STEP 1:`** Regression

    i. Linear Regression -- Handle Outlier(Y) -- Required Feature Transformation(Y).

    ii. Ridge and Lasso Regression -- Handle Outlier(Y) -- Required Feature Transformation(Y).
    
    iii. Decision Tree Regressor -- Handle Outlier(N)
    
    iv. Random Forest Regressor -- Handle Outlier(N) -- Required Feature Transformation(N).
    
    v. XGBoost Regressor -- Handle Outlier(N)
    
    vi. AdaBoost Regressor -- 
    
    vii. ANN --        Required Feature Transformation(Y)
    
    viii. RNN --        Required Feature Transformation(Y)
    
    ix. KNN -- Handle Outlier(Y) -- Required Feature Transformation(Y)
    
    x. SVM -- Handle Outlier(N)
    
    xi. Gradient Boosting -- Handle Outlier(N)

## **`STEP 2:`** Classification

    i. Logistic Regression -- Handle Outlier(Y) -- Required Feature Transformation(Y)

    ii. Decision Tree Classifier -- Handle Outlier(N)

    iii. Random Forest Classifier -- Handle Outlier(N) -- Required Feature Transformation(N).

    iv. XGBoost Classifier -- Handle Outlier(N)

    v. AdaBoost Classifier --

    vi. ANN --      -- Required Feature Transformation(Y)

    vii. CNN --      -- Required Feature Transformation(Y)

    viii. Naive Baye's Classifier -- Handle Outlier(N) -- 

    ix. KNN -- Handle Outlier(Y) -- Required Feature Transformation(Y)

    x. SVM -- Handle Outlier(N)

    xi. Gradient Boosting -- Handle Outlier(N)


# 2. Unsupervised Machine Learning

## **`STEP 1:`** Clustering

## **`STEP 2:`** Dimensionality Reduction

    i. KMeans -- Handle Outlier(Y) -- Required Feature Transformation(Y)

    ii. DBScan -- Handle Outlier(Y)
    
    iii. Hierical Clustering -- Handle Outlier(Y) -- Required Feature Transformation(Y)
    
    iv. KNN Clustering
    
    v. PCA -- Handle Outlier(Y)
    
    vi. LDA
    
    vii. Neural Network -- Handle Outlier(Y)

# 5. Model Deployment
