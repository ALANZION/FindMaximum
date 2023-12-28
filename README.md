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
```Python
Program to mark the maximum of marks using the list method sort
Developed by: ALAN ZION H
RegisterNumber:212223240004 
```
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: ALAN ZION H
RegisterNumber: 212223240004
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: ALAN ZION H
RegisterNumber: 212223240004
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-12-28 163425](https://github.com/ALANZION/FindMaximum/assets/145743064/0ceac1b5-c38d-4734-924d-5c1836c79fc9)

![Screenshot 2023-12-28 163644](https://github.com/ALANZION/FindMaximum/assets/145743064/d6e8ede4-e97b-4219-8edc-696b19d71af9)

![Screenshot 2023-12-28 163813](https://github.com/ALANZION/FindMaximum/assets/145743064/83ec201a-64c8-4078-8dd2-bdb68217c5d8)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
