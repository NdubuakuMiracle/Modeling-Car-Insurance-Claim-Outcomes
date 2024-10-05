# Predicting Insurance Claims: A Machine Learning Approach for On the Road Car Insurance  

## Project Overview  

Insurance companies invest significant resources into optimizing pricing strategies and accurately estimating the likelihood of customer claims. In many countries, having car insurance is a legal requirement for driving on public roads, creating a vast market for insurance providers.   

On the Road Car Insurance has approached us to develop a predictive model to determine whether a customer will make a claim during their policy period. Given their limited expertise and infrastructure for deploying and monitoring machine learning models, they have requested that we focus on identifying the single feature that results in the best-performing model, measured by accuracy. This approach will allow them to implement a simple yet effective model in production.  

## Dataset Description  

The dataset provided for this project is named `car_insurance.csv`. Below is a table detailing the column names and their descriptions:  

| Column Name         | Description                                               |  
|---------------------|-----------------------------------------------------------|  
| `customer_id`       | Unique identifier for each customer                       |  
| `age`               | Age of the customer                                       |  
| `gender`            | Gender of the customer (male/female)                     |  
| `car_age`           | Age of the car                                           |  
| `car_value`         | Estimated value of the car                                |  
| `annual_mileage`    | Estimated annual mileage driven by the customer           |  
| `previous_claims`   | Number of previous claims made by the customer            |  
| `policy_duration`    | Duration of the insurance policy in years                 |  
| `claim`             | Target variable indicating whether a claim was made (1=yes, 0=no) |  

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
