Knight (Intermediate): This mode focuses on a thorough understanding of sorting algorithms and proficiency in intermediate data structures. Participants must be capable of answering fill-in-the-blank questions in under 3 minutes. Points are awarded based on the correctness and speed of the answers.

SORTING, SEARCHING, BASIC DATA STRUCTURES LIKE ARRAYS AND LINKED LISTS

<span style="color:rgb(0, 168, 73)">DATA STRUCTURE</span> - is<span style="color:rgb(255, 174, 0)"> method of organizing data</span> in a way that allows for efficient <span style="color:rgb(255, 174, 0)">storage, retrieval, and manipulation of information</span>.

<span style="color:rgb(0, 168, 73)">ALGORITHM</span> - a <span style="color:rgb(255, 174, 0)">step-by-step procedure or a set of well-defined rules and instructions</span> that are followed to solve a specific problem or perform a particular task.

<span style="color:rgb(0, 168, 73)">NON-HOMOGENEOUS DATA STRUCTURE</span> - The elements may or may not be the same data type

<span style="color:rgb(0, 168, 73)">STATIC DATA STRUCTURES</span> - Those whose sizes and structures associated memory locations are <span style="color:rgb(255, 174, 0)">fixed, at compile time.</span> 

<span style="color:rgb(0, 168, 73)">HOMOGENEUOS DATA STRUCTURE </span>-  Represent a structure <span style="color:rgb(255, 174, 0)">whose elements are of the same type. </span>

NON- LINEAR - The data items are not in sequence.

<span style="color:rgb(0, 168, 73)">LINEAR DATA STRUCTURE</span> - The data items are arranged in a linear sequence

<span style="color:rgb(0, 168, 73)">SORT</span> - Sorting data in a particular order (ascending or descending).

<span style="color:rgb(0, 168, 73)">LINKED LIST</span> -  A linked list stores a collection of items in a linear order. Each element, or node, in a linked list contains a data item as well as a reference, or link, to the next item in the list.

<span style="color:rgb(255, 174, 0)">TIME COMPLEXITY</span> - a way to represent the amount of time required by the program to run till its completion. It's generally a good practice to try to keep the time required minimum, so that our algorithm completes its execution in the minimum time possible.

<span style="color:rgb(255, 174, 0)">LINKED LISTS</span> - Stores a collection of items in a linear order. Each element, or node, in a linked list contains a data item as well as a reference, or link, to the next item in the list.

<span style="color:rgb(0, 168, 73)">UPDATE</span> - It updates the data in the data structure. You can also update any specific data by giving some condition in a loop, like the select approach.

SELECTION - It selects specific data from present data. You can select any specific data by giving a condition in a loop.

# <span style="color:rgb(0, 168, 73)">Quick Sort</span>

- <span style="color:rgb(0, 168, 73)"> FASTEST SORTING ALGORITHM</span>
QUICK SORT - Has a <span style="color:rgb(255, 174, 0)">PIVOT</span> and <span style="color:rgb(255, 174, 0)">PARTITION</span>
-  <span style="color:rgb(255, 174, 0)">*divide and conquer algorithm*</span>. 
		Quick sort first partitions a large array into two smaller sub-arrays. 
		Recursively sorts the sub-arrays.

- <span style="color:rgb(255, 174, 0)">INSERTION SORT</span> is used to sort the sub-arrays

![Quick Sort](/images/QuickSort.png)

# <span style="color:rgb(0, 168, 73)">Bubble Sort </span>
- Two for loops, one nested in the other
- Multiple swap per pass

![Bubble Sort](/images/BubbleSort.png)

# <span style="color:rgb(0, 168, 73)"><span style="color:rgb(0, 168, 73)">Selection Sort</span></span>
- as the arrows progress, it finds the smallest number and swaps is
- Iterative Algorithm
- one swap per pass

![Selection Sort](/images/SelectionSort.png)

# <span style="color:rgb(0, 168, 73)">Merge Sort</span>

- <span style="color:rgb(255, 174, 0)">Divide-and-Conquer algorithm</span>
- Can Sort large scale of data

<span style="color:rgb(0, 168, 73)">MERGE</span> - Merging data of two different orders in a specific order may ascend or descend. We use merge sort to merge sort data.

![Merge Sort](/images/MergeSort.png)

# <span style="color:rgb(0, 168, 73)">Insertion Sort</span>

- <span style="color:rgb(255, 174, 0)">DIVIDE AND CONQUER ALGORITHMS</span>-  recursively breaking them into smaller subproblems, solving each one independently, and then combining the results. This approach is effective for tasks like sorting, as seen in Merge Sort and Quick Sort.
 
- **<span style="color:rgb(255, 174, 0)">GREEDY ALGORITHMS</span>** - These algorithms make a series of choices, each of which looks the best at the moment, with the hope that these local optima will lead to a global optimum. 

- <span style="color:rgb(255, 174, 0)">DYNAMIC PROGRAMMING</span> - This approach solves problems by breaking them down into <span style="color:rgb(255, 174, 0)">overlapping subproblems</span> and storing the results of subproblems to avoid redundant computations. 

