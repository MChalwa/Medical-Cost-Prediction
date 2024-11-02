# Medical Cost Prediction
### Project Overview
This project aims to predict individual medical costs using demographic and health-related data. By building a predictive model, the project seeks to understand which factors contribute most significantly to medical expenses and provide insights that can support decision-making in healthcare cost management.

### Data Source
The primary data used in this project is an 'insurance.csv' file containing detailed information about medical costs. Attached is the dataset.
[insurance.csv](https://github.com/user-attachments/files/17606179/insurance.csv).

The dataset used in this project includes features such as:
Age: Age of the individual.
Sex: Gender of the individual.
BMI: Body Mass Index, a measure of body fat based on height and weight.
Children: Number of children covered by health insurance.
Smoker: Smoking status of the individual.
Region: Geographic region where the individual resides.
Charges: Medical costs incurred by the individual (target variable).

### Project Workflow
The project consists of the following steps:

#### Exploratory Data Analysis (EDA):

Investigated distributions, relationships, and outliers in the dataset.
Visualized correlations to identify which features have the strongest association with medical charges.
#### Data Preprocessing:

Handled missing values and outliers where necessary.
Converted categorical variables (e.g., sex, region, smoker) into numerical representations using encoding techniques.
Scaled features to ensure balanced contribution to the model.

#### Modeling:

Built multiple regression models, including Linear Regression, Ridge, Lasso, and Random Forest Regressor.
Evaluated models using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
#### Model Evaluation & Interpretation:

Selected the best-performing model based on evaluation metrics.
Analyzed feature importance to understand the primary drivers of medical costs.

### Results
- The final model achieved an RMSE of 0.18, indicating its effectiveness in predicting medical costs.
- Key findings included the impact of smoking, BMI, and age on medical costs, with smokers and individuals with higher BMI generally incurring higher charges.

### Tools and Technologies
- Python for data processing, modeling, and evaluation.
- Pandas, NumPy for data manipulation.
- Scikit-Learn for building and evaluating machine learning models.
- Matplotlib and Seaborn for data visualization.
  
### Conclusion
This project demonstrates how data analysis and machine learning can help predict medical costs and provide valuable insights for healthcare decision-makers. The insights derived here could assist in identifying high-risk individuals, implementing preventative care, and managing healthcare resources more effectively.
