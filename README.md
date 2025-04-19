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
```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```
![image](https://github.com/user-attachments/assets/8583a4c7-aed1-49d6-90ca-812e997bf186)
```
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph')
plt.show()
```
![image](https://github.com/user-attachments/assets/b4167dd5-e070-4d64-8ef3-e3e69e85c1da)
```
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/0f9bae48-281c-4a13-b979-90f09f0c40a8)
```
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations')
plt.show()
```
![image](https://github.com/user-attachments/assets/1fc20e10-88d2-474f-8d81-d121f29c12d7)
```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![image](https://github.com/user-attachments/assets/44147b66-f514-4242-8824-2cdc1e3a2d29)
```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```
![image](https://github.com/user-attachments/assets/659397be-c56e-47c1-af94-23bc68e831a4)
```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9375,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.plot(years , apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)');
```
![image](https://github.com/user-attachments/assets/bd21dc86-fe63-4283-85f9-b884303598c1)
```
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)')
plt.title("Crop yield in Kanto")
plt.legend(['Apples','Oranges'])
```
![image](https://github.com/user-attachments/assets/3c47c13c-061a-4b17-b912-19ac53dbaad7)
```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)');
```
![image](https://github.com/user-attachments/assets/36850bbe-9e77-4125-91c2-cdd22db5df69)
```
plt.figure(figsize=(12,6))
years=range(2000,2012)
plt.plot(years,oranges,marker='o')
plt.title("Yield of oranges (tons per hectare)");
```
![image](https://github.com/user-attachments/assets/36766365-5d30-4f86-af6d-1bbdfa6b8647)
```
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title("Crop Yields in kanto")
plt.legend(['Apples','Oranges'])
```
![image](https://github.com/user-attachments/assets/f70b80d4-f4bd-4048-8581-1bdf5e51c868)
```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
```
![image](https://github.com/user-attachments/assets/671bdce7-9e48-486a-8d87-62f6543aaf7a)
```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6,7,8,9,10]
y=[2,4,5,7,6,8,9,11,12,12]
plt.scatter(x,y,label="stars",color="green",marker="*",s=30)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My scatter plot!')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/9d91947c-4ad5-44a0-babb-d2c6dd019007)
```
import numpy as np
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![image](https://github.com/user-attachments/assets/675e9922-437e-4535-b0e1-0284e32ebc75)
```
y
```
![image](https://github.com/user-attachments/assets/65d22706-947e-4001-b7ba-37bf65cafa11)
```
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![image](https://github.com/user-attachments/assets/48f0c6cb-b5bd-462c-9f80-af8c389adf2e)
```
y=x*x
y
```
![image](https://github.com/user-attachments/assets/4860b6c4-0521-40eb-a177-8ab50b81865c)
```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('x axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![image](https://github.com/user-attachments/assets/47f8b373-5dd1-4f25-b51f-51c2ea4f54de)
```
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
```
![image](https://github.com/user-attachments/assets/7fa6df7c-679a-44ba-ac73-88f7d9773d66)
```
np.pi
```
![image](https://github.com/user-attachments/assets/192ceaf1-7010-4005-a445-96702ed55105)
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![image](https://github.com/user-attachments/assets/353ce8a9-c3a9-49b2-a8ab-61058bf04b54)
```
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```
![image](https://github.com/user-attachments/assets/86145e8d-bd61-44a2-83df-94537eae34c6)
```
plt.stackplot(x,y1,y2,y3,labels=['Line 1','Line 2','Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```
![image](https://github.com/user-attachments/assets/763cdcfc-3135-41de-9a42-d5de157bc7c1)
```
import numpy as np
import matplotlib.pyplot as plt
from scipy.interpolate import make_interp_spline
x=np.array([1,2,3,4,5,6,7,8,9,10])
y=np.array([2,4,5,7,8,8,9,10,11,12])
spl=make_interp_spline(x,y)
x_smooth=np.linspace(x.min(),x.max(),100)
y_smooth=spl(x_smooth)
plt.plot(x,y,'o',label='data')
plt.plot(x_smooth,y_smooth,'-',label='Spline')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/94ff5f65-e3f8-4536-bde7-215970618a42)
```
import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.bar(names,values,color="green")
plt.show()
```
![image](https://github.com/user-attachments/assets/43dcf356-e5f8-4700-b446-03d796d8c35d)
```
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.barh(names,values,color="yellowgreen")
plt.show()
```
![image](https://github.com/user-attachments/assets/c47be8c2-1184-47f6-ba06-0d7eff2b8285)
```
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My Bar Chart!')
plt.show()
```
![image](https://github.com/user-attachments/assets/e01e92c1-f688-4158-bc57-0d26400a6869)
```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
![image](https://github.com/user-attachments/assets/0b1f574a-88ba-49ab-8caa-6261f230bd5d)
```
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
```
![image](https://github.com/user-attachments/assets/a21635b0-01c0-4807-9558-323cd9a39f41)
```
x=[2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()
```
![image](https://github.com/user-attachments/assets/f76014a3-5441-48a3-8a2d-83ca6850d093)
```
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![image](https://github.com/user-attachments/assets/95e78c71-7d84-4bd3-823a-342be979f2cc)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Value')
ax.set_title('Box Plot')
```
![image](https://github.com/user-attachments/assets/94485cc0-f558-41a7-bff2-682b46b59478)
```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','g','b','y']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0.1,0,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/c2f387fe-380c-49dc-a11d-b5ae2767fd93)
```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![image](https://github.com/user-attachments/assets/e7ff446a-1c46-4429-a12a-61483fd5c749)

# Result:
 Data Visualization using matplot python library for the given datas has been performed successfully.
