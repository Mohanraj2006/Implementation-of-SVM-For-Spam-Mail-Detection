# Implementation-of-SVM-For-Spam-Mail-Detection

## AIM:
To write a program to implement the SVM For Spam Mail Detection.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
  1.Import the necessary python packages using import statements.

2.Read the given csv file using read_csv() method and print the number of contents to be displayed using df.head().

3.Split the dataset using train_test_split.

4.Calculate Y_Pred and accuracy.

5.Print all the outputs.

6.End the Program.

## Developed by: MOHAN RAJ C
## RegisterNumber:212223040114
## Program:
```
/*
Program to implement the SVM For Spam Mail Detection..
import chardet
file='spam.csv'
with open (file,'rb') as rawdata:
    result = chardet.detect(rawdata.read(100000))
result

import pandas as pd
data=pd.read_csv("spam.csv",encoding='windows-1252')

data.head()

data.info()

data.isnull().sum()

x=data["v1"].values
y=data["v2"].values

from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=0)

from sklearn.feature_extraction.text import CountVectorizer
cv=CountVectorizer()

x_train=cv.fit_transform(x_train)
x_test=cv.transform(x_test)

from sklearn.svm import SVC
svc=SVC()
svc.fit(x_train,y_train)
y_pred=svc.predict(x_test)
y_pred

from sklearn import metrics
accuracy=metrics.accuracy_score(y_test,y_pred)
accuracy
*/
```

## Output:
![SVM For Spam Mail Detection](sam.png)
![Screenshot 2024-11-07 111746](https://github.com/user-attachments/assets/8858dc8b-97b5-4fe9-8948-fcb2abe3d0ec)
## data.head()
![Screenshot 2024-11-07 111758](https://github.com/user-attachments/assets/13c83d03-23ae-49c3-8fb9-66d4bc489517)
## data.tail()
![Screenshot 2024-11-07 111804](https://github.com/user-attachments/assets/bd79481d-2237-4cf7-a95c-d2ae7b3e8326)
## data.info()
![Screenshot 2024-11-07 111814](https://github.com/user-attachments/assets/918e245a-ea81-48d6-89a7-0c96caad115f)
## data.isnull().sum()
![Screenshot 2024-11-07 111827](https://github.com/user-attachments/assets/81705a0a-44eb-41c7-afc8-645f261162fd)
## Prediction y
![Screenshot 2024-11-07 111836](https://github.com/user-attachments/assets/1020bccb-3622-4382-9752-577610b4e0a0)
## Accuracy
![Screenshot 2024-11-07 111842](https://github.com/user-attachments/assets/d9a48267-587e-4444-a04d-734c40dbcafb)




## Result:
Thus the program to implement the SVM For Spam Mail Detection is written and verified using python programming.
