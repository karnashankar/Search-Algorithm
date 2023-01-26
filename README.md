# Linear Search and Binary search
## Aim:
To write a program to perform linear search and binary search using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Linear Search:
1.	Start from the leftmost element of array[] and compare k with each element of array[] one by one.
2.	If k matches with an element in array[] , return the index.
3.	If k doesn’t match with any of elements in array[], return -1 or element not found.
## Binary Search:
1.	Set two pointers low and high at the lowest and the highest positions respectively.
2.	Find the middle element mid of the array ie. arr[(low + high)/2]
3.	If x == mid, then return mid.Else, compare the element to be searched with m.
4.	If x > mid, compare x with the middle element of the elements on the right side of mid. This is done by setting low to low = mid + 1.
5.	Else, compare x with the middle element of the elements on the left side of mid. This is done by setting high to high = mid - 1.
6.	Repeat steps 2 to 5 until low meets high
## Program:
### i)Use a linear search method to match the item in a list.
```
 #Program for linear Search Method to match the item in a list
 #Developed By:karna s
 #RegisterNo:22008977

```
![](1.png)
### ii)Find the element in a list using Binary Search(Iterative Method).
```
 #Program to find the Element in a list using Binary Searh(Iterative Method)
 #Developed By:karna s
 #RegisterNo:22008977
```
![](2.png)
### iii)Find the element in a list using Binary Search (recursive Method).
```
 #Program to find the element in a list using Binary Search (recursive Method)
 #Developed By:karna s
 #RegisterNo:22008977
```
![](3.png)
## Sample Input and Output
### i)
![](11.png)
### ii)
![](22.png)
### iii)
![](33.png)


## Result
  Thus the linear search and binary search algorithm is implemented using python programming.