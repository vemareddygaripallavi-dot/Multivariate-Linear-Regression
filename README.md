# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner


## Algorithm:
### Step1 : Import required libraries and load the dataset.
<br>

### Step2 : Define the feature matrix � and target vector �.

<br>

### Step3 :Split the dataset into training and testing sets.
<br>

### Step4  :Create a Linear Regression model and train it using training data.
<br>

### Step5 : Predict outputs, evaluate the model, and plot the residual errors.
<br>

## Program:
```
#DEVELOPED BY : Vemareddygari Pallavi
#REGISTER NUMBER :212225230293

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("car.csv")
x=df[["Volume","Weight"]]
y=df["CO2"]
regression=linear_model.LinearRegression()
regression.fit(x,y)
print(regression.coef_)
print(regression.intercept_)
print(regression.predict([[3300,1300]]))

```
## Output:



## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
