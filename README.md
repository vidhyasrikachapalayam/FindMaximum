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

Program to mark the maximum of marks using the list method sort

Developed by: vidhyasri.k

RegisterNumber: 22008468

def max_marks(marks):

    marks.sort()

    large = marks[-1]

    return large




ii)	# To find the maximum marks using the list method max().


Developed by: vidhyasri.k

RegisterNumber: 22008468


def max_marks(marks):

   large = max(marks)

   return large




iii) # To find the maximum marks without using builtin functions.

Program to the maximum marks without using builtin functions.

Developed by: vidhyasri.k

RegisterNumber: 22008468

def max_marks(list1):

    max = list1[0]

    for i in list1:

        if i > max:

            max = i

    return max




## Output:
maximum of marks using the list method sort
![maximum1](https://user-images.githubusercontent.com/119477817/215276052-dccf7e8b-0a3e-41ea-91a7-43d0bf863bf8.png)


maximum marks using the list method max().

![maximum2](https://user-images.githubusercontent.com/119477817/215276069-de436536-cb2a-4248-bd86-61944a7512bd.png)


 maximum marks without using builtin functions.
![maximum3](https://user-images.githubusercontent.com/119477817/215276078-4ac4cce5-3593-48d0-97d9-59b1ca560b3e.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