Example of "<span style="color:rgb(0, 168, 73)">DYNAMIC PROGRAMMING</span>" - Fibonacci sequence calculation, Knapsack problem.

![Array and Linked List Sort](/images/ArrayLinkedList.png)

- **Binary Search**:
![Binary Search](/images/BinarySearch.png)
- **Linear Search**: 
![Linear Search](/images/LinearSearch.png)

<span style="color:rgb(0, 168, 73)">LINEAR SEARCH</span> - also known as SEQUENTIAL SEARCH


- <span style="color:rgb(255, 174, 0)">ARRAYS</span> - An array stores a collection of items at adjoining memory locations. Items that are the same type get stored together so that the position of each element can be w calculated or retrieved easily. 

- ARRAY -  one of the simplest data structures, consisting of a collection of elements, each identified by an index or a key. Defined as a finite set of elements having the same type referenced under a common name.

- Each individual data is called an array "<span style="color:rgb(255, 174, 0)">ELEMENT</span>" or a "<span style="color:rgb(255, 174, 0)">KEY</span>" and must be of the same type and size.

<span style="color:rgb(0, 168, 73)">ONE-DIMENSIONAL ARRAY</span> - Where data is arrayed in a line.


![Linear Search](/images/LinearSearch.png)
 
 # **Singly Linked List**
- <span style="color:rgb(255, 174, 0)">Simple Linked List or Singly Linked List</span> – navigation in the list is forward only. In this type of linked list, every node stores address or reference of next node in list and the last node has next address or reference as NULL
![Singly Linked List](/images/SinglyLinkedList.png)

# **Doubly Linked List**

![Doubly Linked List](/images/DoublyLinkedList.png)

 <span style="color:rgb(0, 168, 73)">DOUBLY LINKED LIST</span>– Navigation through the list can be both ways – forward and backward. There are two references associated with each node, One of the reference points to the next node and one to the previous node. 

# **Circular Linked List Linked List**

- In a Circular linked list linked list the last item contains the link of the 1st element ad next and the 1st element has a link to the last element as previous
- <span style="color:rgb(255, 174, 0)">CIRCULAR LINKED LIST</span> – The last item (TAIL) in the list contains a link to the first element (HEAD) as next and the first element has a link to the last element as previous. Circular linked list is a linked list where all nodes are connected to form a circle. There is no NULL at the end. A circular linked list can be a singly circular linked list or doubly circular linked list. Advantage of this data structure is that any node can be made as starting node. This is useful in implementation of circular queue in linked list.
![Circular Linked List](/images/CircularLinkedList.png)
____________________________________________________________________
1. The <span style="color:rgb(255, 174, 0)">"HEAD"</span> points to the first node in a linked list.
2. A data structure that points to an object of the same type as itself is known as a <span style="color:rgb(255, 174, 0)">"SELF REFERENTIAL"</span> data structure.
3. After creating a linked list's head pointer, you should make sure it points to "<span style="color:rgb(255, 174, 0)"><span style="color:rgb(255, 174, 0)">NULL</span></span>" before using it in any operations.
4. <span style="color:rgb(255, 174, 0)">APPENDING</span> - a node means adding it to the end of a list.
5. <span style="color:rgb(255, 174, 0)">INSERTING</span> - a node means adding it to a list, but not necessarily to the end.
6. <span style="color:rgb(255, 174, 0)">TRAVERSING</span> - Traveling through the list and visit the element stored in it.  It visits data in a systematic manner.

**DYNAMIC STRUCTURES** - are those which expands or shrinks depending upon the program need and its execution. Also, their associated memory locations changes. 

**LINKED LIST** - a type of dynamic structure

- DATA  - ITEM inside the node
What are the basic components of a linked list?
	Data members for the information to be stored and a link to the next item
		consists of <span style="color:rgb(0, 168, 73)"><span style="color:rgb(255, 174, 0)">nodes</span></span>, where each node <span style="color:rgb(0, 168, 73)">contains data and a reference to the next node</span>.

INSERTION - Add an element in the given data structure . Insert one or more data elements into an array. Based on the requirement, a new element can be added at the beginning, end, or any given index of the array.
<span style="color:rgb(255, 174, 0)">DELETION </span>- Delete an element in the given data structure. Deletion refers to removing an existing element from the array and reorganizing all elements of an array.
# <span style="color:rgb(255, 174, 0)">DISPLAY / DISPLAYING</span>
- Displays the complete list.


<span style="color:rgb(255, 174, 0)">SEARCH / SEARCHING</span> -  finding a particular element in the given data structure or searches an element using the given key. With this operation, you can search for an item in an array based on a given value (or through an index).

TRAVERSE -  This operation traverses through the elements of an array meaning we print all the array elements one by one as we visit  the element stored in it.  It visits data in a systematic manner.

**NODE** - In linear data structure where each element is called 
 **DATA** -The actual value or information stored in the node.
 **NEXT POINTER** -A REFERENCE to the next node in the sequence.


![Winner Winner Chicken Dinner](/images/WinnerWinnerChickenDinner.png)
