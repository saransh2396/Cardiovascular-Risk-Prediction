# Cardiovascular-Risk-Prediction
The	TenCHD	is	predicted	using	the following Independent Variables:
•	Sex: male or female("M" or "F")
•	Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)
### Behavioral:
•	is_smoking: whether or not the patient is a current smoker ("YES" or "NO")
•	Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)
### Medical( history):
•	BP Meds: whether or not the patient was on blood pressure medication (Nominal)
•	Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
•	Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
•	Diabetes: whether or not the patient had diabetes (Nominal)
### Medical(current):
•	Tot Chol: total cholesterol level (Continuous)
•	Sys BP: systolic blood pressure (Continuous)
 
•	Dia BP: diastolic blood pressure (Continuous)
•	BMI: Body Mass Index (Continuous)
•	Heart Rate: heart rate (Continuous - In medical research, variables such as  heart rate though in fact discrete, yet are considered continuous because of a large number of possible values.)
•	Glucose: glucose level (Continuous)

### Predict variable (desired target):
•	TenCHD: 10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”) - DV
Our goal here is to build a predictive model, which could help the hospitals in predicting Chronic Heart Disease proactively.


# Presentation
[Here is the Presentation]()

# Summary
1)	The Support vector machine is the best performing model in terms of accuracy and the F1 score and Its high AUC-score shows that it has a high true positive rate.
2)	Balancing the dataset by using the SMOTE technique helped in improving the models' sensitivity.
3)	With more data(especially that of the minority class) better models can be built.



