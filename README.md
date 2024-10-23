# CodeAlpha_Data_preprocessing
# NAME: KUHELI SEN
# DOMAIN: DATA SCIENCE
# Life Expectancy Data Preprocessing
This project focuses on preprocessing the Life Expectancy dataset obtained from Kaggle, ensuring it is ready for machine learning models.

## Steps of Data Preprocessing:
1. Import Necessary Libraries: Essential Python libraries like pandas, numpy, and sklearn are imported for data manipulation and analysis.

2. Read Dataset: The dataset is loaded into a DataFrame using pandas for further processing.

3. Sanity Check of Data: Initial checks are performed to assess the structure and integrity of the dataset, including verifying the number of rows and columns.

4. Exploratory Data Analysis (EDA): A thorough analysis is conducted to understand data distributions, relationships between variables, and insights into the dataset.

5. Missing Value Treatments: Missing values are addressed by filling them with the median of their respective columns to maintain data consistency.

6. Outlier Treatments: Outliers are identified and handled to ensure they do not skew the analysis or model performance.

7. Duplicates & Garbage Value Treatments: Duplicate entries are removed, and any erroneous or garbage values are corrected to enhance data quality.

8. Normalization: Numeric features are normalized using MinMaxScaler, scaling all values to a range of 0 to 1 for uniformity in model training.

9. Encoding of Data: Categorical variables, such as "Country" and "Status," are transformed into numerical formats using one-hot encoding, making them suitable for machine learning algorithms.

10. Splitting Dataset into Train and Test Sets: The dataset is split into training (70%) and testing (30%) sets to allow for proper model training and evaluation.


