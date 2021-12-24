#Searching Algorithms
## Linear Search (In Singly Linked List)

It is simplest searching algorithm in which you check element (which you want to find) from every node of linked list. If it matched it prints the statement *Searched element found at index N). Else it prints the statement *Searched element not found at any index*. You can also return index at which element found and -1 if match not found. It depends on function you’re creating.
*Note: There is no index in Linked List. In this algorithm we are giving indexes to every node by ourselve.*

##Algorithm
i.	Function(head, searchValue)
ii.	Set currentNode = head
iii.	Set position = 1
iv.	While CurrentNode != NULL
v.	If CurrentNode.Data == searchValue
vi.	return Position
vii.	End If
viii.	Set Position++
ix.	Set CurrentNode = CurrentNode.Next
x.	End while
xi.	Function end

Time Complexity is O(N) 
For searching the value in linked list depends upon number of iterations.




