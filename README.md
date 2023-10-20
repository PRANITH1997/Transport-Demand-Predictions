# Transport-Demand-Predictions
In a recent machine learning project focused on predicting transport demand, I utilized a dataset from Kaggle containing 50,000 records. My primary objective was to forecast the total number of occupied seats on Mobiticket rides until they reached their destination. Here's a structured summary of the steps I undertook in the project:

Exploratory Data Analysis (EDA): Initially, I performed EDA to gain a comprehensive understanding of the dataset. I created various data visualizations, such as plots, to discern trends, patterns, and distributions within the data.

Data Preprocessing:   Following EDA, I engaged in data preprocessing. This included dealing with missing values, handling outliers, and addressing any data quality issues to ensure the dataset's readiness for modelling.



Data Scaling: To maintain consistency in the dataset, I applied data scaling techniques. Specifically, I employed both Min-Max scaling and Standard scaling to normalize the numerical features.



Data Encoding: Categorical data often needs to be converted into numerical format for machine learning models. I executed data encoding procedures to convert categorical features into numeric ones, ensuring the algorithms could work with them effectively.



Feature Selection: Recognizing the importance of feature selection, I identified and retained the most relevant features for the prediction task. This process optimizes model performance by reducing noise and computational load.



Model Selection: I implemented two machine learning models for the prediction task: Linear Regression and Random Forest.



Model Evaluation: After applying both models, I conducted a thorough model evaluation, which included assessing the models' performance using relevant metrics. In this case, the Random Forest model exhibited the lowest error, making it the more suitable choice for the transport demand prediction task.



This systematic approach ensured that the project was executed efficiently, with a strong emphasis on data preprocessing, feature selection, and model evaluation to deliver the best possible results in predicting Mobiticket's remaining occupied seats during rides.
