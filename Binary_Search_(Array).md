# Searching Algorithms

## Binary Search (In Array)

It finds searched value faster than linear search. In binary search, first you have to find mid. For finding mid you need two things: **left** and **right**. Left is the starting index of array which is 0 and Right is the last index of an array (size-1). We calculate mid by adding left + right and dividing it by 2. After finding mid, you check it with searched value (searchedValue == array[mid]). If searched value is found then we print statement **Searched element found at mid**. Else If (array[mid]) < searchedValue ), we will update left, left will be **mid + 1**. Else we will update right, right will be *mid – 1*. This process will continue until (left <= right). If element not found print statement **Searched element not found**. 

![](https://www.geeksforgeeks.org/wp-content/uploads/Binary-Search.png)

**Image Reference:** [GeeksForGeeks](https://www.geeksforgeeks.org/binary-search/)


***Note: It you are creating function with return type, you will return mid if element found and -1 if element is not found*.**

***Note: Mid is index, we’re finding index then putting in array like array[mid]*.**

### Algorithm
1)	Create Array array[5]={1,2,3,4,5} or take input for array.
2)	Input value you want to search in array.
3)	Store in variable searchedValue
4)	While (left <= right)
5)	If (searchedValue == array[mid])
6)	Print Searched element found at mid
7)	Else If (array[mid]) < searchedValue )
8)	Left = mid + 1
9)	Else
10)	Right = mid  - 1
11)	End While

### Time Complexity is O(N) 
N is size of array. For searching the value in array depends upon number of iterations.




