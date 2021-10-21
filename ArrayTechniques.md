Pattern Finding
===============
1. Is it AP ?
2. Can we use the factors between the numbers ?



Important Problems - Kadenes principle
=====================================
1. Find the maximum Sub Array - O(n)
2. Flip 1s and 0s in a given array and find the maxium subarray with 1s


Compare the previous and next ( Max and Min) and find out the water clogging
============================================================================
Rain water problem - Find the maxarrayFromStart , maxArrayFromEnd and compare both


Array rotation technique
=========================
1 2 3 4 5 - Rotate by 2 

Technique 1: start from 3rd element --> 3 4 5 and add the remaining elements from start 1 and 2 , which becomes 3 4 5 1 2 

Technique 2: (j+currentRotation) % size of the array
            Iterate through the array 0 - 5
    * (0 + 2 ) % 5 = 2  =>  3
    * (1 + 2 ) % 5 = 3  =>  4  
    * (2 + 2 ) % 5 = 4  =>  5
    * (3 + 2 ) % 5 = 0  =>  1
    * (4 + 2 ) % 5 = 1  =>  2
