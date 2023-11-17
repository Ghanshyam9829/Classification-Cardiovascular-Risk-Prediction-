# Classification-Cardiovascular-Risk-Prediction-

Capstone Project-3-Classification (Cardiovascular Risk Prediction)

**Project Summary -**

Introduction – The ongoing research based cardiovascular study in the town of Farmingham, Massachusetts has yielded into a good dataset that contains around 4000 records with over 15 attributes. It provides useful insights on potential risk factors for the residents of coronary heart disease. Our main goal is to make use of this dataset and predict if the patient is prone to CHD in next 10 years. The attributes consists of multi-level factors that play crucial role in CHD prediction; namely, demographics, medical vitals and behavioral habits. The dataset is provided in a single .csv file, easy to handle and implement any machine learning model. Dataset Description – The given Farmingham Dataset has various factors in the form of attributes that can be largely categorized into 3 major categories.

Demographic – age, sex, etc.
Vitals – SysBP, Diabetes, BMI, etc.
Behaviour – Is Smoking, Cigarettes Per day, etc. It has 3389 unique entries with 16 attributes. Data Preprocessing For starters, I uploaded the dataset containing file using the read csv function of pandas library. The first thing I did was to check for any duplicate values, which was none. While checking for any missing/null values I found;
Education - 87
Cigs Per day - 22
BP Meds - 44
Tot Chol - 38
BMI - 14
Heartrate – 1
Glucose – 304 have missing values & With the help of heat map, I could conclude that in 4 columns, namely; education, BP meds, Totchol and Glucose have null values. Out of which most null values are under the glucose column. Data Wrangling – On performing the process of data wrangling, following results were obtained.
Total Entries = 3390
Male = 1467
Female= 1923
Total age range = 32-70
Non-Smoker Females = 1147
Smoker Females = 776
Non-Smoker Males = 556
Smoker Males = 911
People with no risk of 10 years = 511
People with risk of 10 years = 2879 These are brief inferences that could be obtained from a through glance at the rows and columns of the dataset, after which data visualisation was performed.

The logistic, grid-search CV, and XGBoost models were applied to the dataset to test hypotheses. Results indicate varying performance across models. Logistic classification provided insights into the data, grid-search CV optimized model parameters, and XGBoost classification offered enhanced predictive capabilities. Combining these approaches contributes to a comprehensive understanding of the dataset, enabling informed decision-making in relevant contexts.The logistic, grid-search CV, and XGBoost models were applied to the dataset to test hypotheses. Results indicate varying performance across models. Logistic classification provided insights into the data, grid-search CV optimized model parameters, and XGBoost classification offered enhanced predictive capabilities. Combining these approaches contributes to a comprehensive understanding of the dataset, enabling informed decision-making in relevant contexts.

**Problem Statement -**

The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients' information. It includes over 4,000 records and 15 attributes. Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk factors.

**Variables Description**


Attributes : Description

Age - Age of the Patient

Sex : Gender of the patient

Education : Qualification of patient

Is_Smoking: If the patient is smoking these days or not

Cigs_Per_Day : How many cigarettes do they smoke in a day

Prevalent Stroke : If the patient ever had a stroke in the past

Prevalent Hyp : If the patient has a history of hypertensions

Tot Chol : Cholestrol Measure in a patient

Diabetes : If the patient is diabetic or not

Dia BP : BP Measure

Sys BP : BP Measure

BMI :Body Mass Index

Heart Rate : Measure of heart rate

### 1. Which Evaluation metrics did you consider for a positive business impact and why?

confusion matrix determines the performance of the classification model for the test data, it shows the error in the model also know as error matrix, it can be determined if the true value of the data is known, understanding this matrix is easy but its terminology is complex

### 2. Which ML model did you choose from the above created models as your final prediction model and why?

For the final prediction model we are using XGboost which is a gradient boosting technique and know as "Extreme gradient boosting" , this technique is used for wide range machine learning problem , it is a effective mehtod which is used for the large data set , it is a methematical ensemble learning technique which is used to improve the result of so many machine learning models , this technique creates one decision tree in every iteration and add it in the residual of the previous iteration.

### 3. Explain the model which you have used and the feature importance using any model explainability tool?

I will prefer SHapley Additive exPlanation  for the explainability of the model , that will explain the tabuler representation of the test data set. We can mention this method as "SHAP" .

I will explain the details of the SHAP , different representation and charts for understanding the preactical approach of the model , mehtematical explaination of the SHAP can be difficult , but i will try to explain little bit in my terms.

**Conclusion**

The dataset contains a total of 3389 entries. 1923 out of 3389 are female entries.

1467 out of 3389 are male entries.

2879 people have 10 years of CHD disease.

511 People have not 10 years of CHD disease.

The minimum age in the given data set is 32.

The maximum age in the given data set is 72.

A total of 148 people entries are available from the age group 40.

1147 out of 1923 females do not smoke.

776 out of 1923 females do smoke.

556 out of 1467 males do not smoking.

911 out of 1467 males do smoke.

32 age group people consume 15 cigarettes per day.

70 age group people consume 0 cigarettes per day.

62 age group people have an average of 260 cholesterol measure, which is high among all age groups.

70 year old people have an average of 169 cholesterol measures, which is low among all age groups.

Heart rate is higher for age group 32 and 69 which is nearly equal to 80. The lowest heart rate was recorded for age 70 which is 64.



