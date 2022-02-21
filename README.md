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
  a=max(marks)
  return a


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    # write your code here
    a=max(marks)
    return a


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max_mark=0
    for i in list1:
        if i>max_mark:
            max_mark=i
    return max_mark


```
## Sample Input and Output
![Screenshot (27)](https://user-images.githubusercontent.com/94828604/154983479-dc8bbc1b-3522-4c91-99c8-13c41b0e130d.png)


## Output:
![Screenshot (29)](https://user-images.githubusercontent.com/94828604/154983991-58c7c3ba-758b-4777-be7b-f5feea51aecf.png)
![Screenshot (33)](https://user-images.githubusercontent.com/94828604/154984603-2647cfe3-8a99-4ef5-a126-0a3df8746782.png)
![Screenshot (34)](https://user-images.githubusercontent.com/94828604/154984818-3ddfbbc9-8794-4991-8cbd-3b7614800443.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
