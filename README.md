# Healthcare-Intervention-Program

OBJECTIVE: 
The utmost aim of the project is to devise a method for selecting the patients for the intervention program so that the total cost savings are maximised or to minimise the total cost of the intervention program. Another task is to build a model which can predict the patient as diabetic or non-diabetic most accurately and to discuss the highly predictive attributes.

Description:
In Type II Diabetes, the Insulin hormones are not able to work effectively to convert the glucose we get from the food intake into energy. It is also known as Insulin Resistance. As the Type II Diabetes gets worse, the Pancreas makes less insulin and leads to Insulin deficiency. As per National Diabetes Statistics Report 2014, In USA, 86 Million people are prediabetic and among those 29.1 Million people are diabetic. 90% of the diabetic patients have Type II diabetes.
The Intervention Program is started by the Health care Organisation to reduce the likelihood of Type II Diabetes. Currently, The Organisation is selecting patients based on their Fasting Blood Glucose level for the Intervention Program. This Current practice of selecting Patients having FBC greater than 110 incurs total cost $35,639,660. Our first task is to build a model from the data available to us which can reduce the total cost of the intervention program.

Results:
Different algorithms are run and compared based on auc criteria. Results are mentioned in the report.

Summary:
There were different objectives within the project. The first one was to minimize the total cost for the intervention program. For this the best model was Random Forest (with 100 iterations) that provided a cost saving of $4,311,120, which is equivalent to 12.1% saving. The second one was to accurately predict whether a patient will have diabetes. For this we split the dataset into training and testing set using stratified technique. The best model was Random_Forest (with 100 iterations at threshold score of 0.31) with a test accuracy rate of 95.188%. We further improve this accuracy to 95.385% by using the wrapper approach. The last objective was to find the most important predictors as well as finding the characteristics of patients with diabetes. To find the most important predictors we used “Decrease in area under ROC curve” as the deciding factor. To find the distinctive set of characteristics and decision rules of patients with diabetes, a J48 tree model was built by using only those attributes whose absence lead to decrease in area of ROC curve.
