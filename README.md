# Predicting Insurance Claims: A Machine Learning Approach for On the Road Car Insurance  

## Project Overview  

Insurance companies invest significant resources into optimizing pricing strategies and accurately estimating the likelihood of customer claims. In many countries, having car insurance is a legal requirement for driving on public roads, creating a vast market for insurance providers.   

On the Road Car Insurance has approached us to develop a predictive model to determine whether a customer will make a claim during their policy period. Given their limited expertise and infrastructure for deploying and monitoring machine learning models, they have requested that we focus on identifying the single feature that results in the best-performing model, measured by accuracy. This approach will allow them to implement a simple yet effective model in production.  

## Dataset Description  

The dataset provided for this project is a CSV file named `car_insurance.csv`. It contains various attributes about clients that may influence their likelihood of making an insurance claim.  

### Column Descriptions  

| Column Name          | Description                                               |  
|---------------------|-----------------------------------------------------------|  
| `id`                | Unique client identifier                                  |  
| `age`               | Client's age (0: 16-25, 1: 26-39, 2: 40-64, 3: 65+)     |  
| `gender`            | Client's gender (0: Female, 1: Male)                     |  
| `driving_experience`| Years of driving experience (0: 0-9, 1: 10-19, 2: 20-29, 3: 30+) |  
| `education`         | Client's education level (0: No education, 1: High school, 2: University) |  
| `income`            | Client's income level (0: Poverty, 1: Working class, 2: Middle class, 3: Upper class) |  
| `credit_score`      | Client's credit score (between 0 and 1)                  |  
| `vehicle_ownership` | Vehicle ownership status (0: Paying off finance, 1: Owns vehicle) |  
| `vehicle_year`      | Vehicle registration year (0: Before 2015, 1: 2015 or later) |  
| `married`           | Marital status (0: Not married, 1: Married)              |  
| `children`          | Number of children                                       |  
| `postal_code`       | Client's postal code                                     |  
| `annual_mileage`    | Miles driven annually                                     |  
| `vehicle_type`      | Type of car (0: Sedan, 1: Sports car)                    |  
| `speeding_violations`| Total speeding violations                                   |  
| `duis`              | Times caught driving under the influence                  |  
| `past_accidents`    | Previous accidents involved                               |  
| `outcome`           | Target variable indicating claims (0: No claim, 1: Claim) |  

## Objectives  

1. **Data Preprocessing**: Clean and preprocess the dataset, handling any missing values and encoding categorical variables.  
2. **Model Development**: Build a classification model to predict whether a customer will make a claim based on the provided features.  
3. **Feature Importance Analysis**: Identify the single most important feature that contributes to the model's predictive performance.  

## Methodology  

1. **Data Exploration**: Analyze the dataset to understand the distribution of features and the target variable.  
2. **Data Preprocessing**:   
   - Handle missing values.  
   - Encode categorical variables (e.g., gender) using techniques such as one-hot encoding.  
3. **Model Selection**: Implement various classification algorithms (e.g., Logistic Regression, Decision Trees, Random Forest) to predict claim likelihood.  
4. **Model Evaluation**: Use accuracy, precision, recall, and F1-score to evaluate model performance.  
5. **Feature Importance**: Utilize techniques such as feature permutation importance or model coefficients to identify the most significant feature affecting claim prediction.  

## Expected Outcomes  

- A predictive model that accurately forecasts the likelihood of a customer making a claim during the policy period.  
- Identification of the single most important feature that impacts the model's accuracy, allowing On the Road Car Insurance to deploy a straightforward model in production.  
