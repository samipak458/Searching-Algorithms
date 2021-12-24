# Searching Algorithms

## Linear Search (In Singly Linked List)

It is simplest searching algorithm in which you check element (which you want to find) from every node of linked list. If it matched it prints the statement **Searched element found at index N)**. Else it prints the statement **Searched element not found at any index**. You can also return index at which element found and -1 if match not found. It depends on function you’re creating.

![](https://www.w3resource.com/w3r_images/c-linked_list-exercise-10-image.png)

**Image Reference:** [W3Resource](https://www.w3resource.com/c-programming-exercises/linked_list/c-linked_list-exercise-10.php)

***Note: There is no index in Linked List. In this algorithm we are giving indexes to every node by ourselve.***

### Algorithm

1)	Function(head, searchValue)
2)	Set currentNode = head
3)	Set position = 1
4)	While CurrentNode != NULL
5)	If CurrentNode.Data == searchValue
6)	return Position
7)	End If
8)	Set Position++
9)	Set CurrentNode = CurrentNode.Next
10) End while
11)	Function end

### Time Complexity is O(N)

For searching the value in linked list depends upon number of iterations.




