
The moveZeroes function rearranges elements in the array nums by moving all zeros to the end while preserving the order of non-zero elements. 
It uses a two-pointer technique: non_zero to track the position for the next non-zero element and current to scan through the array. 
As it traverses the array, each non-zero element is swapped with the element at the non_zero pointer, then non_zero is incremented. 
This approach efficiently moves zeros to the end of the array in-place with O(n) time complexity and no additional space.
