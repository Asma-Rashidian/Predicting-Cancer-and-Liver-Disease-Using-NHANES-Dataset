# Project Title: Predicting Cancer and Liver Disease Using NHANES Dataset

## Project Description
The goal of this project is to build regression models to predict the occurrence of cancer and liver disease using the National Health and Nutrition Examination Survey (NHANES) data. This dataset includes demographic, socioeconomic, dietary, and health-related information collected from U.S. adults and children, which are essential for assessing health and nutrition status.

## Dataset
The dataset used is the NHANES dataset, which encompasses a variety of health-related questions and includes medical, dental, and physiological measurements as well as laboratory tests. Features within this dataset are encrypted but can be understood through the Column Definitions file provided.

### Understanding the Dataset
- **Demographics, Diet, Examination, Labs**: Each category provides a set of data that contributes differently to the overall analysis.
- **Data Preprocessing**: This involves handling missing values, outliers, and inconsistencies. Columns with over 8% missing values should be considered for removal. Special codes such as 7 and 9, indicating unusable responses, should be appropriately handled.

## Methodology

### 1. Feature Selection
- **Correlation Analysis**: Calculate the correlation coefficient between each pair of attributes to identify relationships.
- **Heat Map Visualization**: Use a heat map to display the correlations between pairs of attributes, focusing on the 100 attributes with the highest absolute correlations.

### 2. Dimension Reduction
- **PCA (Principal Component Analysis)**: Reduce the dimensionality of the dataset based on the features identified in the correlation analysis.
- **Isometric Mapping**: It is a dimensionality reduction technique that aims to preserve the geodesic distances between data points in a lower-dimensional space.

### 3. Regression Models
- Develop separate regression models to predict the incidence of liver disease (MCQ160L) and cancer (MCQ220). The models should interpret '1' as the presence of disease and '2' as the absence.

### 4. Model Evaluation
- Evaluate the performance of the regression models using metrics such as accuracy and confusion matrix. Perform this evaluation separately for models derived from PCA and the alternative dimension reduction method.

## Results and Conclusion
- **Comparison**: Compare the effectiveness of PCA and the alternative method in feature selection and dimensionality reduction.
- **Impact Assessment**: Discuss any negative impacts or challenges encountered during the feature selection or dimension reduction phases.
- **Performance Metrics**: Compare different features such as accuracy and speed between the two dimensionality reduction models.

## Additional Analysis
- Encourage the use of additional analytical methods or creative initiatives to enhance the project's outcomes.

## How to Contribute
Contributors are welcome to enhance the models, propose new methods for analysis, or improve the data preprocessing steps. Please ensure you follow the provided coding and commit standards.

