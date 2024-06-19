# Customer-Churn-Prediction


Introduction:-

Customer churn, the loss of subscribers or customers to a competitor, is a significant challenge for businesses across various industries. Predicting churn allows companies to proactively identify customers at risk of leaving and implement targeted retention strategies. This project aims to develop a machine learning model capable of accurately predicting customer churn. We will explore various feature engineering techniques, evaluate different classification algorithms, and ultimately build a model that can effectively distinguish between churning and loyal customers. By deploying this model, businesses can gain valuable insights into customer behavior and take preventative actions to minimize churn and maximize customer lifetime value.

Dataset Explanation:-

The dataset used in this project includes the following features:

age: The age of the customer.
tenure: The duration (in years) the customer has been with the company.
nationality: The nationality of the customer.
balance: The current account balance of the customer.
salary: The annual salary of the customer.
score: A customer credit score.
card: The type of card the customer has.
gender: The gender of the customer.
active: Whether the customer is currently active or not.
products: The number of products the customer has with the company.
Age bins: A new feature created through feature engineering, which categorizes the customers into different age groups.


Steps performed:-

1)Analysing dataset
2)Data cleaning and feature selection
3)Data encoding and Data transformation
4)Exploratory data analysis
5)Finding best machine learning model for prediction
6)Model Evaluation

Data Exploration and Visualization:-

Our exploration of the data yielded valuable insights into customer behavior and churn patterns. Key findings include:

->Age Distribution: The customer base spans various age groups, with a concentration in the middle-aged demographic.
->Tenure and Churn: Customers with longer tenures exhibit a lower tendency to churn, highlighting the importance of building customer loyalty over time.
->Balance and Churn: A correlation exists between higher account balances and lower churn rates, suggesting financial stability as a factor influencing customer retention.
->Gender and Churn: A slight disparity in churn rate between genders exists, potentially warranting consideration in customer retention strategies.
->Active vs. Inactive Customers: Analysis reveals a significant difference in churn rates between active and inactive customers, emphasizing the importance of customer engagement.

These findings provide a deeper understanding of customer churn and can be leveraged to develop effective retention strategies.

Data Preprocessing and Resampling:-

To prepare the data for machine learning model training, we implemented several key steps:

Missing Value Handling: We addressed missing values within the dataset to ensure the integrity of the data used for model training.
Categorical Feature Encoding: Categorical variables were appropriately encoded to make them interpretable by machine learning algorithms.
Numerical Feature Scaling: Numerical features were scaled to a common range to prevent them from unduly influencing the models.
Imbalanced Class Handling: To address potential biases due to imbalanced classes in the target variable (churn), we employed a suitable technique to achieve a more balanced representation.

These preprocessing steps ensured the data was in a suitable format for optimal machine learning model performance.

Machine Learning Models:-

To predict customer churn, we trained several machine learning models, including:

Logistic Regression
K Nearest Neighbors
Random Forest
GradientBoostingClassifier

Each model was evaluated using various performance metrics, such as accuracy, precision, recall, and F1-score, to ensure the most effective model for predicting customer churn.

Results and Insights:-

The random forest model provided valuable insights into the key factors influencing customer churn. Additionally, the model performance metrics indicated that the Random Forest model achieved the highest accuracy(86%) and F1-score in predicting customer churn.

Future Recommendations:-


The future of customer churn analysis lies in leveraging advanced machine learning techniques like deep learning and anomaly detection, incorporating external data sources like social media and economic indicators, and focusing on the customer journey through micro-moment analysis and customer lifetime value. Additionally, explainable AI (XAI) will be crucial for understanding complex models, while real-time churn prediction with immediate interventions will enable businesses to proactively retain their customer base.Organizations can create focused plans to increase customer retention and lower churn rates by utilizing the insights from data exploration, feature engineering, and machine learning models.

