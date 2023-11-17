# Classification-Cardiovascular-Risk-Prediction-
Capstone Project-3-Classification (Cardiovascular Risk Prediction)

Project Summary -
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
