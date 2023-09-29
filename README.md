The ‘Diabetes Dataset.csv’ file,contains details of blood samples of diabetic patients collected in an Iraqi University Hospital in 2020 as published under the reference given below. 
The file provided includes 12 relevant variables as follows: 
Gender- Male / Female

Age- Patient Age

Urea- A diamine, chief nitrogenous waste product in humans 
Cr- Creatinine Ratio, a parameter to assess kidney function CLASS
HbA1c -Average blood glucose (sugar) Levels 
Chol - Cholesterol, a parameter to assess liver function 
TG - Triglycerides a type of fat in the blood used to transport energy 
HDL -High-density lipoprotein, the “good” cholesterol
 LDL - Low-density lipoprotein, the “bad” cholesterol
 VLDL - Very-low-density lipoprotein cholesterol

BMI- Body-Mass-Index

CLASS -  N/Y/P – class of diabetes
Ignoring the CLASS==’P’ data entries, you are required to estimate a binary logistic regression model to facilitate diabetes diagnostic based on blood results. Use the exploratory data analysis to make decisions about transformations of the variables. Split the dataset in a suitable manner into training and test dataset. Evaluate the models on the test dataset using a confusion matrix. Test your final model on the CLASS==’P’ cases. What is the probability that these ‘prediabetic’ cases are diagnosed as diabetic? 
