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
Developed by: BOOBESH PM
RegisterNumber:23000342 
'''
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max
```
ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: BOOBESH PM
RegisterNumber:23000342 
'''
def max_marks(marks):
    max_val=max(marks)
    return max_val
```
iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: BOOBESH PM
RegisterNumber: 23000342
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max
```
## Sample Input and Output
![image](https://github.com/Boobeshkrishna/FindMaximum/assets/141472052/466fe4a7-bbcc-4e9b-add4-39ee39ec03e9)
![image](https://github.com/Boobeshkrishna/FindMaximum/assets/141472052/3eed0f24-8bb1-4a32-9b7c-fe47deb08eba)
![image](https://github.com/Boobeshkrishna/FindMaximum/assets/141472052/70f8e035-c49d-4be1-872d-7232a61c34f7)
## Output:
![3 a1](https://github.com/Boobeshkrishna/FindMaximum/assets/141472052/30ec092b-94ee-49d2-aff9-547955a43ad6)
![3 a2](https://github.com/Boobeshkrishna/FindMaximum/assets/141472052/0827c7ea-0a4b-47da-b670-9cba081aa3e2)
![3 a3](https://github.com/Boobeshkrishna/FindMaximum/assets/141472052/02666db2-a779-4958-91f8-8db178cbabda)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
