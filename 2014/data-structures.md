# data structures
when you want to think about those other data structures, maybe you don't really need but intellectually stimulating... All you really _need_ is an array
## tradoffs - how are you interacting with the data
* time
* space
* complexity

## complexity notation
* O(1) - constant time
* O(n) - linearly based on size of data
* O(log n) - proportionally to the log of n 
* ...

## arrays
* access - constant time O(1)
* insert/delete - o(n)
* linear space

## linked list
* add to head/tail - constant time
* insert (have to find) - O(n)
* delete (doubly linked and not find) - O(1)
* access - O(n)

## trees
* binary trees
	* node has at most 2 children
	* full binary tree -> all children have 0 or 2 children
	* perfect binary tree -> all at the same depth (aka a family tree)
* binary search trees -> comparanble and left child is smaller than right
	* linear space
	* O(log n) search
* red black tree
	* causes rebalancing when rules broken
* merkle trees
	* cassandra and git and bit coin

