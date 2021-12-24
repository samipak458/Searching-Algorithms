# Searching Algorithms

## Linear Search (In Array)

It is simplest searching algorithm in which you check element (which you want to find) from every element of an array. If it matched it prints the statement **Searched element found at index N)**. Else it prints the statement **Searched element not found at any index**. You can also return index at which element found and -1 if match not found. It depends on function you’re creating.

### Algorithm

1)	Create Array array[5]={1,2,3,4,5} or take input for array.
2)	Input value you want to search in array.
3)	Store in variable searchedValue
4)	Set for loop 0 to size-1 of array [ for(int i=0;  i<size; i++) ]
5)	Set condition If(searchedValue == array[i])
6)	Print Searched element found at index i
7)	Else
8)	Print Searched element not found at any index
9)	End For Loop

### Time Complexity is O(N) 

N is size of array. For searching the value in array depends upon number of iterations.



