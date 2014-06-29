Maximus
=============

This problem involves finding the maximum values in a list of values.

You will be given the parameters (a, c, m, X0) to an LCG for generating random numbers.  Using these values, you will generate a list of N numbers, and pick the M maximum values from that list.  Print the sum of the M values, modulo D.

The input file will be in a single line in the following format:

    a c m X0 N M D

Where:
 * a, c, m, and X0 are the initialization values for an LCG
 * N is the number of values to pull from the LCG
 * M is the number (<= N) of values to include in the sum
 * D compute the sum modulo this number

 Problem Drilldown
=============

Problem 1
-------------
For this problem, you only need to return the maximum value from the list, modulo D (M=1)

Problem 2
-------------
This one gets a bit more complicated, here you're going to have to find the largest 15% out of a million values.

Problem 3
-------------
In this one you have to consider 10 million values less than m=2**32, and return the largest 111


Unfortunately the algorithm that has the fastest worst case performance with this problem does not really show up in the problem sizes that we can handle with this format, but take some time to think about what that approach might be. 