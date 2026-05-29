# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>

### Step2
<br>

### Step3
<br>

### Step4
<br>

### Step5
<br>

## Program:
```
name: moogethshivanG G 
reg no: 212225040259
import numpy as np 
import matplotlib.pyplot as plt  
x = np.array([0,1,2,3,4,5,6,7,8,9])
y = np.array([1,3,2,5,7,8,8,9,10,12])
plt.scatter(x,y)
plt.show()
xmean = np.mean(x)
ymean = np.mean(y)
num = 0  
den = 0  
for i in range(len(x)):  
    num += (x[i]-xmean)*(y[i]-ymean)  
    den += (x[i]-xmean)**2  
m = num/den
b = ymean - m*xmean
print(m,b)
ypred = m*x+b
print(ypred)

plt.scatter(x,y,color='Red')
plt.plot(x,ypred,color='Blue')
plt.show()





```
## Output:
<img width="1059" height="501" alt="image" src="https://github.com/user-attachments/assets/0f2457a2-7e73-4d61-884c-1fae33327192" />
<img width="879" height="459" alt="image" src="https://github.com/user-attachments/assets/c87ccb75-01be-4eb1-a69b-5c3b48cf3d60" />

### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
