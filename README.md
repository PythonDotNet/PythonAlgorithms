# AlgorithmsInPython
This repo contain Searching algorithms python with sorting using values and pointer, tree data structure ,Log algorithms,Finding series in given number of list and Interfaces implementation.
### Algorithm
###### DEFINITION 
An algorithm is a sequence of unambiguous instructions for solving a problem.

### Selection sort
A sorting technique that is typically used for sequencing small lists. It starts by comparing the entire list for the lowest item and moves it to the #1 position. It then compares the rest of the list for the next-lowest item and places it in the #2 position and so on until all items are in the required order. Selection sorts perform numerous comparisons, but fewer data movements than other methods input values.<br/>
**Time Complexity**	Best	Average O(n<sup>2</sup>)	Bubble Sort	O(n<sup>2</sup>)

### Bubble sort
Sometimes referred to as sinking sort, is a simple sorting algorithm that works by repeatedly stepping through the list to be sorted, comparing each pair of adjacent items and swapping them if they are in the wrong order.<br/>
**Time Complexity**	Best	Average O(n)	Bubble Sort	O(n<sup>2</sup>)

### Insertion sort
A sorting algorithm that inserts each item in the proper place into an initially empty list by comparing it with each item in the list until it finds the new element's successor or the end of the list. <br/>
**Time Complexity**	Best	Average O(n)	Bubble Sort	O(n<sup>2</sup>)

### Merge sort
A sorting technique that sequences data by continuously merging items in the list. Every single item in the original unordered list is merged with another, creating groups of two. Every two-item group is merged, creating groups of four and so on until there is one ordered list.<br/>
**Time Complexity**	Best	Average  O(n log(n))	 Bubble Sort		O(n log(n))

### Quick sort
A sorting technique that sequences a list by continuously dividing the list into two parts and moving the lower items to one side and the higher items to the other. It starts by picking one item in the entire list to serve as a pivot point. The pivot could be the first item or a randomly chosen one. All items that compare lower than the pivot are moved to the left of the pivot; all equal or higher items are moved to the right. It then picks a pivot for the left side and moves those items to left and right of the pivot and continues the pivot picking and dividing until there is only one item left in the group. It then proceeds to the right side and performs the same operation again. <br/>
**Time Complexity**	Best	Average  O(n log(n))	 Bubble Sort		O(n log(n))

### Heap sort
A sorting algorithm that works by first organizing the data to be sorted into a special type of binary tree called a heap. The heap itself has, by definition, the largest value at the top of the tree, so the heap sort algorithm must also reverse the order input values.

### Tree data structure 
 A tree is a widely used abstract data type (ADT) or data structure implementing this ADT that simulates a hierarchical tree structure, with a root value and subtrees of children, represented as a set of linked nodes.<br/>
**Insertion Complexity:**	worst case O(logn), average best case O(logn)<br/>
**Searching Complexity:**	worst case O(logn), average best case O(logn)<br/>
**Deletion Complexity:**	worst case O(logn), average best case O(logn)<br/>
**Sorting Complexity:**  O(nlogn)

### AVL tree
<p>An AVL tree is another balanced binary search tree. Named after their inventors, Adelson-Velskii and Landis, they were the first dynamically balanced trees to be proposed. Like red-black trees, they are not perfectly balanced, but pairs of sub-trees differ in height by at most **1**, maintaining an **O(logn)** search time. Addition and deletion operations also take O(logn) time.</p>
#######Definition of an AVL tree
An AVL tree is a binary search tree which has the following properties:<br/>
<ol>
<li>The sub-trees of every node differ in height by at most one.</li>
<li>Every sub-tree is an AVL tree.</li>
</ol>
**Search Complexity:**	worst case O(logn), average best case O(logn)<br/>
**Insert Complexity:** worst case O(logn), average best case O(logn)<br/>
**Delete Complexity:**	worst case O(logn), average best case O(logn)<br/>
### Red Black tree
<p>A red–black tree is a kind of self-balancing binary search tree. Each node of the binary tree has an extra bit, and that bit is often interpreted as the color (red or black) of the node. These color bits are used to ensure the tree remains approximately balanced during insertions and deletions.</p>
######Properties
<ol>
<li>A node is either red or black.</li>
<li>The root is black. This rule is sometimes omitted. Since the root can always be changed from red to black, but not necessarily vice versa, this rule has little effect on analysis.</li>
<li>All leaves (NIL) are black.</li>
<li>If a node is red, then both its children are black.</li>
<li>Every path from a given node to any of its descendant NIL nodes contains the same number of black nodes. Some definitions: the number of black nodes from the root to a node is the node's black depth; the uniform number of black nodes in all paths from root to the leaves is called the black-height of the red–black tree.</li>
</ol>
