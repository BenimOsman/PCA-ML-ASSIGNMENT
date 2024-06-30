**Dataset:**
Dataset Used: Breast Cancer dataset from scikit-learn

**Implementation:**
1. Data Loading and Preprocessing:
Loaded the Breast Cancer dataset into a Pandas DataFrame. Handled missing values and standardized the dataset to scale the features.

2. Custom Implementation of PCA:
Implemented PCA from scratch using Python, NumPy, and Matplotlib. Visualized the results using heatmaps and scatter plots.

3. PCA Using scikit-learn:
Compared the results with the custom implementation to ensure accuracy and consistency.

4. Explained Variance and Selection of Principal Components:
Selected the appropriate number of principal components based on the cumulative explained variance.

5. Reconstruction and Evaluation:
Reconstructed the original dataset using the selected principal components. 

6. Dimensionality Reduction and Classification:
Used logistic regression to compare classification accuracy with and without dimensionality reduction. Evaluated the impact of PCA on the classification performance using metrics like accuracy.

**Key Findings:**
1. PCA effectively reduced the dimensionality of the dataset while preserving most of the variance.
2. Dimensionality reduction through PCA improved computational efficiency without significantly affecting the classification accuracy.
3. The reconstruction error was minimal, indicating that the selected principal components captured the essential information in the dataset.