# Telecom-Customer-Churn-Analysis-and-Prediction-Using-Logistic-Regression

📌 Introduction

             This project focuses on analyzing customer behaviour and predicting customer churn in the telecom industry. Customer churn occurs when a customer stops using a company's services.
             The project uses Python libraries for data cleaning, exploratory data analysis, data visualization and machine learning. Logistic Regression is used to predict whether a customer is likely to continue or discontinue the service.
             The main objective is to identify important factors associated with customer churn, predict high-risk customers and help businesses improve customer retention.

🎯 Project Objectives

           Understand customer behaviour and churn patterns.
           Identify important factors associated with customer churn.
           Analyze customer demographics, contracts and payment methods.
           Visualize customer churn patterns.
           Predict customer churn using Logistic Regression.
           Provide business insights to improve customer retention.

📂 Dataset Description

           Dataset: Telco Customer Churn
           Source: Kaggle
           Total Records: 7,043
           Total Columns: 21
           File Format: CSV

🛠️ Tools and Technologies

                    Tool / Library                       Purpose
                       Python                           Programming
                       Pandas                      Data cleaning and analysis
                       NumPy                           Numerical operations
                    Matplotlib                        Data visualization
                      Seaborn                      Statistical visualization
                  Scikit-learn                Machine learning and model evaluation
                Jupyter Notebook                   Development environment

🔄 Project Workflow

1. Data Collection

             Collected the Telco Customer Churn dataset.
             Imported the CSV file using Pandas.
             Examined dataset structure, dimensions and data types.
             Generated descriptive statistics.

2. Data Cleaning

            Checked missing values.
            Checked duplicate customer IDs.
            Examined unique values.
            Inspected column data types.

3. Exploratory Data Analysis (EDA)

            Calculated total customer count.
            Identified churned and retained customers.
            Calculated the overall churn rate.
            Analyzed average monthly charges and customer tenure.
            Analyzed customer churn based on gender.
            Identified churn rates across different contract types.
            Analyzed churn based on internet services.

4. Data Visualization

           Created various charts using Matplotlib and Seaborn:

               Pie Chart – Customer churn distribution.
               Count Plot – Customer churn by gender.
               Bar Chart – Churn rate by contract type.
               Box Plot – Monthly charges vs customer churn.
               Stacked Bar Chart – Churn by internet service.
               Horizontal Count Plot – Churn by payment method.
               Heatmap – Confusion matrix.

5. Data Preprocessing

              Removed the customerID column.
              Defined independent and dependent variables.
              Converted the target variable into numerical values.
              Performed One-Hot Encoding.
              Split the dataset into 80% training and 20% testing data.
              Applied feature scaling using StandardScaler.

6. Machine Learning Model Training

              Implemented Logistic Regression to predict customer churn.

                   0 – Customer is likely to stay.
                   1 – Customer is likely to leave.

              The model was trained using historical customer data and evaluated using the testing dataset.

7. Model Evaluation

              The Logistic Regression model achieved the following results:

              Evaluation Metric                   Result

               Accuracy                           77.64%

               Precision                          59.31%

                Recall                            50.27%

               F1-score                           54.41%

             True Positives                         188

             True Negatives                         906

             False Positives                        129

             False Negatives                         186

8. Customer Churn Prediction

             The trained model predicts whether a customer is likely to leave or continue the service and calculates their churn probability.

             Sample prediction from the testing dataset:

             Prediction: Customer will likely stay.

             Churn Probability: 0.24%

📊 Key Findings

                     KPI                     Result

                 Total Customers              7,043

                Retained Customers            5,174

                Churned Customers             1,869

               Customer Churn Rate            26.54%

              Customer Retention Rate         73.46%

              Average Monthly Charges          64.76

              Average Customer Tenure        32.37 months

Business Insights

             Month-to-month contract customers have the highest churn rate of 42.71%.
             One-year contract customers have a churn rate of 11.27%.
             Two-year contract customers have the lowest churn rate of 2.83%.
             Fiber optic internet customers have a churn rate of 41.89%.
             Customers with longer contract commitments show lower churn rates.

💡 Business Recommendations

            Provide special offers to high-risk customers.
            Encourage customers to choose long-term contracts.
            Improve internet service quality and customer support.
            Introduce personalized discounts and retention plans.
            Monitor customer churn regularly.

🚀 Future Enhancements

           Improve data preprocessing and feature engineering.
           Handle class imbalance.
           Improve model recall and F1-score.
           Compare Logistic Regression with other machine learning algorithms.
           Develop an interactive customer churn prediction dashboard.

📝 Conclusion

          This project demonstrates how Python, data analytics and machine learning can be used to solve a real-world business problem.
          The Logistic Regression model achieved an accuracy of 77.64% and helps identify customers who are likely to discontinue telecom services. However, there is scope to improve its ability to detect churned customers.
          The insights obtained from this project can help telecom companies understand customer behaviour, improve customer retention and reduce potential revenue loss.
          Overall, this project highlights the importance of data-driven decision-making in business analytics.
