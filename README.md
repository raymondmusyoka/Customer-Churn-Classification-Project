# Customer-Churn-Classification-Project

**Enhancing Customer Retention through Churn Prediction: A Machine Learning Approach to Classification Models**

**Introduction**
Customer attrition is one of the biggest expenditures of any organization. Customer churn otherwise known as customer attrition or customer turnover is the percentage of customers that stopped using your company's product or service within a specified timeframe.
For instance, if you began the year with 500 customers but later ended with 480 customers, the percentage of customers that left would be 4%. If we could figure out why a customer leaves and when they leave with reasonable accuracy, it would immensely help the organization to strategize their retention initiatives manifold.

In this project, we aim to find the likelihood of a customer leaving the organization, the key indicators of churn as well as the retention strategies that can be implemented to avert this problem.

**Goal and Objectives**
**Goal**: 
I aim to predict customer churn using advanced data science techniques. This article shares the journey, methodology, and key findings of this project.
**Objectives**:
Identify the key factors that contribute to customer churn.
Develop a predictive model to forecast customer churn.
Propose actionable strategies to improve customer retention based on insights from the model.
## Stakeholders

**Internal**:
Marketing Team
Customer Service Team
Product Development Team
Senior Management
**External**:
Customers
Investors


**Data Understanding**
The data for this project is in a csv format. The following describes the columns present in the data.

Gender -- Whether the customer is a male or a female

SeniorCitizen -- Whether a customer is a senior citizen or not

Partner -- Whether the customer has a partner or not (Yes, No)

Dependents -- Whether the customer has dependents or not (Yes, No)

Tenure -- Number of months the customer has stayed with the company

Phone Service -- Whether the customer has a phone service or not (Yes, No)

MultipleLines -- Whether the customer has multiple lines or not

InternetService -- Customer's internet service provider (DSL, Fiber Optic, No)

OnlineSecurity -- Whether the customer has online security or not (Yes, No, No Internet)

OnlineBackup -- Whether the customer has online backup or not (Yes, No, No Internet)

DeviceProtection -- Whether the customer has device protection or not (Yes, No, No internet service)

TechSupport -- Whether the customer has tech support or not (Yes, No, No internet)

StreamingTV -- Whether the customer has streaming TV or not (Yes, No, No internet service)

StreamingMovies -- Whether the customer has streaming movies or not (Yes, No, No Internet service)

Contract -- The contract term of the customer (Month-to-Month, One year, Two year)

PaperlessBilling -- Whether the customer has paperless billing or not (Yes, No)

Payment Method -- The customer's payment method (Electronic check, mailed check, Bank transfer(automatic), Credit card(automatic))

MonthlyCharges -- The amount charged to the customer monthly

TotalCharges -- The total amount charged to the customer

Churn -- Whether the customer churned or not (Yes or No)

**Hypothesis Testing**

- Null Hypothesis (H0):

There is no significant relationship between the type of internet service (DSL, Fiber Optic, No) and customer churn.

- Alternative Hypothesis (H1):

There is a significant relationship between the type of internet service (DSL, Fiber Optic, No) and customer churn.

## Business Questions

1. What are the demographic characteristics of customers who are more likely to churn?

2. How does the tenure of a customer relate to their likelihood of churning?

3. What role do service-related factors (e.g., internet service, tech support) play in customer churn?

4. How do different contract types and payment methods affect customer churn?

5. What is the relationship between monthly charges and total charges and customer churn?

## Power BI Dashboard

[Power BI Link](https://app.powerbi.com/links/A5z8qLU0yR?ctid=4487b52f-f118-4830-b49d-3c298cb71075&pbi_source=linkShare)

Scope and Constraints
Scope:
Analysis of customer data from the past two years.
Development and validation of a churn prediction model.
Recommendation of retention strategies based on model insights.
Constraints:
Availability and quality of data.
Time and resource limitations.
Potential biases in the data that may affect model accuracy.
Usage
To run this analysis, follow these steps:

pip install -r requirements.txt
git clone https://github.com/raymondmusyoka/Customer-Churn-Classification-Project.git
cd Churn-Prediction-Enhancing-Retention-with-Machine-Learning
jupyter notebook main.ipynb

LinkedIn Article [LinkedIn Article](https://www.linkedin.com/feed/update/urn:li:activity:7216767859434090497/)
**Technologies Used**
- Python: Programming language used for data analysis and modeling.
- Pandas: For data manipulation and analysis.
- NumPy: For numerical computing.
- Scikit-learn: Machine learning library for model building.
- Matplotlib & Seaborn: Libraries for data visualization.
- Jupyter Notebook: Interactive computing environment used for developing the project.
- Power BI: Business analytics service used for visualizing and sharing insights from the data
**License**
This project is licensed under the MIT License - see the LICENSE file for details.

**Contact**
For any queries regarding this project, please contact:

Raymond Musyoka - raymutati@gmail.com

Thank you for visiting this repository, and I hope you find the Machine Learning Project useful!