# Random-Forest-Regression

Random Forest Regression is an ensemble machine learning algorithm used for predicting continuous values (regression tasks). It builds multiple decision trees during training and outputs the average of their predictions, improving accuracy and reducing overfitting.

Hello ! This is Swapna and here I created a Random Forest Regression on **Boston Housing dataset**.

Let's see.....

# Random Forest Regression on Boston Housing 

![istockphoto-675258098-2048x2048](https://github.com/user-attachments/assets/b9c98942-5856-4544-b1ba-5c3d5283725f)



The Boston Housing Dataset is a classic dataset used in regression analysis and machine learning. It contains information collected by the U.S. Census Service about housing in the Boston, Massachusetts area.



**👉Key Details:**

↪Purpose: Predict the median value of owner-occupied homes (in $1000s) based on various features.

↪Number of instances: 506

↪Number of features: 13 (independent variables) + 1 target variable


**👉Features include:**


↪CRIM-	Per capita crime rate by town

↪ZN-	Proportion of residential land zoned for lots over 25,000 sq.ft.

↪INDUS-	Proportion of non-retail business acres per town

↪CHAS-	Charles River dummy variable (1 if tract bounds river; 0 otherwise)

↪NOX-	Nitric oxides concentration (parts per 10 million)

↪RM-	Average number of rooms per dwelling

↪AGE-	Proportion of owner-occupied units built prior to 1940

↪DIS-	Weighted distances to five Boston employment centers

↪RAD-	Index of accessibility to radial highways

↪TAX-	Full-value property tax rate per $10,000

↪PTRATIO-	Pupil-teacher ratio by town

↪B-  1000(Bk−0.63)^2, where Bk is the proportion of Black residents by town	

↪LSTAT-	% lower status of the population

↪MEDV- 	Median value of owner-occupied homes in $1000s (Target variable)


**👉 Goal of this Project:**


To develop a predictive model using the Boston Housing Dataset that accurately estimates the median value of homes based on various socio-economic and environmental factors, while also uncovering key insights into which features most significantly influence housing prices.

↪Enable data-driven decision making for real estate pricing.

↪Help understand urban factors (crime, education, pollution) affecting property value.

↪Provide a base for regression modeling and feature importance analysis.


**👉Key Outcomes:**

This project focused on analyzing the Boston Housing Dataset to build an effective regression model for predicting housing prices and uncovering the key factors influencing them. Below are the primary outcomes achieved:

↪Accurate Prediction of Home Prices-  A predictive model was developed using regression algorithms, such as Linear Regression and Random Forest, to estimate the median value of owner-occupied homes (MEDV). The model demonstrated solid performance with evaluation metrics like R² score and Mean Squared Error, confirming its reliability.

↪Identification of Influential Factors-  The analysis revealed that several features had a significant impact on housing prices:

**RM (average number of rooms)** was strongly positively correlated with price.

**LSTAT (% lower status population)** and CRIM **(crime rate)** showed strong negative correlations.

**PTRATIO (pupil-teacher ratio)** and **TAX (property tax rate)** also negatively affected home values.

↪Valuable Data Insights-  Homes near the Charles River (CHAS = 1) often had higher median values.

Areas with lower crime and higher educational quality tended to have more valuable properties.

↪Comprehensive Model Evaluation-  Multiple models were tested, and their performance was compared using standard regression evaluation metrics. Cross-validation was applied to ensure the robustness of the chosen model.

↪Data Cleaning & Preparation-  The dataset was carefully cleaned by handling missing values, verifying data types, and performing normalization where necessary. This ensured the accuracy and quality of both analysis and predictions.



![image](https://github.com/user-attachments/assets/b9ff8bf3-d367-45d9-a6a7-2a0385c52644)





**👉Conclusion:**


The Boston Housing dataset reveals that factors such as the number of rooms (RM), crime rate (CRIM), and the percentage of lower status population (LSTAT) significantly impact housing prices. Larger homes and areas with lower crime rates tend to have higher prices, while areas with higher poverty rates have lower prices.


Thanks for watching

SWAPNA DEY

(Data Analyst)
