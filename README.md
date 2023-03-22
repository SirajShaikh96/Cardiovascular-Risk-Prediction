# Cardiovascular-Risk-Prediction

![heart](https://user-images.githubusercontent.com/116551866/226852716-83f526cd-6ba3-47c3-93eb-4a925821fbc5.PNG)

# 📋 Project Summary

**As the cardio vascular risk is increase year by year. from the given data we've to predict whether or not a person will have cardio vascular risk within 10 years.**

**We are gonna do some eda to visaulize the dataset and will fnd some insight from eda, check for missing value, distribution of the features, target feature is balanced or not. Capping outliers, Balacing the target feature by SMOTE**

**After EDA, feature engineering and feature selection we'll split the dataset into training and testing set. Then we'll train multiple classification models, Hyperparameter tunning, evaluating model on the basis of classification metrics.**

**Finalizing the metric and best model on the basis of selected metric.**

# 📋 Problem Statement

**As the cardiovascular risk is increasing. No of patient will also increase but the no of doctors avlaible is not enough to scrutinize every report. Which is a huge problem.** 

# 📋 Business Objective

**We'll make a robust classification model which will classify whether or not a person will have cardiovascular risk within 10 years.**

**They just have to fill up required information on which model will predict whether or not a person will have cardiovascular risk within 10 years. It will increse the speed of identifying that person and reduce the cost, which will solve the problem of shortage of doctors and identifying that person at the right time and in a cost effective way.**

# 📋 Visualization

# 1) Distribution of target features value
![target](https://user-images.githubusercontent.com/116551866/226856716-03138f27-dfe6-481f-9e39-6f9d74628f1f.PNG)

# 2) Somkers & Non Smokers in Male & Female
![sns](https://user-images.githubusercontent.com/116551866/226856916-b853fff6-73b7-419a-9592-b7aaa1e4a7a3.PNG)

# 3) NO_of cigarette's per day
![nc](https://user-images.githubusercontent.com/116551866/226857087-dab5f074-d7a3-4cfd-95c8-e2a619b0718f.PNG)

# 4) Distribution of people will have risk if they smoke or not
![10y](https://user-images.githubusercontent.com/116551866/226858559-f4157d1e-0f31-4062-8573-fb3b02a482b0.PNG)

# 5) Age Cardiovascular risk relation
![agerisk](https://user-images.githubusercontent.com/116551866/226859223-69ccaae4-bf8d-4005-83a3-919311f534c6.PNG)

# 6) Distribution of glucose level
![disf](https://user-images.githubusercontent.com/116551866/226860665-0f3e3e22-33d3-4eae-acc9-c3a3fdcf4f36.PNG)

**After log transformation**
![afterlog](https://user-images.githubusercontent.com/116551866/226860683-a33adf32-83a7-4f63-b523-da058226a20f.PNG)

**Every feature is right skew except age, so do log tranformation on every feature except age.**

# 7) Correlation Chart
![cor](https://user-images.githubusercontent.com/116551866/226862034-4671c51d-f3e0-40e0-b4a1-ba21934a0cb0.PNG)

# 📋 Model Performance

# Within 10 years who will have cardiovascular risk is denoted by 1. In this project detecting 1 is very important. So we'll only focus on the mertics of 1

![mp](https://user-images.githubusercontent.com/116551866/226862472-bbc2828b-b454-4cf2-bc82-a8a1425a6e5a.PNG)

**IN this project we are taking Recall as final metric b'coz classifying a person whether or not have cardio vascular risk within 10 years, recall is important.**

**KNN is the final model we've selected for this project b'coz its recall value is the highest.**

# 📋 Conclusion

**In this project we found out that age is the biggest factor of having developing cardio vascular risk, and all other factors may increase the cardio vascular risk at that age.**
**In this dataset male who smokes are more tha the man who do not smoke and their are less female who smokes than the female who do not smokes. According to overall data male smoke's more.**

