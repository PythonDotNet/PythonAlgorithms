this programm use Merge sort algorithm to sort a list of unordered number. In main function program will search for a nasir.txt file to read input data from it.if compiler does not found data file , it will create a file and will populate it with a number of values
merge sort->
A sorting technique that sequences data by continuously merging items in the list. Every single item in the original unordered list is merged with another, creatinggroups of two. Every two-item group is merged,creating groups of four and so on until there is one ordered list.

input values:
		2,3,4,5,6-7 ==> -7,2,3,4,5,6
		/	\
(2,3,4)	     2, 3 ,4	5,6,-7	(-7,5,6)
	    /      \		/     \
(3,4)	2        3,4         5          6,-7	(-7,6)
	        /     \	      /      \
	   3          4	  6	-7
output value:-7,2,3,4,5,6
Complexity:	n(logn)
