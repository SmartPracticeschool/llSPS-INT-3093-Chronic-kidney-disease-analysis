
Machine Learning Engineer: Chronic Kidney Disease Analysis


************** Group Members - Project :SmartPracticeschool/llSPS-INT-3093-Chronic-kidney-disease-analysis ************************* 

1. Prateek Gupta (Leader,Code debugger,Tester)
2. AKULA NAVEEN (Coder)
3. LAMMATHA SUNEETHA (Documentation)

*********************** Acknowledge ********************************* 

We created this project in an attempt to predict whether a patient has chronic kidney disease based on multiple health indicator. You can find more information about the variables I used to make the prediction.We have used a Machine learning approch for predicting if a patient has CKD. This project involves different ML algorithms such as Decesion trees, Random Forest, Logestic Regression, Support Vector Classifier, Naive Bayes, SGD classifier and KNN. Our accuracy is above 96% in all the models including 100% in 3 of them.

In this project we have build a model which predicts the Chronic Kidney Disease based on the patient's report with a 97% accuracy.

********************************* Project Description ***************************************************************************************

Chronic Kidney Disease (CKD) is a major medical problem and can be cured if treated it in the early stages. Usually, people are not aware that medical tests, we take for different purposes could contain valuable information concerning kidney diseases. Consequently, attributes of various medical tests are investigated to distinguish which attributes may contain helpful information about the disease.The information says that it helps us to measure the severity of the problem, the predicted survival of the patient after the illness, the pattern of the disease and work for curing the disease.

The chronic kidney disease (CKD) describes the heterogeneous disorders that affect the functionality and the structure of kidney.
The progression of CKD may lead to complications such as high blood pressure, anemia, weak bones, poor nutritional health and
damage and if not treated, it may eventually lead to kidney failure which requires dialysis or kidney transplant.
Therefore, it is vital to detect it and prevent its progression in the early stages. The existing markers for CKD diagnosis
can only identify high-risk patients and do not improve the understanding of the pathogenesis and progression of disease.

In this study, the objective is to analyze and determine the possible predictive factors that are reliable and easily measured
in laboratory environment for the early recognition and prevention of the progression of the disease. In this report, we try to use GLM along with various model selection techniques to build a prediction model for CKD detection. We validate the model and test its predictive power via the generalized linear models.

Chronic kidney disease (CKD) has been on the rise in recent years and is a major cause of mortality and health expenditure in the United States. This project uses 235 features extracted from the U.S. Census Bureau to test whether hyper-local rates of CKD can be determined using readily available demographic data. These features include data on age, sex, marital status, disability, employment, profession, household type, housing costs, and type of insurance. Regression and ensemble methods were used to predict rates of chronic kidney disease. Ultimately, gradient boosted decision trees proved to be the best prediction model with a predictive accuracy of 83.94%

Chronic kidney disease (CKD) is a type of kidney disease in which there is gradual loss of kidney function over a period of months or years. Early on there are typically no symptoms. Later, leg swelling, feeling tired, vomiting, loss of appetite, or confusion may develop. Complications may include heart disease, high blood pressure, bone disease, or anemia.

******************** Aim of the project ***************************************************************************************

The purpose of this project was to assist federal, state, and local public health agencies and organization to improve targeting of public health campaigns related to chronic kidney disease prevention. The predictive model helps to accomplish this goal by allowing limited resources to be targeted to neighborhoods with the greatest need for intervention.

Our kidneys perform an important function to help filter blood and pass waste as urine. Chronic kidney disease, also called chronic kidney failure, describes the gradual loss of this function. At advanced stages, dangerous levels of fluid, electrolytes and wastes can build up in the body. Once this happens, patients must go through dialysis or consider a transplant.
Our goal in this project is to see if we can predict if a patient will have chronic kidney disease or not using 24 predictors. If we are able to find variables with a strong influence on kidney failure, we may be able to detect and help patients at risk to prevent it.

********************* Steps to proceed ******************************************
1. Define the problem.
2. Obtain the data.
3. Explore the data.
4. Model the data.
5. Evaluate the model.
6. Answer the problem.


************* Description & Data - files *************************************************************** 

This is a classification problem to predict kidney disease.The chronic kidney disease dataset contains both categorical and numeric features, but contains lots of missing values. 

The data was downloaded from the following URL - 

[CKD Dataset]  (https://thesmartbridge.com/documents/spsaimldocs/Data.csv)
The dataset information such as attributes, their description and values can be found in the downloaded folder.
The dataset is renamed to CKD.csv which is used for both R and Python Scripts
There are 400 observations with 25 attributes including the outcome.

The source of the dataset is Dr.P.Soundarapandian M.D., D.M (Senior Consultant Nephrologist), Apollo Hospitals, Managiri, Madurai Main Road, Karaikudi, Tamilnadu, India. The dataset was found in the UCI Machine Learning Repository.

This dataset has 400 observations and 25 variables. (250 ckd, 150 notckd)

1. age: age in years
2. bp: Blood pressure in mm of Hg.
3. sg: Specific Gravity
4. al: Albumin - (0,1,2,3,4,5)
5. su: Sugar - (0,1,2,3,4,5)
6. rbc: Red Blood Cells - (normal,abnormal)
7. pc: Pus Cell - (normal,abnormal)
8. pcc: Pus Cell clumps - (present,notpresent)
9. ba: Bacteria - (present,notpresent)
10. bgr: Blood Glucose Random(numerical) in mgs/dl
11. bu: Blood Urea in mgs/dl
12. sc: Serum Creatinine in mgs/dl
13. sod: Sodium in mEq/L
14. pot: Potassium in mEq/L
15. hemo: Hemoglobin in gms
16. pcv: Packed Cell Volume
17. wbcc: White Blood Cell Count in cells/cumm
18. rbcc: Red Blood Cell Count in millions/cmm
19. htn: Hypertension - (yes,no)
20. dm: Diabetes Mellitus - (yes,no)
21. cad: Coronary Artery Disease - (yes,no)
22. appet: Appetite - (good,poor)
23. pe: Pedal Edema - (yes,no)
24. ane: Anemia - (yes,no)
25. class: Class - (ckd,notckd)

******************* Installationm - Instructions ***************************

-> Steps for creating environment for testing the app:

> conda create -n test python=3.6.2 pip

> activate test

> pip install -r requirements.txt

-> To run the app:

-> Move to the directory where app.py file is located in conda prompt while the activated environment is "test".

-> Run 'python app.py' (without quotes)

-> Open 'localhost:5000' in the browser to acess the app.

********************************* Software requirement ************************

1. scikit-learn == 0.20.2
2. flask == 1.0.2
3. numpy == 1.15.4
4. pandas == 0.24.1
5. matplotlib == 3.0.2
6. scipy == 1.2.1
7. jinja2 == 2.10

