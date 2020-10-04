# linked-list with trim
It is the same Implementation as containers/list with the addition of 2 trim functions
It allows to trim the linked list both from left and right side up to/from an element of it.
The impemenation could be super performant O(1) if it was not needed to update the length of the resulting
List. But to achieve the correct length after the trim, we need to iterate over the trimmed elements to know 
how many elements have been removed(taking advantage of the iteration to remove the links as well to help the GC)
