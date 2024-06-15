# Income Classification Based on Census Data

In a time of increasing socio-economic disparities and limited government resources, accurately identifying individuals who require assistance is crucial for effective policy making. This study constructs predictive models capable of accurately categorizing individuals into income brackets, thereby uncovering valuable socio-economic insights and aiding in informed decision-making processes.

## Unique concepts used:
### SMOTE - Synthetic Minority Over-sampling Technique:
SMOTE is a technique used in machine learning to address the class imbalance problem in binary and multiclass classification. Class imbalance occurs when one class in the dataset has significantly fewer instances than the other class(es), leading to biased model training and potentially poor performance on the minority class.

SMOTE works by generating synthetic examples of the minority class, thereby balancing the class distribution. It does this by creating synthetic samples that are interpolations of existing minority class instances.

### SHAP - SHapley Additive exPlanations:
SHAP values are based on cooperative game theory and Shapley values, and they aim to fairly distribute the contribution of each feature to the prediction of a specific instance. Basically SHAP helps to determine how important each feature in the dataset is to the target variable which in this case is Income.

## Skills and Topics Covered

- **Data Cleaning and Preprocessing**: Handling missing values, encoding categorical features, and scaling numerical features.
- **Exploratory Data Analysis (EDA)**: Visualizing data distributions, relationships, and outliers.
- **Feature Selection**: Identifying and selecting relevant features for the model.
- **Modeling**: Implementing and evaluating various machine learning models, including Logistic Regression, Naive Bayes, K-Nearest Neighbors, and Neural Networks.
- **Model Evaluation**: Using metrics such as accuracy, precision, recall, F1 score, and ROC AUC score.
- **Imbalanced Data Handling**: Applying techniques like SMOTE to handle class imbalance.

## Key Learnings

- **Data Quality Improvement**: Techniques for data cleaning and preprocessing to ensure high data quality.
- **Model Selection**: Criteria for selecting appropriate models based on the problem requirements.
- **Performance Optimization**: Strategies to optimize model performance and handle overfitting.
- **Practical Applications**: Real-world applications of machine learning models in socio-economic policy-making and resource allocation.

## Results

The project implemented multiple raw coded models (built without using Scikit-learn library) including Logistic Regression, Discrete Naive Bayes, Decision Tree and Neural Network, with Naive Bayes achieving the highest accuracy of 79%. The results contribute to a better understanding of the socio-economic determinants of income levels and can assist government agencies in resource allocation.
