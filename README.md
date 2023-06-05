# Prediction-and-Classification-of-Diabetes-based-on-patient-medical-record
Introduction

Diabetes is one of the most common diseases prevailing all over the world in all age groups today. Diabetes happens when your body isn't able to take up sugar (glucose) into its cells and use it for energy. This results in a buildup of extra sugar in your bloodstream, hence causing diabetes. Thus, early diagnosis of diabetes before it could be any later is very essential as it could lead to issues like coronary artery disease, chest pain, heart attack, stroke, high blood pressure, high cholesterol, atherosclerosis, kidney failure, Hearing loss, dental problems and many more. 
Diagnosis can be done with just a few medical values. This project aims to use the patient's medical record values like  pregnancies, BMI, Insulin level, age, Glucose level, blood pressure, skin thickness and DiabetesPedigreeFunction to predict and diagnose the presence of diabetes. At the end of the project, one can use the above-mentioned medical record to predict if the person has diabetes or not in just a few minutes of running the values through the model.


Objective:
To predict the presence of diabetes using patient medical record
To analyze and clean the given dataset 
To visualize the graphs for better understanding of the data and required output
To make use of KNN algorithm to obtain the prediction and classification of diabetes
To perform analysis that helps us determine the nearest neighbors for KNN model.
To obtain the accuracy of prediction using KNN and the confusion matrix for understanding of this accuracy value.

Data set:
The dataset consists of several medical predictor (independent) variables and one target (dependent) variable, Outcome. Independent variables include the number of pregnancies the patient has had, their BMI, insulin level, age, Skin thickness, Blood pressure, Glucose level and DiabetesPedigreeFunction.

Analysis    -   discussion about the result
By using the KNN algorithm an accuracy of 76.56% was achieved. The entire dataset was split for training and testing in 1:2 ratio, where 1 is for testing the model and 2 is for training the model. Out of the 256 record values assigned for testing the model, it is observed that 142 values were correctly predicted to have no diabetes given the actual value also has no diabetes. 54 were predicted to have diabetes when the person was actually diabetic. The remaining 25 and 35 were predicted wrongly to have diabetes and no diabetes. 
The usage of scaling techniques seemed to be very useful in obtaining a higher accuracy. Bringing all the features to the same scale for applying KNN is always advisable. The feature with greater range will overshadow or diminish the smaller feature completely and this will impact the performance of the model as it will give higher weightage to variables which have higher magnitude.
It was also observed that when KNN neighbors set for the model were 11, it seemed to have higher accuracy than other values as shown in the graph. 



Conclusion   
Diabetes prediction and classification was done using a KNN algorithm. Using this model an early diagnosis of diabetes can be done, following the prevention of high risks. Although the accuracy is 76.56%, there could be an improvement in the value which needs to be explored further. 
