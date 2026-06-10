# 🧹 Complete Data Preprocessing Notebook

This notebook provides a **comprehensive, hands-on guide to data preprocessing** techniques in Python, covering the full pipeline from raw data cleaning to model-ready transformations. It is designed as a practical reference for data analysts, machine learning practitioners, and students preparing for interviews or projects.

## 📑 Contents

### 1. Handling Missing Values
- Detecting nulls with `isnull()` and `isna()`
- Strategies: `dropna()`, forward/backward fill, `fillna()`
- Advanced imputation: `SimpleImputer`, `KNNImputer`

### 2. Outlier Detection & Treatment
- Statistical methods: IQR, Z-score
- Machine learning approaches: Isolation Forest, DBSCAN
- Capping/Winsorization and transformations (log, square root, Box-Cox, Yeo-Johnson)

### 3. Train-Test-Validation Split
- Stratified splitting with `train_test_split`
- Ensuring balanced datasets for classification tasks

### 4. Feature Scaling
- Standardization (`StandardScaler`)
- Normalization (`MinMaxScaler`)
- Robust scaling for outlier-heavy data

### 5. Feature Encoding
- Ordinal, Label, and One-Hot Encoding
- Target and frequency encoding for high-cardinality features

### 6. Data Transformation
- Log, cube, Box-Cox, and Yeo-Johnson transformations
- Normality checks with Q-Q plots and KDE plots

### 7. Feature Selection
- Filter methods: variance threshold, correlation, ANOVA, chi-square
- Wrapper methods: forward/backward selection
- Regularization: Lasso, ElasticNet, Ridge
- Tree-based feature importance (Decision Trees, Random Forests)

### 8. Handling Imbalanced Data
- Oversampling: RandomOverSampler, SMOTE
- Undersampling: RandomUnderSampler

### 9. Numerical Encoding
- Binning continuous variables
- Binarization with thresholds

### 10. Pipelines & ColumnTransformer
- Building preprocessing pipelines with `Pipeline`
- Applying different transformations to numerical and categorical features
- Custom transformer (`OutlierCapper`) for robust outlier handling
- End-to-end pipeline with Decision Tree classifier
- Model persistence using `pickle`

## 🎯 Key Takeaways
- Covers **all major preprocessing steps** required before modeling.
- Demonstrates both **statistical and ML-based approaches** for cleaning and transforming data.
- Provides **visualizations** to understand distributions, outliers, and transformations.
- Ends with a **production-ready pipeline** that integrates preprocessing and modeling seamlessly.

---

👉 This notebook is ideal for anyone looking to **master preprocessing workflows** and build a strong foundation for machine learning projects.  
