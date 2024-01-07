<a href="https://github.com/drshahizan/Python-big-data/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/Python-big-data" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/Python-big-data/network/members"><img src="https://img.shields.io/github/forks/drshahizan/Python-big-data" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/Python-big-data/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/Python-big-data" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/Python-big-data/issues"><img src="https://img.shields.io/github/issues/drshahizan/Python-big-data" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/Python-big-data/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/Python-big-data?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2FPython-big-data&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

Don't forget to hit the :star: if you like this repo.

# Assignment 4: Feature_Engineering

### Group Name: Ayam Rendang
### Group Members

| Name          | Matric Number  | 
| ------------- | -------------- | 
| NURUL WAHIEDA BINTI MUHAMMAD FARID SELLEKUMAR   | (MCS231022)     |
|THANEATHARRAN A/L SANTHARASEKARAN    | (MSC232006)       | 
| RANJEET A/L THIAGARAJAN   | (MCS231015)         | 
| LINGGESH A/L TAMILMANI   | (MCS232005)         | 

# Dataset: Predict Diabetes
This dataset is originally from the National Institute of Diabetes and Digestive and KidneyDiseases. The objective of the dataset is to diagnostically predict whether a patient has diabetes,based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

## Conclusion

### Key Findings:

1.Dataset Overview:
  - The diabetes dataset comprises information on health metrics and patient details, including features like 'Glucose,' 'BMI,' and 'Age.'
    
2.Exploratory Data Analysis (EDA):
  - Checked for missing values: Identified that 'Glucose' had missing values, requiring further attention.
  - Examined data types and statistics: Observed that 'Glucose' exhibited right-skewness in its distribution.

3.Feature Selection:
  - Utilized correlation analysis: Found that 'BMI' and 'Age' are moderately correlated with the target variable.
  - Domain knowledge: Recognized the importance of 'Glucose' in diabetes-related analyses.

4.Feature Preprocessing:
  - Handled missing values: Imputed missing 'Glucose' values using the mean or median.
  - Addressed outliers: Detected and treated outliers in 'BMI' using appropriate methods.

5.Feature Transformation:
  - Applied logarithmic transformations: Addressed skewness in 'Glucose' by applying a logarithmic transformation.

6.Feature Creation:
  - Introduced a new feature, 'Avg_Age_Pregnancies':
  - Computed as the average of 'Age' and 'Pregnancies' for each patient.

7.Visualization:
  - Created visualizations:
  - Box plot for 'BMI' after outlier treatment.
  - Distribution plot for 'Glucose' before and after logarithmic transformation.

## Insights:
Imputing missing values and treating outliers improved the overall quality of the dataset.
Logarithmic transformation on 'Glucose' effectively addressed its right-skewed distribution.
The newly created feature, 'Avg_Age_Pregnancies,' offers a combined metric capturing both age and pregnancy history.

## Future Steps:
Further exploration could involve additional feature engineering techniques tailored to the characteristics of specific variables.
Continuous monitoring and refinement of feature engineering strategies based on model performance and domain insights.
By systematically addressing challenges and enhancing features, we've prepared the diabetes dataset for more robust and meaningful machine learning analyses.
