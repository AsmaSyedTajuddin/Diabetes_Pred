# Diabetes_Pred

![NL1_blog_2](https://user-images.githubusercontent.com/100385953/179560314-a60608f4-11a7-4ddf-8848-ccaf5bfc1685.png)

The following features have been provided to help us predict whether a person is diabetic or not:
Pregnancies: Number of times pregnant
Glucose: Plasma glucose concentration over 2 hours in an oral glucose tolerance test
Blood Pressure: Diastolic blood pressure (mm Hg)
Skin Thickness: Triceps skin fold thickness (mm)
Insulin: 2-Hour serum insulin (mu U/ml)
BMI: Body mass index (weight in kg/(height in m)2)
Diabetes Pedigree Function: Diabetes pedigree function (a function which scores likelihood of diabetes based on family history)
Age: Age (years)
Outcome: Class variable (0 if non-diabetic, 1 if diabetic)
Ø Step 1: Data gathering & Importing Libraries
All the standard libraries like numpy, pandas, matplotlib and seaborn are imported in this step. We use numpy for linear algebra operations, pandas for using data frames, matplotlib and seaborn for plotting graphs. The dataset is imported using the pandas command read_csv ().

Ø Step 2: Process the data for analysis
Check the missing values
Check Corrupted values, such as invalid entries

1. There are a total of 768 records and 9 features in the dataset.
2. Each feature can be either of integer or float data type.
3. Some features like Glucose, Blood pressure, Insulin, BMI have zero values which represent missing data.
4. There are zero NaN values in the dataset.
5. In the outcome column, 1 represents diabetes positive and 0 represents diabetes negative
Ø Step 3: Data Visualizations
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

Ø Step 4: Data Preprocessing

In this dataset, the missing values are represented by zero values that need to be replaced. The zero values are replaced by NaN so that missing values can easily be imputed using the fillna() command.
Ø Step 5: Data Modelling & Model Evolution

o Logistic Regression
• Logistic regression is a supervised learning classification algorithm used to predict the probability of a target variable. The nature of target or dependent variable is dichotomous, which means there would be only two possible classes.
In simple words, the dependent variable is binary in nature having data coded as either 1 (stands for success/yes) or 0 (stands for failure/no).
