this program shows the implemenatataion of tree data structure. basic opertaion e.g. insertiondeletion, sorting and searching property is performed on list.
Tree datastructure 
 a tree is a widely used abstract data type (ADT) or data structure implementing this ADT that simulates a hierarchical tree structure, with a root value and subtrees of children, represented as a set of linked nodes.
input: 5,6,7,5,7,8,6,4,3,2
output:2,3,4,5,6,7(dublication of elements is eliminated)
		           root
		       /           \
	      leftchild	     rightchild
                  /       \	      		 /        \
   leftchild   rightchild          leftchild   rightchild
. . .		. . . 	      . . .               . . .
insertion Complexity:	worst case ==>O(logn), average best case O(logn)
searching Complexity:	worst case ==>O(logn), average best case O(logn)
deletion Complexity :	worst case ==>O(logn), average best case O(logn)
sorting Complexisty :  O(nlogn)
 
