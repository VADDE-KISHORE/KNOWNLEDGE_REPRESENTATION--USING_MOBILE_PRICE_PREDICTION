# KNOWNLEDGE_REPRESENTATION--USING_MOBILE_PRICE_PREDICTION

Knowledge Representation and Insights Generation from Structured Datasets  
                   This is the project has been completed by team  of CT University students  
 Done by :
 
Vadde Kishore, 
Gutta Sai Prasanna
K.Bhuvaneswary.

Here , this project  contains about knowledge reprentation and insights generation from structured datasets. To give brief explanation on this we have choosen one of the real world examples.

The example that we have choosen on knowledge representation and insights generation from structured datasets : “MOBILE PRICE PREDICTION USING MACHINE LEARNING”.



MOBILE PRICE PREDITION USING
MACHINE LEARNING
![image](https://github.com/user-attachments/assets/5f0a923e-00e1-4044-8987-4b94db8d8b50)

             
This dataset consists of  information about  price and other aspects such as RAM, ROM etc. When we work on these sorts of data, we need to see which column is important for us and which is not. Our main aim  is to make a model which can give us a good prediction on the price of the mobile on other Features.
               We  used Linear Regression, Random Forest Regressor, Gradient Boosting Regressor. Regression for this dataset and see if it gives us a good accuracy or not.
               
Project contents :

 1.Overview
 2.Motivation
 3.Understanding the Problem Statement
 4.About the Dataset
 5.About the algorithm used 
 6.Data Collection
 7.Data Preprocessing
 8.Exploratory Data Analysis (EDA)
 9.Feature Observation
 10.Feature Selection
 11.Model Building
 12.Model Performance
 13.Prediction and Final Score
 14.output and Conclusion



1.OVERVIEW:

        In this project we had implemented a salable model for  the mobile price prediction using  some of the regression techniques based on some of  thefeatures in the dataset which is called Mobile Price Prediction. There are some of the processing techniques for creating a model. In this project we used sales prediction dataset website for collecting the mobile data.
        
2.MOTIVATION: 

 The Motivation behind it I just want know about the various kinds of mobile prices during the lock down period. Because now a days most of the E-Commerce website are focusing to sell the mobile for consumers.
3.UNDERSTAND THE PFOBLEM STATEMENT:

We all know that mobile phones most using object in present generations.so we can say that mobile phones  are an important reflection of thye humans and some rangesw are of great interest for bot both buyers and sellers.so in this project we are goping to see about how prices are divided or segregated based on features.as well as target features prediction is based on the same features. Target features are  means describe the mobile featuires based on mobile buyers.

4.ABOUT THE DATASET:

In this data, we had took it by price prediction datasets websites like e-commerce price prediction website. We had used wrapping tools to make changes but we made  changes the columns and according to our ideas we had not changes more data because the dataset is more usefull way and easy to understand for everyone. 

#lets understand feature of this dataset
![image](https://github.com/user-attachments/assets/312b977f-91a1-4909-a780-a5bcfe887770)


##Overview of data

![image](https://github.com/user-attachments/assets/0eb25778-68c0-4eed-8de2-2e91ba63fe15)


1.Unnamed _ This is the first feature of our datset which denotes serial numbers of the columns of data.
1. Brand me — This is first feature of our dataset. Its Denotes name of the mobile phones and Brands.
2. Ratings — This Feature Denotes Number of the ratings gave by the consumers for each mobile.
3. RAM — It’s have RAM size of the phone.
4. ROM — It’s have ROM (Internal Memory) size of the phone.
5. Mobile-Size — It’s represents how many inches of the particular mobile phone have. Here all the values are gave in inches
6. Primary-Cam — It’s Denotes Number of the pixels of the primary camera (Back Camera) for each mobile.
7. Selfi-Cam — It’s Denotes Number of the pixels of the Selficamera (Front Camera) for each mobile.
             .  8. Batery_power — It’s Denotes amount of the battery  
               Power in each mobiles in MAH                                                        
            .  9. Price — It’s a Dependent Feature of the dataset. Its just denoting prices of each mobiles.
            

5. About Alogorithms Used
 
1.Linear Regression
2.Random Forest Regressor
3.Gradiend Boosting Regressor

Machine Learning Packages are used for in this Project

![image](https://github.com/user-attachments/assets/a8d13048-a55f-42cf-a177-05448cb3d4a5)

                         
6. Data Collection:Here if search for data set you will find the same data set in different websites like Kaggle,github.but we took data from price prediction websites like e-commerce salable price preditiction ,we had took it for refrence if u need the dataset we will provide you a link 

7. Data Preprocessing:
In this process involves cleaning the data to make it ready for use by the ml algorithm

# to clean the data various steps are taken such as

#removing outliers
#filling missing values
#removing irrelevant fields

To know the null values we call find through using df.isna()show() or df.isnull()show() both are same so don’t confuse.

#Shape of the data

![image](https://github.com/user-attachments/assets/ad75577a-493c-479a-be51-16c2b1386fb1)


#finding the null values of the data

![image](https://github.com/user-attachments/assets/707bfdce-16a3-4794-8742-9f85bf7f9090)
    
    
Handling the missing values by removing the outliers and filling the null values .
       
![image](https://github.com/user-attachments/assets/5aa8a103-ee36-41fd-947c-33d64e21e61b)

![image](https://github.com/user-attachments/assets/02ce39fb-fe86-47de-ae6a-91e393d4d48e)

![image](https://github.com/user-attachments/assets/6cab6e50-4fa8-4737-b1bd-f6fad4a80c91)

![image](https://github.com/user-attachments/assets/ae133688-108b-4095-95e5-eb8462d144a9)

![image](https://github.com/user-attachments/assets/1c6c3dd0-8786-4cd1-b338-a3e62cec200b)


From data removing the outlier above codes are for the datset of having or present data .
We used the code to fill the missing values by show given below;

![image](https://github.com/user-attachments/assets/e49ac023-4f58-40c8-a173-5e3727e19ef9)

![image](https://github.com/user-attachments/assets/dcfa2b1b-a138-4dbd-99f5-6020ff34ec92)


Using mode we had filled or cleared the null values.
Note: we had removed some of features like unnamed and brand me because it is serial numbers and mobile name.

After handling all the null values and missing values will be look as:

![image](https://github.com/user-attachments/assets/1defef41-31b2-4691-b53b-2e59f5e84f01)


8. Exploratory Data Analysis(EDA):
In statistics, exploratory data analysis (EDA) is an approach to analyzing data sets to summarize their main characteristics, often with visual methods. A statistical model can be used or not, but primarily EDA is for seeing what the data can tell us beyond the formal modeling or hypothesis testing task.
#information of data set feature
df.info()

![image](https://github.com/user-attachments/assets/fcede2a3-ec40-4db8-9ab0-777312b62018)


![image](https://github.com/user-attachments/assets/ccb1427a-6011-4187-9c3c-5f0f7a80a14f)



10. Feature Observation

![image](https://github.com/user-attachments/assets/c3e23685-9721-4a5b-bc19-07fbe6d80718)

First Understanding the correlation of features between target and other features

![image](https://github.com/user-attachments/assets/609b01e4-32ba-441c-970e-0e10015007ea)

![image](https://github.com/user-attachments/assets/06b6bac5-2f73-4aff-ab8a-8cf69b8a0924)

![image](https://github.com/user-attachments/assets/4fdadb53-a50d-44f4-b348-c50208c454de)

![image](https://github.com/user-attachments/assets/bf73f580-156d-404b-a8ff-0a4cf2f1e285)

![image](https://github.com/user-attachments/assets/a993d8ca-8178-4810-8bc9-4bebf6d76bd8)

![image](https://github.com/user-attachments/assets/ebfc5f0a-1e4b-4d3b-883a-f0312b6c09e3)

![image](https://github.com/user-attachments/assets/580a9855-c568-4011-84aa-dc1bee52c894)


![image](https://github.com/user-attachments/assets/3f9fd2e1-8ded-4e4b-a004-1c7ae7b05c3f)

![image](https://github.com/user-attachments/assets/6a465aa7-8d9d-44c4-bae7-69ecbcf1b1c2)


10. Feature Selection:
Feature Selection is the process where you automatically or manually select those features which contribute most to your prediction variable or output in which you are interested in. Having irrelevant features in your data can decrease the accuracy of the models and make your model learn based on irrelevant features.

So that we used the regression features like to implement our project using linear regression ,randon forest regressor, gradient boosting regressor.

 Since we are trying to predict the price , we need to  use  Regression models as the models are good for predicting continuous variables 
 
Linear Regression: Linear regression is a statistical method used to model the relationship between a dependent variable (target) and one or more independent variables (predictors) by fitting a linear equation to the observed data.The simplest form is the equation y=mx + b, where y is the dependednt bariable, x is the independent variable, m is the slope, and b is the intercept

Random Forest Regressor : It operates by constructing multiple decision trees during training and outputs the average of their predictions. 

Gradient Boosting Regressor : It builds an ensemble of weak prediction models, typically decision trees, in a sequential manner. Each new model attempts to correct the errors made by the previous models. The core idea is to optimize a loss function by iteratively adding new models that minimize this loss using gradient descent. The result is a strong predictive model that combines the strengths of multiple weak learners.

Spitting of data:

Splitting data into X and Y Variables
splitting the data into feature(x) and target(y)

![image](https://github.com/user-attachments/assets/f9d38c76-d7e1-4060-8ffc-4ea2b97bec50)

![image](https://github.com/user-attachments/assets/bf892ee0-883e-4d02-92dc-c38e16dd5a7c)


11. Model Building:
    
Splitting the data into training and test data

![image](https://github.com/user-attachments/assets/23729fb1-41c1-4dcc-9b44-af6283617e66)


Using Linear Regression

![image](https://github.com/user-attachments/assets/40c9675b-2dcf-4e1f-8359-87c7e1318b10)
![image](https://github.com/user-attachments/assets/eab44d4e-f11b-461e-a0c7-8ec103de46e3)


Using Random Forest Regressor

![image](https://github.com/user-attachments/assets/d68fd0cd-ce82-44f2-b9c6-653d57d76fb6)

![image](https://github.com/user-attachments/assets/7dfd176e-908a-4dd6-9259-b0266f3debc2)


Using Gradient Boosting Regressor

![image](https://github.com/user-attachments/assets/02e717e6-da33-4623-8899-2bdce7f59caa)
![image](https://github.com/user-attachments/assets/3053fa00-f617-4264-afcd-1609d1698bbd)


![image](https://github.com/user-attachments/assets/79133be5-b730-4c90-bc11-e330bdb924df)


12. Model Performance:
Using the evaluation we can say how our model has well performed ,through r2 score which is called r squared score if it is near to zero or zero that says our model is bad and if it has one or near to one then we can say our model has well goodly or excellently performed.

![image](https://github.com/user-attachments/assets/36b52efb-ef40-4131-8f23-f07d36287636)


![image](https://github.com/user-attachments/assets/dde5685d-86ea-44ac-845a-612a65e3dc6e)

![image](https://github.com/user-attachments/assets/7ddc4ad1-9e1d-4a9b-a001-a9205b989224)


From above:

The linear regression  r2_score is near to zero.
The randon forest regressor r2_score is near to one and above to zero.
The gradient boosting regressor r2 score also near to one and above to zero.


14. OUTPUT AND CONCLUSION:

 ![image](https://github.com/user-attachments/assets/fefb46e3-392c-40b1-9655-d09aff661e81)


 ![image](https://github.com/user-attachments/assets/f5f78239-7aee-42b1-a8d7-7be783cc86a4)
 

 ![image](https://github.com/user-attachments/assets/dce9d845-c0ba-4b09-8bc8-3466f41c05d8)


Conclusion:
From the above we can see that the first algorithm of Linear Regression  didn’t do well as performance is less than 50% but the remaianing two that the Randon forest regressor and Gradient Boosting Regressor did well and it’s perforamnce is above 90%.
