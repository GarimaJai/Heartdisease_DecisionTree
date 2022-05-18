# Heartdisease_DecisionTree
Heart Disease Case Study
Objective : Predict the presence of heart disease in a pateint.

Data contain a binary outcome HD for 454 patients who presented with chest pain. An outcome value of Yes indicates the presence of heart disease based on an angiographic test, while No means no heart disease

There are 13 predictors including Age, Sex, Chol (a cholesterol measurement), and other heart and lung function measurements

In the data, some of the predictors, such as Sex, Thal (Thallium stress test), and ChestPain, are qualitative

Data Source-UCI Machine Learning Repository

Data Description

(age)-> age in years
(sex)-sex (1 = male; 0 = female)
(chestPain)
-- Value 1: typical angina
-- Value 2: atypical angina
-- Value 3: non-anginal pain
-- Value 4: asymptomatic

(RestBP)->resting blood pressure (in mm Hg on admission to the hospital)
(chol)->serum cholestoral in mg/dl
(fbs)->(fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
(restecg)->resting electrocardiographic results
-- Value 0: normal
-- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
-- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

(MaxHR)->maximum heart rate achieved
(exang)->exercise induced angina (1 = yes; 0 = no)
(oldpeak)->ST depression induced by exercise relative to rest
(slope)->the slope of the peak exercise ST segment
-- Value 1: upsloping
-- Value 2: flat
-- Value 3: downsloping

(ca)->number of major vessels (0-3) colored by flourosopy
(thal)->3 = normal; 6 = fixed defect; 7 = reversable defect
(AHD) (the predicted attribute) ->diagnosis of heart disease (angiographic disease status) Yes/No
