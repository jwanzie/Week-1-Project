## WEEK 1 PROJECT: PREDICTING CUSTOMER CHURN.
#### Step 1; Business Understanding
Figure out the goals of the business. In this case the goal is customer retention. By predicting customer churn the business is able to find reasons as to why customers are leaving and find solutions to mitigate that. With this kind of problem machine learning is the best way to approach it.
#### Step 2; Data Understanding
First, determine your data sources. The company already has past data that contains customers who’ve churned. Familiarize yourself with the given data i.e. shape of data, column headers, data types etc.. Make sure you figure out the relevance of the data needed. 
#### Step 3; Data Preprocessing
After acquiring dataset needed from the business or other resources such as kaggle, import all crucial python libraries required for data preprocessing in machine learning like NumPy, Pandas, Matplotlib. Import the dataset that you have gathered for the ML project. Perform EDA using pandas profiling or ydata profiling, this will explore and visualize your datasets to help you identify patterns and uncover insights. In this stage you will also identify and handle missing values and make sure the data types are consistent. Import customer churn from given dataset, check the shape of this data, convert string values to numerical so that model can read it and do a visualization of customer churn. Visualize churn rate by other variables e.g. gender, payment method etc. Encode categorical data i.e. convert categorical values to numerical values. Perform feature scaling to standardize independent variables so as to optimize predictions. Split the dataset into training set (70%) and test set (30%). 
#### Step 4; Predictive Modeling
First, import machine learning classification libraries and train model. Use fit method on model in order to fit model in training dataset. The model will find correlation within the parameters and be able to predict churn values for new and unseen data. Then find accuracy using accuracy_score method. Repeat this for all selected models.
#### Step 5; Model Evaluation
Compare trained models according to accuracy by creating panda dataframe to figure out what is the best model to be used. 

Dataset used: https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data