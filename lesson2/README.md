Fibonacci
=============

This problem is a relatively straightforward calculation of fibonacci numbers.

The fibonacci sequence is a series of numbers, starting with 0 and 1, where every number in the sequence is the sum of the previous two.  The first few numbers in the sequence are:

    0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, ...

You will be given the parameters (a, c, m, X0) to an LCG for generating random numbers.  Pull N numbers from the LCG, and calculate the fibonacci number at the matching index.  Print the sum of the N associated fibonacci numbers, modulo D.

The input file will be in a single line in the following format:

    a c m X0 N D

Where:
 * a, c, m, and X0 are the initialization values for an LCG
 * N is the number of values to pull from the LCG
 * D compute the sum modulo this number

 Problem Drilldown
=============

Problem 1
-------------
For this problem, you only need to compute the sum of 60 values.

Problem 2
-------------
For this problem, you will have to compute the sum of 1.5 million fibonacci numbers, but only the first 1024 are included.

Problem 3
-------------
For this problem you will only have to consider 150 values, but they can be any index up to 2\*\*64