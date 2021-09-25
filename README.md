# Risk_Score_Model_for_Diabetes_Patients
In this project, you'll build a risk score model for retinopathy in diabetes patients using logistic regression.
### Diabetic Retinopathy
Retinopathy is an eye condition that causes changes to the blood vessels in the part of the eye called the retina.
This often leads to vision changes or blindness.
Diabetic patients are known to be at high risk for retinopathy. 
Dataset is about 6000 diabetes patients
### Exploratory Data

![E](/download.png)

## Evaluate the Model Using the C-index
I will use the c-index to evaluate the model
* The c-index measures the discriminatory power of a risk score. 
* Intuitively, a higher c-index indicates that the model's prediction is in agreement with the actual outcomes of a pair of patients.
* A permissible pair is a pair of patients who have different outcomes.
* A concordant pair is a permissible pair in which the patient with the higher risk score also has the worse outcome.
* A tie is a permissible pair where the patients have the same risk score.

### Result

Three variables have the largest impact on the model are Age, Syctolic_BP and Cholesterol

We need more data on different relevant features to improve the model.

This model will help doctor have a better retinopathy pronosis in diabetes patients.

![E](/coef.png)

