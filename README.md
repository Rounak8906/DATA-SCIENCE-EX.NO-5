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
<img width="701" height="517" alt="image" src="https://github.com/user-attachments/assets/fbc6a77c-65e2-49d5-ba10-264a2a832bbb" />

```
import matplotlib.pyplot as plt
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph!')
plt.show()
```
<img width="756" height="568" alt="image" src="https://github.com/user-attachments/assets/e6da668b-b0ff-4c3e-bade-7c779e7c07fb" />

```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()

```
<img width="726" height="575" alt="image" src="https://github.com/user-attachments/assets/de8c42ca-f4a2-4e6a-84c1-4eea47538862" />

```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)

plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')

plt.show()
```

<img width="719" height="567" alt="image" src="https://github.com/user-attachments/assets/f215db66-de27-4a11-8d49-359aeec2d4c1" />

```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```

<img width="764" height="546" alt="image" src="https://github.com/user-attachments/assets/864c1c31-bcf9-45ea-b84b-b2c8bad8e84a" />

```
years=[2010,2011,2012,2013,2014,2015]
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yeild_apples)

```

<img width="705" height="553" alt="image" src="https://github.com/user-attachments/assets/c477fb13-c09d-4e8a-9d85-139479560d05" />

```
years=range(2000,2012)
apples= [0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)');
```

<img width="749" height="550" alt="image" src="https://github.com/user-attachments/assets/4f9fa38e-c79d-4a85-9fbf-99d51efc060d" />

```
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)')
plt.title("Crop Yeilds in Kanto")
plt.legend(['Apples','Oranges']);
```

<img width="732" height="562" alt="image" src="https://github.com/user-attachments/assets/106e6d68-e419-4416-91f1-27abe7b2d0ed" />

```
years=[2010,2011,2012,2013,2014,2015]
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yeild_apples)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)');
```

<img width="708" height="533" alt="image" src="https://github.com/user-attachments/assets/3eb68dde-bee3-430b-b04e-8ea5b17aef70" />

```
years=range(2000,2012)
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yeild of Oranges (tons per hectare)");
```

<img width="833" height="429" alt="image" src="https://github.com/user-attachments/assets/72c4e4db-6fc2-404c-a603-23136b5760d5" />

```
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)')
plt.title("Crop Yeilds in Kanto")
plt.legend(['Apples','Oranges']);
```

<img width="731" height="577" alt="image" src="https://github.com/user-attachments/assets/693f3fef-6f85-46f8-ac97-ac8413f369ca" />

```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()

```

<img width="717" height="522" alt="image" src="https://github.com/user-attachments/assets/9a5f8e3a-b6c2-4c7f-96a9-8f9a68972379" />
```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')

```
<img width="716" height="561" alt="image" src="https://github.com/user-attachments/assets/d82d95cb-c8fb-4a35-a126-48ff23bf273a" />

```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()

```
<img width="693" height="522" alt="image" src="https://github.com/user-attachments/assets/98e2e5d8-4bd9-4adb-950a-30debf0c57c0" />

```

import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color="blue")
plt.fill_between(x,y2,color="green")
plt.plot(x,y1,color="red")
plt.plot(x,y2,color="black")
plt.legend(['y1','y2'])
plt.show()
```
<img width="759" height="517" alt="image" src="https://github.com/user-attachments/assets/f2c542ae-415e-4bb7-aacf-35db12f60e5d" />

```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
<img width="708" height="549" alt="image" src="https://github.com/user-attachments/assets/ea06cc91-aee5-40c0-bce4-2042fcd3cbbf" />

```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,11]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
<img width="701" height="572" alt="image" src="https://github.com/user-attachments/assets/beabfbcf-56f6-49c7-b4bd-50cbaf9df552" />

```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No.of people')
plt.title('My histogram')
plt.show()
```
<img width="750" height="567" alt="image" src="https://github.com/user-attachments/assets/a4489376-6573-47cb-add2-513752022641" />

```

import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
<img width="752" height="449" alt="image" src="https://github.com/user-attachments/assets/6b17f4a4-a397-4937-9b8f-84d230ac97d9" />
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box plot'
```
<img width="768" height="596" alt="image" src="https://github.com/user-attachments/assets/3088c333-18b8-4136-ab84-c442fbee0846" />

```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,
autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()

```
<img width="583" height="478" alt="image" src="https://github.com/user-attachments/assets/d8f01657-d7a8-41fb-a153-e0967017964d" />

```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,
        startangle=90,shadow=True,explode=(0,0,0.1,0),
        radius=1.2,autopct='%1.1f%%')
plt.legend()
```
<img width="634" height="530" alt="image" src="https://github.com/user-attachments/assets/e5019379-7e77-40ae-9acf-91086154e2e0" />

# Result:
To Perform Data Visualization using matplot python library for the given datas is successful.
