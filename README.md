# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
 ```python
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
```
Line Plot:
```python
marks=[43,41,56,72,32]
student=['Max','Jude','Pedri','Yamal','Kiliyan']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()
```
<img width="859" height="564" alt="Screenshot 2025-10-23 141234" src="https://github.com/user-attachments/assets/1598b6b5-7050-48a7-b8a9-b27a2daea57f" />

Scatter Plot:
```python
x=[20,25,30,35,40]
y=[50,100,150,200,250]
plt.scatter(x,y,label='stars',color='red',marker='*',s=40)
plt.show()
```
<img width="816" height="548" alt="Screenshot 2025-10-23 141240" src="https://github.com/user-attachments/assets/2247f641-f43a-4471-bac7-e15daf370104" />


```python

x=np.arange(0,17)
y=np.arange(0,17)
plt.scatter(x,y,c='b')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()

```
<img width="813" height="589" alt="Screenshot 2025-10-23 141246" src="https://github.com/user-attachments/assets/68e09a37-ed3e-4053-a669-5a117c5cc4e8" />

Pie Chart:
```python

act=['eat','sleep','work','play']
slices=[4,8,9,7]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
<img width="632" height="548" alt="Screenshot 2025-10-23 141251" src="https://github.com/user-attachments/assets/d764fd2a-57e0-4a84-bb6f-cca57566d540" />

Area Chart:
```python

x = [0,2,4,6,8]
y1 = [10, 12, 14, 16, 18]
y2 = [3,5,7,9,11]
y3 = [1,2,3,4,5]
plt.fill_between(x, y1, color='yellow')
plt.fill_between(x, y2, color='red')
plt.plot(x, y1, color='blue')
plt.plot(x, y2, color='green')
plt.legend(['y1','y2'])
plt.show()
```
<img width="871" height="546" alt="Screenshot 2025-10-23 141256" src="https://github.com/user-attachments/assets/d3b9402c-8877-46bb-8350-069baf3ad6e1" />

Bar Chart:
```python
height = [7, 10 , 22 , 30 , 15 , 4 ]
names = ['one', 'two', 'three', 'four', 'five' , 'six']
c1=['blue', 'yellow']
c2=['green', 'red']
plt.bar (names, height, width=0.8, color=c2)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('bar chart')
plt.show()
```
<img width="856" height="588" alt="Screenshot 2025-10-23 141301" src="https://github.com/user-attachments/assets/31241d07-fb14-4014-a636-259bdccd4daf" />

Histogram:

```python
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=1)
plt.show()
```
<img width="765" height="533" alt="Screenshot 2025-10-23 141306" src="https://github.com/user-attachments/assets/9f2cb706-9bb8-40a9-8102-43b4c3d460f4" />

Box Plot:
```python
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=50)
data
```
<img width="765" height="247" alt="Screenshot 2025-10-23 141312" src="https://github.com/user-attachments/assets/01a7d8ca-d4ef-4cfd-b07b-a18fc4858d0a" />

```python

plt.boxplot(data)
plt.xlabel('data')
plt.ylabel('values')
plt.title('Boxplot')
```
<img width="835" height="622" alt="Screenshot 2025-10-23 141316" src="https://github.com/user-attachments/assets/af539e37-8b2c-40d5-8b77-f4da4797a5f1" />



# Result:
Thus , the data visualization was peformed using matplot python library for the given datas successfully.
