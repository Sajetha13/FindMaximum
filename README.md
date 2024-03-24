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
    return max(marks)



```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(marks):
    max_mark = marks[0] 
    for mark in marks:
        if mark > max_mark:
            max_mark = mark
    return max_mark


```



## Output:
![Screenshot 2024-03-24 203648](https://github.com/Sajetha13/FindMaximum/assets/138849316/5ddf81b5-c358-48f0-a8a7-f9bfccbc5122)
![Screenshot 2024-03-24 203857](https://github.com/Sajetha13/FindMaximum/assets/138849316/51939da3-cb67-4edd-8912-fed04698a49c)

![image](https://github.com/Sajetha13/FindMaximum/assets/138849316/7754eb09-47a5-46ca-9aa4-a5ec7a5421db)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
