this programm use Merge sort algorithm to sort a list of unordered number. In main function program will search for a nasir.txt file to read input data from it.if compiler does not found data file , it will create a file and will populate it with a number of values
Quick sort->
A sorting technique that sequences a list by continuously dividing the list into two parts and moving the lower items to one side and the higheritems to the other. It starts by picking one item in the entire list to serve as a pivot point. The pivot could be the first item or a randomly chosen one. All items that compare lower than the pivot are moved to the left of the pivot;all equal or higher items are moved to the right. It then picks a pivot for the left side and moves those items to left and right of the pivot and continues the pivot picking and dividing until there is only one item left in the group. It then proceeds to the right side and performs the same operation again. 

input values:
povit=2		2,3,4,5,6-7 ==> -7,2,3,4,5,6
		/	\
	     -7       	(3,4,5,6)      povit=3
	          		 /    \
	                           	      4,5,6     povit=4
			      /     \
				5,6	povit=5  
	            	      	           /     \
				       6
	             	  	
output value:-7,2,3,4,5,6
Complexity:	n(logn)
