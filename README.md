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
Developed by: DHARSHINIYAA K S
RegisterNumber: 23014039
def max_marks(marks):
    marks.sort()
    x=marks[-1]
    return x
```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: DHARSHINIYAA K S
RegisterNumber: 23014039
'''
def max_marks(marks):
    marks.sort()
    a=marks[-1]
    return a
```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: DHARSHINIYAA K S
RegisterNumber: 23014039
'''
def max_marks(list1):
    list1.sort()
    m=list1[-1]
    return m
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-12-29 104844](https://github.com/Dharshiniyaaks/FindMaximum/assets/155055420/508d2585-1734-4ee6-a623-87a82c65bb43)
![Screenshot 2023-12-29 105026](https://github.com/Dharshiniyaaks/FindMaximum/assets/155055420/47aea02a-c03a-46d5-9b67-f56d743f7601)
![Screenshot 2023-12-29 105316](https://github.com/Dharshiniyaaks/FindMaximum/assets/155055420/f71c3e90-66cf-46c2-8a7a-972e9f8bbed2)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
