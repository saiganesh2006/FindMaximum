# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```
Program to mark the maximum of marks using the list method sort
Developed by: D.B.V.SAI GANESH
RegisterNumber: 23009248
def max_marks(marks):
    a=sorted(marks)
    b=a[-1]
    return b
```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: D.B.V.SAI GANESH
RegisterNumber: 23009248

def max_marks(marks):
    a=max(marks)
    return a
```
iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: D.B.V.SAI GANESH
RegisterNumber: 23009248

def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-11-28 125542](https://github.com/saiganesh2006/FindMaximum/assets/145742342/38feb630-4d69-41ff-9c73-71d00d3d6884)

![Screenshot 2023-11-28 125558](https://github.com/saiganesh2006/FindMaximum/assets/145742342/38874114-99e7-4ff1-983e-b2f519b023e9)

![image](https://github.com/saiganesh2006/FindMaximum/assets/145742342/085829b3-61af-4d31-9bfe-f1505209fe60)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
