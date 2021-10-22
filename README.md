# problem_solving

This repository consists of multiple problems and the appropriate approach to solve these problems.

Tips and Techniques : 
=====================

1. Square root Computation - Log n ( N is divided by N/2 repeately to narrow down the number )
2. Arithmetic progression - n ( n+1) /2
3. Prime number computation - Square root of n and factors rule applies - Hence log n steps are sufficient to find them

Substrings
==========
1. 1234 or abcd === Maximum number of strings possible are (n(n+1))/2

Important Problems
==================
1.Largest 


Kadanes Algorithm
==================
max subarray - Find the max contribution 
Example:   
            -1    1   1    -1   1   1   -1
 Assuming = 0 is the largest sum 
 
                                        -1    1     1   -1    1     1    -1   -1   -1   -1          1                               1
          Sum till now            = 0    0    1     2    1    2     3     2    1    0   -1      move start index to this pos     
          Largest ans till now    = 0    0    1     2    2    2     3     3    3    3    3 
            
            At index=3 (i.e) -1 ,since sum till now = 1 , it will add to the existing subarray - hence include


GCD (or) HCF
====================
GCD/HCF - Find the highest common divisor 

6,8         6  ->       1,2,3,6
            8  ->       1,2,4,8
    
    Highest common factor here is 2
    Note : Highest common factor should be one of the factor minimum(6,8)
    
   GCD Properties 
   * Not applicable for negative numbers 
   * GCD(a,b) = GCD(b,a)
   * GCD(a,a) = a
   * GCD(a,0) = a
   * GCD(a,1) = 1
   * GCD(a,b-a) = GCD(a,b)
   * GCD(a,b-a) = GCD(a,b%a) ==> XXX ----------- GCD of 2 numbers can be solved in log complexity -------------
       
       
LCM  - Common multiples between 2 numbers       
====
6,8    6  ->  6, 12, 18, 24,      = 24 is the LCM     
       8  ->  8, 16, 24      
       
For given 2 numbers , maximum LCM could be 6 * 8

GCD and LCM theorum =  HCF(a,b) * LCM(a,b) = a * b








            


