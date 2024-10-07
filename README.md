# DATE :
# EXP NO : 6
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


def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python


def max_marks(marks):
    large=marks[len(marks)-1]
    marks.sort(reverse=True)
    large=marks[0]
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(marks):
    maxmark=0
    for i in marks:
        if i>maxmark:
            maxmark=i
    return maxmark

```



## Output:
i]# To find the maximum of marks using the list method sort.

![Screenshot 2024-03-30 180928](https://github.com/ANU23000217/FindMaximum/assets/139117108/d2d4244e-d3bb-4a47-9d22-5d50083fe200)


ii]# To find the maximum marks using the list method max().

![Screenshot 2024-03-30 180937](https://github.com/ANU23000217/FindMaximum/assets/139117108/1e1e43cc-12d7-43a0-8bf4-236cb874ebd4)



iii]# To find the maximum marks without using builtin functions.

![Screenshot 2024-03-30 180948](https://github.com/ANU23000217/FindMaximum/assets/139117108/e2cca978-a39e-40d5-9d4b-152fa9167661)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
