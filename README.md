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
NAME: SHARON STEFFANI.F

REG NO : 212223110049

DEP:CSE(IOT)

## Program:

i)	# To find the maximum of marks using the list method sort.
```
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    max_num=list1[0]
    for i in list1:
        if i>max_num:
            max_num=i
    return max_num
```

## Output:

![image](https://github.com/Sharonsteffani2005/FindMaximum/assets/144979934/428b8da1-e578-4eaa-8bea-a9a1f2742341)

![image](https://github.com/Sharonsteffani2005/FindMaximum/assets/144979934/b0987ab7-4a8c-44a8-ad7f-7750cecc6f58)

![image](https://github.com/Sharonsteffani2005/FindMaximum/assets/144979934/6b8a230d-2466-4c0d-b84d-9f9ef5707768)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
