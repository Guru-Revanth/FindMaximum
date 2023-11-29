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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: GURU REVANTH KUMARAVEL RADHIKA
RegisterNumber: 23004484
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: GURU REVANTH KUMARAVEL RADHIKA
RegisterNumber: 23004484
'''
def max_marks(marks):
    # write your code here
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: GURU REVANTH KUMARAVEL RADHIKA
RegisterNumber: 23004484
'''
def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input and Output
i)
![Alt text](q1-1.png)

ii)
![Alt text](q2-1.png)

iii)
![Alt text](q3-1.png)

## Output:
i) # Program to mark the maximum of marks using the list method sort.
![Alt text](ans1-1.png)

ii) # Program to find the maximum marks using the list method max().
![Alt text](ans2-1.png)

iii) # Program to find the maximum marks without using builtin functions.
![Alt text](ans3-1.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.