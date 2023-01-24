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

i)	To find the maximum of marks using the list method sort.
```python
Program to mark the maximum of marks using the list method sort
Developed by: Mohanish.K
RegisterNumber: 22002294

def max_marks(marks):
    #Write your code here
    marks.sort()
    large = marks[-1]
    return large
```



ii)	To find the maximum marks using the list method max().
```python
Program to find the maximum marks using the list method max().
Developed by:Mohanish.K
RegisterNumber:22002294

def max_marks(marks):
    # write your code here
    large = max(marks)
    return large
 ```


iii)  To find the maximum marks without using builtin functions.
```python
Program to the maximum marks without using builtin functions.
Developed by:Mohanish.k
RegisterNumber: 22002294

def max_marks(list1):
    # write your code here
    max = list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
 ```
    

## Sample Input and Output
# i)
![input](./img/max_marks1.jpg) 
# ii)
![findmaximum2](https://user-images.githubusercontent.com/111619160/214207894-ae8cd928-66d5-412e-ba4b-1f24c5003b3d.png)

# iii)
![WhatsApp Image 2023-01-24 at 9 10 16 AM](https://user-images.githubusercontent.com/111619160/214207900-76760769-20f5-470b-a91f-858abb0bad50.jpeg)


## Output:
![WhatsApp Image 2023-01-24 at 9 10 17 AM](https://user-images.githubusercontent.com/111619160/214207907-9497a950-26d0-48d1-bdf3-193a1034b40f.jpeg)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
