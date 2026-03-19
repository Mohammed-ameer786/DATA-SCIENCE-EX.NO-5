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

# Coding:
Matplotlib:
```python
import matplotlib.pyplot as plt
import numpy as np

x = np.arange(20, 50)
y = np.arange(50, 80)
a = np.arange(80, 110)
b = np.arange(110, 140)

plt.scatter(x, y, c='b')
plt.xlabel('X-Axis')
plt.ylabel('Y-Axis')
plt.title('Graph in 2D')
plt.show()
```
2D Diagram:

```python
plt.plot(x, y, 'b*', linestyle='dashed', linewidth=1, markersize=10)
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('2D Diagram')
plt.show()
```

```python
plt.subplot(3, 2, 1)
plt.plot(x, y, 'r.')
plt.subplot(3, 2, 2)
plt.plot(x, y, 'b*')
plt.subplot(3, 2, 3)
plt.plot(x, y, 'yo')
plt.subplot(3, 2, 4)
plt.plot(x, y, 'g*')
plt.subplot(3, 2, 5)
plt.plot(x, y, 'r.--')
plt.subplot(3, 2, 6)
plt.plot(x, y, 'g*')
```


```python
x = np.arange(1, 10)
y = x * x

plt.plot(x, y, 'ro')
plt.xlabel('X-Axis')
plt.ylabel('Y-Axis')
plt.title('Graph')
plt.show()
```
Sinewave:

```python
x = np.arange(0, 4 * np.pi, 0.1)
y = np.sin(x)

plt.title('Sine Wave')
plt.plot(x, y)
plt.show()
```
Sinewave and Coswave:

```python
x = np.arange(0, 6 * np.pi, 0.1)
y_sin = np.sin(x)
y_cos = np.cos(x)

plt.subplot(2, 1, 1)
plt.plot(x, y_sin, 'y-')
plt.title('Sine Wave')
plt.show()

plt.subplot(2, 1, 2)
plt.plot(x, y_cos, 'b-')
plt.title('Cos Wave')
plt.show()
```
Bargraph:

```python
x = [2, 4, 6]
y = [3, 5, 7]
x2 = [12, 14, 16]
y2 = [13, 15, 17]

plt.bar(x, y, color='b')
plt.bar(x2, y2, color='y')
plt.title("Bar Graph")
plt.show()
```
Histogram:

```python
a = np.array([34, 65, 79, 90, 82, 10, 94, 39, 34, 92, 72, 49])
plt.hist(a)
plt.title("Histogram")
plt.show()
```
BoxPlot:

```python
a = [np.random.normal(0, std, 100) for std in range(1, 4)]
plt.boxplot(a, vert=True, patch_artist=True)
plt.show()
```

```python
plt.boxplot(a, vert=False, patch_artist=False)
plt.show()
```
PieChart:

```python
labels = ['RCB', 'CSK', 'MI', 'SRH']
sizes = [250, 250, 250, 250]
colors = ['red', 'yellow', 'blue', 'orange']
explode = (0.4, 0, 0, 0)

plt.pie(sizes, explode=explode, labels=labels, colors=colors, autopct='%.1f')
plt.axis('equal')
plt.show()
```

# Output:

<img width="630" height="457" alt="Screenshot 2026-03-10 160406" src="https://github.com/user-attachments/assets/18b3eb2f-bcd0-4698-b7c2-5b9de0b3f412" />


<img width="638" height="495" alt="Screenshot 2026-03-10 160438" src="https://github.com/user-attachments/assets/f9732b01-522e-43bd-ba43-8011bd0cfd62" />


<img width="654" height="478" alt="Screenshot 2026-03-10 160508" src="https://github.com/user-attachments/assets/a9c2a6dc-802c-47c2-aa25-031f723c0634" />


<img width="626" height="466" alt="Screenshot 2026-03-10 160540" src="https://github.com/user-attachments/assets/12dcb7fa-6f12-4e89-907d-5377e559613b" />


<img width="718" height="484" alt="Screenshot 2026-03-10 160604" src="https://github.com/user-attachments/assets/b9d743ce-c568-40f2-a4a6-dc5b4aac2182" />


<img width="678" height="519" alt="Screenshot 2026-03-10 160629" src="https://github.com/user-attachments/assets/18506c7e-41be-43e9-abbd-0191a8742541" />


<img width="667" height="511" alt="Screenshot 2026-03-10 160656" src="https://github.com/user-attachments/assets/8d8c7a91-b728-49e8-a560-c33d0083fa70" />


<img width="631" height="488" alt="Screenshot 2026-03-10 160719" src="https://github.com/user-attachments/assets/1813f638-dcdb-4b38-8a6b-5118aecbb028" />


<img width="589" height="484" alt="Screenshot 2026-03-10 160828" src="https://github.com/user-attachments/assets/e6259224-538e-47e2-94b3-f83db03cf351" />


<img width="606" height="457" alt="Screenshot 2026-03-10 161156" src="https://github.com/user-attachments/assets/235e0b76-df8c-4eb1-a370-383f17d77e17" />


<img width="457" height="420" alt="Screenshot 2026-03-10 161238" src="https://github.com/user-attachments/assets/d04eb844-a3c5-4515-a3a9-884e123deb33" />

















# Result:

Thus the Data visualisation was successfully done with the MatPlotlib.
 
